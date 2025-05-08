Grigore Mihai - AIA IV - Grupa I

Traffic Sign Recognition Web App
A web-based application that uses machine learning to automatically recognize and classify traffic signs from uploaded images. Designed to enhance road safety and assist in driver education through accurate and rapid visual feedback.

🚦 Features
Upload images with traffic signs for recognition

Automatic classification using trained ML models

Visual feedback of results

History tracking for authenticated users

Community contributions for model improvement

Public API for integration with third-party tools

Notifications for uncertain or failed identifications

🧠 Tech Stack
Frontend: HTML/CSS/JS (assumed)

Backend: Django (Python)

Machine Learning: TensorFlow / Keras

Database: PostgreSQL

Infrastructure: Docker, Linux server, nGINX

Communication: REST API, WebSockets

Other Tools: Redis, OpenCV

📦 Requirements
Python 3.8+

Docker & Docker Compose

Internet connection

Supported image formats: JPG, PNG

Recommended: GPU for model training

👥 User Roles
Guest Users: Limited access (test-only)

Authenticated Users: Full feature access

Admins: Manage users and training data

📈 Non-Functional Requirements
⏱️ Response time < 2 seconds

📶 Uptime > 99.9%

🔐 Data encryption & secure authentication

🌐 Multi-language support and accessibility

🔁 CI/CD integration

📚 References
GTSRB Dataset

TensorFlow / Keras

OpenCV

ISO Road Sign Standards

🔌 API Access
Public API with key-based authentication for developers. See docs/api.md (to be created) for usage.

⚠️ Known Challenges
Dataset diversity and class imbalance

Image quality affecting model accuracy

Infrastructure scaling under high load
