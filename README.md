# 2022-7A - Bootcamp - Engenheiro(a) de Dados

## Requisitos
- [Docker](https://docs.docker.com/engine/install/)
- [WSL](https://docs.microsoft.com/pt-br/windows/wsl/install)

---
## MySQL
### **Como subir o serviço**
- Estando na pasta raiz do projeto:
```
cd mysql
make up
```

### Como desligar o serviço
- Estando na pasta raiz do projeto:
```
cd mysql
make down
```

### Como ver logs do container
- Estando na pasta raiz do projeto:
```
cd mysql
make get-logs
```

## Adminer
### **Como acessar o banco**
- Abrir o browser e acessar os links:
http://localhost:8080/ ou http://127.0.0.1:8080/

- Inserir credenciais
 ``` 
Servidor: db
Usuário: root
Senha: root
```
