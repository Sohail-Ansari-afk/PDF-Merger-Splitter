# 📄 PDF Merger & Splitter Utility

A simple Python desktop GUI tool built with `Tkinter` and `PyPDF2` to:
- 🔗 Merge multiple PDF files
- ✂️ Split a PDF into individual pages
- 📑 Extract selected pages from a PDF

---

## 🚀 Features

- 🖱️ Easy-to-use GUI interface
- 📂 Merge multiple PDFs into one
- 📃 Split a PDF into separate pages
- 🔍 Extract specific pages and save them

---

## 🛠️ Requirements

Install the required dependencies:

```bash
pip install -r requirements.txt
````

📦 Required:

* `PyPDF2==3.0.1`
* Python 3.x

---

## 🧰 File Structure

```
.
├── main.py           # 🔁 Main entry point (starts the UI)
├── ui.py             # 🖥️ Tkinter GUI logic
├── pdf_utils.py      # 🧠 Core PDF merging, splitting, extracting logic
├── requirements.txt  # 📦 Dependencies
```

---

## ⚙️ How to Run the App

Follow these steps to run the tool:

### 🐍 Step 1: Clone or Download the Project

```bash
git clone https://github.com/your-username/pdf-tool.git
cd pdf-tool
```

### 💾 Step 2: Install Dependencies

```bash
pip install -r requirements.txt
```

### ▶️ Step 3: Run the App

```bash
python main.py
```

---

## 🧑‍💻 How to Use

Once the GUI opens:

1. 🔗 **Merge PDFs**

   * Click "Merge PDFs"
   * Select multiple PDF files
   * Choose where to save the merged PDF

2. ✂️ **Split PDF**

   * Click "Split PDF"
   * Select one PDF file
   * Choose a folder to save individual pages

3. 📑 **Extract Pages**

   * Click "Extract Pages"
   * Select one PDF file
   * Enter page numbers (e.g., `1, 3, 5`)
   * Choose where to save the new PDF

---

## 🧼 Example Output

* `page_1.pdf`, `page_2.pdf`, etc., after splitting
* `extracted_pages.pdf` for selected page extraction
* `merged_output.pdf` for merged PDFs

---

## 🙌 Contribution

Feel free to fork and improve. Pull requests are welcome! 🎉

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).

---

> Made with ❤️ using Python and Tkinter

```

