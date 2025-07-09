# 📚 Book Management App

A full-stack Book Management system built using:

- 🛠 **Backend:** Django + Django REST Framework + Simple JWT
- 💻 **Frontend:** Next.js + Axios
- 🔐 **Authentication:** Token-based login using JWT

---

## 📂 Project Structure
manage_books/
├── book_backend/ # Django REST API
├── book-frontend/ # Next.js frontend
├── my_venv/ # Python virtual environment (not pushed to GitHub)

🔧 Backend Setup (Django)

### 📌 Step 1: Create and activate virtual environment

```bash
cd book_backend
python -m venv venv
venv\Scripts\activate  # On Windows
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver


Frontend Setup (Next.js)
📌 Step 1: Go to frontend directory
cd ../book-frontend
📌 Step 2: Install Node.js dependencies
npm install
📌 Step 3: Run the Next.js development server
npm run dev
✅ App URL: http://localhost:3000/login


📦 Backend Dependencies
Django
djangorestframework
django-cors-headers
djangorestframework-simplejwt
Install using:
pip install django djangorestframework django-cors-headers djangorestframework-simplejwt
🌐 Frontend Dependencies
Next.js
React
Axios
