# 🐍 Snake Game

Uma versão moderna do clássico **Jogo da Cobrinha (Snake)** desenvolvida utilizando apenas **HTML5, CSS3 e JavaScript Vanilla**, sem qualquer dependência externa.

O projeto foi criado para funcionar diretamente em navegadores modernos através de um único arquivo `index.html`, tornando sua execução extremamente simples e portátil.

---

## 🎮 Demonstração

O objetivo do jogo é controlar a cobrinha, coletar alimentos e acumular a maior pontuação possível sem colidir com as paredes ou com o próprio corpo.

### Controles

| Tecla | Ação                  |
| ----- | --------------------- |
| ⬆️    | Mover para cima       |
| ⬇️    | Mover para baixo      |
| ⬅️    | Mover para a esquerda |
| ➡️    | Mover para a direita  |

---

## ✨ Funcionalidades

* ✅ Controle por teclado utilizando as setas direcionais
* ✅ Movimentação em grade
* ✅ Geração aleatória de comida
* ✅ Crescimento progressivo da cobrinha
* ✅ Sistema de pontuação em tempo real
* ✅ Detecção de colisão com as bordas
* ✅ Detecção de colisão com o próprio corpo
* ✅ Tela de Game Over
* ✅ Exibição da pontuação final
* ✅ Reinício da partida com um clique
* ✅ Interface moderna e responsiva
* ✅ Animações suaves
* ✅ Compatível com navegadores modernos

---

## 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido sem bibliotecas ou frameworks.

* HTML5
* CSS3
* JavaScript (ES6+)

---

## 📁 Estrutura do Projeto

```text
snake-game/
│
└── index.html
```

Todo o código está contido em um único arquivo:

```text
index.html
├── Estrutura HTML
├── Estilos CSS
└── Scripts JavaScript
```

---

## 🚀 Como Executar

### Opção 1 — Abrir diretamente

Basta baixar ou clonar o projeto e abrir o arquivo:

```text
index.html
```

em qualquer navegador moderno.

### Opção 2 — Servidor Local

Caso prefira executar via servidor local:

```bash
# Python
python -m http.server
```

Depois acesse:

```text
http://localhost:8000
```

---

## 🎯 Regras do Jogo

1. A cobrinha inicia no centro do tabuleiro.
2. Cada alimento consumido aumenta seu tamanho.
3. Cada alimento consumido adiciona pontos ao placar.
4. O jogo termina quando:

   * A cobrinha toca uma parede.
   * A cobrinha colide com seu próprio corpo.
5. Após o Game Over é possível reiniciar a partida.

---

## 📱 Responsividade

O layout foi desenvolvido para se adaptar a diferentes resoluções de tela:

* Desktop
* Notebook
* Tablet
* Smartphone

A área de jogo permanece centralizada para garantir uma boa experiência em qualquer dispositivo.

---

## 🎨 Características Visuais

* Interface moderna
* Painel com efeito glassmorphism
* Paleta de cores agradável
* Contraste otimizado para leitura
* Animações suaves
* Feedback visual para ações do jogador

---

## ⚙️ Arquitetura do Código

O JavaScript foi organizado em módulos lógicos:

### Inicialização

Responsável por configurar o estado inicial do jogo.

### Loop Principal

Executa continuamente:

* Atualização da posição da cobrinha
* Verificação de colisões
* Consumo de alimentos
* Atualização da pontuação

### Sistema de Renderização

Responsável por desenhar:

* Grade
* Cobrinha
* Comida
* Interface

### Controle de Entrada

Captura os eventos do teclado e altera a direção da cobrinha.

### Gerenciamento de Estado

Controla:

* Início do jogo
* Pontuação
* Game Over
* Reinício

---

## 📈 Possíveis Melhorias Futuras

* Sistema de recordes (High Score)
* Armazenamento utilizando LocalStorage
* Sons e efeitos sonoros
* Diferentes níveis de dificuldade
* Obstáculos dinâmicos
* Modo infinito
* Modo multiplayer local
* Suporte a controles touch
* Ranking online
* Temas visuais customizáveis

---

## 🤝 Contribuição

Contribuições são bem-vindas.

Caso deseje melhorar o projeto:

1. Faça um Fork
2. Crie uma Branch

```bash
git checkout -b feature/minha-feature
```

3. Faça suas alterações

```bash
git commit -m "feat: adiciona nova funcionalidade"
```

4. Envie para seu repositório

```bash
git push origin feature/minha-feature
```

5. Abra um Pull Request

---

## 📄 Licença

Este projeto está disponível sob a licença MIT.

Sinta-se livre para estudar, modificar e distribuir.

---

## 👨‍💻 Autor

Desenvolvido como uma implementação moderna do clássico Snake Game utilizando tecnologias web nativas.

Se este projeto foi útil para você, considere deixar uma ⭐ no repositório.
