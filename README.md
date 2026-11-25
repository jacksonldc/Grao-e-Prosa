# ☕ Grão & Prosa — Cafeteria Artesanal

Website institucional desenvolvido para a cafeteria artesanal **Grão & Prosa**, projetado para transmitir uma atmosfera rústica e acolhedora com navegação intuitiva entre a página inicial, o cardápio digital e o sistema de reservas.

🔗 **[Acessar Protótipo no Figma (Desktop & Mobile)](https://www.figma.com/proto/eZXYjapZAfhZUGTTleT4I6/Gr%C3%A3o---Prosa?node-id=0-1&t=NI2buaZKZB0dVUOg-1)**

---

## 📋 Sobre o Projeto

O **Grão & Prosa** nasceu do conceito de desacelerar a rotina unindo cafés especiais, receitas caseiras e um ambiente pensado para boas conversas. O projeto foi prototipado no **Figma** (versões Desktop e Mobile) e implementado utilizando **HTML5 semântico** e **CSS3 puro**, com foco em tipografia editorial, layout responsivo e fidelidade visual.

### Páginas e Funcionalidades

- **Página Inicial (`index.html`):**
  - Seção de apresentação (*Hero*) com chamada principal e acesso direto ao cardápio.
  - Seção **Nossa História** destacando os pilares da cafeteria (*100% Artesanal*, *Receitas de Família* e *Ambiente Acolhedor*).
  - Citação filosófica de Jean-Paul Sartre.
  - Vitrine dos ambientes internos (*Bancada do Barista* e *Canto da Prosa*).
- **Cardápio (`cardapio.html`):**
  - Organização em colunas categorizadas (*Cafés & Métodos*, *Para Acompanhar* e *Doces & Prosa*) com adaptação automática para leitura vertical em dispositivos móveis.
- **Reserva (`reserva.html`):**
  - Exibição de horários de funcionamento, endereço (Asa Norte, Brasília - DF) e canais de contato.
  - Formulário interativo para agendamento de mesas (nome, quantidade de pessoas, data, horário e e-mail).

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação semântica das páginas (`header`, `nav`, `section`, `main`, `footer`).
- **CSS3:** Estilização customizada com **Flexbox**, **CSS Grid**, unidades relativas (`rem`) e **Media Queries** para responsividade entre desktop e smartphones.
- **Google Fonts:** Tipografias *Playfair Display*, *Montserrat* e *Roboto Mono*.
- **Figma:** Prototipação de alta fidelidade das interfaces Desktop e Mobile — [Ver protótipo](https://www.figma.com/proto/eZXYjapZAfhZUGTTleT4I6/Gr%C3%A3o---Prosa?node-id=0-1&t=NI2buaZKZB0dVUOg-1).

---

## 👨‍💻 Participantes

- [Jackson Luiz Dias Carvalho](https://github.com/jacksonldc)
- [Pablo Rodrigues Melo](https://github.com/PabloRdg-dev)

---

## 📁 Estrutura de Arquivos

```text
Grão & Prosa/
├── index.html       # Página principal (Início, Sobre, Espaço)
├── cardapio.html    # Página do cardápio digital
├── reserva.html     # Página de informações e formulário de reserva
├── style.css        # Folha de estilos principal e regras responsivas (@media)
└── imagens/         # Ativos visuais, logotipo, ícones e planos de fundo
