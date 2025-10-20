# 🌐 Spring Boot API RESTful Web Service

Este projeto é um **serviço web RESTful** desenvolvido em **Spring Boot**, que demonstra o funcionamento básico de uma API simples que retorna saudações.  
O projeto foi criado a partir do **Spring Initializr** e pode ser executado com **Maven** ou **Gradle**.

---

## 🚀 Tecnologias utilizadas
- **Java 17+**
- **Spring Boot**
- **Spring Web**
- **Maven**

---

---

## ⚙️ Como configurar o projeto

### 🔹 1. Gerar o projeto pelo Spring Initializr
Acesse [https://start.spring.io](https://start.spring.io)

- **Project:** Maven 
- **Language:** Java  
- **Spring Boot:** versão estável mais recente  
- **Dependencies:**  
  - `Spring Web`

Clique em **Generate**, baixe o `.zip` e extraia o conteúdo.

---

## 🧰 Clonar o repositório

```bash
git clone https://github.com/LuanPirr3/Spring_Boot_Api_Restful_Web_Service.git
cd Spring_Boot_Api_Restful_Web_Service
```

---

## ▶️ Executar o servidor

### 🧩 Se estiver usando **Maven**
```bash
./mvnw spring-boot:run
```

O servidor será iniciado por padrão em:
```
http://localhost:8080
```

---

## 🌐 Testar a API

Abra o navegador ou use o `curl`:

### Endpoint principal:
```bash
http://localhost:8080/greeting
```

**Retorno esperado:**
```json
{"id":1,"content":"Hello, World!"}
```

### Endpoint com parâmetro:
```bash
http://localhost:8080/greeting?name=User
```

**Retorno esperado:**
```json
{"id":2,"content":"Hello, User"}
```

---

## 🧠 Conceitos principais
- **Spring Boot** fornece um servidor embutido (Tomcat) para rodar a aplicação facilmente.  
- **Spring Web** permite criar endpoints RESTful com anotações simples como `@RestController` e `@GetMapping`.  
- **Java Record** simplifica a criação de classes imutáveis.  

---

