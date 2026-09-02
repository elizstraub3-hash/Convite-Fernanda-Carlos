# Convite de Casamento — Francieli & Carlos Eduardo

Convite digital (página única) com contagem regressiva, painel de confirmação de presença e mural de fotos.

**Data:** 06 de fevereiro de 2027, às 11h · É da Pam Café Colonial

## Como personalizar

Abra o arquivo `index.html` e ajuste 2 coisas:

### 1. WhatsApp do casal (para receber as confirmações)
No final do arquivo, dentro do `<script>`, troque o número:
```js
var WHATSAPP = "5551999999999"; // 55 (Brasil) + DDD + número, só dígitos
```

### 2. As 3 fotos do mural
Procure por `<!-- Substitua o conteúdo de cada <figure> -->` e troque cada bloco `<div class="ph">...</div>` por uma imagem:
```html
<figure><img src="foto1.jpg" alt="Francieli e Carlos"></figure>
```
Coloque as imagens `foto1.jpg`, `foto2.jpg`, `foto3.jpg` na mesma pasta do `index.html`.

## Como publicar
É só um arquivo `index.html` — pode subir em qualquer hospedagem estática (GitHub Pages, Netlify, Vercel) ou abrir direto no navegador.

## Recursos
- ⏳ Contagem regressiva automática até a data
- 🤍 Painel de confirmação de presença (salva no dispositivo + envia pro WhatsApp do casal)
- 🖼️ Mural de 3 fotos
- 📖 História do casal
- 📍 Botão "Ver no mapa"
- 📱 Responsivo (celular e desktop)
