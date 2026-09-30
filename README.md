# 🎬 CineHouse

O **CineHouse** é um projeto web dedicado a notícias e críticas de cinema. Atualmente, é uma aplicação estática focada na estrutura e estilização de conteúdo, servindo como base para futuras implementações de backend e dinâmica de dados.

## 🛠️ Tecnologias Utilizadas
- **HTML5** (Estrutura e semântica)
- **CSS3** (Estilização e layout)

## 📂 Estrutura do Projeto
```text
CineHouse/
├── cartazes/       # Imagens e assets visuais dos filmes
├── frontend/       # Páginas principais e estrutura do site
├── noticias/       # Conteúdo estático de notícias e críticas
└── styles/         # Folhas de estilo CSS
```

## 🚀 Como Executar
Sendo um projeto estático, a execução é simples e não requer servidores complexos:

1. Clone o repositório:
```bash
   git clone https://github.com/Helder-Maneco/CineHouse.git
   cd CineHouse
```
2. Abra o ficheiro `index.html` (ou o equivalente na pasta `frontend`) diretamente no teu navegador.
3. *(Opcional)* Para simular um ambiente de produção, usa um servidor local:
```bash
   # Com Python
   python3 -m http.server 8000
   
   # Com Node.js
   npx http-server
```

## 🔮 Próximos Passos (Roadmap Backend)
Este projeto é uma base. Para evoluir a arquitetura, os próximos passos incluem:
- [ ] Migrar o conteúdo estático (notícias/críticas) para um ficheiro `data.json`.
- [ ] Usar **JavaScript (Fetch API)** para renderizar os dados dinamicamente no frontend.
- [ ] Desenvolver uma API simples em **Node.js (Express)** ou **Ruby (Sinatra/Rails)** para servir os dados e gerir um futuro sistema de comentários ou avaliações.

## 📝 Licença
Este projeto está sob a licença MIT. Sente-te à vontade para estudar e modificar.
