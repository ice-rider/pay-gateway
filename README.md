# pay-gateway  
service like a yookassa for make pays in demo-mode without making real payment. (You can for this to define pay system and use it).  

---
# Architecture  
project has microservice architecture. You can find api on server/api/docs if you deploy it (or if test-server is working)  

# Backend (RESTful api)  
made with python:
- api: framework Flask, Flask-restful  
- database: orm SQLAlchemy, Flask-SQLAlchemy.  (default db url is sqlite:///database.db, but you can chanche it by set env var `DATABASE_URI`
- docs: /api/docs  made with swagger documentation

# Client (Web app)
made with node js:
- framework: React
- components: [material-ui](https://mui.com/material-ui/)
