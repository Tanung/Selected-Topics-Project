# Selected-Topics-Project

React + FastAPI + Msql

Frontend
- cd frontend
- npm install
- npm start

Backend
- cd backend
- virtualenv venv
- pip install fastapi sqlalchemy pymysql uvicorn
- uvicorn main:app --reload

Docker
- docker pull mysql
- docker run --name mysqldb -e MYSQL_DATABASE=test -e MYSQL_ROOT_PASSWORD=password -d -p 3306:3306 mysql:latest
