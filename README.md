# 📦 Delivery API

API de Delivery desenvolvida em **Java 21** com **Spring Boot 3.5.6**.  
Projeto acadêmico com foco em praticar **configuração de projetos Spring Boot, endpoints REST, DevTools e banco de dados em memória H2**.

---

## 🚀 Tecnologias Utilizadas
- **Java 21**
- **Spring Boot 3.5.6**
- **Spring Web**
- **Spring Data JPA**
- **Lombok**
- **H2 Database**
- **DevTools**

---

## 📂 Estrutura do Projeto
delivery-api/
├── pom.xml
├── src/main/java/com/deliverytech/delivery_api
│ ├── DeliveryApiApplication.java # Classe principal
│ └── controller
│ └── HealthController.java # Endpoints de Health e Info
└── src/main/resources
└── application.properties # Configurações da aplicação

## ⚙️ Como Rodar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/KayBranco/delivery-api.git
Entre no diretório do projeto:


cd delivery-api
Compile e rode a aplicação:

mvn spring-boot:run
Acesse a aplicação em:

Health Check → http://localhost:8080/health

Informações → http://localhost:8080/info

Console do H2 → http://localhost:8080/h2-console

🔍 Exemplos de Respostas
Health Check
{
  "status": "UP",
  "timestamp": "2025-10-01T11:10:30",
  "service": "Delivery API",
  "javaVersion": "21"
}
Info
{
  "application": "Delivery Tech API",
  "version": "1.0.0",
  "developer": "Kaiky Lucas",
  "javaVersion": "JDK 21",
  "framework": "Spring Boot 3.x"
}
🛠️ Testando o DevTools
Alterar o retorno do endpoint /health (campo service).

Salvar o arquivo.

O DevTools reinicia automaticamente a aplicação.

Recarregar /health no navegador → o novo valor é exibido.

📸 Inserir print aqui

🖼️ Prints de Validação
Aplicação rodando no terminal 

Endpoint /health 

Endpoint /info 

Console do H2 (/h2-console) 

Teste de hot reload com DevTools 

📸 Inserir prints aqui


👤 Kaiky Lucas
Estudante de Engenharia da Computação - UNITAU
Apaixonado por tecnologia e desenvolvimento de software.