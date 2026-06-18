# FounderMatch — Discovery

App estilo Tinder para encontrar sócios de startup. Tela de descoberta (swipe) implementada a partir de um design do Figma, em **HTML/CSS/JS puro**, 100% offline.

🔗 **Demo:** https://foundermatch-beta.vercel.app

## Recursos
- **Swipe arrastável** (mouse/touch) — esquerda (pular), direita (conectar), cima (super like), com stamps e rotação.
- **Botões** X / ★ / ✓ e **Rewind** (desfaz o último swipe, estilo Tinder Gold).
- **Atalhos de teclado:** ← / → / ↑ e `R` (rewind).
- **Animação de entrada** dos cards e do chrome.
- **Modal "É um match!"** e empty state com recomeço.
- **Seed de 10 profissionais** com foto, tags, bio e % de compatibilidade.

## Offline / autossuficiente
- Fonte **Inter** empacotada localmente (`fonts/`).
- Retratos **1024×1024** locais (`img/`).
- Ícones como **SVG inline** (lucide). Nenhuma requisição externa.

## Rodar localmente
```bash
python3 -m http.server 4180
# abra http://localhost:4180
```

Fonte do design: Figma — "Teste Tinder empresário" (FounderMatch).
