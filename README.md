# Finance-web-app
---

## 🚀 Technologies

**Backend:**
- 🐍 Python 3.10+
- ⚡ FastAPI
- 🧬 Pydantic 
- 🐳 Docker 
- 🧪 Pytest 
- 🗃️ ORM 
---


### Backend 
```plaintext
mi_app/
│
├── main.py                    
├── config/                     
│   ├── __init__.py
│   ├── settings.py            
│   └── database.py            
├── api/                      
│   ├── __init__.py
│   ├── routes/                
│   │   ├── __init__.py
│   │   ├── usuarios.py
│   │   └── auth.py
│   └── dependencies.py        
├── core/                      
│   ├── __init__.py
│   ├── security.py            
│   └── exceptions.py          
├── services/                 
│   ├── __init__.py
│   ├── usuario_service.py
│   └── base_service.py        
├── repositories/              
│   ├── __init__.py
│   ├── usuario_repository.py
│   ├── base_repository.py     
│   └── interfaces/            
│       ├── __init__.py
│       └── usuario_repository_interface.py
├── models/                    
│   ├── __init__.py
│   ├── domain/               
│   │   ├── __init__.py
│   │   └── usuario.py
│   ├── schemas/               
│   │   ├── __init__.py
│   │   ├── usuario_schema.py
│   │   └── request_response.py
│   └── enums/                
│       ├── __init__.py
│       └── usuario_enum.py
├── db/                        
│   ├── __init__.py
│   ├── database.py            
│   └── migrations/          
├── utils/                
│   ├── __init__.py
│   └── validators.py         
├── tests/                 
│   ├── __init__.py
│   ├── conftest.py            
│   ├── test_usuarios.py
│   └── integration/           
└── requirements.txt

```



http://localhost:8000/docs → Swagger UI

http://localhost:8000/redoc → Redoc

