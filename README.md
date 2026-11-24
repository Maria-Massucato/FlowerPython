# Flor Pontilhista 🌸

Um experimento de arte generativa pontilhista em Python que simula o ciclo de vida de uma flor: ela brota em um solo texturizado, desabrocha em camadas de pétalas, emite partículas luminosas e, gradualmente, murcha.

## Recursos
- **Pontilhismo procedural:** desenha o solo, o caule, as folhas e as pétalas com dezenas de milhares de partículas dinâmicas, em vez de áreas preenchidas.
- **Ciclo de vida com quadros-chave:** interpola suavemente entre diferentes fases: movimentação do solo, crescimento do caule, abertura das folhas, florescimento e murchamento.
- **Curvas de Bézier e projeções 3D:** usa curvas cúbicas de Bézier para o caule e projeta pétalas em camadas, com ordenação por profundidade e movimento ao vento.
- **Efeitos atmosféricos e aura:** inclui anéis de energia, estames pulsantes, halos suaves e partículas de pétalas que se desprendem quando a flor murcha.
- **Interface interativa e exportação:** abre uma janela Tkinter com controles pelo teclado (`Espaço`, `R`, `S`, `Esc`) e permite exportar imagens PNG ou uma animação GIF.

## Como executar

É necessário ter o Python instalado. Instale as dependências:

```bash
python -m pip install numpy pillow
```

Inicie a janela interativa:

```bash
python flow.py
```

Controles: `Espaço` pausa ou retoma a animação, `R` reinicia, `S` salva o quadro atual como `flower_frame.png` e `Esc` fecha a janela.

Para exportar imagens das etapas da flor ou uma animação:

```bash
python flow.py --png
python flow.py --gif
```
