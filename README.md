# Unreal Engine Spline Instancer
This project investigates the capabilities of UE5's PCG framework with the goal of developing a versatile, spline-based generation tool. Designed for multi-purpose use, the tool supports procedural placement of assets such as walls, fences, and vegetation, enabling flexible deployment across a range of environment design scenarios

## How To Guide
1. In Unreal Engine, browse to the "PCG_SplineInstancer" actor and drag an instance into the world
2. Edit the spline to the desired shape
3. On the PCG component, under "Instance", apply a custom <b>Graph<b/> or edit any <b>Parameter Overrides<b/> to get desired outcome

## Features
### Exclusion/Exclusion Fill
Able to use "Exclusion" Spline to exclude sections or replace sections with alternative asset i.e gates:<br/>
![image](https://github.com/user-attachments/assets/dbae56b1-0b42-4472-a4ea-c9c383a43166)

### Mirror
Mirror toggle to duplicate spline:<br/>
![image](https://github.com/user-attachments/assets/0d99b9cf-a1b9-46a2-b99a-cc48dc041b8c)

### Offset and Rotation Noise
Min/Max Offset and Rotation Noise:<br/>
![image](https://github.com/user-attachments/assets/b0c29740-e200-44be-98de-bc3b90a34a9c)

## Setup
>[!NOTE]
> - Unreal Engine version - 5.5.2
1. Download the "Unreal Engine" folder from this repository
2. In your Unreal Engine project, ensure the "Procedural Content Generation Framework (PCG)" and "Procedural Content Generation Framework (PCG) Geometry Script Interop" is enabled
3. Via windows explorer, copy the folders inside of the "Unreal Engine" folder into the "Content" folder of your project
   
## Further Reading
- Useful introduction tutorial to PCG - https://dev.epicgames.com/community/learning/tutorials/j4xJ/unreal-engine-introduction-to-procedural-generation-plugin-in-ue5-4

## ToDo
- [x] Proof of Concept
- [x] Feature - Noise offset and rotation
- [x] Feature - Mirror
- [x] Feature - Exclusion/Exclusion Fill
- [ ] Corners - Update to allow for threshold control
