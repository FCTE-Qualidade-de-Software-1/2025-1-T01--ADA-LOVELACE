# Projeto AGROMART: Fase 4 – Execução da Avaliação

**Equipe:**
* Artur Ricardo dos Santos Lopes
* Diego Carlito Rodrigues de Souza
* Gabriel Moura dos Santos
* João Pedro Nóbrega Fernandes
* Marcos Antonio Teles de Castilhos
* Víctor Moreira Almeida

---

## 1. Introdução

Este documento apresenta os resultados da Fase 4 do projeto AGROMART, focada na execução da avaliação do sistema. O processo foi conduzido em conformidade com o plano de medição e avaliação (GQM) definido nas fases anteriores.

O objetivo principal desta fase foi coletar dados quantitativos e qualitativos sobre a usabilidade e eficiência da plataforma, identificar oportunidades de melhoria com base nesses dados e executar uma ação de melhoria tangível para aprimorar a experiência do usuário.

## 2. Metodologia da Avaliação

A avaliação foi projetada para testar a aplicação em um cenário de uso realista, com foco especial em acessibilidade e facilidade de uso para um público amplo.

### 2.1. Perfil dos Participantes

Para garantir que a plataforma seja intuitiva para todos os públicos, a avaliação foi realizada com um painel de **12 participantes voluntários, todos com idade superior a 60 anos**. A escolha deste grupo demográfico foi estratégica para identificar barreiras de usabilidade que poderiam não ser evidentes para usuários mais jovens e com maior afinidade tecnológica.

### 2.2. Tarefas Avaliadas

Os participantes foram instruídos a executar um conjunto de tarefas essenciais no sistema, tanto na interface web quanto na mobile:

1.  **Tarefa de Consumidor:** Encontrar e adicionar três tipos diferentes de vegetais ao carrinho de compras.
2.  **Tarefa de Agricultor:** Realizar o cadastro de um novo produto (ex: "Tomate Orgânico").
3.  **Tarefa Geral:** Criar uma conta de usuário na plataforma.

### 2.3. Coleta de Dados

Os seguintes métodos foram utilizados para coletar os dados, de acordo com o plano GQM:

* **Observação Direta:** Acompanhamento da interação dos usuários com o sistema.
* **Cronometragem:** Medição do tempo para completar cada tarefa.
* **Questionário Pós-Tarefa:** Aplicação do Net Promoter Score (NPS) focado em usabilidade.
* **Monitoramento Técnico:** Ferramentas para medir latência, uso de CPU e tempo de carregamento.

## 3. Resultados Obtidos

Os dados coletados foram consolidados e comparados com os critérios de sucesso definidos no plano de avaliação.

### 3.1. Objetivo de Medição 1: Usabilidade

Os resultados de usabilidade revelaram pontos críticos que necessitam de atenção, especialmente considerando o perfil dos participantes.

| Questão | Métrica (Q-RAPID)          | Resultado Obtido | Nível Aceitável | Critério de Julgamento   | Avaliação             |
| :------ | :------------------------- | :--------------- | :-------------- | :----------------------- | :-------------------- |
| Q1      | Taxa de conclusão de tarefas | 65%              | ≥ 80%           | < 70% = Crítico          | **Crítico** |
| Q2      | Pontuação NPS (Usabilidade)  | 4.2              | ≥ 7             | < 7 = Insatisfatório     | **Insatisfatório** |
| Q3      | Tempo médio por tarefa     | 195 segundos     | ≤ 120s          | > 150s = Otimização      | **Necessita Otimização** |

### 3.2. Objetivo de Medição 2: Eficiência

Os testes de eficiência, realizados em ambiente controlado, apresentaram resultados majoritariamente dentro do esperado.

| Questão | Métrica (Q-RAPID)          | Resultado Obtido | Nível Aceitável | Critério de Julgamento     | Avaliação     |
| :------ | :------------------------- | :--------------- | :-------------- | :------------------------- | :------------ |
| Q4      | Latência de resposta       | 850ms            | ≤ 1000ms        | > 1500ms = Falha           | **Aceitável** |
| Q5      | Uso médio de CPU           | 60%              | ≤ 70%           | > 85% = Risco              | **Aceitável** |
| Q6      | Tempo resposta (1Mbps)     | 2800ms           | ≤ 3000ms        | > 4000ms = Inaceitável     | **Aceitável** |
| Q7      | Tempo carregamento inicial | 5.5s (mobile)    | ≤ 5s (mobile)   | > 8s = Necessita otimização | **Alerta** |

## 4. Análise e Oportunidades de Melhoria

A análise dos dados, especialmente o feedback qualitativo dos 12 participantes, aponta para **barreiras significativas de usabilidade**. Enquanto a performance técnica do sistema é robusta, a interface não se mostrou intuitiva para o público idoso.

**Principais Oportunidades Identificadas:**

1.  **Fluxo de Navegação Complexo:** A taxa de conclusão de tarefas (65%) foi severamente impactada pela dificuldade dos usuários em encontrar os botões corretos e entender a sequência de ações, principalmente no cadastro de produtos. Muitos participantes abandonaram a tarefa.
2.  **Baixa Legibilidade e Contraste:** Vários usuários relataram dificuldade para ler os textos devido ao tamanho da fonte e à combinação de cores, que não oferecia contraste suficiente.
3.  **Ícones Não Intuitivos:** Ícones sem rótulos de texto geraram confusão. Por exemplo, o ícone de "salvar" não foi prontamente reconhecido por todos.
4.  **Frustração do Usuário:** O baixo NPS (4.2) e o tempo elevado por tarefa (195s) são indicadores claros de que a experiência atual gera frustração, o que representa um risco elevado de abandono da plataforma.

## 5. Conclusão

A avaliação com 12 usuários idosos foi fundamental para revelar que, embora o AGROMART seja funcional do ponto de vista técnico, ele possui falhas críticas de usabilidade que podem impedir sua adoção por uma parcela importante do público-alvo.

A criação do protótipo de alta fidelidade representa o primeiro passo concreto para mitigar esses riscos. Recomenda-se que a próxima etapa seja a implementação das melhorias propostas e a realização de uma nova rodada de testes de usabilidade com o mesmo perfil de público para validar a eficácia das soluções.

---

## Anexos

### Tabela de Contribuição

| Matrícula | Nome completo                    | Contribuição (%) |
| :-------- | :------------------------------- | :--------------- |
| 190102977 | Artur Ricardo dos Santos Lopes   | 16,7%            |
| 221007690 | Diego Carlito Rodrigues de Souza | 16,7%            |
| 221008060 | Gabriel Moura dos Santos         | 16,7%            |
| 211029361 | João Pedro Nóbrega Fernandes     | 16,7%            |
| 221008300 | Marcos Antonio Teles de Castilhos| 16,7%            |
| 221008481 | Víctor Moreira Almeida           | 16,7%            |

### Histórico de Versão

| Versão | Data       | Autor          | Descrição                                                                      | Revisor             |
| :----- | :--------- | :------------- | :------------------------------------------------------------------------------- | :------------------ |
| 1.0    | 04/07/2025 | Diego Carlito  | Criação do documento GQM                                                         | Gabriel Moura       |
| 1.1    | 05/07/2025 | Diego Carlito  | Melhora o Abstraction Sheet                                                      | Gabriel Moura       |
| 1.2    | 06/07/2025 | Víctor Moreira | Especificação da Avaliação                                                       | João Pedro Nóbrega  |
| **2.0**| **08/07/2025** | **Equipe** | **Execução da Avaliação e Ação de Melhoria** | **Todos** |