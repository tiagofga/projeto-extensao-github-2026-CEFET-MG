# Projeto Extensão GitHub 2026

Página colaborativa dos alunos do CEFET-MG, publicada com GitHub Pages.

## Como editar

1. Abra o arquivo `index.html`.
2. Substitua “Nome do aluno” e o texto de um cartão pelos seus dados.
3. Em **Settings > Pages**, configure **Source** como **GitHub Actions** antes do primeiro deploy automático.
4. Faça um commit e envie a alteração para a branch `main`.

O workflow em `.github/workflows/pages.yml` publica automaticamente a página após cada alteração na `main`. Sem a configuração inicial do GitHub Pages, a etapa `Configurar GitHub Pages` falha no workflow de deploy.