
# Group Selected Objects Window unity tool

## Overview

This tool was created to help editors easily manage objects created in the Hierachy window in a more consistent and clear way. It also helps the editor's interface become more lively to inspire the editor to work. As well as allowing developers to easily search for grouped objects.

## Features

- **Group objects**: Collect all selected objects in a new parent object..
- **Set active**: Set activation and deactivation of the parent object as well as child objects.
- **Set Color to parent**: Randomly choose a color to set for the backround of the parent object to make the interface easier to see.
- **Remove child**: Delete the child objects selected in the Remove Child Objects window.
- **Remove parent**: Delete all parent and child objects.
- **Remove Parent and Keep Children**: Delete the parent object and keep the child object.

## Installation

**Download the Script**:
    - Copy the `GroupSelectedObjectsWindow.cs` script to the `Assets/Editor/` directory in your Unity project.
    - Copy the `HierarchyColorEditor.cs` script to the `Assets/Editor/` directory in your Unity project.
    - Copy the `CustomHierarchyColor.cs` script to any folder. directory in your Unity project.

## Usage

### Option 1: Using the Unity Editor

1. **Open Unity** and load your project.
2. Go to the top menu bar and navigate to `ND > GroupSelectedObjectsWindow`.
3. The tool will open and you can start managing your objects.

### Script Overview

First, it is a fairly diverse group of functions for managing child objects.
![image](![1](https://github.com/user-attachments/assets/6dbaf397-b827-4cae-ad7a-e24eb2a31fc6))

You can add multiple parent objects in the New Parent Name box and click Add Parent() [UnityEvent]

Notice: New Parent Name must not be null.

Then, you create a parent object with its own functions.
![image](![2](https://github.com/user-attachments/assets/5e948b2b-2c7f-472c-a64e-2be6147c759f))

Group Selected Object button to put the objects you selected in Hierachy into a new parent object.
![image](![3](https://github.com/user-attachments/assets/0ef46a53-5185-4228-aff4-2ad6b6ba3299)
)

Set Active button to update the active status of the parent object and child objects.
![image](![4](https://github.com/user-attachments/assets/bc833954-798f-47d1-82fc-0d321ce6a670)
)

Randomize Color button and Set Color To Parent button to randomly select a color and set it for the backround of the parent object in Hierachy.
![image](![5](https://github.com/user-attachments/assets/da680695-8598-4b9e-8916-3176acd2ec50)
)

Remove Child Objects button displays a table to select the object you want to delete.
![image](![6](https://github.com/user-attachments/assets/6c587741-d73a-40a4-822b-d8aee4d3ccd2)
)

Remove Parent button to delete all parent objects and child objects inside.
![image](![7](https://github.com/user-attachments/assets/4cc44d58-8f1f-4c68-91f8-110169869602)
)

Remove Parent And Keep Children button to delete the parent Object but keep the child object.
![image](![8](https://github.com/user-attachments/assets/a14e8f52-37e9-49ee-9b00-ae523e42ec86)
)

## Notes

- **Check parent custom**: Be careful of the parents you created because when you close the project you are using, it will disappear the parents you are customizing.
