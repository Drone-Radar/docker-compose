# docker-compose para execução dos microsserviços do projeto drone-radar

### Repositórios dos microsserviços: <br>
**Front End:** https://github.com/Drone-Radar/drone-radar <br>
**Back End:** https://github.com/Drone-Radar/drone-api <br>
**Comunicado:** https://github.com/Drone-Radar/drone-radar-comunicado <br>

### Passo-a-passo para execução dos microsserviços utilizando conteineres docker:

- Clonar o repositório: <br>
> git clone https://github.com/Drone-Radar/docker-compose

- Abrir o prompt de comando de sua preferência na pasta na qual o repositório foi clonado e executar os seguintes comandos: <br>
> cd docker-compose <br>
> docker-compose up -d

- Com isso, os microsserviços **users** e **providers** estarão disponíveis nas portas **3000** e **3001**, respectivamente, em seu **localhost**. <br>
> **Back:** http://localhost:3333/api/ <br>

> **Front:** http://localhost:3000 <br>


- Swagger
> **Drone Radar:** http://localhost:3333/api-docs/ <br>

- Para encerrar a execução dos conteineres do projeto, utilize o comando: <br>
> docker-compose down
