## TodoService
Rest API service was created by using Node.js, Express.js and MongoDB in Todo service.
### Steps
1.	npm install
2.	npm start

### Postman API Test
- [x] (GET) URL: localhost:3000/tasks
- [x] (POST) URL: localhost:3000/tasks
  - Body: {"title": "My First Note","content": "This is my Notes."}
- [x] (PUT) URL: localhost:3000/tasks/5dda5282632f4a04949e9cfd
  - Task Id: 5dda5282632f4a04949e9cfd
    - Body: {"title": "My Second Note","content": "This is my Notes."}
- [x] (DELETE)URL: localhost:3000/notes/5daf13a2dfa2c2445846880b
  - Task Id: 5daf13a2dfa2c2445846880b

