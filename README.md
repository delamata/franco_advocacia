# Site de Escritório de Advocacia

Template estático em HTML/CSS para homepage de um escritório de advocacia, preparado para ser usado como base em WordPress ou hospedado no GitHub Pages.

## Estrutura

```text
.
├── index.html
├── css
│   └── style.css
└── img
    ├── hero-law.jpg
    ├── scales.png
    ├── team-photo.jpg
    ├── post1.jpg
    ├── post2.jpg
    └── post3.jpg
```

Substitua as imagens da pasta `img/` por arquivos reais (idealmente em formato `.webp` para melhor performance).

## Como usar no GitHub

1. Crie um repositório novo no GitHub (por exemplo, `advocacia-site`).
2. Faça o upload dos arquivos desta pasta para o repositório.
3. (Opcional) Ative o **GitHub Pages**:
   - Vá em **Settings > Pages**.
   - Em **Source**, selecione a branch (`main` ou `master`) e a pasta `/root`.
   - Salve. O GitHub gerará uma URL pública para o site.

## Como clonar e subir via Git

```bash
git init
git add .
git commit -m "Site estático do escritório de advocacia"
git branch -M main
git remote add origin git@github.com:SEU-USUARIO/advocacia-site.git
git push -u origin main
```

Depois é só acessar o repositório no GitHub e, se desejar, habilitar o GitHub Pages.
