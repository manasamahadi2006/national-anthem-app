# National Anthem App

A simple Flask web application for the National Anthem Git Workshop.

## Project structure

```text
national-anthem-app/
├── app.py
├── anthem-draft.txt
├── README.md
├── requirements.txt
├── templates/
│   └── index.html
└── static/
    └── style.css
```

## Run locally

1. Open this folder in PyCharm.
2. Open the PyCharm terminal.
3. Create and activate a virtual environment if desired.
4. Install dependencies:

   ```bash
   python -m pip install -r requirements.txt
   ```

5. Start the app:

   ```bash
   python app.py
   ```

6. Open http://127.0.0.1:5000 in your browser.

## Git practice

```bash
git init
git add .
git commit -m "Create National Anthem app"
```

Create a GitHub repository, add its URL as the `origin` remote, and push the `main` branch. For team collaboration, each member should clone the repository and use separate feature branches.
