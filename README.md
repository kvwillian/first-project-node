# First Project in NodeJS ()

## What's that? (O que é isso?)
It's a back-end code to create appointments at a barber shop. (É um código back-end para criar agendamentos em uma barbearia.)
## What concepts do we use? (Que conceitos utilizamos?)
We use a few of development concepts to organize our code the best way. (Utilizamos alguns conceitos de desenvolvimento para organizar nosso código.)
Like : 
1. Services 
2. SOLID 
3. Models 
4. Routes

## How to Run the C0de? (Como rodar o código?)

``` 
git clone github.com/kvwillian/first-project-node
``` 
In the terminal, select the project folder (No terminal, selecione a pasta do projeto)

Execute ```yarn ``` in the terminal to install the dependencies. (Execute yarn no terminal para instalar as dependências.) 

Execute ``` yarn dev:server ``` to start the server. (Execute yarn dev:server para iniciar o servidor)

#### Open the INSOMNIA
Create a new POST Request with a JSON Code  = 
```
{
	"provider": "(your name)",
	"date": "{Timestamp => ISO-8601}"
}
```
 Set the URL to = 
```http://localhost:3333/appointments ```

Create a new GET Request to List the created appointments. 
