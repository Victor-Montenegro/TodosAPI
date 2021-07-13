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

    route para atualizar o title e o deadline de um todo : PUT - http://localhost:3333/todos/{id}
        deve passar o username pelo header
        Ex.:
        header
        {
             "usernme": "JVM"
        }

        deve passar o id do todo na url
        Ex.:
        http://localhost:3333/todos/fbe3a25f-6b2d-4203-9f7b-e2ec7ccf6037

        Ex.: Os dados devem ser passando via JSON no body
        body
        {
            {
                "title": "Praticar os conhecimentos do ignite",
                "deadline" : "2021-07-14"
            }
        }
---