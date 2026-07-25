# Code2Scan

https://colab.research.google.com/drive/1FG6kWLqB8VOzjp8NupWIniOxfl8pOk5A?usp=sharing

**Code2Scan** is a simple and lightweight Python utility that converts any URL into a high-quality, scannable QR code. Whether it's your portfolio, GitHub, LinkedIn, LeetCode profile, YouTube video, or any website, Code2Scan generates a QR code in just a few seconds.

---

## Problem Statement

Sharing long URLs can be inconvenient, especially for resumes, portfolios, presentations, or printed materials. **Code2Scan** solves this problem by converting any valid URL into a QR code that can be scanned instantly using any smartphone.

---

## Features

* Generate QR codes for any website or URL.
* High error correction for reliable scanning.
* Save QR codes as PNG images.
* Display the generated QR code after creation.
* Beginner-friendly and easy to customize.
* Lightweight with minimal dependencies.

---

## Technologies Used

* Python 3
* qrcode
* Pillow (PIL)

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Code2Scan.git
cd Code2Scan
```

Install the required package:

```bash
pip install qrcode[pil]
```

---

## Usage

1. Open `qr_generator.py`.
2. Replace the URL with your desired website.

```python
url = "https://your-website.com"
```

3. Run the program.

The generated QR code will:

* Be displayed on the screen.
* Be saved as `leetcode_qr.png`.

You can rename the output file to anything you like.

---

## Example Use Cases

* LeetCode Profile
* GitHub Profile
* LinkedIn Profile
* Portfolio Website
* YouTube Videos
* Google Forms
* Event Registration Links
* Personal Blogs
* Business Websites
* Digital Business Cards

---

## Future Improvements

* Add support for custom QR code colors.
* Embed logos in the center of the QR code.
* Create a desktop GUI using Tkinter or PyQt.
* Develop a web application using Flask or Streamlit.
* Allow users to customize the output filename and image size.
* Support batch generation for multiple URLs.

---
## Requirements

```text
Python 3.8+
qrcode
Pillow
```

---

## License

This project is open-source and available under the MIT License.
