📁 Python File Organizer

A simple Python project that automatically organizes files into folders based on their file types. Point it at a messy folder (like Downloads), run it, and everything gets sorted for you.

✨ Features
Organizes images
Organizes videos
Organizes documents
Organizes Excel and CSV files
Organizes Python files
Organizes PowerPoint presentations
Places unknown file types into an Others folder
🛠️ Technologies Used
Python 3
Jupyter Notebook
os module
shutil module
⚙️ How It Works

The program reads the extension of each file in the chosen folder and moves it into the matching category folder. If a category folder doesn't exist yet, it is created automatically.

Extension(s)	Destination folder
.jpg, .png	Images
.mp4	Videos
.pdf, .docx	Documents
.xlsx, .csv	Excel
.ipynb, .py	Python
.pptx	Presentations
Anything else	Others
📂 Project Structure
Python-File-Organizer/
├── File_Organizer.ipynb   # Main notebook with the organizing logic
└── README.md              # Project documentation
📋 Prerequisites
Python 3.x installed
Jupyter Notebook (or JupyterLab / VS Code with the Jupyter extension)

Install Jupyter if you don't have it:

bash
pip install notebook

No other libraries are needed, since os and shutil come with Python.

🚀 How to Run
Clone or download this repository.
Open File_Organizer.ipynb in Jupyter Notebook.
Set the path of the folder you want to organize.
Run all the cells.
Your files will be sorted into folders automatically.
⚠️ Important Notes
The script moves files rather than copying them, so back up important data before running it on a large folder.
Run it on one folder at a time and double-check the folder path first.
🔧 Customization

To add support for a new file type, add its extension to the matching category in the notebook, or create a new category with its own folder name.

👩‍💻 Author

K. Purnima
