# Meu Kit de IA

Desafio de Projeto da [DIO](https://dio.me): monte o seu kit de IA para o dia a dia e delegue uma tarefa real, com você no comando.

O kit foi criado pelo Expert Bruno Lima com os prompts, templates, checklists e skills usados nas Aulas. Ele não é uma apostila: abra a pasta que resolve o seu problema, copie o modelo, adapte e use.

**Copie → adapte → teste → confira → melhore**

## Como Fazer o Desafio

Você não precisa instalar nada nem saber programar. Tudo acontece no navegador.

1. Clique em **Use this template**, depois em **Create a new repository**. Dê um nome simples, como `meu-kit-de-ia`, deixe **Public** e confirme.
2. Siga os passos abaixo com uma tarefa real da sua semana.
3. Preencha a seção [Minha Entrega](#minha-entrega) da sua cópia e entregue o link dela na DIO.

## Os Passos

1. **Escolha uma tarefa real.** Comece pelo trabalho que se repete na sua semana, como preparar uma reunião ou montar um relatório, e não pela ferramenta.
2. **Pegue um modelo.** Abra a pasta do kit que combina com a sua tarefa. Cada modelo tem um botão de copiar no canto.
3. **Adapte.** Troque o que está entre colchetes pelo seu contexto, objetivo, dados, limites e formato.
4. **Teste.** A primeira resposta é um ponto de partida. Ajuste até funcionar para a sua realidade.
5. **Delegue.** Com o [template de delegação](02-templates/03-delegacao.md), entregue a tarefa à IA. Peça o plano antes de ela começar, acompanhe e valide o resultado.
6. **Confira.** Provável não é o mesmo que verdadeiro. Revise com o [Pare, Confira, Use](03-checklists/01-pare-confira-use.md) antes de usar.

## O Que Tem no Kit

| Pasta | Para que serve |
|---|---|
| [01-prompts](01-prompts) | Pedidos prontos para adaptar: escrita, comunicação, pesquisa, comparação e preparação de reuniões |
| [02-templates](02-templates) | Estruturas para preencher: bom pedido, pesquisa e decisão, e delegação |
| [03-checklists](03-checklists) | Revisão de respostas, de textos e de tarefas delegadas |
| [04-skills](04-skills) | Como criar uma skill, e a Skill Preparador de Reuniões usada nas Aulas |
| [05-delegacao-e-automacao](05-delegacao-e-automacao) | Gatilhos de automação, supervisão e checkpoints |

## Os Frameworks das Aulas

- **Bom pedido:** contexto + instrução + objetivo + formato. Quanto menos a IA precisa adivinhar, melhor você consegue avaliar a resposta.
- **Pesquisa e decisão:** pergunta → pesquisa → critérios → comparação → você. Peça fontes quando precisar de informação externa. A decisão final é sua.
- **Segurança:** pare → confira → use. Valide fatos, números, datas, fontes e contexto.
- **Atalhos reutilizáveis:** criar → testar → ajustar → salvar. Separe as instruções fixas das informações que mudam a cada uso.
- **Delegação:** objetivo + contexto + recursos + limites + sucesso. Autonomia funciona melhor quando o resultado esperado está claro.
- **Supervisão:** definir → delegar → acompanhar → validar. Em tarefas maiores, confira o plano, acompanhe os checkpoints e valide o resultado.

> A IA pode ajudar você a escrever, pesquisar, organizar e executar. A responsabilidade pelo resultado continua sendo sua.

---

### Minha Tarefa Real

Atuo na liderança operacional de setor no varejo alimentar em regime de escala 6x1. Escolhi a organização semanal da auditoria de validade (PVPS) e reposição crítica de gôndola, pois é uma rotina recorrente que impacta diretamente na redução de quebras/perdas e evita rupturas nos horários de pico sem comprometer o fluxo da equipe.

### Meus Atalhos

Adaptei dois modelos de prompts para a rotina operacional de loja: um para diagnóstico semanal de indicadores (quebras e rupturas) e outro para alinhamento rápido de turno (briefing de 5 minutos). Ficou fixo o papel da IA, as regras de divisão entre fatos e sugestões e o formato enxuto de entrega; o que muda a cada uso são apenas os percentuais da semana, as categorias críticas e o quadro de folgas do dia.

```text
Atue como um Especialista em Gestão Estratégica do Varejo e Logística de Loja.
Analise os indicadores semanais do meu setor abaixo e me ajude a preparar o plano de ação para a próxima semana.

Dados da semana (valores simulados/percentuais):
- Meta de vendas atingida: 96%
- Índice de quebra/perda operacional: 1,8% (acima da meta de 1,2%)
- Principais categorias em ruptura (falta na gôndola): Laticínios refrigerados e itens de giro rápido
- Categorias com risco de vencimento (PVPS): Iogurtes e frios fatiados

Entregue a resposta dividida estritamente em:
1. Fatos Identificados: O que os números mostram objetivamente (sem suposições).
2. Sugestões de Ação Imediata: 3 ações práticas para corrigir ruptura e evitar vencimento no piso de loja.
3. Checklist de Delegação para a Equipe: 4 tarefas curtas para distribuir entre os operadores no turno.
```

```text
Atue como um Encarregado de Setor focado em liderança prática e engajamento de equipe no varejo alimentar.
Preciso conduzir um alinhamento rápido de 5 minutos com a equipe antes da abertura da loja.

Contexto do dia:
- Foco comercial do dia/semana: Reposição prioritária de itens de curva A e organização de pontas de gôndola
- Ponto de atenção operacional: Conferência rigorosa de validade (PVPS) e precificação correta
- Desafio de escala hoje: Equipe reduzida devido a folga programada na escala 6x1

Crie um roteiro direto, motivador e sem enrolação com:
1. Abertura curta (reconhecendo o esforço da equipe).
2. As 3 prioridades inegociáveis do turno.
3. Uma frase de fechamento para gerar senso de dono e trabalho em equipe.
```

### Minha Delegação

```text
Quero delegar a você a criação de um Cronograma Semanal de Prevenção de Perdas (PVPS) e Reposição Crítica para o meu setor no varejo.

- Objetivo: Reduzir perdas por vencimento e evitar ruptura nos horários de pico (sexta e sábado).
- Contexto: Trabalho em escala 6x1 com uma equipe de 4 operadores divididos em dois turnos (manhã e tarde).
- Recursos: Tenho apenas a equipe atual e os horários normais de recebimento de mercadoria pela manhã.
- Limites: Não posso gerar hora extra e não posso parar o abastecimento das gôndolas nos horários de maior fluxo (11h às 13h e 17h às 19h).
- Critério de Sucesso: Uma tabela prática de segunda a domingo definindo qual categoria auditar em cada dia e qual turno é responsável.

Regra de Execução: Antes de gerar a tabela final, apresente apenas o PLANO DE EXECUÇÃO (quais etapas você vai seguir e quais premissas vai usar) e aguarde minha aprovação para continuar.
```

### O Plano da IA

<img width="1589" height="1131" alt="image" src="https://github.com/user-attachments/assets/38a5262d-a6d7-4e78-922d-416f41dde797" />
Antes de autorizar a execução, conferi se o plano respeitava os horários de pico (11h–13h e 17h–19h) e a divisão de turnos da escala 6x1 sem gerar horas extras, aprovando a etapa seguinte somente após validar essas premissas.


### O Resultado

<img width="1094" height="627" alt="image" src="https://github.com/user-attachments/assets/e7f6dded-3f1b-42db-9014-2b256da64ca3" />
Conferi a tabela dia a dia para garantir que as categorias perecíveis fossem auditadas antes do pico de sexta-feira e que nenhum dado interno ou confidencial da loja estivesse exposto.


### Como Foi para Você

Ganhei agilidade e padronização para organizar a rotina semanal da equipe e preparar alinhamentos de turno em poucos minutos. Trabalhar com trava de aprovação antes da execução garante que a IA atue como apoio operacional, mantendo a decisão final sempre sob meu controle.
