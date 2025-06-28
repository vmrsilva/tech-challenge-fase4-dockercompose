# Tech Challenge FIAP

## Fase 3 - Arquitetura de Sistemas .NET

Nome: Valmir Severino da Silva <br/>
RM: 360650

1º Clonar os repositórios; <br/>

[Clonar Solução Contact](https://github.com/vmrsilva/tech-challenge-fase-3-contact)

[Clonar Solução Region](https://github.com/vmrsilva/tech-challenge-fase-3-region)

2º Clonar esse repostório [tech-challenge-fase3-dockercompose]; <br/>

3º Preparar os diretórios conforme o diagrama abaixo: <br/>

root/ <br/>
  ├── tech-challenge-fase-3-contact/ <br/>
  ├── tech-challenge-fase-3-region/<br/> 
  ├── grafana/<br/>
  ├── prometheus/<br/>
  ├── docker-compose.yml<br/>

4º Executar:

Executar o build do docker-compose: <br/>  

```bash
docker-compose up --build -d
````

ou iniciar o docker-compose caso já tenha realizado o build:
```bash
docker-compose up -d
````

Comando parar os containers: <br/>
```bash
docker-compose down
```
