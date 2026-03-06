# Secret Word 🎮

Secret Word é um jogo simples de adivinhar palavras desenvolvido em **React**.  
O jogador deve descobrir uma palavra secreta digitando letras. Letras corretas revelam suas posições na palavra, enquanto letras incorretas diminuem o número de tentativas disponíveis.

O jogo possui **tela inicial**, **tela de jogo** e **tela de fim de jogo**, além de um sistema de **pontuação**.

---

# 📋 Sumário

- Introdução
- Funcionalidades
- Instalação
- Como Jogar
- Estrutura do Projeto
- Fluxo do Jogo
- Dependências
- Configuração
- Exemplos
- Solução de Problemas
- Contribuidores
- Licença

---

# 📖 Introdução

Secret Word é um jogo de navegador inspirado em jogos clássicos de **adivinhar palavras**, parecido com o jogo da forca.

O jogador recebe uma **dica de categoria** e precisa adivinhar qual é a palavra secreta, digitando **uma letra por vez**.

O jogo também possui:

- Sistema de **pontuação**
- Controle de **tentativas restantes**
- Registro de **letras erradas**

---

# ✨ Funcionalidades

- Tela inicial para começar o jogo
- Dica de categoria da palavra
- Sistema de tentativas
- Adivinhação letra por letra
- Validação de entrada (apenas uma letra)
- Sistema de pontuação
- Exibição de letras erradas
- Campo de entrada com foco automático
- Tela de **fim de jogo**
- Botão para **reiniciar o jogo**

---

# ⚙️ Instalação

1. Clone o repositório:

```bash
git clone https://github.com/seuusuario/secret-word.git
```

2. Entre na pasta do projeto:

```bash
cd secret-word
```

3. Instale as dependências:

```bash
npm install
```

4. Execute o projeto:

```bash
npm start
```

O projeto abrirá em: http://localhost:3000

🚀 Como Jogar

Abra o jogo no navegador.

Clique em "Começar o jogo".

Veja a categoria da palavra.

Digite uma letra no campo.

Clique em "Jogar!".

Continue tentando até:

descobrir a palavra, ou

acabar suas tentativas.

Ao final, sua pontuação será exibida.

📦 Dependências

Principais tecnologias utilizadas:

React

JavaScript

React Hooks

useState

useRef

Instalação básica:

```bash
npm install react
```

⚙️ Configuração

O componente Game recebe algumas props do componente principal (App.js):

Propriedade Descrição
verifyLetter Função que verifica a letra digitada
pickedWord Palavra secreta
pickedCategory Categoria da palavra
letters Letras da palavra
guessedLetters Letras corretas
wrongLetters Letras erradas
score Pontuação
guesses Tentativas restantes

🧪 Exemplo

Categoria:

Animais

Palavra:

ELEFANTE

Exibição inicial:

---

Se o jogador digitar:

E

Resultado:

E _ E _ \_ \_ \_ \_

👨‍💻 Contribuidores

Desenvolvido por:

Gabriel Santiago Davi com base no curso da UDEMY : React do Zero a Maestria (c/ hooks, router, API, Projetos)
