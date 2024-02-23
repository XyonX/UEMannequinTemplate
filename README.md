# Unreal Engine Character Template Project

This is a template project created for Unreal Engine developers to kickstart their character-based projects. It includes skeletal meshes for both Unreal Engine 4 (UE4) and Unreal Engine 5 (UE5) along with a base skeletal structure for easy implementation into your game projects.

## Features

- **Base Skeletal Meshes**: Includes the master skeletal meshes for UE4 and UE5, providing a starting point for character creation and animation.
- **Template Project**: A fully-functional Unreal Engine project set up with basic configurations, ready for character development.

## Getting Started

To get started with this template project, follow these steps:

1. Clone or download this repository to your local machine.
2. Open the project in either Unreal Engine 4 or Unreal Engine 5.
3. Explore the provided skeletal meshes and template setup to understand how they can be integrated into your project.
4. Customize and expand upon the template to fit the requirements of your specific game or project.

## Folder Structure

- **Content/MasterSkeletalUE4**: Contains the master skeletal mesh for Unreal Engine 4.
- **Content/MasterSkeletalUE5**: Contains the master skeletal mesh for Unreal Engine 5.
- **Other folders and files**: Additional content and configurations for the template 
```
project.
├───Content
│   ├───MasterCharacter
│   │   ├───Interface
│   │   │   └───Implementations
│   │   ├───MasterSkeleton
│   │   │   ├───UE4
│   │   │   └───UE5
│   │   ├───SkeletonMeshes
│   │   │   ├───UE4
│   │   │   │   └───Mannequin
│   │   │   │       ├───Materials
│   │   │   │       │   └───Layers
│   │   │   │       └───Textures
│   │   │   └───UE5
│   │   │       └───Mannequin
│   │   │           ├───Materials
│   │   │           │   ├───Instances
│   │   │           │   │   ├───Manny
│   │   │           │   │   └───Quinn
│   │   │           │   └───Functions
│   │   │           └───Textures
│   │   │               ├───Shared
│   │   │               ├───Manny
│   │   │               └───Quinn
│   │   └───Rigs
│   │       └───Master
│   │           ├───UE5
│   │           │   └───Poses
│   │           │       ├───Manny
│   │           │       └───Quinn
│   │           └───UE4
│   ├───Data
│   └───Animations
│       ├───UE4
│       │   └───Mobility
│       │       ├───Loop
│       │       ├───Stop
│       │       ├───Start
│       │       │   └───Trimmed
│       │       └───Idle
│       └───UE5
│           ├───Mobility
│           │   ├───Start
│           │   ├───Stop
│           │   ├───Loop
│           │   │   └───Jog
│           │   └───Idle
│           ├───Quinn
│           └───Manny
```

## Master Skeletal

```
├───MasterSkeleton
│   ├───UE4
│   │       SK_Master_UE4.uasset
│   │       SK_PA_Master_UE4.uasset
│   │
│   └───UE5
│           SK_Master_UE5.uasset

```



## Contributing

If you'd like to contribute to this project, feel free to fork the repository, make your changes, and submit a pull request. Contributions, whether they are bug fixes, feature enhancements, or documentation improvements, are always welcome.

## License

This project is licensed under the [MIT License](LICENSE), which means you are free to use, modify, and distribute the code as long as you include the appropriate license file and give credit to the original authors.

## Acknowledgements

Special thanks to Epic Games for providing Unreal Engine, and to the Unreal Engine community for their continuous support and contributions.

## Feedback

If you have any feedback, suggestions, or issues regarding this template project, please don't hesitate to open an issue on GitHub or contact the project maintainers directly.

Happy game developing! 🚀
