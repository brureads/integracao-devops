# Integração DevOps — Unidade 1  
## Fundamentos do DevOps 

**Professor:** Daniel Lim-Apo  
**Disciplina:** Integração DevOps  

> Resumo em linguagem simples: DevOps é fazer as equipes trabalharem juntas para entregar software mais rápido, com menos erros e sem transformar cada atualização em um filme de terror.

---

## 1. O problema antes do DevOps

Muitas empresas conseguem **criar um sistema**, mas têm dificuldade para colocá-lo em produção com segurança.

Os problemas mais comuns são:

- deploys demorados e arriscados;
- tarefas manuais demais;
- erros descobertos muito tarde;
- equipes que não conversam;
- muito retrabalho;
- operação vivendo de “apagar incêndios”;
- baixa confiança entre Desenvolvimento, Operações, Qualidade e Segurança.

### O conflito clássico

As equipes costumavam ter objetivos diferentes:

- **Desenvolvimento (Dev):** entregar novas funcionalidades rapidamente;
- **Operações (Ops):** manter o sistema estável e evitar mudanças perigosas.

Isso gera a famosa situação:

> Dev: “Na minha máquina funciona.”  
> Ops: “Em produção não funciona.”

O problema não é uma equipe ser “ruim”.  
O problema é o **modelo de trabalho separado**, chamado de **silos**.

---

## 2. O que são silos?

Silos acontecem quando cada equipe trabalha isolada e apenas “passa o problema para a próxima”.

Exemplo:

```text
Requisito
   ↓
Desenvolvimento
   ↓
Testes
   ↓
Operações
   ↓
Produção
```

Cada setor cuida somente da própria parte.

Isso causa:

- espera;
- falta de informação;
- transferência de culpa;
- retrabalho;
- deploys maiores e mais perigosos.

---

## 3. O que é DevOps?

**DevOps** é uma abordagem que integra:

- Desenvolvimento;
- Operações;
- Qualidade;
- Segurança;
- Negócio.

Seu objetivo é criar uma forma de trabalho capaz de entregar valor:

- rapidamente;
- com segurança;
- com qualidade;
- com confiabilidade;
- aprendendo continuamente.

### Tradução

DevOps é:

> Todo mundo trabalhando junto do começo ao fim, usando processos organizados e automação para colocar melhorias no sistema sem causar caos.

---

## 4. DevOps envolve três partes

### Cultura

É a forma como as pessoas trabalham juntas.

Inclui:

- confiança;
- colaboração;
- comunicação;
- transparência;
- responsabilidade compartilhada;
- aprendizado com erros.

### Práticas

São formas organizadas de trabalhar.

Exemplos:

- integração contínua;
- testes automatizados;
- entregas frequentes;
- monitoramento;
- revisão de código;
- feedback rápido.

### Tecnologia

São ferramentas que ajudam o processo.

Exemplos:

- Git;
- GitHub Actions;
- GitLab CI;
- Jenkins;
- Docker;
- Kubernetes;
- Terraform.

> As ferramentas ajudam, mas não criam DevOps sozinhas.

---

## 5. O que DevOps **não** é

DevOps não é:

- apenas Docker;
- apenas Kubernetes;
- apenas automação;
- uma ferramenta específica;
- trocar o nome da equipe de Operações;
- contratar uma pessoa chamada “DevOps” e achar que tudo está resolvido;
- criar um “time DevOps” isolado entre Dev e Ops;
- eliminar testes ou controles de qualidade.

A frase mais importante é:

> DevOps não é apenas tecnologia. É uma mudança cultural e organizacional.

---

## 6. Responsabilidade compartilhada

No modelo DevOps, a responsabilidade não termina quando o código é entregue.

A ideia é:

> “Você constrói, você também ajuda a operar e melhorar.”

### Desenvolvimento

Precisa pensar desde o início em:

- desempenho;
- segurança;
- testes;
- monitoramento;
- funcionamento em produção.

### Operações

Participa do projeto e ajuda a:

- automatizar ambientes;
- melhorar a confiabilidade;
- acompanhar o sistema;
- dar feedback sobre produção.

### Negócio

Ajuda a definir:

- prioridades;
- valor esperado;
- riscos;
- impacto das mudanças.

---

## 7. Dívida técnica

**Dívida técnica** acontece quando escolhemos uma solução rápida agora, mas que vai dificultar a manutenção depois.

Exemplo:

> Fazer uma gambiarra para entregar rápido e não organizar depois.

Com o tempo, isso gera:

- sistema frágil;
- documentação ruim;
- mais retrabalho;
- deploys menos frequentes;
- mudanças maiores;
- mais incidentes;
- menos tempo para melhorar.

### O paradoxo

Quando um deploy é perigoso, a empresa começa a fazer menos deploys.

Só que, fazendo menos deploys:

- mais mudanças ficam acumuladas;
- o pacote fica maior;
- o risco aumenta;
- fica mais difícil descobrir qual mudança causou o erro.

> Evitar mudanças pequenas pode deixar a próxima mudança ainda mais perigosa.

---

## 8. DevOps e Metodologia Ágil

O **Ágil** trabalha com:

- ciclos curtos;
- entregas frequentes;
- colaboração com o cliente;
- adaptação às mudanças.

O **DevOps** amplia isso até a produção.

Ele inclui:

- implantação;
- operação;
- monitoramento;
- segurança;
- feedback real dos usuários;
- confiabilidade.

### Resumindo

- **Ágil:** ajuda a desenvolver melhor.
- **DevOps:** ajuda a desenvolver, entregar, operar e melhorar continuamente.

---

## 9. DevOps e Lean

**Lean** busca entregar valor eliminando desperdícios.

No DevOps, isso significa:

- reduzir filas;
- diminuir espera;
- evitar retrabalho;
- automatizar tarefas repetitivas;
- trabalhar com pequenos lotes;
- limitar tarefas em andamento;
- remover gargalos;
- melhorar continuamente.

### Ideia principal

> Entregar mais não significa fazer todo mundo trabalhar mais.  
> Significa remover aquilo que atrasa o trabalho.

---

## 10. Fluxo de valor tecnológico

O **fluxo de valor** é o caminho que uma ideia percorre até virar algo útil para o usuário.

```text
Ideia
  ↓
Planejamento
  ↓
Código
  ↓
Build
  ↓
Testes
  ↓
Deploy
  ↓
Operação
  ↓
Feedback
  ↓
Aprendizado
```

Uma funcionalidade só gera valor quando:

- chega ao usuário;
- funciona;
- é útil;
- é segura;
- permanece estável.

Não adianta a programação terminar rápido se a mudança ficar parada durante semanas esperando teste ou aprovação.

---

## 11. Modelo CALMS

O modelo **CALMS** resume os principais valores do DevOps.

| Letra | Significado | Explicação simples                                  |
| ----- | ----------- | --------------------------------------------------- |
| **C** | Culture     | Cultura de colaboração e confiança                  |
| **A** | Automation  | Automatizar tarefas repetitivas                     |
| **L** | Lean        | Reduzir desperdícios e trabalhar com lotes pequenos |
| **M** | Measurement | Medir o sistema e os resultados                     |
| **S** | Sharing     | Compartilhar conhecimento e responsabilidade        |

### Macete

> **C**ultura, **A**utomação, **L**ean, **M**edição e **S**haring.

As ferramentas apoiam o CALMS, mas não substituem esses valores.

---

## 12. Objetivos do DevOps

DevOps tenta melhorar **velocidade e estabilidade ao mesmo tempo**.

Principais objetivos:

- entregar mais rápido;
- aumentar a frequência de deploy;
- reduzir erros em produção;
- recuperar o sistema rapidamente;
- melhorar a qualidade;
- melhorar a segurança;
- reduzir tarefas repetitivas;
- diminuir o sofrimento da equipe;
- aprender com dados e incidentes.

---

## 13. Qualidade e segurança desde o início

No modelo antigo, testes e segurança apareciam somente no final.

No DevOps, eles entram desde o planejamento.

Isso é chamado de:

## Shift Left

**Shift Left** significa trazer verificações para etapas mais iniciais do ciclo.

Exemplos:

- definir requisitos de segurança no planejamento;
- fazer testes durante o desenvolvimento;
- verificar dependências no pipeline;
- revisar código antes do deploy.

> Quanto mais cedo um erro aparece, mais fácil e barato é corrigi-lo.

---

# 14. O ciclo DevOps

O ciclo é contínuo e não possui um “fim definitivo”.

```text
Planejar
   ↓
Desenvolver
   ↓
Construir
   ↓
Testar
   ↓
Entregar
   ↓
Implantar
   ↓
Operar
   ↓
Monitorar
   ↓
Aprender
   ↺
```

Produção gera informações que voltam para o planejamento.

---

## 15. Etapa 1 — Planejar

Planejar é descobrir:

- qual problema será resolvido;
- quem será beneficiado;
- qual valor a mudança deve gerar;
- quais riscos existem;
- como saberemos se funcionou;
- qual é a menor entrega útil.

No DevOps, o planejamento também pensa em:

- segurança;
- operação;
- monitoramento;
- capacidade;
- recuperação de falhas.

---

## 16. Etapa 2 — Desenvolver ou codificar

O código deve ser:

### Versionado

As mudanças ficam registradas em ferramentas como o Git.

### Revisável

As alterações devem ser pequenas e fáceis de entender.

### Testável

O código precisa permitir testes automáticos.

Boas práticas:

- commits pequenos;
- branches de curta duração;
- revisão de código;
- testes automatizados;
- ambiente padronizado;
- integração frequente ao repositório principal.

---

## 17. Etapas 3 e 4 — Construir e testar

### Build

O **build** transforma o código em algo que pode ser executado.

Esse resultado é chamado de **artefato**.

Exemplos de artefato:

- arquivo `.jar`;
- aplicativo;
- pacote;
- imagem Docker.

O processo deve ser:

- reproduzível;
- automatizado;
- rápido;
- rastreável;
- consistente.

### Tipos de teste

- **Teste unitário:** testa uma pequena parte do código;
- **Teste de integração:** verifica se partes diferentes funcionam juntas;
- **Teste de aceitação:** verifica se o sistema atende ao que foi pedido;
- **Teste de segurança:** procura vulnerabilidades;
- **Teste de desempenho:** verifica velocidade e capacidade;
- **Teste de fumaça:** verifica rapidamente se o sistema continua vivo após o deploy.

---

## 18. Teste de fumaça

O **smoke test** é uma verificação rápida feita depois do deploy.

Ele verifica coisas básicas, como:

- a aplicação iniciou;
- a página principal responde;
- o login funciona;
- o banco de dados está acessível;
- um fluxo importante funciona;
- serviços externos estão disponíveis;
- não surgiram muitos erros nos logs.

### Origem do nome

Em testes de equipamentos, se ligasse e saísse fumaça, algo estava obviamente errado.

No software, o teste procura problemas grandes e evidentes logo após a implantação.

---

## 19. Etapa 5 — Entregar e implantar

### Entrega contínua

O software fica sempre pronto para ser colocado em produção.

Porém, alguém ainda decide quando o deploy acontecerá.

### Implantação contínua

Quando uma mudança passa por todas as verificações do pipeline, ela pode ir automaticamente para produção.

### Diferença

| Entrega contínua                    | Implantação contínua                   |
| ----------------------------------- | -------------------------------------- |
| O sistema está pronto para publicar | O sistema é publicado automaticamente  |
| Existe uma decisão antes do deploy  | O pipeline pode fazer o deploy sozinho |

> Deploy deve ser uma atividade comum, não um evento traumático.

---

## 20. Etapa 6 — Operar

Operar significa manter o sistema funcionando e entregando valor.

Responsabilidades:

- disponibilidade;
- desempenho;
- escalabilidade;
- segurança;
- resposta a incidentes;
- gestão de mudanças;
- continuidade do serviço;
- recuperação de falhas.

DevOps não elimina Operações.

A equipe de Ops deixa de apenas executar tarefas manuais e passa a:

- automatizar ambientes;
- criar plataformas internas;
- melhorar observabilidade;
- aumentar a confiabilidade;
- compartilhar responsabilidade com Dev.

---

## 21. Etapa 7 — Monitorar

Monitorar é acompanhar os sinais do sistema.

### Monitoramento

Mostra o que está acontecendo.

Exemplo:

> “O uso de memória está em 95%.”

### Observabilidade

Ajuda a entender **por que** o problema está acontecendo.

Sinais comuns:

- logs;
- métricas;
- traces;
- alertas;
- eventos de deploy;
- indicadores de negócio.

O monitoramento ajuda a responder:

- O sistema está funcionando?
- O usuário está conseguindo usar?
- Onde existe um gargalo?
- O que precisa melhorar?

---

# 22. Métricas importantes

### Lead time

Tempo desde o início da mudança até ela chegar em produção.

### Frequência de deploy

Quantas vezes mudanças são colocadas em produção.

### Taxa de falha de mudança

Quantidade de deploys que causam problema ou precisam de correção.

### Tempo médio de recuperação

Quanto tempo a equipe leva para restaurar o serviço depois de uma falha.

### Trabalho em andamento

Quantidade de tarefas iniciadas e ainda não concluídas.

### Retrabalho

Tempo gasto corrigindo algo que já havia sido feito.

---

# 23. As Três Maneiras do DevOps

O Manual de DevOps organiza seus princípios em três ideias:

1. Fluxo;
2. Feedback;
3. Aprendizado contínuo e experimentação.

---

## 24. Primeira Maneira — Fluxo

O fluxo representa o trabalho avançando da esquerda para a direita:

```text
Negócio → Desenvolvimento → Operações → Cliente
```

O objetivo é fazer o trabalho avançar com:

- menos espera;
- menos retrabalho;
- menos risco;
- menos transferências entre equipes.

Para melhorar o fluxo:

- tornar o trabalho visível;
- reduzir filas;
- diminuir dependências;
- limitar tarefas em andamento;
- usar lotes pequenos;
- automatizar tarefas;
- remover gargalos;
- manter ambientes parecidos.

---

## 25. Pequenos lotes

Um lote é um conjunto de mudanças enviadas juntas.

### Lote grande

- revisão demorada;
- risco maior;
- erro difícil de localizar;
- feedback tardio;
- reversão complicada.

### Lote pequeno

- revisão rápida;
- impacto menor;
- problema fácil de localizar;
- feedback frequente;
- reversão simples.

### Exemplo

Em vez de esperar três meses para publicar vinte funcionalidades, a equipe publica pequenas melhorias durante o mês.

> Mudanças pequenas costumam ser mais seguras do que uma mudança gigantesca.

---

## 26. WIP — Trabalho em Andamento

**WIP** significa **Work in Progress**, ou Trabalho em Andamento.

É tudo que foi iniciado, mas ainda não foi concluído.

Quando a equipe inicia muitas tarefas ao mesmo tempo:

- aumenta a multitarefa;
- surgem filas;
- aparecem gargalos;
- o trabalho demora mais;
- bloqueios ficam escondidos;
- poucas coisas são realmente concluídas.

Limitar WIP significa:

> Terminar o que já começou antes de puxar várias tarefas novas.

O objetivo não é manter todo mundo ocupado.  
O objetivo é fazer as tarefas chegarem até a conclusão.

---

## 27. Segunda Maneira — Feedback

O feedback volta da direita para a esquerda:

```text
Produção → Operações → Desenvolvimento → Negócio
```

Seu objetivo é:

- encontrar erros cedo;
- corrigir enquanto o problema ainda é pequeno;
- aprender rapidamente.

Quanto menor o tempo de feedback:

- mais cedo o erro aparece;
- mais barata é a correção;
- mais rápido acontece o aprendizado.

### Exemplos de feedback rápido

Durante o código:

- testes locais;
- revisão de código;
- análise estática.

Durante o pipeline:

- build automático;
- testes automatizados;
- análise de dependências;
- testes de integração.

Em produção:

- métricas;
- logs;
- alertas;
- feedback dos usuários.

---

## 28. Feedback técnico e feedback de negócio

### Feedback técnico

Mostra se o software está funcionando corretamente.

Exemplos:

- pipeline falhou;
- teste quebrou;
- erro 500 aumentou;
- consumo de memória subiu;
- sistema ficou lento.

### Feedback de negócio

Mostra se a mudança gerou valor.

Exemplos:

- mais usuários concluíram o cadastro?
- o abandono diminuiu?
- a funcionalidade foi usada?
- o atendimento ficou mais rápido?
- a experiência do cliente melhorou?

> Um sistema pode funcionar tecnicamente e, mesmo assim, não gerar valor para o usuário.

---

## 29. Terceira Maneira — Aprendizado contínuo

A organização deve aprender com:

- erros;
- incidentes;
- métricas;
- experimentos;
- feedback dos usuários.

O foco não é encontrar uma pessoa para culpar.

O foco é melhorar o sistema de trabalho.

Práticas:

- postmortem sem culpa;
- treinamento;
- experimentação controlada;
- compartilhamento entre equipes;
- melhoria diária;
- tempo para inovação;
- aprendizado com incidentes.

---

## 30. Postmortem sem culpa

Um **postmortem** é uma análise feita depois de um incidente.

Perguntas importantes:

- O que aconteceu?
- Como o problema foi detectado?
- Como a equipe respondeu?
- O que dificultou a recuperação?
- Quais proteções falharam?
- Como evitar que aconteça novamente?
- O que deve ser automatizado ou monitorado?

### O foco correto

- compreender a causa;
- melhorar o processo;
- criar barreiras contra recorrência.

### O foco errado

- procurar alguém para punir.

---

## 31. Segurança psicológica

A equipe precisa conseguir falar sobre erros sem medo.

Quando as pessoas escondem problemas:

- os erros continuam;
- o risco aumenta;
- ninguém aprende;
- o sistema fica mais frágil.

Em uma cultura saudável:

- erros são analisados;
- riscos são discutidos;
- dúvidas são permitidas;
- conhecimento é compartilhado;
- melhorias são priorizadas.

---

## 32. Experimentação

DevOps incentiva experimentos pequenos e controlados.

Exemplos:

- testes A/B;
- feature flags;
- canary release;
- simulação de falhas;
- validação progressiva.

O objetivo é:

> Aprender rapidamente sem colocar todos os usuários em risco.

---

## 33. DevSecOps

**DevSecOps** é a integração da segurança em todo o ciclo DevOps.

A segurança participa de:

- planejamento;
- desenvolvimento;
- revisão de código;
- pipeline;
- testes;
- deploy;
- operação;
- resposta a incidentes.

No modelo tradicional, Segurança aparece no final para aprovar ou bloquear.

No DevSecOps, Segurança ajuda a criar verificações automáticas.

Exemplos:

- análise de dependências;
- procura de senhas e segredos no código;
- análise estática;
- políticas no pipeline;
- registro de evidências para auditoria.

---

# 34. Estudo de caso 

## Situação

Uma empresa faz deploy apenas uma vez por mês, sempre no fim de semana.

O processo usa:

- planilhas;
- comandos manuais;
- aprovação de várias áreas.

### Problemas

- mudanças grandes;
- feedback lento;
- muito estresse;
- baixa rastreabilidade;
- rollback difícil;
- equipe de Operações sobrecarregada.

### Aplicando as Três Maneiras

**Fluxo:** diminuir os lotes e automatizar o pipeline.

**Feedback:** executar testes e monitoramento a cada mudança.

**Aprendizado:** fazer postmortems e transformar os erros em melhorias permanentes.

---

# 35. Atividade do sistema universitário

## Situação

Uma aplicação universitária falha todo início de semestre, quando recebe muitos acessos.  
A equipe só percebe depois das reclamações dos alunos.

### Onde há falha de fluxo?

A equipe não preparou e testou o sistema para o aumento de acessos antes do início do semestre.

### Onde há falha de feedback?

Não existem alertas e métricas suficientes.  
Os alunos descobrem o problema antes da equipe.

### O que aprender com o incidente?

É necessário:

- prever picos de acesso;
- fazer testes de carga;
- monitorar desempenho;
- criar alertas;
- preparar capacidade extra.

### Qual prática DevOps priorizar?

**Monitoramento com alertas e testes de desempenho/carga antes do início do semestre.**

---

# 36. Perguntas de revisão com respostas

## O que é DevOps?

É uma abordagem cultural, organizacional e técnica que integra equipes para entregar software com rapidez, segurança e confiabilidade.

## Por que DevOps não é apenas automação?

Porque ferramentas não resolvem falta de comunicação, silos e responsabilidade separada.

## Qual é o conflito clássico entre Dev e Ops?

Dev quer mudar rapidamente. Ops quer evitar mudanças para manter estabilidade.

## O que é fluxo de valor tecnológico?

É o caminho da ideia até a entrega de algo útil e funcionando para o usuário.

## Qual é a diferença entre fluxo e feedback?

- **Fluxo:** o trabalho vai até o usuário.
- **Feedback:** as informações voltam para melhorar o trabalho.

## Como pequenos lotes reduzem risco?

Eles possuem menos mudanças, são mais fáceis de testar, revisar, corrigir e reverter.

## Qual a diferença entre feedback técnico e de negócio?

- **Técnico:** mostra se o sistema funciona.
- **Negócio:** mostra se a mudança gerou valor.

## Por que o postmortem sem culpa é importante?

Porque ajuda a encontrar causas reais e melhorar o sistema sem incentivar as pessoas a esconder erros.

---

# 37. Cola final 

```text
DevOps = Cultura + Práticas + Tecnologia

Problema:
Dev quer velocidade
Ops quer estabilidade

Solução:
Responsabilidade compartilhada

CALMS:
Culture
Automation
Lean
Measurement
Sharing

Ciclo:
Planejar → Codificar → Construir → Testar
→ Entregar → Implantar → Operar → Monitorar → Aprender

Três Maneiras:
1. Fluxo
2. Feedback
3. Aprendizado contínuo

Regra de ouro:
Mudanças pequenas + testes rápidos + feedback cedo
= menos risco e menos sofrimento
```

---

## Frase para lembrar na prova

> DevOps organiza pessoas, processos e ferramentas para entregar valor continuamente, com rapidez, segurança, qualidade e aprendizado.