![GitHub repo size](https://img.shields.io/github/repo-size/Domisnnet/N8n-Workflow-Essentials?style=for-the-badge)
![GitHub stars](https://img.shields.io/github/stars/domisnnet/N8n-Workflow-Essentials?style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/Domisnnet/N8n-Workflow-Essentials?style=for-the-badge)

<h2 id="sobre-o-projeto">1. N8N Workflow Essentials - Automação com IA 🤖⚙️</h2>

![Status do Deploy](https://img.shields.io/badge/Status-Online-brightgreen)
![Tecnologias](https://img.shields.io/badge/Tecnologias-N8N%20%7C%20Gemini%20%7C%20GitHub%20API-blueviolet)
[![Licença MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Domisnnet/N8n-Workflow-Essentials/blob/main/LICENSE)

![N8N Workflow](https://github.com/Domisnnet/N8N-Workflow-Essentials/blob/main/src/assets/images/arquitetura.png)

Bem-vindo ao **N8N Workflow Essentials**! Uma coleção de automações low-code que conecta seus projetos Web Essentials (TecBlog, Videos, Domflix, Responsive) com Inteligência Artificial. Inspirado na trilha **Santander - Automação com N8N** da DIO, este projeto transforma commits do GitHub em documentação visual automática via NotebookLM e Gemini.

---

<h2>📚 Tabela de Conteúdo</h2>

| 🤖 O Projeto | 🛠 Técnico | 🤝 Comunidade |
| :---: | :---: | :---: |
| [![1. Sobre](https://img.shields.io/badge/1%20-%20Sobre-4CAF50)](#sobre-o-projeto) | [![5. Destaques](https://img.shields.io/badge/5%20-%20Destaques-607D8B)](#destaques-tecnicos) | [![9. Código](https://img.shields.io/badge/9%20-%20Código-795548)](#codigo-fonte) |
| [![2. Techs](https://img.shields.io/badge/2%20-%20Techs-2196F3)](#tecnologias-utilizadas) | [![6. Instalação](https://img.shields.io/badge/6%20-%20Instalação-009688)](#instalacao) | [![10. Créditos](https://img.shields.io/badge/10%20-%20Créditos-607D8B)](#créditos) |
| [![3. Acessar](https://img.shields.io/badge/3%20-%20Acessar-FF9800)](#como-acessar) | [![7. Contribuir](https://img.shields.io/badge/7%20-%20Contribuir-3F51B5)](#como-contribuir) | [![11. Licença](https://img.shields.io/badge/11%20-%20Licença-E91E63)](#licenca) |
| [![4. Funções](https://img.shields.io/badge/4%20-%20Funções-9C27B0)](#funcionalidades) | [![8. FAQ](https://img.shields.io/badge/8%20-%20FAQ-FFC107)](#faq) | [![12. Perfil](https://img.shields.io/badge/12%20-%20Perfil-212121)](#perfil-do-github) |

---

<h2 id="tecnologias-utilizadas">2. ⚙ Tecnologias Utilizadas</h2>

| Camada | Tecnologias | Descrição |
| :--- | :--- | :--- |
| **Automação** | ![N8N](https://img.shields.io/badge/N8N-FF0000?style=flat-square&logo=n8n&logoColor=white) | Orquestração de workflows low-code rodando em localhost:5678 |
| **IA Generativa** | ![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=google&logoColor=white) ![NotebookLM](https://img.shields.io/badge/NotebookLM-34A853?style=flat-square&logo=google) | Análise de código e geração de mapa mental, podcast e infográfico |
| **API** | ![GitHub](https://img.shields.io/badge/GitHub_API-181717?style=flat-square&logo=github&logoColor=white) | Coleta de commits, descrição e linguagens dos repos Web Essentials |
| **Geração Visual** | ![Stability](https://img.shields.io/badge/Stability_AI-000000?style=flat-square) | Criação do blueprint isométrico: Web Essentials - A Arquitetura dos Fundamentos |

---

<h2 id="como-acessar">3. 🚀 Como Acessar</h2>

Este projeto roda localmente. Para testar:

<h3>Para Rodar N8N localmente</h3>

<h4>No Terminal rode:</h4>

```bash
npx n8n start
```

```bash
Acesse http://localhost:5678
```

Importe o workflow `workflows/web-essentials.json`

<div align="left">
  <a href="https://n8n.io/" target="_blank">
    <img alt="Botão N8N" src="https://img.shields.io/badge/Importar_Workflow-FF0000?style=for-the-badge&logo=n8n" />
  </a>
</div>

---

<h2 id="funcionalidades">4. 🧩 Funcionalidades Principais</h2>

| Funcionalidade | Descrição |
| :--- | :--- |
| 📥 **GitHub Trigger** | Monitora novos commits nos repos TecBlog, Videos, Domflix e Responsive via API |
| 🧠 **Prompt Engineering** | Melhora automaticamente o prompt antes de enviar para Gemini/NotebookLM |
| 🗺️ **Geração Automática** | Cria Mapa Mental, Guia de Estudos e Infográfico estilo blueprint isométrico |
| 🔗 **Integração** | Conecta NotebookLM -> Google Docs / Notion -> Telegram/WhatsApp |
| 💾 **Versionamento** | Salva workflows em JSON para reuso e portfólio (N8n-Workflow-Essentials) |

---

<h2 id="destaques-tecnicos">5. 💻 Destaques Técnicos</h2>

<h3>📐 Arquitetura do Workflow</h3>

> Uso do padrão `Manual Trigger -> Set -> HTTP Request - GitHub API -> Code Node -> AI Node -> HTTP` para garantir que a automação funcione offline e online.

<h3>🔄 NotebookLM + N8N</h3>
Implementação do conceito RAG (Retrieval-Augmented Generation): o N8N alimenta o NotebookLM com 3 fontes (GitHub) e o NotebookLM gera a documentação visual "Web Essentials: A Arquitetura dos Fundamentos - Uma dissecação técnica de UI, Semântica e Multimídia por DomisDev" com cubos neon HTML5 (verde), CSS3 (azul) e MULTIMEDIA API (vermelho).

---

<h2 id="instalacao">6. 🚀 Instalação Local</h2>

<h4>Clonar o repositório:</h4>

```bash
git clone https://github.com/Domisnnet/N8n-Workflow-Essentials.git
```
```bash
cd N8n-Workflow-Essentials
```

<h4>Rodar N8N:</h4>

```bash
npx n8n start
```

<h4>Ou docker:</h4>

```bash
docker run -it --rm --name n8n -p 5678:5678 -v ~/.n8n:/home/node/.n8n n8nio/n8n
```

> Importar workflow
>
> No UI: Workflows -> Import from File -> workflows/web-essentials-notebooklm.json
>
> Configurar credenciais
> Crie credencial Google Gemini API e GitHub (opcional)

---

<h2 id="como-contribuir">7. 🤝 Como Contribuir</h2>

| Fase | Ação | Comando |
| :--- | :--- | :--- |
| **01** | **Fork** | Faça Fork do repo |
| **02** | **Branch** | `git checkout -b feature/NovoWorkflow` |
| **03** | **Commit** | `git commit -m 'feat: workflow github-para-notion'` |
| **04** | **Push** | `git push origin feature/NovoWorkflow` |
| **05** | **PR** | Abra um Pull Request |

---

<h2 id="faq">8. 🧠 Perguntas Frequentes</h2>

<details>
<summary><strong>Preciso criar repo específico para rodar local? ❓</strong></summary>
<p>💻 <strong>Resposta:</strong> Não. O N8N salva tudo em ~/.n8n localmente. O repo N8n-Workflow-Essentials serve para versionar seus JSONs, documentar e entregar como projeto na DIO. Pode ser privado. Nunca commite credenciais ou .env com chaves.</p>
</details>

<details>
<summary><strong>Posso usar IA no N8N? ❓</strong></summary>
<p>🤖 <strong>Resposta:</strong> Sim! Este projeto é a prova. Usamos Gemini/Google AI + NotebookLM dentro do workflow para transformar código em infográfico, podcast e guia de estudos automaticamente.</p>
</details>

<details>
<summary><strong>Como gerar o infográfico surreal? ❓</strong></summary>
<p>🎨 <strong>Resposta:</strong> O nó Code gera o prompt: "Isometric blueprint technical illustration, dark background with grid, 3 glowing cubes HTML5 SEMANTICS neon green, CSS3 LAYOUT neon blue, MULTIMEDIA API neon red...". Use esse prompt em Stability AI, DALL-E ou Leonardo.AI.</p>
</details>

---

<h2 id="codigo-fonte">9. 💻 Código Fonte</h2>

[![Repositório](https://img.shields.io/badge/Repositório-Domisnnet%2FN8n--Workflow--Essentials-F7DF1E?style=for-the-badge&logo=github&labelColor=0d1117)](https://github.com/Domisnnet/N8n-Workflow-Essentials)

---

<h2 id="créditos">10. 📝 Créditos</h2>

| Atribuição | Responsável |
| :--- | :--- |
| **Dev & Automação** | **DomisDev** |
| **Inspiração** | **DIO - Santander Automação com N8N & NotebookLM** |
| **IA** | **Google Gemini & NotebookLM** |

---

<h2 id="licenca">11. 📄 Licença</h2>

[![Licença MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Domisnnet/N8n-Workflow-Essentials/blob/main/LICENSE)

---

<h2 id="perfil-do-github">12. 👨💻 Perfil</h2>

<a href="https://github.com/Domisnnet">
  <img src="src/assets/images/DomisDev.png" width="90" alt="DomisDev">
</a>

&nbsp;
<p align="center">
  <a href="#sobre-o-projeto">
    <img src="https://img.shields.io/badge/⬆%20VOLTAR%20AO%20TOPO-26FF00?style=flat&labelColor=111827&color=0A0F1C" alt="Voltar ao topo" style="height: 30px;">
  </a>
</p>

