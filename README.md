# 🤖 Assistente de Respostas a Comentários do YouTube (Make)

Desenvolvi um agente automatizado capaz de responder aos comentários do YouTube de forma imediata, mantendo um tom de comunicação altamente empático, natural e alinhado à identidade da marca, além de evitar loops infinitos de resposta e impedir respostas duplicadas.

---

## 📸 Visão geral do fluxo

![Fluxo do Make](Fluxo%20principal.png)
---

## 🎯 Solução e Recursos

* **Prevenção de Duplicidade:** Lógica implementada para checar e impedir que um mesmo comentário seja respondido duas vezes.
* **Prevenção de Loops:** Filtros dedicados para que o agente não responda aos próprios comentários gerados.
* **Personalização de Tom:** Integração com IA ajustada com prompt direcionado para manter a linguagem da marca.

---

## 🛠️ Tecnologias Utilizadas

* **Make (Integromat)** — Plataforma de automação
* **YouTube Data API** — Captura de comentários e publicação das respostas
* **OpenAI (ChatGPT)** — Geração de texto humanizado e contextualizado

---

## 📁 Arquivos do Projeto

* 📄 **Apresentação em PDF:** [Acessar Documentação](Projeto%201%20(Make)_Agente%20Inteligente%20de%20Automação%20e%20Moderação%20de%20Engajamento%20no%20Youtube.pdf)
* ⚙️ **Blueprint para Importação:** Arquivo `.json` disponível na pasta `exports/`.
