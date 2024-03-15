# fiap-checkpoint1-microsservices

### Executar a aplicação a partir do docker hub do respectivo membro com profile "dev"

```
  docker pull contatoassisarthur1109/fiap-checkpoint1:latest
  docker run -p 8080:8080 -e "PROFILE=dev" contatoassisarthur1109/fiap-checkpoint1
```

### Executar a aplicação a partir do docker hub do respectivo membro com profile "stg"

```
  docker pull contatoassisarthur1109/fiap-checkpoint1:latest
  docker run -p 8080:8080 -e "PROFILE=stg" contatoassisarthur1109/fiap-checkpoint1
```

### Executar a aplicação a partir do docker hub do respectivo membro com profile "prd"

```
  docker pull contatoassisarthur1109/fiap-checkpoint1:latest
  docker run -p 8080:8080 -e "PROFILE=prd" contatoassisarthur1109/fiap-checkpoint1
```
