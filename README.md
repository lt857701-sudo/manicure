# Nailé Nail Studio

Site institucional do estúdio de unhas Nailé — cuidado premium, nail art exclusiva e autocuidado para suas unhas.

## 🚀 Tecnologias

- HTML5 semântico
- [Tailwind CSS](https://tailwindcss.com/) (via CDN)
- Fontes Google: Cormorant Garamond, Plus Jakarta Sans, Caveat
- JavaScript vanilla (mínimo, sem dependências)

## 📁 Estrutura

```
nailé-nail-studio/
├── index.html
├── assets/
│   ├── css/
│   │   └── style.css        # Estilos customizados (tipografia, transições)
│   ├── js/
│   │   └── main.js          # Scroll suave, ano automático, nav mobile
│   └── images/
│       ├── hero.png         # Imagem principal da Hero (modelo)
│       └── screen.png       # Captura de referência do site
├── README.md
└── .gitignore
```

## ▶️ Rodar localmente

Basta abrir o `index.html` no navegador, ou usar um servidor estático:

```bash
# Com Python
python -m http.server 5173
# Acesse: http://localhost:5173

# Ou com Node (http-server)
npx http-server -p 5173
```

## ☁️ Deploy

### Vercel
1. Conecte este repositório na [Vercel](https://vercel.com)
2. Import → selecione o repo `manicure`
3. Deploy automático a cada push na `main`

### Hostinger / HostGator
1. Faça upload do conteúdo da pasta (exceto `.git`) via FTP ou Gerenciador de Arquivos
2. Aponte o domínio para a pasta raiz onde está o `index.html`
3. Não é necessário banco de dados nem build — é um site estático

## 📄 Licença

Uso exclusivo do estúdio Nailé Nail Studio.
