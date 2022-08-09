# Jupyter lab
## **Como subir o serviço**
- Estando na pasta raiz do projeto:
```
cd jupyter
make up
```
- Esperar o serviço subir, e pegar a url gerada para acessar o jupyter lab. A url será parecida com:
```
http://127.0.0.1:8888/lab?token=5eb6e14c7a6a0d5995cb6475677cc32704dbd7cbb4713c79
```
- Abrir um browser e colar a url gerada

### Como desligar o serviço
- Estando na pasta raiz do projeto:
```
cd jupyter
make down
```

### Como ver logs do container
- Estando na pasta raiz do projeto:
```
cd jupyter
make get-logs
```
