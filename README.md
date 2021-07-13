## TodosAPI  
 Uma aplicação para gerenciar terefas com nodejs + express para realizar um CRUD de dados, com os conceitos de uma API

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

    route para remove um todo: DELETE - http://localhost:3333/todos/{id}
        deve passar o username pelo header
        Ex.:
        header
        {
             "usernme": "JVM"
        }
         deve passar o id do todo na url

        Ex.:
        http://localhost:3333/todos/fbe3a25f-6b2d-4203-9f7b-e2ec7ccf6037

---

    route para atualizar o done de um todo : PATCH - http://localhost:3333/todos/{id}
        deve passar o username pelo header
        Ex.:
        header
        {
             "usernme": "JVM"
        }

        deve passar o id do todo na url
        Ex.:
        http://localhost:3333/todos/fbe3a25f-6b2d-4203-9f7b-e2ec7ccf6037



# Victor Montenegro 

## Olá, tudo bem! :wave:
    Eu sou João Victor Montenegro Rocha, mas pode me chamar de João. Atualmente desenvolvendo aplicações web
    com nodejs e sempre em busca de crescimento e aprimoramento profissional e pessoal. 

    Estou disposto a trabalhar em um ambiente que proporcione conhecimento e crescimento profissional. Tenho como 
    objetivo de me atualizar para novas tecnologias e poder ajudar a comunidade e os novos developers.

 <br/> :purple_heart: Buscando colaborar com projetos no back-end, utilizando o framework nodejs.
 <br/> :blush: Com o que eu puder ajudar vou ajudar!
 <br/> :computer: O que estou aprendendo: javaScript, MongoDB, MySQL, PostgreSQL, nodejs/TypeScript.
 <br/> 💬  &nbsp; Sobre mim: Curto tecnologias,podCasts, games, seriados e animações. 
 <br/> :email: Entre em contato comigo: [![Linkedin Badge](https://img.shields.io/badge/-VictorMontenegro-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://https://www.linkedin.com/in/joao-victor-montenegro-595791194/)](https://www.linkedin.com/in/joao-victor-montenegro-595791194/) 
 [![Gmail Badge](https://img.shields.io/badge/-jvcmontenegro67@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=victor:jvcmontenegro67@gmail.com)](victor:jvcmontenegro67@gmail.com)
