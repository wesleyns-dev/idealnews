# 🌐 Ideal Conecta

O **Ideal Conecta** é uma plataforma web desenvolvida para centralizar informações, eventos comunitários, cultura e a história do distrito de Ideal (Aracoiaba - CE). O objetivo principal é conectar a comunidade e manter todos informados sobre torneios regionais, programações e notícias locais.

🚀 **Acesse o site ao vivo:** [conectaidealweb.vercel.app](https://conectaidealweb.vercel.app/)

---

## 📌 Funcionalidades

- **Destaque do Último Evento:** Exibição dinâmica do evento mais recente na página inicial com atalho para a visualização de detalhes.
- **Listagem de Eventos:** Página dedicada para visualizar a agenda de eventos locais e torneios (futsal masculino, feminino, etc.).
- **Detalhamento de Eventos:** Páginas individuais com informações completas (data, horário, premiação, regras e apoio).
- **Design Totalmente Responsivo:** Layout fluido e adaptado para dispositivos móveis (smartphones) e computadores (desktop).
- **Conteúdo Cultural:** Seções informativas com história local e o hino oficial da região.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação semântica do conteúdo.
- **CSS3:** Estilização moderna, consumo de *flexbox*, *CSS grid* e *media queries* para responsividade completa.
- **JavaScript (Vanilla JS):** Lógica de renderização dinâmica de eventos via consumo de arquivos JSON locais.
- **JSON:** Armazenamento estruturado dos dados dos eventos.
- **Vercel:** Plataforma de hospedagem e *deploy* contínuo integrado ao GitHub.

---

## 📁 Estrutura do Projeto

```text
├── css/                  # Arquivos de estilo (estilos globais e responsivos)
├── js/                   # Scripts JavaScript (carregamento de eventos e lógica)
├── json/                 # Arquivos de dados (eventos.json)
├── imagens/              # Imagens do site, logotipos e cartazes dos eventos
├── index.html            # Página inicial
├── eventos.html          # Página da lista de eventos
├── detalhes-evento.html  # Página de detalhes do evento selecionado
└── README.md             # Documentação do projeto
