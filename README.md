# SwasthyaSaathi

GitHub-ready project structure with separate **backend** and **frontend** folders.

## Folder structure

```
SwasthyaSaathi/
├── backend/
├── frontend/
├── .gitignore
├── LICENSE
└── README.md
```

## What to put where

### backend/
Put all Django backend files here, for example:
- `manage.py`
- project folder such as `swasthya/` or `config/`
- app folders such as `chatbot/`, `symptoms/`, `users/`
- `requirements.txt`
- `.env` (do not upload real secrets)

### frontend/
Put all frontend files here, for example:
- HTML, CSS, JS files
- React / Vite / Next.js frontend files if you built a separate frontend
- assets like images, icons, translations

If your current project is a normal Django project with templates and static files inside it, you can still use:
- `backend/templates/`
- `backend/static/`

and keep `frontend/` for a future standalone frontend.

## Suggested backend structure

```
backend/
├── manage.py
├── requirements.txt
├── .env.example
├── README.md
├── config/
├── apps/
├── templates/
└── static/
```

## Suggested frontend structure

### Option 1: Separate frontend app

```
frontend/
├── package.json
├── src/
├── public/
└── README.md
```

### Option 2: Django templates only
Keep frontend inside backend:
- `backend/templates/`
- `backend/static/`

## Before uploading to GitHub
1. Copy your real Django project files into `backend/`
2. Copy any standalone frontend into `frontend/`
3. Remove secrets from `.env`
4. Commit and push

## Git commands

```bash
git init
git add .
git commit -m "Initial project structure"
git branch -M main
git remote add origin YOUR_GITHUB_REPO_URL
git push -u origin main
```

## Important
The uploaded file in this chat was only:
- `swasthya_django_v2_.code-workspace`

That file only points to a local folder on your computer and does **not** contain the actual code. So this repo is a clean structure/template, not your full project source.
