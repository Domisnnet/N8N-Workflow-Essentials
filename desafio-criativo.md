![GitHub repo size](https://img.shields.io/github/repo-size/Domisnnet/N8n-Workflow-Essentials?style=for-the-badge)
![GitHub stars](https://img.shields.io/github/stars/domisnnet/N8n-Workflow-Essentials?style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/Domisnnet/N8n-Workflow-Essentials?style=for-the-badge)

<h1 align="center">🎯 Desafio Criativo: Planejando Automações com N8N</h1>
<p align="center">
  <strong>Usando Apenas Bons Prompts</strong><br>
  <em>Documentação oficial da entrega do desafio | Trilha Santander - Automação com N8N (DIO)</em>
</p>

<div align="center">
  <a href="https://github.com/Domisnnet/N8n-Workflow-Essentials">
    <img src="https://img.shields.io/badge/⬅%20Voltar%20ao%20Repo%20Principal-26FF00?style=for-the-badge&labelColor=111827&color=0A0F1C" alt="Voltar ao Repo Principal">
  </a>
</div>

---

<h2 id="sobre-o-desafio">💡 Sobre o Exercício</h2>
<p>Um bom prompt nasce de intenção clara, contexto e instruções específicas. Nesta atividade, organizei minhas ideias e as transformei em comandos claros para orientar uma IA a produzir exatamente o workflow imaginado para o projeto <strong>N8N Workflow Essentials</strong>.</p>

---

<h2 id="passo-1">🧱 Passo 1: Defina a automação desejada</h2>
<p>Nesta etapa, descrevi qual processo desejo automatizar e quem será beneficiado por ele.</p>

| Campo | Descrição |
| :--- | :--- |
| **Tarefa repetitiva** | Processar novos commits de repositórios Web Essentials e gerar documentação visual e de estudo automaticamente. |
| **Público ou responsável** | Desenvolvedor Full-stack (DomisDev) e comunidade de tecnologia. |
| **Resultado esperado** | Transformar código e mensagens de commit em resumos técnicos, mapas mentais e blueprints isométricos, salvando-os de forma organizada. |

---

<h2 id="passo-2">🧱 Passo 2: Adicione contexto e regras</h2>
<p>Aqui, informei os sistemas envolvidos, as etapas do fluxo e as restrições importantes para garantir a robustez e segurança da automação.</p>

| Categoria | Detalhes |
| :--- | :--- |
| **Ferramentas envolvidas** | GitHub API (Trigger), N8N, Google Gemini / NotebookLM (IA Generativa) e Stability AI (Geração de imagem). |
| **Fluxo desejado** | 1. Receber notificação de novo commit via Webhook ou Polling.<br>2. Coletar dados detalhados do commit via HTTP Request (GitHub API).<br>3. Processar os dados e enviar para a IA para gerar resumo técnico ou roteiro.<br>4. Gerar prompt de imagem e enviar para Stability AI criar um blueprint isométrico.<br>5. Salvar resultados no repositório ou enviar notificação (Telegram/Notion). |
| **Regras importantes** | • Ignorar commits de merge ou com mensagens genéricas (ex: "update", "fix").<br>• <strong>Nunca</strong> enviar credenciais, tokens ou dados sensíveis (.env) no contexto para a IA.<br>• Em caso de falha na geração da imagem, prosseguir o fluxo salvando apenas a documentação em texto. |

---

<h2 id="passo-3">🧱 Passo 3: Monte o prompt final</h2>
<p>A união de todas as peças em um único prompt completo, pronto para ser executado por uma IA especialista em N8N.</p>

<details>
<summary><strong>📋 Clique aqui para ver/copiar o Prompt Final</strong></summary>
<br>

    Atue como um especialista em N8N e Engenharia de Prompt.

    Crie uma automação para processar novos commits de repositórios Web Essentials e gerar documentação visual e de estudo automaticamente.

    Público:
    Desenvolvedor Full-stack (DomisDev) e comunidade de tecnologia.

    Ferramentas envolvidas:
    GitHub API (Trigger), N8N, Google Gemini / NotebookLM (IA Generativa) e Stability AI (Geração de imagem).

    Fluxo:
    1. Receber notificação de novo commit no repositório via Webhook ou Polling.
    2. Coletar dados detalhados do commit (mensagem, autor, arquivos alterados) via HTTP Request (GitHub API).
    3. Processar os dados e enviar para a IA (Gemini/NotebookLM) com engenharia de prompt para gerar um resumo técnico, mapa mental ou roteiro de podcast.
    4. Gerar um prompt de imagem baseado na arquitetura e enviar para Stability AI criar um blueprint isométrico.
    5. Salvar os resultados no repositório ou enviar notificação formatada (Telegram/Notion).

    Regras:
    - Ignorar commits de merge ou com mensagens genéricas (ex: "update", "fix", "test").
    - Garantir que nenhuma credencial, token ou dado sensível (.env) seja enviado no contexto para a IA.
    - Em caso de falha na geração da imagem (Stability AI), prosseguir o fluxo salvando apenas a documentação em texto.

    Explique quais nós do N8N devem ser utilizados e a lógica de funcionamento do workflow.

</details>

---

<h2 id="entrega">☁️ Sobre esta Entrega</h2>
<p>Este arquivo <code>desafio-criativo.md</code> foi criado no repositório público <strong>N8n-Workflow-Essentials</strong> para garantir a melhor prática de versionamento e portfólio, conforme as opções recomendadas pela DIO (Opção 2: Git/GitHub).</p>

<div align="center">
  <a href="https://github.com/Domisnnet">
    <img src="https://img.shields.io/badge/Perfil%20GitHub-Domisnnet-26FF00?style=for-the-badge&logo=github&labelColor=111827&color=0A0F1C" alt="Perfil GitHub">
  </a>
</div>
