# 🖼️ Image Watermark Tool

A simple Python script to add a watermark to multiple images in a folder using the Python Imaging Library (PIL).

---

## 📌 Description

This project allows you to automatically add a watermark image to all `.jpg` and `.png` files inside a specified folder. The watermark is resized dynamically and placed at the bottom-right corner of each image.

---

## 🚀 Features

- Batch processing of images  
- Supports `.jpg` and `.png` formats  
- Automatically resizes watermark  
- Positions watermark at bottom-right  
- Creates a separate `output/` folder for results  

---

## 🛠️ Technologies Used

- Python 3  
- PIL (Python Imaging Library)

---

## 📂 Project Structure
.
├── watermark.py
├── requirements.txt
└── README.md


---

## ⚙️ Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/image-watermark.git
cd image-watermark
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

⚠️ Note: PIL==1.1.6 is outdated. If installation fails, use:
```bash
pip install pillow
```

## ▶️ Usage

Run the script:
```bash
python3 watermark.py
```
Enter the required inputs when prompted:

Folder Path → Path containing images

Watermark Path → Path to watermark image (PNG recommended)


## 💡 Example
```bash
Enter Folder Path: /home/user/images
Enter Watermark Path: logo.png
```

## 📤 Output

A new folder named output/ will be created inside the given directory

Watermarked images will be saved in the output/ folder

## ⚙️ How It Works

- Reads all files from the given folder

- Filters .jpg and .png images

- Resizes watermark to 8% of image width

- Places watermark at bottom-right with padding

- Saves optimized output image

## ✏️ Customization

You can modify watermark.py to:

- Change watermark size
- Adjust position
- Add transparency
- Support more formats

## ⚠️ Requirements
```bash
PIL==1.1.6
```
Recommended alternative:
```bash
Pillow
```

## 👤 Author

MD Minhaj Ali

## 📜 License

This project is open-source and free to use.

---
