# 🧠 Resume Matcher AI

An AI-powered web application that compares and ranks resumes based on how well they match a given job description. Built using **Python**, **Flask**, and **scikit-learn**, it uses **TF-IDF vectorization** and **cosine similarity** to find the most relevant candidates.

## 🔍 What It Does

- Upload multiple resumes in `.pdf`, `.docx`, or `.txt` formats
- Enter any job description in the input field
- Automatically compares and ranks the top 5 resumes by similarity score
- Displays the best matches on a simple web interface

## 🚀 Technologies Used

- **Python**  
- **Flask** – Web framework  
- **scikit-learn** – For TF-IDF and cosine similarity  
- **PyPDF2** – To extract text from PDFs  
- **docx2txt** – To extract text from DOCX files  
- **HTML + Jinja2** – For frontend rendering

## 📁 Project Structure

resume-matcher-ai/
├── templates/
│ └── matchresume.html # Web interface template
├── uploads/ # Folder to store uploaded resumes
├── main.py # Main Flask application
└── README.md # Project documentation

## ▶️ How to Run

1. **Clone the repository**  
   ```bash
   git clone https://github.com/AyushAmrutkar/resume-matcher-ai.git
   cd resume-matcher-ai
   
2. Install dependencies
   Make sure you have Python 3 installed. Then run:
   pip install -r requirements.txt
   
3. Run the app
   python main.py

4. Open in browser
   Go to http://127.0.0.1:5000 and try uploading resumes with a job description.

📌 Example Use Case
Upload resumes of applicants

Paste the job description of a Software Engineer

Get the top 5 matching resumes with similarity percentages

🌱 Learning Outcomes
Basics of Natural Language Processing (NLP)

TF-IDF and Cosine Similarity concepts

Full-stack Python web development with Flask

File parsing for real-world applications

📈 Future Enhancements
Deploy to cloud (Render/Heroku)

Add support for more file types like .rtf, .odt

Improve frontend with Bootstrap

Visualize scores using charts or graphs

🙌 Acknowledgments
This project was built as part of learning AI-based automation and developer productivity, aligning with real-world hiring challenges.

🧑‍💻 Author: Ayush Amrutkar
📫 Email: ayushamrutkar11@gmail.com   

