React
npx create-react-app my-app
cd my-app
npm start

React Documentation

Next.js
npx create-next-app@latest my-next-app
cd my-next-app
npm run dev

Next.js Documentation

Django
pip install django
django-admin startproject myproject
cd myproject
python manage.py runserver

Django Documentation

Flask
pip install flask
echo "from flask import Flask\napp = Flask(__name__)\n@app.route('/')\ndef hello():\n    return 'Hello, World!'\nif __name__ == '__main__':\n    app.run()" > app.py
python app.py

Flask Documentation

Java (Spring Boot)
curl -s https://start.spring.io/starter.zip -d dependencies=web -d name=myapp -d type=gradle-project | bsdtar -xvf-
cd myapp
./gradlew bootRun

Spring Boot Documentation

Ruby on Rails
gem install rails
rails new myapp
cd myapp
rails server

Rails Documentation

Python (Flask, Django, FastAPI)
Flask: See above.
Django: See above.
FastAPI:
pip install fastapi uvicorn
echo "from fastapi import FastAPI\napp = FastAPI()\n@app.get('/')\ndef read_root():\n    return {'Hello': 'World'}\nif __name__ == '__main__':\n    import uvicorn\n    uvicorn.run(app, host='0.0.0.0', port=8000)" > main.py
uvicorn main:app --reload

FastAPI Documentation
Go (Gin)
go get -u github.com/gin-gonic/gin
echo "package main\nimport \"github.com/gin-gonic/gin\"\nfunc main() {\n    r := gin.Default()\n    r.GET(\"/\", func(c *gin.Context) {\n        c.JSON(200, gin.H{\n            \"message\": \"Hello, World!\",\n        })\n    })\n    r.Run()\n}" > main.go
go run main.go

Gin Documentation
