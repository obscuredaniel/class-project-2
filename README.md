📘 Student Result Collation System

This is a simple web-based Python Flask application for collating student results. It allows users to input multiple students' scores, calculate totals, averages, grades, remarks, and view a ranked summary with an option to restart the process.

🛠 Features

* Input number of students
* Collect individual student data:

  * 9-digit unique ID (validated)
  * First and Last names (letters only)
  * Scores in Math, English, and Science (between 1 and 100)
* Automatic calculation of:

  * Total and Average score
  * Grade assignment (A–F)
  * Performance remark (Excellent – Fail)
* Displays class average and student rankings
* Input validation with inline error messages
* "Go Back" and "Restart" functionality

🚀 How It Works

1. Page 1: Enter number of students.
2. Page 2: Input each student’s:

   * 9-digit Student ID (must be unique and numeric)
   * First & Last Name (only letters allowed)
   * Subject scores (1 to 100)
3. Page 3: Results are displayed with grade, remark, and a restart button.



 💡 Technologies Used

* Python 3
* Flask
* HTML5/CSS3
* Jinja2 Templating

---

 🔧 Setup Instructions

1. Clone the repo:

   bash
   git clone https://github.com/your-username/student-result-collation.git
   cd student-result-collation
   

2. **Create and activate virtual environment**:

   bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   

3. Install dependencies:

   bash
   pip install Flask
   

4. **Run the app**:

   bash
   python app.py
   

5. Visit:
   Open your browser and go to `http://127.0.0.1:5000/`



 📁 Project Structure

``
├── app.py                  # Flask main application
├── templates/
│   ├── pagee1.html         # Enter number of students
│   ├── pagee2.html         # Enter student data
│   └── pagee3.html         # View results
├── static/
│   └── style.css           # (Optional) custom styling
├── README.md               # Project documentation
`

 📌 Notes

* Data is stored temporarily (in-memory) and will be lost on server restart.
* This app is suitable for small classrooms, demos, or training.


 📞 Contact

Created by **Cybercode**





