# Sample Project for [StarLightGS](https://github.com/CoSTAR-National-Lab/relighting-gaussians-unreal)
<img width="1188" height="650" alt="image" src="https://github.com/user-attachments/assets/50c614a8-46a5-4de4-92d8-56fd8e53d5e9" />

Sample project for [StarLightGS](https://github.com/CoSTAR-National-Lab/relighting-gaussians-unreal), a Gaussian Splat plugin for Unreal Engine featuring relighting and native shadow casting support.

See the [StarLightGS README](https://github.com/CoSTAR-National-Lab/relighting-gaussians-unreal) and [usage guide](https://github.com/CoSTAR-National-Lab/relighting-gaussians-unreal/blob/main/Docs/StarLightGS_Usage_Guide.md) for detail instructions on using the plugin.

To work with relighting, Gaussian Splat assets must have per-splat normal vectors and material properties (metallic/roughness).

The assets used in this project were produced using [StarLightGS Training Pipeline](https://github.com/CoSTAR-National-Lab/relighting-gaussians-training). See the [training pipeline README](https://github.com/CoSTAR-National-Lab/relighting-gaussians-training) for details on how to create your own relightable Gaussian Splat assets.

## Requirements
- Unreal Engine 5.7 or newer.
- Visual Studio 2022 or newer.

## Getting Started

1. Clone this repository with submodules:
    ```sh
    git clone --recursive https://github.com/CoSTAR-National-Lab/starlightgs-sample
    ```
    If you cloned without submodules, then you can run this command:
    ```sh
    git submodule update --init
    ```
2. Right-click on `StarLightSample.uproject` and select `Generate Visual Studio project files` (you will have to click `Show more options...` first on Windows 11).
3. Open the generated `StarLightSample.sln`.
4. Press F5 within visual studio to build and run the sample project.

## Asset Credits

Assets in this sample project were produced from datasets from the below sources. The datasets were turned into relightable gaussian splat assets using our [StarLightGS Training Pipeline](https://github.com/CoSTAR-National-Lab/relighting-gaussians-training). They are provided as sample assets for our [StarLightGS](https://github.com/CoSTAR-National-Lab/relighting-gaussians-unreal) plugin.

We would particularly like to thank [Mike Caronna](https://www.linkedin.com/in/mikecaronna/) from [Starling Labs](https://www.linkedin.com/company/starlinglab/home/) for his support and feedback, and especially for providing the excellent boat dataset.

Asset|Made By|License
-|-|-
Boat|Mike Caronna|CC BY-NC-SA
Garden|Google|CC BY-NC-SA
Suzanne|Blender Foundation|`TBC`

## License
This project is licensed under the `<insert license>` license - see the LICENSE file for details.
