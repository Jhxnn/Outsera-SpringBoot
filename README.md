Como rodar o projeto

1. **Clone o repositório**

```bash
git clone https://github.com/Jhxnn/Outsera.git
cd outsera
```

2. **Rode o projeto**
```bash
mvn spring-boot:run
```


3. **Rode os testes**
```bash
mvn test
```


4. Acesse o endpoint no navegador para ver todos os filmes:
   http://localhost:8080/movie


Exemplo de resposta:

![image](https://github.com/user-attachments/assets/f76775bf-e80c-49b3-85a1-fa76d559ca82)



5. Acesse o endpoint para ver o maior e menor intervalo de prêmios de um produtor:
   http://localhost:8080/movie/interval

Exemplo de resposta:

![image](https://github.com/user-attachments/assets/c653f01f-3fdc-4bb5-b7ad-d3b15d405afa)

6. Acesse o endpoint para ver a documentação do projeto:
   http://localhost:8080/swagger-ui/index.html