🖼️ Image Watermark Tool

A simple Python script to batch-process images and add a watermark using the Python Imaging Library (PIL).

📌 Description

The Image Watermark Tool allows you to automatically add a watermark image to all .jpg and .png files in a folder. The watermark is resized dynamically and placed neatly at the bottom-right corner of each image.

🚀 Features

Batch processing of images in a folder

Supports .jpg and .png formats

Automatically resizes watermark

Places watermark at bottom-right with padding

Creates a separate output/ folder for processed images

🛠️ Technologies Used

Python 3

PIL (Python Imaging Library)

📂 Project Structure
.
├── watermark.py        # Main script
├── requirements.txt    # Dependencies
├── README.md           # Documentation
⚙️ Installation

Clone the repository:

git clone https://github.com/your-username/image-watermark.git
cd image-watermark

Install dependencies:

pip install -r requirements.txt

⚠️ Note:
If PIL==1.1.6 does not install properly (it is outdated), use:

pip install pillow
▶️ Usage

Run the script:

python3 watermark.py

You will be prompted to enter:

📁 Folder Path → Path containing images

🖼️ Watermark Path → Path to watermark image (PNG recommended)

💡 Example
Enter Folder Path: /home/user/images
Enter Watermark Path: logo.png
📤 Output

A new folder named output/ will be created inside your image directory.

All processed images will be saved there with the watermark applied.

⚙️ How It Works

Reads all images in the given folder

Resizes watermark to 8% of image width

Places watermark at bottom-right corner with margin

Preserves image quality during saving

✏️ Customization

You can modify watermark.py to:

Change watermark size ratio

Adjust position (top-left, center, etc.)

Add transparency effects

Support more file formats

⚠️ Requirements
PIL==1.1.6

👉 Recommended (modern alternative):

Pillow
👤 Author

MD Minhaj Ali

📜 License

This project is open-source and free to use.
