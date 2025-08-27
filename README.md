
# 📱 App de Empréstimos - React Native

Este projeto é um aplicativo mobile desenvolvido em **React Native** como parte de um desafio técnico. O app permite simular e contratar empréstimos com base em produtos cadastrados pelo usuário.

## 👨‍💻 Autor
**Lucas Bassichetto**

## 🎯 Objetivo
Criar um simulador de empréstimos com funcionalidades completas, incluindo cadastro de produtos, simulação com memória de cálculo mês a mês, histórico de contratações e integração com API.

## 🛠 Tecnologias Utilizadas
- React Native
- Context API + useReducer
- Axios (API mock)
- AsyncStorage
- Jest + React Native Testing Library
- StyleSheet / Tailwind / styled-components

## 📋 Funcionalidades
- Cadastro de produtos de empréstimo
- Visualização de produtos cadastrados
- Simulação de empréstimos com cálculo detalhado
- Confirmação de contratação
- Histórico de contratações
- Navegação entre telas

## 🧪 Testes
- Cobertura mínima de 80%
- Testes unitários e de integração com Jest e React Native Testing Library

## 🚀 Como Rodar o Projeto

1. Instale as dependências:
   ```bash
   npm install
   # ou
   yarn install
   ```

2. Inicie o projeto:
   ```bash
   npx expo start
   ```

3. Rode os testes:
   ```bash
   npm test
   ```

## 📦 Estrutura do Projeto
- `/components`: componentes reutilizáveis
- `/screens`: telas principais do app
- `/context`: gerenciamento de estado global
- `/services/api.js`: integração com API mock
- `/storage`: persistência com AsyncStorage

## 📈 Melhorias Futuras
- Autenticação de usuários
- Integração com APIs reais de crédito
- Persistência em banco local
- Estilização aprimorada

---

📄 Documentação completa disponível em PDF: [documentacao_projeto_final_sem_erro.pdf](./documentacao_projeto_final_sem_erro.pdf)
