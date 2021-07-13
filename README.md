## TodosAPI  
 Uma aplicação para gerenciar terefas. 

---

## Instruções 
    URL para acessar as routes: http://localhost:3333

    route para criar uma user: POST - http://localhost:3333/users
        Ex.: Os dados devem ser passando via JSON no body
        body
        {
            "name": "João Victor",
            "username": "JVM"
        }
---

    route para visualizar lista de tarefas do user: GET - http://localhost:3333/todos
        deve passar o username pelo header
        Ex.:
        header{
            "username": "JVM"
        }
---

    route para criar um todo para o usuario: POST - http://localhost:3333/todos
        deve passar o username pelo header
        Ex.:
        header
        {
            "usernme": "JVM"
        }
        
        Ex.: Os dados devem ser passando via JSON no body
        body
        {
            "title": "Estudar o ignite",
            "deadline": "2021-07-13"
        }
---