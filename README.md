# Food Or Not - Image Labeler with AWS Rekognition

This Python script utilizes AWS Rekognition to analyze images and label them accordingly. It detects objects in images and provides labels, such as "Hot Dog", "Food", or "Not Food". The labeling is based on the confidence level specified.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/image-labeler.git
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure you have an AWS account and configure AWS credentials on your machine.

## Usage

To label an image, run the script `label_image.py` and provide either a URL or filename of the image as an argument.

Example:
```bash
python label_image.py https://example.com/image.jpg
```

The script will display the labeled image with the detected objects.

## AWS Rekognition Setup

This script requires access to the AWS Rekognition service. Make sure you have set up AWS credentials with appropriate permissions.

## Customization

You can customize the confidence level for object detection by modifying the `confidence` parameter in the `label_image` function.
