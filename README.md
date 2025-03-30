# Neural-Style-Transfer
Neural Style Transfer (NST) using the pre-trained VGG19 model in TensorFlow. NST is a technique that blends the artistic style of one image with the content of another to generate a new, aesthetically appealing image.

**Requirements:**


Python 3.x,
TensorFlow,
NumPy,
Matplotlib,
Pillow (PIL)

**Project Files**

1. neural_style_transfer.py: The main script for performing style transfer.
2. wallpaper.png: The content image.
3. img.png: The style image.
4. output_image.jpg: The output image

**Code Explanation**

Load and preprocess images: Images are resized to 224x224 and normalized for VGG19.

Feature extraction: The VGG19 model extracts content and style features.

Loss calculation: Style loss is based on Gram matrix differences, while content loss measures feature map differences.

Optimization: The image is iteratively optimized using gradient descent to minimize loss.

