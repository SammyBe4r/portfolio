# Portfólio — Samuel Oliveira

Site estático em português com uma seleção de projetos, uma apresentação breve e links para demonstrações e repositórios públicos.

## Executar localmente

Abra `index.html` no navegador. Não há dependências de build nem instalação necessária.

## Publicar no GitHub Pages

O workflow em `.github/workflows/pages.yml` publica o conteúdo da raiz do repositório no GitHub Pages quando há um push para `main` ou uma execução manual do workflow.

Na primeira publicação, abra **Settings → Pages** no repositório e selecione **GitHub Actions** como fonte de build, se essa opção ainda não estiver definida. Depois que o workflow terminar, o site estará disponível em `https://sammybe4r.github.io/portfolio/`.
