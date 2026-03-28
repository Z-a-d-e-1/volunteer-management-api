# Volunteer Management API

A RESTful API built with Flask to manage volunteer data.
This project demonstrates backend development fundamentals, including API design, structured JSON responses, and filtering data based on user input.

---

## Purpose

This project was developed as part of my transition into cybersecurity and backend development.

It demonstrates how APIs can securely handle structured data, process user queries, and return clean, structured responses. These are essential skills for roles involving system monitoring, data handling, and security analysis.

---

## Features

* View all volunteers
* Search volunteers by skill
* Structured JSON responses
* Lightweight and easy to extend
* Designed for backend practice and portfolio demonstration

---

## Tech Stack

* Python
* Flask
* REST API
* JSON

---

## API Endpoints

| Method | Endpoint                | Description                |
| ------ | ----------------------- | -------------------------- |
| GET    | /volunteers             | Get all volunteers         |
| GET    | /search?skill=first_aid | Filter volunteers by skill |

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

# Activate virtual environment
# Windows:
venv\Scripts\activate

# Mac/Linux:
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
├── README.md
├── .gitignore
```

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
Cybersecurity & Python Developer in Training

* Open University BSc (Hons) Cyber Security
* Building hands-on labs in Python, Linux, and networking
* Actively developing backend and security-focused projects

---

## License

This project is for educational and portfolio purposes.
