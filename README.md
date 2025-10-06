# 📦 Delivery API

API de Delivery desenvolvida em *Java 21* com *Spring Boot 3.5.6*.  
Projeto acadêmico com foco em praticar *configuração de projetos Spring Boot, endpoints REST, DevTools e banco de dados em memória H2*.



## 🚀 Tecnologias Utilizadas
- *Java 21*
- *Spring Boot 3.5.6*
- *Spring Web*
- *Spring Data JPA*
- *Lombok*
- *H2 Database*
- *DevTools*



## 📂 Estrutura do Projeto

```bash
delivery-api/
├── pom.xml
├── src/
│   └── main/
│       ├── java/
│       │   └── com/
│       │       └── deliverytech/
│       │           └── delivery_api/
│       │               ├── DeliveryApiApplication.java   # Classe principal
│       │               └── controller/
│       │                   └── HealthController.java     # Endpoints de Health e Info
│       └── resources/
│           └── application.properties                    # Configurações da aplicação
```

## ⚙ Como Rodar o Projeto
	1.	Clone este repositório:

git clone https://github.com/KayBranco/delivery-api.git


	2.	Entre no diretório do projeto:

cd delivery-api


	3.	Compile e rode a aplicação:

mvn spring-boot:run


	4.	Acesse a aplicação em:
	•	Health Check: http://localhost:8080/health
	•	Informações: http://localhost:8080/info
	•	Console do H2: http://localhost:8080/h2-console


## 🔍 Exemplos de Respostas

🩺 Health Check

{
  "status": "UP",
  "timestamp": "2025-10-01T11:10:30",
  "service": "Delivery API",
  "javaVersion": "21"
}

ℹ Info

{
  "application": "Delivery Tech API",
  "version": "1.0.0",
  "developer": "Kaiky Lucas",
  "javaVersion": "JDK 21",
  "framework": "Spring Boot 3.5.6"
}

## 🛠 Testando o DevTools

	1.	Altere o retorno do endpoint /health (campo service).
	2.	Salve o arquivo.
	3.	O DevTools reinicia automaticamente a aplicação.
	4.	Recarregue /health no navegador → o novo valor é exibido.



## 🖼 Prints de Validação

⚙ Aplicação rodando no terminal

<img width="706" height="384" alt="image" src="https://github.com/user-attachments/assets/ab4b8de3-a540-4d18-9c81-2e617c2cb4ed" />


🩺 Endpoint /health

<img width="682" height="276" alt="image" src="https://github.com/user-attachments/assets/54dca7c9-984f-43ac-adc7-c87e2e816ef4" />


ℹ Endpoint /info

<img width="668" height="326" alt="image" src="https://github.com/user-attachments/assets/210df263-6a61-4eb9-a502-80e83b3735d3" />


💾 Console do H2 (/h2-console)

<img width="663" height="464" alt="image" src="https://github.com/user-attachments/assets/4445ea78-1a65-49ea-99ec-741e71dcc522" />


🔁 Teste de Hot Reload com DevTools

<img width="663" height="220" alt="image" src="https://github.com/user-attachments/assets/b98714c5-3866-4484-88b4-f91dc51c12da" />





👤 Kaiky Lucas
```
Estudante de Engenharia da Computação - UNITAU
Apaixonado por tecnologia e desenvolvimento de software.
