An interactive web application that analyzes resumes based on a job description using natural language processing techniques. https://www.youtube.com/watch?v=0eo_5oyW11o&t=1s

## :rocket: Features

- Upload job descriptions and resumes in PDF format.
- Process resumes to extract names, emails, and text content.
- Calculate the similarity between the job description and each resume.
- Rank resumes based on similarity percentage.
- Download the ranked resumes in a CSV file. (Fixed by @atiumcache)
- Dark Mode Contributed by @hbalickgoodman 

## :wrench: Setup and Usage

1. Clone the repository:
   ```sh
   https://github.com/iamamanporwal/resume-ranker.git
   ```

2. Navigate to the project directory:
   ```sh
   cd resume-analyzer
   ```

3. Install dependencies (Install the latest libraries instead of the specific ones mentioned in the txt file):
   ```sh
   pip install -r requirements.txt
   ```

4. Run the Flask app:
   ```sh
   python app.py
   ```

5. Access the app in your web browser at `http://localhost:5000`.

## :file_folder: Directory Structure

```
├── app.py
├── static/
│   └── styles.css
├── templates/
│   └── index.html
├── uploads/             # Uploaded resumes will be saved here
├── requirements.txt
├── README.md
└── .gitignore
```



