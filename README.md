# Neural Style Transfer (TensorFlow + TF-Hub)

This project performs **Neural Style Transfer**, a technique that blends the **content** of one image with the **style** of another using a pretrained TensorFlow Hub model.

The project uses the **Magenta Arbitrary Image Stylization model**, which generates high-quality stylized images with fast inference.


## Features
- Uses **TensorFlow Hub** pretrained NST model  
- Supports **any image** as content and style  
- Generates high-quality outputs  
- Supports exporting stylized images  
- Fully reproducible code  


## Model Used
**TensorFlow Hub Model:**  
`google/magenta/arbitrary-image-stylization-v1-256/2`

This model takes two inputs:
- Content Image  
- Style Image  

And outputs a stylized result.


## Installation

Install dependencies:

```bash
pip install tensorflow tensorflow_hub matplotlib numpy opencv-python
```
