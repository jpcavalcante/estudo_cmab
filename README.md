# MAB Contextual · Alertas Pix Anti-Fraude

Pacote de materiais (100% offline, exceto fórmulas do deck técnico) sobre o sistema de
Multi-Armed Bandit contextual para personalização de alertas anti-fraude em Pix.

## Conteúdo

| Arquivo | O que é |
|---|---|
| `index.html` | Central de materiais — comece por aqui |
| `apostila.html` | Apostila técnica completa (32 seções, exemplos e exercícios) |
| `deck-executivo.html` | Deck visual para o fórum de diretores (21 slides) |
| `roteiro-executivo.html` | Roteiro para montar o PowerPoint executivo |
| `deck-tecnico.html` | Deck visual técnico para cientistas de dados (14 slides) |
| `roteiro-tecnico.html` | Roteiro para montar o PowerPoint técnico |
| `assets/style.css` | Folha de estilo compartilhada pelos documentos de texto |

## Como publicar com GitHub Pages

1. Crie um repositório vazio no GitHub (não inicialize com README).
2. No seu computador, dentro da pasta com estes arquivos:
   ```bash
   git init
   git add .
   git commit -m "Materiais MAB Pix"
   git branch -M main
   git remote add origin https://github.com/SEU-USUARIO/SEU-REPO.git
   git push -u origin main
   ```
3. No GitHub: **Settings → Pages → Source → Deploy from a branch → `main` / `/ (root)` → Save**.
4. Em ~1 minuto o site fica no ar em `https://SEU-USUARIO.github.io/SEU-REPO/`.

## Observações

- Todos os links entre os arquivos são relativos — funcionam tanto no GitHub Pages quanto
  abrindo `index.html` localmente no navegador, desde que a pasta `assets/` seja mantida junto.
- `deck-tecnico.html` carrega o MathJax via CDN (`cdnjs.cloudflare.com`) para renderizar as
  fórmulas — é a única dependência de internet do pacote.
- O GitHub **não renderiza HTML no site do repositório** (só mostra o código-fonte). É preciso
  ativar o GitHub Pages (passo 3) ou abrir os arquivos localmente para navegar de verdade.
