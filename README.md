# ASCII-image-of-Darshan-Raval
Turning images into colored ASCII portraits using pure Python logic, loops, and conditional statements.

A **Minor-II academic project** that converts a real image of a famous personality into a **colored ASCII art portrait** using **core Python concepts** such as loops, conditional statements, and logical thinking.

This project preserves the **original image colors**, enhances **facial features** (eyes, eyebrows, jawline, smile), and generates a **screen‑fit ASCII output** suitable for laptops and presentations.

---

## 📌 Project Highlights

* ✅ Uses **nested loops** for pixel-by-pixel processing
* ✅ Uses **conditional statements** for brightness mapping and feature enhancement
* ✅ Preserves **original RGB colors** of the image
* ✅ Enhances **eyes, eyebrows, jawline, and teeth (whitening)**
* ✅ Fits output on screen (no scrolling)
* ✅ Google Colab compatible

---

## 🧠 Concepts Used

* Python Basics

  * `for` loops
  * `if–elif–else` conditions
  * Functions
* Image Processing

  * RGB color model
  * Pixel brightness calculation
* Logical Thinking

  * Feature-based enhancement (mouth, hair, face)

---

## 🛠️ Technologies & Libraries

* **Python 3**
* **Pillow (PIL)** – for image loading and resizing
* **NumPy** – for pixel array manipulation

---

## 📂 Project Structure

```
ASCII-Art-Project/
│
├── darshan.jpg          # Input image (can be replaced)
├── ascii_art.py         # Python code
├── README.md            # Project documentation
```

---

## 🚀 How to Run the Project (Google Colab)

1. Open **Google Colab**
2. Upload the project file and the image (`darshan.jpg`)
3. Run the code cell by cell or as a single script
4. View the colored ASCII portrait in the output

---

## 🔍 How It Works (Short Explanation)

* The image is resized to fit the screen
* Each pixel’s **brightness** is calculated using RGB values
* Brightness is mapped to ASCII characters using conditions
* Original pixel colors are applied to ASCII characters
* Facial features are enhanced using logical conditions

---

## 🧪 Sample Logic Used

```python
brightness = (0.299*r + 0.587*g + 0.114*b)
```

This formula converts RGB values into grayscale brightness for ASCII mapping.

---

## 🎓 Academic Use Case

This project was developed as part of a **Minor II Project** to demonstrate:

* Problem-solving skills
* Understanding of Python fundamentals
* Logical application of programming concepts
* Creativity in technical implementation

---

## 📸 Output Preview

> Colored ASCII portrait that closely resembles the original image with clear facial details.



This project is for **educational purposes only**.

