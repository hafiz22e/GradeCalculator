# Python Grade & Negative Marking Calculator

A professional GUI-based calculator built with Python's `tkinter` library. This tool is designed to calculate student grades for MCQ-based exams that involve negative marking.

## 🚀 Features
- **Customizable Setup:** Define the total marks and the total number of questions for any exam.
- **Auto-Scaling:** Automatically calculates marks per question (e.g., 40 marks for 20 questions = 2 marks per question).
- **Negative Marking:** Deducts -1 for every wrong answer, while unattempted questions result in 0 (no penalty).
- **User-Friendly GUI:** Simple interface with an easy exit command ('OK' or 'ok').
- **Looping Capability:** Perform multiple calculations in one session without restarting the app.

## 📊 How the Calculation Works
The tool follows this mathematical logic:
1.  **Correct Marks:** `Correct Answers` × `Marks Per Question`
2.  **Penalty:** `Wrong Answers` × `1`
3.  **Final Score:** `Correct Marks` - `Penalty`

**Example:**
- Total Marks: 40 | Total Questions: 20 (Each Q = 2 marks)
- 16 Correct ($16 \times 2 = 32$)
- 4 Wrong ($-4$)
- **Result:** $32 - 4 = 28 / 40$

## 🛠️ Installation & Usage
1. **Prerequisites:** Ensure you have Python installed on your machine.
2. **Run the App:** - Download the `.py` file.
   - Run it via terminal: `python calculator.py` or through VS Code.
3. **Exit:** Type `OK` in the exit box and press Enter.

## 📝 License
This project is open-source and free to use for educational purposes.

