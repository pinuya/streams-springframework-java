# Streams Spring Framework Java
Este projeto é um estudo prático de Streams em Java, utilizando Spring Boot como base para organização e estrutura. A ideia é demonstrar conceitos fundamentais e avançados de manipulação de dados com Streams.

### Tecnologias utilizadas

- Java 17+
- Spring Boot 3+
- Maven (gerenciador de dependências)

---

## Como rodar o projeto localmente

### Pré-requisitos
Antes de começar, você vai precisar ter instalado na sua máquina:
-   Java 17 ou superior
- [Download Java](https://www.oracle.com/java/technologies/downloads/)
- Maven (opcional, mas recomendado para compilar/rodar o projeto)
- [Download Maven](https://maven.apache.org/download.cgi)
- Uma IDE (recomendado: IntelliJ IDEA ou Eclipse), ou use qualquer editor de código.

### Passo a passo
1. Clone o repositório
```
git clone https://github.com/pinuya/streams-springframework-java.git
cd streams-springframework-java
```

2. Importe o projeto na sua IDE
   Se estiver usando IntelliJ ou Eclipse:
- Escolha a opção "Importar projeto Maven".
- O Maven irá baixar todas as dependências automaticamente.

3. Rodando o projeto

    Se estiver usando a linha de comando:

```
./mvnw spring-boot:run
```

Ou no Windows:

```
mvnw.cmd spring-boot:run
```
> Obs: Se preferir, você pode rodar direto pela IDE clicando na classe StreamsSpringframeworkJavaApplication.java e executando como uma aplicação Java.

4. Acessando a aplicação

Após rodar o projeto, ele sobe um servidor local, geralmente em:

`http://localhost:8080
`

---

## Estrutura do projeto

```
src
└── main
    └── java
        └── com
            └── pinuya
                └── streams
                    ├── controller  // Controladores REST (se houver)
                    ├── model       // Modelos de dados
                    ├── service     // Lógica de negócio
                    └── StreamsSpringframeworkJavaApplication.java // Classe principal

```

---

Feito com ❤️ por [Tifany](https://github.com/pinuya)