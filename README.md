# Dataset Setup for Project

This repository requires a dataset to be set up for proper functioning. Follow the steps below to decompress the dataset and place it in the correct location within the repository structure.

## Steps to Set Up the Dataset

1. **Download the Dataset**: 
   - Download the `dataset.zip` file containing all necessary data files.

2. **Decompress the Dataset**:
   - Unzip `dataset.zip` to reveal a folder named `dataset`.
   - Inside this folder, you should see two subdirectories: `iris` and `faces`.

3. **Place the Dataset Folder**:
   - Move the entire `dataset` folder into the root directory of the repository (the main branch).
   - After placing, the directory structure should look like this:

     ```
     ├── dataset/
     │   ├── iris/
     │   └── faces/
     └── other_repository_files
     ```

4. **Verify**:
   - Ensure that both `iris` and `faces` folders are within the `dataset` directory in the main branch. This setup is essential for the code to locate and process the data files correctly.

## Repository Structure Overview

The repository should look as follows after setup:
project-root/ ├── dataset/ │ ├── iris/ │ └── faces/ ├── README.md └── <other project files>

## Notes
- Ensure that `dataset` remains in the root directory (main branch).
- If you encounter any issues with locating the folders or files, double-check the structure against the one shown above.

Thank you for setting up the dataset correctly!

