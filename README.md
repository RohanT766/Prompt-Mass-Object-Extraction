# Prompt-Mass-Object-Extraction

## Description
The Prompt-Mass-Object-Extraction project leverages Grounding DINO and the Segment Anything Model for prompt-based object extraction. It is designed to process a folder of images and extract a specified object from each image. This project is intended to be run on Google Colab using the GPU.

## Getting Started
To run this project, follow these steps:

1. **Enable GPU**:
   - Go to Google Colab.
   - Click on "Runtime" in the top menu.
   - Select "Change runtime type."
   - Choose either "GPU" or "T4 GPU" as the hardware accelerator.

2. **Upload Images**:
   - Run the notebook cells.
   - Click "Choose Files" to upload the images you want to process.

3. **Restart Runtime (if necessary)**:
   - If you encounter an error after running `!pip install supervision==0.12.0` saying "You must restart the runtime in order to use newly installed versions," click "RESTART RUNTIME."
   - After restarting the runtime, run the first cell and then continue (at cell 7).

4. **Input Object**:
   - Once you reach cell 16, input the object you wish to extract from all the uploaded images.

## Usage
Follow the instructions in the notebook cells to specify the object you want to extract. The project will then apply object extraction to the uploaded images.
