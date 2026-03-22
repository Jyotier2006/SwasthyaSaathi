
# SwasthyaSaathi

GitHub-ready project structure for your uploaded SwasthyaSaathi app.

## What is included
- `backend/` - your actual Django project code, cleaned for GitHub
- `frontend/` - separate frontend scaffold with copied UI assets as migration references
- `docker-compose.yml` - local container setup
- `k8s/` - basic Kubernetes manifests

## Notes
- The original uploaded project is mainly a Django monolith.
- To keep frontend and backend separate for GitHub, the current HTML/CSS/JS UI was copied into `frontend/` as reference files.
- The live app still runs from Django templates in `backend/core/templates` unless you fully migrate the UI.

## Quick start
```bash
cd backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

## GitHub upload
```bash
git init
git add .
git commit -m "initial project structure"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
git push -u origin main
```
