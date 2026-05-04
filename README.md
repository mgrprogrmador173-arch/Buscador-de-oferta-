# Retro Mobile Racer

Jogo de corrida arcade com visual retrô/pseudo-3D, HUD completo e controles móveis na tela.

## Como jogar
1. Abra `index.html` no navegador.
2. Clique em **INICIAR CORRIDA**.
3. O carro acelera sozinho.
4. Use `←` e `→` (teclado) ou os botões na tela para desviar do tráfego.
5. Colisões aumentam o dano; ao chegar em 100, a corrida termina.
# Top Racer 3D Mini (inspirado em Top Gear)

Minigame de corrida em HTML5 Canvas com visual pseudo-3D, som dinâmico de motor e controles por teclado + botões touch invisíveis na tela.

## Novidades
- Renderização pseudo-3D com profundidade (escala por distância).
- Cenário com horizonte e sensação de relevo/velocidade.
- Som procedural (WebAudio): motor contínuo + efeitos de colisão/coleta.
- Botão de mute e botões de controle sobre o canvas para mobile.
- Tráfego, pickups de combustível, HUD e recorde local.

## Como jogar
1. Abra `index.html` no navegador.
2. Clique em **Iniciar / Reiniciar**.
3. Use setas do teclado ou botões na tela.
4. Evite colisões e colete combustível para bater o recorde.

## Correções de conflito de controle
- Eventos touch/mouse duplicados foram consolidados em Pointer Events para evitar entradas repetidas.
- Adicionado reset de entradas em troca de aba/perda de foco para não travar comandos pressionados.
