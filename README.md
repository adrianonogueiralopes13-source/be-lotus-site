
# Bê Lótus - Site (Spring Boot + Thymeleaf)

Projeto gerado automaticamente. Estrutura pronta para rodar localmente e fazer deploy.

## Como rodar localmente
Requisitos: Java 17+, Maven

```bash
mvn clean package
java -jar target/be-lotus-site-1.0.0.jar
```

Abra no navegador: http://localhost:8080

## Deploy (opções gratuitas)
- Render.com: subir repositório no GitHub e conectar a Render (build: `mvn clean package`, start: `java -jar target/*.jar`).
- Railway.app: conectar repositório GitHub e seguir deploy guiado.

Logo copiada para o projeto como static/images/logo.png

## Personalização rápida
- Substitua `src/main/resources/static/images/logo.png` pela sua logo preferida.
- Atualize contatos em `src/main/resources/templates/contact.html`.
- Ajuste cores em `src/main/resources/static/css/styles.css`.

