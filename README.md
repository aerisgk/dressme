# Dress Me

**Authors:** Aeris Kelleher, Gabriel Kleinschmidt, Leigh Jasmine Metran, Cam Shortt, Isma Swati

A project by Crane7 Software.

---

## Project Overview
Dress Me is a **personal digital closet app** that allows users to upload and organize their clothing items, browse their wardrobe, and build outfits manually or automatically. Users can also generate outfit suggestions based on weather conditions or random selection. The app aims to make outfit planning easy and visual.

---

## Features
- User registration and login
- Upload clothing items with name, category, tags, and images
- Browse wardrobe with search and category filters
- Build outfits manually by selecting tops, bottoms, and shoes
- Generate random outfits
- Generate weather-based outfits
- Dark mode toggle

---

##  Tech Stack
- Backend: Python, Flask, Flask-WTF  
- Frontend: HTML, CSS, JavaScript, Bootstrap 5  
- Database: SQLite (for storing users and clothing items)

---

### How to Setup

1. Clone the repo:
```
$ git clone https://github.com/aerisgk/dressmei
```

2. Create a virtual environment (optional, but recommended):
```
$ python -m venv venv
$ source venv/bin/activate 
```

3. Install dependencies:
```
$ pip install -r requirements.txt
```

4. Setup an HTTP Reverse Proxy to listen on localhost:8080
For Caddy:
cat /etc/caddy/Caddyfile
example.com {
	reverse_proxy * 127.0.0.1:8080
}

5. Run the Flask app:
This script should never exit (detach the session for production use).
sh deploy.sh
---

