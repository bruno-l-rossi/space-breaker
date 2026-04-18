# 🚀 Space Breaker

Um jogo de breakout com tema espacial, jogável no navegador — desktop e mobile.

## Como jogar

- **Desktop:** setas ou `A/D` para mover a nave · `Espaço` para lançar a bola · `P` ou `Esc` para pausar
- **Mobile:** deslize na tela ou use os botões ◀ ▶ · toque em **Lançar** para soltar a bola

## Funcionalidades

- 6 fases com layouts criativos e dificuldade progressiva
- Asteroides com 1, 2 ou 3 pontos de vida — e blocos de aço indestrutíveis
- Velocidade da bola aumenta gradualmente com o tempo e com cada asteroide destruído
- Power-ups: **Turbo**, **Largo**, **Estreito** e **Bola Dupla**
- Efeitos sonoros sintetizados via Web Audio API
- Animações de explosão e trilha da bola
- Totalmente responsivo — funciona bem em qualquer tamanho de tela

## Assets

Sprites do pack [Kenney Space Shooter Remastered](https://kenney.nl/assets/space-shooter-remastered) (CC0).

## Deploy

Hospedado via [Netlify](https://netlify.com), com deploy contínuo a partir deste repositório.

## Estrutura

```
space-breaker/
├── index.html        # jogo completo (HTML + CSS + JS em um único arquivo)
└── assets/
    ├── Backgrounds/
    └── PNG/
        ├── Enemies/
        ├── Meteors/
        └── Power-ups/
```
