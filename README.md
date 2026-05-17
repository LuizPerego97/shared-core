# shared-core
Módulo compartilhado entre os microsserviços **lumiere-backend** e **ticket-master-backend**. 

O objetivo deste projeto é centralizar utilitários, configurações e componentes comuns para evitar duplicação de código e garantir consistência arquitetural no ecossistema.

## 🛠️ Tecnologias
* **Java 25**
* **Spring Boot 3.x**

## 🛑 Funcionalidades Atuais
* **Global Exception Handler:** Centralização e padronização das respostas de erro da API (ex: `ResourceNotFoundException`), retornando JSONs limpos em vez de estourar Erro 500/StackTraces no cliente.

## 📦 Como usar localmente

1. Na raiz do projeto `shared_core`, compile e instale o JAR no seu repositório Maven local:
   ```bash
   mvn clean install
