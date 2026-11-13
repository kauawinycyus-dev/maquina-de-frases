# 🤖 Máquina de Frases!

Uma aplicação web educativa e interativa desenvolvida para introduzir conceitos fundamentais de **Pensamento Computacional** e alfabetização para crianças de forma lúdica, visual e acessível.

> 🎓 **Projeto de Extensão Universitária — UFLA**  
> Este projeto foi desenvolvido como parte de um **Projeto de Extensão Universitária da Universidade Federal de Lavras (UFLA)**, com o objetivo de levar noções de lógica de programação, algoritmos e tecnologia para o ambiente escolar de maneira divertida e inclusiva.

---

## 🎯 Objetivo Pedagógico

A **Máquina de Frases!** simula o funcionamento básico de um sistema computacional dividido em três etapas sequenciais:

1. **📥 Input (Entrada de Dados):** As crianças alimentam caixas temáticas com palavras, nomes de colegas, ações e lugares.
2. **⚙️ Processamento (Algoritmo):** O sistema mistura os dados inseridos e realiza um sorteio aleatório de um item de cada categoria.
3. **📤 Output (Saída e Depuração):** A partir dos cartões sorteados, o aluno constrói e digita uma frase completa, exercitando a escrita, a concordância e a validação lógica (debugging).

---

## ✨ Funcionalidades

- **Fluxo Guiado em Telas Separadas:** Tela inicial lúdica, seleção de nível de dificuldade e divisão clara entre *Input*, *Processamento* e *Output* para manter o foco dos alunos.
- **4 Níveis / Modos de Jogo:**
  - **Nível 1 (3 Caixas):** Sujeito + Ação + Lugar
  - **Nível 2 (4 Caixas):** Momento + Pessoa + Ação + Comida
  - **Nível 3 (5 Caixas):** Clima + Personagem + Ação + Objeto + Lugar
  - **Modo Turma:** Nomes dos Alunos + Ação + Complementos (personalizável com os nomes da sala de aula)
- **Validação Inteligente de Frases:** Verifica automaticamente se a frase escrita pelo aluno contém todas as palavras sorteadas nas caixas, exibindo feedback sonoro e visual (mascote comemorando com *"Muito bem!"* e confetes).
- **Acessibilidade e Áudio:**
  - Efeitos sonoros sintetizados offline via **Web Audio API** (com botão de ativar/silenciar).
  - Leitura das frases em voz alta em português (`pt-BR`) via **Web Speech API**.
- **🎨 Galeria da Turma:** Menu lateral (hambúrguer) e **modo de tela estendida (tela cheia)** para exibir os desenhos produzidos pelos alunos em carrossel contínuo.
- **🏆 Mural da Turma:** Histórico local (`localStorage`) com as frases validadas durante a aula.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** semântico
- **CSS3** (Design responsivo, animações e paleta lúdica de alto contraste)
- **JavaScript (ES6+)** puro (sem dependências externas, 100% compatível com funcionamento offline e hospedagem estática)
- **Web Audio API** & **Web Speech API**

---

## 📂 Estrutura de Pastas

```text
├── index.html          # Aplicação principal (HTML, CSS e JS integrados)
├── robo.png            # Mascote da Máquina de Frases
├── desenhos/           # Pasta com as ilustrações dos alunos (1.jpg até 59.jpg)
└── README.md           # Documentação do projeto
