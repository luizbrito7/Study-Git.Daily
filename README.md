# Desafios Práticos Diários de Git

Este material apresenta 13 desafios práticos e progressivos para desenvolver sua proficiência em Git, desde fundamentos até tópicos avançados. Cada desafio é projetado para ser realizado em 20 a 40 minutos, com foco em prática, documentação e reflexão.

---

## ✅ Dia 1: Iniciando com Git e Repositórios

**Descrição da tarefa:**  
Crie um repositório Git local, adicione um arquivo chamado `index.txt`, insira conteúdo e registre seu primeiro commit.

**Objetivo:**  
Compreender o ciclo básico de versionamento com Git.

**Conceitos abordados:**  
Inicialização de repositório, adição de arquivos, commit, status e visualização de histórico.

**Critérios de sucesso:**  
O commit deve aparecer no log e o arquivo deve estar versionado.

**Documentação sugerida:**  
Registre os comandos utilizados e o que cada um faz no arquivo `Diario.md`.

---

## 🚀 Dia 2: Branches com Git Flow

**Descrição da tarefa:**  
Crie duas branches para desenvolvimento de funcionalidades diferentes. Faça alterações em arquivos distintos e integre as branches à principal.

**Objetivo:**  
Aprender a criar, alternar e fundir branches.

**Conceitos abordados:**  
Branches, merges e fluxo básico de trabalho em equipe.

**Critérios de sucesso:**  
As funcionalidades das branches devem estar integradas na branch principal com histórico visual claro.

**Documentação sugerida:**  
Explique a diferença entre criar e alternar branches e como o merge foi realizado.

---

## 💥 Dia 3: Conflitos de Merge

**Descrição da tarefa:**  
Crie propositalmente um conflito de merge entre duas branches que editam a mesma linha de um arquivo. Resolva o conflito manualmente.

**Objetivo:**  
Entender a origem dos conflitos e como resolvê-los.

**Conceitos abordados:**  
Conflitos de merge, edição manual, análise de diferenças.

**Critérios de sucesso:**  
Merge resolvido corretamente e histórico de fusão visível.

**Documentação sugerida:**  
Explique a origem do conflito e como foi solucionado.

---

## 🔁 Dia 4: Rollback com Reset e Revert

**Descrição da tarefa:**  
Crie dois commits. Em seguida, reverta ou remova o último commit utilizando abordagens diferentes.

**Objetivo:**  
Aprender formas de desfazer ações no histórico.

**Conceitos abordados:**  
Reset, revert, tipos de reset (soft, mixed, hard).

**Critérios de sucesso:**  
O histórico deve refletir corretamente o rollback executado.

**Documentação sugerida:**  
Descreva as diferenças entre reset e revert e em que situações usá-los.

---

## 🧱 Dia 5: Manipulação da Staged Area

**Descrição da tarefa:**  
Crie alterações em arquivos e manipule a staged area adicionando e removendo arquivos seletivamente antes de fazer commit.

**Objetivo:**  
Compreender a separação entre área de staging e repositório.

**Conceitos abordados:**  
Área de staging, controle de versões parciais, preparação para commit.

**Critérios de sucesso:**  
Capacidade de manipular corretamente o que será incluído no próximo commit.

**Documentação sugerida:**  
Explique a utilidade da staged area e registre os testes realizados.

---

## 🧙 Dia 6: Reescrevendo Commits Locais

**Descrição da tarefa:**  
Corrija a mensagem de um commit e remova um commit local da linha do tempo de forma interativa.

**Objetivo:**  
Controlar e editar o histórico de forma segura antes do push.

**Conceitos abordados:**  
Amend, rebase interativo, edição e remoção de commits.

**Critérios de sucesso:**  
Histórico local ajustado com sucesso.

**Documentação sugerida:**  
Descreva os impactos e cuidados ao alterar commits locais.

---

## 📡 Dia 7: Push e Force Push

**Descrição da tarefa:**  
Envie commits para um repositório remoto e experimente uma situação controlada que exija `force push`.

**Objetivo:**  
Entender o funcionamento do push e os riscos de sobrescrever histórico remoto.

**Conceitos abordados:**  
Push, upstream, force push, boas práticas.

**Critérios de sucesso:**  
Histórico remoto atualizado de forma intencional.

**Documentação sugerida:**  
Explique quando é (in)seguro usar force push.

---

## 🔐 Dia 8: Autenticação com Git (SSH, HTTPS, Token)

**Descrição da tarefa:**  
Clone um repositório remoto utilizando HTTPS com token e configure uma chave SSH para autenticação segura.

**Objetivo:**  
Dominar os métodos de autenticação disponíveis.

**Conceitos abordados:**  
Tokens pessoais, chaves SSH, credenciais seguras.

**Critérios de sucesso:**  
Autenticação bem-sucedida com ambos os métodos.

**Documentação sugerida:**  
Descreva vantagens e desvantagens de cada forma de autenticação.

---

## 🔍 Dia 9: Explorando o Histórico com `git log`

**Descrição da tarefa:**  
Visualize e filtre o histórico com diferentes opções do log, como autor, data e formatações visuais.

**Objetivo:**  
Investigar o histórico de forma eficiente.

**Conceitos abordados:**  
Filtros de log, visualização gráfica e detalhada do histórico.

**Critérios de sucesso:**  
Capacidade de extrair informações específicas do histórico.

**Documentação sugerida:**  
Registre exemplos úteis de comandos de log e suas saídas.

---

## 🧪 Dia 10: Usando o `git stash`

**Descrição da tarefa:**  
Crie alterações e armazene-as temporariamente utilizando `stash`. Depois, recupere as alterações.

**Objetivo:**  
Salvar modificações não finalizadas sem perdê-las.

**Conceitos abordados:**  
Stash, listagem, recuperação de alterações temporárias.

**Critérios de sucesso:**  
As mudanças devem ser armazenadas e restauradas com sucesso.

**Documentação sugerida:**  
Explique quando o uso de stash é útil e quando evitá-lo.

---

## 🌲 Dia 11: Tipos de Objetos Git

**Descrição da tarefa:**  
Explore os objetos internos do Git e entenda como os dados são armazenados.

**Objetivo:**  
Compreender a estrutura interna do Git.

**Conceitos abordados:**  
Blobs, árvores (trees), commits e tags.

**Critérios de sucesso:**  
Identificação da estrutura e conexão entre objetos.

**Documentação sugerida:**  
Desenhe ou explique o relacionamento entre os objetos.

---

## ⚔️ Dia 12: Resolução de Conflitos Avançada

**Descrição da tarefa:**  
Realize um merge com conflito e utilize uma ferramenta de resolução de conflitos para solucioná-lo.

**Objetivo:**  
Aprimorar a habilidade de resolver conflitos de forma profissional.

**Conceitos abordados:**  
Merge tools, conflitos complexos, práticas colaborativas.

**Critérios de sucesso:**  
Conflito resolvido corretamente e histórico consistente.

**Documentação sugerida:**  
Compare a solução manual com a via ferramenta.

---

## 🌀 Dia 13: Introdução ao Rebase

**Descrição da tarefa:**  
Reescreva a base de commits de uma branch utilizando `rebase` para simular um histórico linear.

**Objetivo:**  
Entender o impacto do rebase e quando aplicá-lo.

**Conceitos abordados:**  
Rebase, diferenças entre merge e rebase, reescrita de histórico.

**Critérios de sucesso:**  
Histórico linear e sem conflitos após rebase.

**Documentação sugerida:**  
Explique visualmente como o histórico foi alterado.

---

## 📓 Dica Final

Ao final de cada desafio, escreva no seu `Diario.md`:

- O que foi aprendido.
- O que funcionou e o que não funcionou.
- Onde buscar mais informações.
- Como o conhecimento pode ser aplicado em projetos reais.

Revisar seus registros ao final da trilha é uma excelente forma de consolidar o aprendizado e reforçar boas práticas com Git.

---
