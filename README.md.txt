# 🧪 Projeto QA - Cadastro de Usuário (Automation Practice)

Este é meu primeiro projeto de portfólio como **QA Júnior**, desenvolvido para praticar **análise, planejamento e execução de testes manuais**.  
O foco foi validar o fluxo de **cadastro de novo usuário** no site [Automation Practice](https://automationpratice.com.br/register).

---

## 🧭 Objetivo

- Criar e executar casos de teste manuais com base em critérios funcionais.  
- Registrar resultados e evidências de execução.  
- Utilizar o Trello para controle de execução e documentação.  
- Identificar e reportar bugs encontrados durante os testes.  

---

## 🧩 Escopo do Projeto

A tela de **Cadastro de Usuário** contém três campos obrigatórios:
- Nome  
- E-mail  
- Senha  

O objetivo dos testes foi validar se o sistema aceita apenas cadastros válidos e apresenta mensagens de erro adequadas em situações negativas.

---

## 🗂️ Planejamento no Trello

O planejamento dos testes foi realizado no Trello, com as colunas:  
**Backlog de Testes → Em Execução → Bloqueados → Bugs Encontrados → Concluídos → Documentação**

🔗 [Acesse o quadro público no Trello](https://trello.com/b/PamcroH7/qa-cadastro-usuario)

![Quadro Trello](Trello/print_trello.png)

---

## 📋 Plano de Testes

A planilha foi desenvolvida no Google Sheets, contendo os casos de teste e seus resultados.  
Inclui colunas de ID, funcionalidade, pré-condições, passos, resultado esperado, tipo de execução, prioridade e status.

🔗 [Acesse a planilha de casos de teste](https://docs.google.com/spreadsheets/d/1_gC-ZfSKbWb4RVt-qWux6d9UgbESlD2V/edit?gid=1441739572#gid=1441739572)

---

## 📸 Evidências

As evidências de execução dos testes estão organizadas na pasta `/Evidencias`.

Cada imagem corresponde a um **caso de teste executado** durante a validação manual no site [Automation Practice](https://automationpratice.com.br/register).

| ID  | Caso de Teste                                | Resultado | Observações |
|-----|----------------------------------------------|------------|--------------|
| CT01 | Cadastro com dados válidos                  | ✅ Passou  | Fluxo completo validado |
| CT02 | Cadastro com e-mail inválido                | ✅ Passou  | Mensagem de erro exibida corretamente |
| CT03 | Cadastro sem preencher o campo Nome         | ✅ Passou  | Validação de campo obrigatório |
| CT04 | Cadastro sem senha                          | ✅ Passou  | Mensagem de erro exibida |
| CT05 | Senha fraca (menos de 6 caracteres)         | ⚠️ Falhou  | Sistema aceitou senha com 3 caracteres |
| CT06 | Cadastro com e-mail já cadastrado           | ✅ Passou  | Mensagem adequada de duplicidade |
| CT07 | Bug - Senha aceita com 3 caracteres         | ❌ Bug encontrado | Reportado no Trello |
| CT08 | Campos obrigatórios corretamente preenchidos| ✅ Passou  | Cadastro concluído com sucesso |

📂 **Pasta:** [`/Evidencias`](./Evidencias)

Cada evidência contém:
- **Print da tela do resultado do teste**
- **Identificação do caso (CTXX)**  
- **Status e observação breve**

🎥 *Caso tenha vídeos de execução:*  
[Ver execução em vídeo (Google Drive)](https://drive.google.com/...) *(substitua pelo seu link, se quiser adicionar)*

---

## 🐞 Bug Encontrado

Durante a execução do caso **CT07 - Senha com menos de 6 caracteres**, foi identificado um **defeito funcional**:
> O sistema aceitou o cadastro com senha de apenas 3 caracteres.

- **Status:** Aberto  
- **Prioridade:** Média  
- **Evidência:** Captura de tela anexada no Trello (card de bug).  
- **Ação esperada:** Implementar validação mínima de 6 caracteres para o campo “Senha”.  

---

## 🧰 Ferramentas Utilizadas

- **Trello** → Planejamento e acompanhamento dos testes  
- **Google Sheets** → Registro e documentação dos casos  
- **Navegador Chrome** → Execução manual dos testes  
- **Snipping Tool / Print Screen** → Captura de evidências  
- **GitHub** → Divulgação do projeto  

---

## 🧠 Aprendizados

Durante o desenvolvimento deste projeto, pratiquei:
- Criação e estruturação de casos de teste.  
- Escrita clara e objetiva de resultados esperados.  
- Organização de tarefas e status no Trello.  
- Registro e documentação de bugs.  
- Apresentação profissional de um projeto QA no GitHub.  

---

## 📎 Contato

📧 **Rodrigo Garcia da Silva**  
💼 [LinkedIn](https://www.linkedin.com/in/rodrigogarciadasilva/)  
🐙 [GitHub](https://github.com/) *(adicione seu link aqui após subir o projeto)*  

---

> Projeto criado com o objetivo de aprendizado e portfólio para vaga de QA Júnior. 🚀  
