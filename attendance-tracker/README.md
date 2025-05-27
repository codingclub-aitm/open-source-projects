# Attendance Tracker (Starter Skeleton)

Tracks student attendance via QR codes.

## Tech
Backend – Django  
Frontend – React  
DB       – SQLite (dev) / PostgreSQL (prod)

### Local quick-start
```bash
# backend
cd backend
python3 -m venv env && source env/bin/activate
pip install django
python manage.py migrate
python manage.py runserver

# frontend
cd frontend
npm install
npm run dev
