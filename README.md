# Lotus Lounge

PT-BR | [EN](#EN)

<img width="1280" height="720" alt="Gameplay de Lotus Lounge" src="https://github.com/user-attachments/assets/c8aecb19-8f86-401c-9775-b741e3ae4c28" />

## PT-BR

### Sobre o projeto
**Lotus Lounge** e um jogo 2D feito em **C** com **Raylib**, com foco em arquitetura modular, gameplay responsiva e fundamentos de desenvolvimento de jogos em baixo nivel.

Este repositorio representa um projeto de portifolio que demonstra:
- Organizacao de codigo em modulos (`menu`, `game`, `player`, `phaseOne`)
- Estrutura clara de loop principal, estados e transicoes
- Integracao de renderizacao, input e audio com Raylib
- Base preparada para expansao de fases e mecanicas

### Stack
- **Linguagem:** C
- **Framework:** Raylib
- **Build:** Makefile (`mingw32-make`)
- **Ambiente:** VS Code

### Estrutura do repositorio
```text
.
|- assets/      # imagens, fontes e recursos visuais
|- data/        # anotacoes e suporte de dados
|- saves/       # pasta reservada para saves
|- utils/       # utilitarios e notas
|- main.c       # ponto de entrada
|- menu.c       # telas e navegacao de menu
|- game.c/h     # estado principal e logica do jogo
|- player.c     # movimentacao e comportamento do jogador
|- phaseOne.c   # primeira fase
`- Makefile     # compilacao
```

### Como executar
1. Garanta que o Raylib esteja instalado e com caminho configurado no `Makefile`.
2. Compile em modo debug:
   ```bash
   mingw32-make RAYLIB_PATH=C:/raylib/raylib PROJECT_NAME=main OBJS=main.c BUILD_MODE=DEBUG
   ```
3. Execute o binario gerado.

### Destaques tecnicos
- Separacao de responsabilidades por arquivo para facilitar manutencao
- Pipeline simples e eficiente para prototipacao de gameplay
- Fundacao ideal para evoluir para novas fases, inimigos e sistemas

### Time
- Andre Lima
- Lucas Leal
- Maria Gabriella
- Ismael Alvaro
- Matheus Braglia
- Milla Rwana
- Rayssa Vitoria

---

<a id="EN"></a>
## EN

### About the project
**Lotus Lounge** is a 2D game built in **C** using **Raylib**, focused on modular architecture, responsive gameplay, and low-level game development fundamentals.

This repository is presented as a portfolio project and showcases:
- Modular code organization (`menu`, `game`, `player`, `phaseOne`)
- Clear main loop and game-state transitions
- Rendering, input, and audio integration with Raylib
- A solid foundation for future gameplay and level expansion

### Tech stack
- **Language:** C
- **Framework:** Raylib
- **Build:** Makefile (`mingw32-make`)
- **Environment:** VS Code

### Repository structure
```text
.
|- assets/      # images, fonts, and visual resources
|- data/        # notes and support data
|- saves/       # reserved save folder
|- utils/       # utilities and notes
|- main.c       # entry point
|- menu.c       # menu screens and navigation
|- game.c/h     # core game state and logic
|- player.c     # player behavior and movement
|- phaseOne.c   # first level implementation
`- Makefile     # build configuration
```

### Run locally
1. Make sure Raylib is installed and the path is configured in the `Makefile`.
2. Build in debug mode:
   ```bash
   mingw32-make RAYLIB_PATH=C:/raylib/raylib PROJECT_NAME=main OBJS=main.c BUILD_MODE=DEBUG
   ```
3. Run the generated executable.

### Technical highlights
- File-level separation of concerns for maintainability
- Lightweight and efficient gameplay prototyping workflow
- Strong base for adding new levels, enemies, and mechanics

### Team
- Andre Lima
- Lucas Leal
- Maria Gabriella
- Ismael Alvaro
- Matheus Braglia
- Milla Rwana
- Rayssa Vitoria
