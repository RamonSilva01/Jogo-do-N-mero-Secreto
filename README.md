# 🔢 Jogo do Número Secreto

Um pequeno jogo interativo feito com JavaScript, onde o usuário deve adivinhar um número secreto gerado aleatoriamente entre 1 e 100.

## 🕹️ Como jogar

- Ao abrir o jogo, será exibida a mensagem: **"Escolha entre 1 e 100"**.
- Digite um número no campo de entrada e clique no botão para verificar.
- O jogo irá informar se o número secreto é **maior** ou **menor** que o chute.
- Ao acertar, uma mensagem de sucesso será exibida com o número de tentativas.
- O botão **Reiniciar Jogo** será habilitado para começar uma nova rodada.

## ✨ Funcionalidades

- Geração aleatória de número secreto sem repetição.
- Interface com feedback auditivo via `responsiveVoice`.
- Estilização moderna com `CSS` e suporte responsivo.
- Botão de reinício desabilitado até que o jogo termine.

## 🧪 Tecnologias utilizadas

- **HTML5**
- **CSS3**
- **JavaScript (Vanilla JS)**
- **[ResponsiveVoice](https://responsivevoice.org/)** para narração de textos

## 📁 Estrutura do projeto

```
📦 jogo-numero-secreto/
├── index.html
├── app.js
├── style.css
└── /img
    ├── code.png
    └── Ruido.png
```

## 🖼️ Estilo visual

- Cores em gradiente para o fundo
- Fontes personalizadas (`Chakra Petch` e `Inter`)
- Design responsivo para telas menores
- Imagens de fundo com opacidade para efeito visual

## 🔄 Regras do jogo

- O número é sorteado de forma aleatória entre 1 e 100.
- O mesmo número não será sorteado duas vezes seguidas.
- A cada tentativa incorreta, o jogador recebe uma dica.
- O jogo contabiliza as tentativas e apresenta ao final.

## 🚀 Como executar localmente

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

2. Navegue até a pasta do projeto:
```bash
cd seu-repositorio
```

3. Abra o `index.html` em seu navegador.

## 📌 Observações

- Certifique-se de estar conectado à internet para que a biblioteca `responsiveVoice` funcione corretamente.
- As imagens de fundo devem estar na pasta `/img` com os nomes exatos: `code.png` e `Ruido.png`.

## 📄 Licença

Este é um projeto de código aberto..

---

Desenvolvido com ❤️ por Ramon Silva
