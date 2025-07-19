# RailSathi-Dockerization
setup instruction :
1)clone the repository:-
git clone https://github.com/s2pl/RailSathiBE.git
cd RailSathiBE
2)install dependencies:-
pip install -r requirements.txt
3) Copy .env.example as .env and updated
4) add Dockerfile,docker-compose.yml  files, pytz==2024.1 is added to handle timezone conversions in Python.

some endpoints:-
http://localhost:8000/rs_microservice
http://localhost:8000/rs_microservice/docs → Swagger UI
http://localhost:8000/rs_microservice/redoc → ReDoc
OpenAPI schema at:
http://localhost:8000/rs_microservice/openapi.json
http://localhost:8000/health

 
