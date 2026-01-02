# Buscador de CEP – Java 17

Aplicação desenvolvida em **Java 17** para consulta de endereços a partir de um **CEP informado pelo usuário**, utilizando a API pública **ViaCEP**.  
O projeto foi **orientado pela Alura** com o objetivo de praticar **consumo de APIs REST**, **manipulação de dados em JSON** e **conceitos de Orientação a Objetos**.

---

## 📌 Visão Geral

O sistema realiza uma requisição HTTP para a API ViaCEP, processa a resposta e apresenta ao usuário as informações de endereço. Além disso, os dados retornados são persistidos em um arquivo JSON nomeado de acordo com o CEP consultado.

---

## ⚙️ Funcionalidades

- Entrada de CEP via terminal
- Consumo da API ViaCEP
- Exibição das seguintes informações:
  - CEP
  - Logradouro
  - Complemento
  - Localidade
  - UF
- Geração automática de arquivo JSON contendo os dados da consulta
  - Padrão de nome do arquivo:  
    ```
    {numeroDoCep}.json
    ```

---

## 🛠️ Tecnologias e Recursos

- **Java 17**
- **API ViaCEP**
- **HTTP Client (java.net.http)**
- **Serialização de dados em JSON**
- **Manipulação de arquivos**
- **Orientação a Objetos**

---

## 🌐 API Utilizada

**ViaCEP – Webservice de CEP**
https://viacep.com.br/
