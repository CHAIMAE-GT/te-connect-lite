 Te-connect-lite 

Plateforme de communication interne** pour entreprise, développée avec Angular (frontend) et FastAPI (backend).

 Fonctionnalités

-  Authentification JWT
-  Annonces internes
-  Chatbot intelligent (ML simplifié)
-  Gestion de réunions
-  Tâches collaboratives
-  Demande & validation de congés
-  Gestion des utilisateurs (RH, Admin, Employés)
-  Notifications internes
-  Dashboard unifié

 Technologies

| Frontend  | Backend  | DB        | Autres     |
|-----------|----------|-----------|------------|
| Angular   | FastAPI  | MongoDB   | TailwindCSS, JWT, Docker |

 Lancer le projet

 Backend (FastAPI)
```
cd backend
pip install -r requirements.txt
uvicorn app.main:app --reload
```
Frontend (Angular)
```
npm install
ng serve
----
```
PS C:\Users\shaim\OneDrive\Bureau\te-connect-lite\backend\app> tree /F
Structure du dossier backend
Le numéro de série du volume est 6661-CDF2
C:.
│   config.py
│   database.py
│   main.py
│   __init__.py
│
├───auth
│       jwt.py
│       router.py
│       utils.py
│
├───models
│       announcement.py
│       leave.py
│       task.py
│       user.py
│
├───routers
│       announcements.py
│       chatbot.py
│       leaves.py
│       tasks.py
│       users.py
│
├───schemas
│       announcement.py
│       leave.py
│       task.py
│       user.py
│
└───services
        announcement_service.py
        chatbot_service.py
        leave_service.py
        task_service.py
        user_service.py
-----
Structure du dossier Frontend :
C:.
├───core
│   ├───auth
│   ├───guards
│   ├───models
│   └───services
├───modules
│   ├───admin
│   ├───chatbot
│   ├───dashboard
│   ├───hr
│   ├───leaves
│   ├───profile
│   └───tasks
└───shared
    ├───components
    ├───directives
    └───pipes




