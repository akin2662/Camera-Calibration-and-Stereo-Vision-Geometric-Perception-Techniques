# Camera-Calibration-and-Stereo-Vision-Geometric-Perception-Techniques
**Note:** This project was a requirement for the course ENPM 673- Perception for Autonomous Robots at University of Maryland, College Park

## Project Description
This project focuses on camera calibration and stereo vision using OpenCV. The single-camera calibration section involves capturing 50 images of a calibration board, detecting corners or centroids, and computing intrinsic and extrinsic parameters to correct distortions. Reprojection error analysis is performed to evaluate accuracy, and results are visualized by comparing original and reprojected points. The stereo vision system processes stereo image datasets by matching features, estimating the Fundamental and Essential matrices, and extracting rotation and translation. Rectification ensures proper alignment, and depth estimation is achieved through disparity maps, visualized in both grayscale and heat maps. This implementation follows standard computer vision techniques for accurate 3D perception.

## Dependencies
* Python 3.11.11
* Google Colab

## Libraries used
* OpenCv
* Numpy
  
## Instructions
* Clone the repository or download the zip file. Upload the 'kinikara_project3.ipynb' file to Google Drive along with the  folders 'images_chessboard' and 'problem2_dataset'. Click on the '.ipynb' file, which would open it in Google Colab. In code snippet 2, change 'path_to_folder' to your path.
* Run the code snippets one after the other. The explanation of the concept and the code is in the python notebook
