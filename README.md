# Automated-Coding-Stats-Tracker
Automated Coding Stats Tracker is a Python-based tool that analyzes LeetCode and Codeforces profiles. It fetches real-time stats, visualizes problem-solving and contest performance, and runs seamlessly in Jupyter Notebooks within VS Code.
This project analyzes your **LeetCode** and **Codeforces** profiles using public APIs, and visualizes your problem-solving history, difficulty distribution, and contest ratings.  
It is built using **Jupyter Notebooks**, which can be run directly inside **Visual Studio Code's Python environment**.

## ✨ Features

- 🔍 Analyze your **Codeforces** and **LeetCode** activity
- 📊 Breakdown of problems by difficulty (Easy, Medium, Hard)
- 📈 Visual rating trend charts (Codeforces)
- 📄 Submission statistics and contest summaries
- ✅ Runs smoothly in **VS Code’s Python interactive notebook interface**

---

## 🛠 Tech Stack

| Tool/Library       | Purpose                          |
|--------------------|----------------------------------|
| Python (3.8+)      | Core programming language        |
| Jupyter Notebooks  | Code and analysis interface      |
| VS Code            | IDE with notebook support        |
| `requests`         | API requests                     |
| `pandas`           | Data manipulation                |
| `matplotlib`       | Data visualization               |

---

## 📁 Project Structure
```bash
competitive-programming-profile-analyzer/
│
├── Codeforces_Profile_Analyzer.ipynb
├── LeetCode_Profile_Analyzer.ipynb
├── requirements.txt
└── README.md
```
## 🔧 Setup & Usage

To get started, follow these simple steps:

1. **Clone the Repository**
   git clone https://github.com/your-username/automated-coding-stats-tracker.git
   cd automated-coding-stats-tracker
   ```
3. **Create a Virtual Environment** (optional)
   python -m venv venv
   source venv/bin/activate       # On Windows: venv\Scripts\activate
   ```
4. **Install Required Libraries**
   pip install -r requirements.txt
   
5. **Open in VS Code**
    Make sure the Python extension is installed.
    Open Automated_Stats_Tracker.ipynb.
    Run the notebook cells using Shift + Enter or the ▶️ button.
   
6.  **Enter Your Info**

When prompted, enter your:

✅ Codeforces handle

✅ LeetCode username

🖥 Example Output
Platform	TotalSolved	Easy	Medium	Hard	Rating
LeetCode	 245         95	   120	  30    Not Rated
Codeforces	0	         N/A	 N/A	  N/A	    0

📌 LeetCode rating is "Not Rated" if you haven’t participated in contests.
📌 Codeforces will show a 0 rating and N/A stats if you haven’t solved problems or entered contests.

📌 Notes
The project uses:

✅ Codeforces official API — no login required

✅ LeetCode Stats API — a trusted third-party source

Requires an active internet connection to retrieve data

All analysis runs interactively inside VS Code’s notebook interface

Easily extendable to add new platforms and export formats

🚀 Future Improvements
This project can be enhanced with:

🧠 Support for HackerRank, CodeChef, AtCoder

📤 Export to PDF, CSV, or Markdown formats

⏱ Scheduled updates via GitHub Actions

💻 CLI support using Python scripts (.py version)

🙌 Acknowledgements
------------------------------------------------------
  Codeforces API
  LeetCode Stats API
  Matplotlib
  Pandas
  Visual Studio Code





