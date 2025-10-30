🐳 Two-Tier Flask + MySQL App

This project runs a Flask web app and a MySQL database in separate Docker containers on the same network.

🧩 Requirements:

Docker installed

A Docker network named "lakshya"
(create one using: docker network create lakshya)

MySQL container image
(pull it using: docker pull mysql:latest)

⚙️ Setup:

1 Dockerfile → for the Flask app

1 docker-compose.yml → to manage both containers

🙌 Credits:
Thanks to "Train with Shubham" for the inspiration!
