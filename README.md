# Flask‑Personal‑Website  
A simple, clean personal website built with Flask for showcasing projects, résumé, and contact information.

## Features  
- Lightweight Flask application (one main entry point: `main.py`)  
- HTML templates structured in the `templates/` directory  
- Static assets (CSS, images, JS) in the `assets/` folder  
- Built with HTML5, CSS3, minimal JavaScript—easy to understand and extend  
- Ready for deployment (for example on Heroku, PythonAnywhere, or any WSGI‑compatible host)  
- Simple routing for Home, About, Projects, Contact pages  
- Easily customizable for your own branding, content, and style  

## Tech Stack  
- **Python** (Flask)  
- **Flask** micro‑framework for routing & templating  
- **HTML / CSS / JavaScript** front‑end  
- No heavy front‑end frameworks (for simplicity & performance)  
- Works well on any hosting platform that supports Python/Flask  

## Getting Started  

### Prerequisites  
- Python 3.x  
- `pip` (Python package manager)  
- (Recommended) Virtual environment: `python3 -m venv venv`

### Installation  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/luqmankittur/Flask‑Personal‑Website.git  
   cd Flask‑Personal‑Website  
   ```  
2. (Optional) Activate your virtual environment:  
   ```bash  
   source venv/bin/activate   # On macOS/Linux  
   .\venv\Scripts\activate    # On Windows  
   ```  
3. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  
   *(If a `requirements.txt` is not present, you can install Flask manually: `pip install Flask`.)*  
4. Run the app:  
   ```bash  
   python main.py  
   ```  
5. Visit `http://127.0.0.1:5000/` in your browser to view the site.

### Deployment  
- You can deploy this site on platforms like Heroku, PythonAnywhere, or a VPS with Gunicorn + Nginx.  
- Ensure `FLASK_ENV=production` (or equivalent) and use a proper WSGI server for production.  
- Update configuration (if any) for domain name, SSL, environment variables, etc.

## Customization  
- Edit the HTML templates in `templates/` to modify layout, content, and pages.  
- Replace the static files in `assets/` (CSS, JS, images) to reflect your own branding.  
- Add new routes in `main.py` if you need additional pages (e.g., Blog, Portfolio).  
- Extend the site with contact forms, dynamic content, or integration with a CMS as needed.

## Directory Structure  
```
Flask‑Personal‑Website/
│  
├── assets/           # Static files: CSS, images, JS  
├── templates/        # HTML templates  
├── main.py           # Flask application entry point  
├── requirements.txt  # (Optional) dependencies list  
└── README.md         # This file  
```

## About the Author  
**Luqman Kittur** – Developer & Designer at Luqman Graphics.  
You can contact me at: [kitturluqman007@gmail.com](mailto:kitturluqman007@gmail.com)

---

*Thank you for checking out this project. I hope it helps you build a great personal website!*  
