# ERA5 to CERRA via Diffusion Models

### Project Structure

This repository contains several key components that are integral to the project. Below is an overview of each file and its purpose:

- `setup.py`: 
    - **Description**: This file serves as the backbone of the project setup, containing the main parameters and configurations required for initialization. It is essential for setting up the project environment and ensuring all components interact correctly.

- `utils.py`: 
    - **Description**: A collection of accessory functions that provide support across various modules of the project. These functions are utilities that aid in tasks such as data manipulation, formatting, and other common operations.

- `generators.py`: 
    - **Description**: Contains the core code for generating sequences dynamically during both the training and evaluation phases. This module is crucial for on-the-fly data processing, ensuring efficient and adaptive handling of input data during model training and testing.

- `denoising_unet.py`: 
    - **Description**: Implements the denoising U-Net architecture using Keras. This file is central to the diffusion process, providing a deep learning model specifically designed for denoising tasks within the project.

- `wind_ESPCN-EDSR_downscaling.ipynb`: 
    - **Description**: A Jupyter notebook that includes experiments and analyses related to the ESCN-EDSR downscaling methods. This notebook is instrumental in exploring and visualizing the performance of the ESPCN-EDSR approach in the context of wind data downscaling.

- `wind_diffusion_downscaling.ipynb`: 
    - **Description**: This notebook focuses on experiments involving the diffusion model for wind data downscaling. It contains a detailed exploration of the diffusion model's application and its effectiveness in the project's specific context.

- `wind_unet_downscaling.ipynb`: 
    - **Description**: Contains experiments using the U-Net model for wind downscaling tasks. 
    - **Warning**: Currently, the weights for the U-Net model are not available due to memory constraints. This notebook serves as a record of the experimental approach and findings but may require additional resources for full replication.

- `graph_visualization_maker.ipynb`: 
    - **Description**: A notebook dedicated to creating graphical representations of the results obtained from various experiments. It is a vital tool for visualizing and interpreting the performance and outcomes of different models and approaches used in the project.



A guide documenting the reprojection process is available [here](https://github.com/fmerizzi/ERA5-to-CERRA-via-Diffusion-Models/blob/main/how_to_reproject_CERRA.md).


Wind speed downscaling via Diffusion Models, from ERA5 to CERRA in the mediterranean region  

![result](https://github.com/fmerizzi/ERA5-to-CERRA-via-Diffusion-Models/blob/main/bigResult.png)
