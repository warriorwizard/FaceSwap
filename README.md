# FaceSwap
# Face Swapping using InsightFace and OpenCV

This repository contains a Python script that demonstrates how to perform face swapping using the InsightFace library and OpenCV. With this code, you can replace faces in an image with faces from another image.


<!-- <div style="display: flex; justify-content: center;">
  <div style="margin-right: 10px;">
    <img src="https://github.com/warriorwizard/FaceSwap/blob/main/img.jpg" alt="Image 1" width="300" />
    <p>Original Image</p>
  </div>
  <div>
    <img src="https://github.com/warriorwizard/FaceSwap/blob/main/output.png" alt="Image 2" width="300" />
    <p>Altered Image</p>
  </div>
</div> -->

<div style="display: flex; justify-content: center;">
  <img src="https://github.com/warriorwizard/FaceSwap/blob/main/img.jpg" alt="Original Image" width="300" style="margin-right: 10px;" />
  <img src="https://github.com/warriorwizard/FaceSwap/blob/main/output.png" alt="Altered Image" width="300" />
</div>



## Dependencies

Before running the code, make sure you have the following dependencies installed:

- Python 3.x
- OpenCV (`cv2`)
- NumPy (`numpy`)
- Matplotlib (`matplotlib`)
- InsightFace (`insightface`)

You can install the necessary Python packages using `pip`:

```
pip install opencv-python numpy matplotlib insightface
```

## Usage
Clone this repository to your local machine:

```
git clone https://github.com/yourusername/face-swapping.git
cd face-swapping
```

## Ensure that you have two images ready:

img.jpg: The input image containing faces you want to replace.
img2.png: The image containing the faces you want to use as replacements.
Run the Python script face_swapping.py:


```
python face_swapping.py
```
The script will load the input image and the replacement image, detect faces in the input image, and replace them with faces from the replacement image.

The result will be displayed using Matplotlib, showing the original image with the swapped faces. The output image will not be saved by default, but you can modify the script to save it if needed.

## Configuration
You can configure the code by modifying the following variables in the face_swapping.py script:

```
input_img_path: Path to the input image (img.jpg by default).
replace_with_img_path: Path to the replacement image (img2.png by default).
swapper_model_path: Path to the face swapping model (model_zoo\inswapper_128.onnx by default).
output_img_path: Path to save the output image (uncomment and set if you want to save the result).
```

## License
This project is licensed under the MIT License - see the LICENSE file for details.