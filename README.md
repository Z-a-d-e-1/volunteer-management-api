# Volunteer Management API

A backend system built with Flask to manage volunteers, designed as a foundation for real-world event or organisation management systems.

---

## Purpose

This project was developed as part of my transition into cybersecurity and backend development.

It demonstrates how APIs can securely handle structured data, process user queries, and return clean, structured responses. These are essential skills for roles involving system monitoring, data handling, and security analysis.

---

## Features

RESTful API for managing volunteers
JSON-based data handling
Scalable structure for database integration
Ready for frontend integration

---

## Tech Stack

Python
Flask
JSON (currently)
SQLite (planned)

---

## API Endpoints

| Method | Endpoint | Description |
|--------|---------|-------------|
| GET | /volunteers | Get all volunteers |
| GET | /volunteers/<id> | Get a specific volunteer |
| GET | /volunteers?skill=first_aid | Filter volunteers by skill |
| POST | /volunteers | Create a new volunteer |
| PUT | /volunteers/<id> | Update a volunteer |
| DELETE | /volunteers/<id> | Delete a volunteer |

---

## Example Response

```json
[
  {
    "id": 1,
    "name": "Tracy Mckoy",
    "skills": ["first aid", "admin"]
  }
]
```

---

## How to Run

Clone the repository and run the application locally:

```bash
git clone https://github.com/Z-a-d-e-1/volunteer-management-api.git
cd volunteer-management-api

python -m venv venv

# Windows
venv\Scripts\activate

# Mac/Linux
source venv/bin/activate

pip install flask
python app.py
```

Then open your browser and go to:

http://127.0.0.1:5000

---

## Project Structure

```
volunteer-management-api/
│
├── app.py
├── init_db.py
├── volunteers.db
├── requirements.txt
├── README.md
└── .gitignore

---

## Future Improvements

* Add SQLite database for persistent storage
* Implement POST, PUT, DELETE endpoints
* Add a frontend interface (HTML/CSS)
* Deploy the API online (Render / Railway)
* Add authentication for secure access

---

## Author

**Tracy McKoy**
Cybersecurity & Python Developer (in Training)

* Open University BSc (Hons) Cyber Security
* Building hands-on labs in Python, Linux, and networking
* Actively developing backend and security-focused projects

---

## Licence

This project is for educational and portfolio purposes.
