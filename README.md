# Public URL: 
https://upgraded-enigma-7wrqq4wrjvcrwwj-3000.app.github.dev/


# Deployment logs:
Deploying "khanhkd1-todo-app-4" to stage "dev" (us-east-1)

✔ Service deployed to stack khanhkd1-todo-app-4-dev (62s)

endpoints:
  GET - https://q5efa3wwm7.execute-api.us-east-1.amazonaws.com/dev/todos
  POST - https://q5efa3wwm7.execute-api.us-east-1.amazonaws.com/dev/todos
  DELETE - https://q5efa3wwm7.execute-api.us-east-1.amazonaws.com/dev/todos/{todoId}
  PATCH - https://q5efa3wwm7.execute-api.us-east-1.amazonaws.com/dev/todos/{todoId}
  POST - https://q5efa3wwm7.execute-api.us-east-1.amazonaws.com/dev/todos/{todoId}/attachment
functions:
  Auth: khanhkd1-todo-app-4-dev-Auth (7.3 MB)
  GetTodos: khanhkd1-todo-app-4-dev-GetTodos (7.3 MB)
  CreateTodo: khanhkd1-todo-app-4-dev-CreateTodo (7.3 MB)
  DeleteTodo: khanhkd1-todo-app-4-dev-DeleteTodo (7.3 MB)
  UpdateTodo: khanhkd1-todo-app-4-dev-UpdateTodo (7.3 MB)
  GenerateUploadUrl: khanhkd1-todo-app-4-dev-GenerateUploadUrl (7.3 MB)