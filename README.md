# Ignite Timer - README

## Descrição do Projeto
O **Ignite Timer** é uma aplicação desenvolvida com React, utilizando Styled Components para estilização e gerenciamento de tema. O projeto implementa funcionalidades de temporizador, histórico de ciclos e gerenciamento de estado com `useReducer` e `context API`. A persistência de dados é realizada com `localStorage`, garantindo que as informações sejam mantidas entre sessões.

---

## Tecnologias Utilizadas
- **React**: Biblioteca JavaScript para construção de interfaces de usuário.
- **Styled Components**: Estilização de componentes com suporte a temas.
- **React Hook Form**: Gerenciamento de formulários de forma simples e eficiente.
- **Zod**: Validação e tipagem de dados.
- **Immer**: Manipulação imutável de estados.
- **Phosphor Icons**: Conjunto de ícones para aplicações web.
- **Date-fns**: Manipulação de datas.
- **React Router**: Gerenciamento de rotas.

---

## Funcionalidades
1. **Temporizador**
   - Criação de ciclos de tarefas com tempo pré-definido.
   - Pausa e interrupção do ciclo.
   - Contagem regressiva com exibição dinâmica no título da aba do navegador.

2. **Histórico**
   - Registro de tarefas realizadas, interrompidas ou em andamento.
   - Cálculo de tempo decorrido desde o início de cada ciclo.

3. **Gerenciamento de Estado**
   - Uso de `useReducer` e `context API` para armazenar ciclos e estado ativo.
   - Persistência de dados no `localStorage`.

4. **Validação de Dados**
   - Validação de campos do formulário com regras pré-definidas.

---

## Pré-requisitos
- Node.js versão 16 ou superior
- Gerenciador de pacotes (npm ou yarn)

---

## Como Executar o Projeto

### 1. Clonar o Repositório
```bash
git clone https://github.com/WigorCosta21/ignite-timer.git
cd ignite-timer
```

### 2. Instalar Dependências
```bash
npm install
# ou
yarn install
```

### 3. Iniciar a Aplicação
```bash
npm run dev
# ou
yarn dev
```

A aplicação estará disponível em: [http://localhost:5173](http://localhost:5173)

---

## Personalização do Tema
O arquivo `styles/themes/default.ts` contém as configurações de cores da aplicação. É possível adicionar novos temas ou alterar o tema existente.

---
