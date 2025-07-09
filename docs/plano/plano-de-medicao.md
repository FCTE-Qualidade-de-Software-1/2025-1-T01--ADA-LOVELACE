# 📋 Plano de Avaliação de Usabilidade e Eficiência - App Mobile e Web

## 👩‍🦳 Persona
- **Idade:** 65+ anos
- **Escolaridade:** Ensino Fundamental
- **Experiência prévia:** Facebook, WhatsApp, apps da Caixa Econômica Federal
- **Dispositivo:** Samsung Galaxy A01 (hardware modesto)
- **Habilidades digitais:** Básicas
- **Necessidades:** Texto claro, fonte grande, feedbacks visuais simples

---

## ⚙️ Configuração da Avaliação

### 📱 Dispositivo Mobile
- **Modelo:** Samsung Galaxy A01  
- **RAM:** 2 GB  
- **Tela:** 5.7", 720 x 1520 px  
- **Sistema:** Android 11 (One UI Core)

### 🌐 Dispositivo Web
- **Navegador:** Google Chrome  
- **Resolução mínima:** 1366x768  
- **Redes:** Wi-Fi 10 Mbps e simulação de 1 Mbps

### ⏳ Estimativas Cognitivas da Persona

| Item                        | Estimativa                         |
|-----------------------------|------------------------------------|
| Tempo de reação médio       | 1.5 – 2 s                           |
| Tempo de leitura por linha  | 4 – 6 s                             |
| Taxa de erro de leitura     | 20–25% (caso de fontes pequenas)   |

---

## 🎯 Objetivo 1: Avaliar Usabilidade

### 🔹 Q1: Navegação Simples
- **Métrica M1:** Taxa de sucesso em tarefas  
- **Tarefa:** Acessar uma tela e realizar uma ação (ex: enviar formulário)  
- **Meta:** ≥ 80% de sucesso sem ajuda  
- **Método:** Observação direta e gravação de tela

### 🔹 Q2: Satisfação Visual
- **Métrica M2:** NPS (Net Promoter Score)  
- **Tarefa:** Avaliação da interface (0 a 10)  
- **Meta:** NPS ≥ 30  
- **Método:** Escala oral adaptada: “Você recomendaria este app para alguém como você?”

### 🔹 Q3: Tempo de Tarefas
- **Métrica M3:** Tempo médio por tarefa  
- **Tarefa:** Conclusão de tarefas principais  
- **Meta:** ≤ 60 segundos por tarefa  
- **Método:** Cronometragem direta

---

## ⚙️ Objetivo 2: Avaliar Eficiência

### 🔹 Q4: Tempo de Resposta
- **Métrica M4:** Tempo médio de resposta em ações críticas  
- **Meta:** ≤ 2 segundos  
- **Método:** Log ou cronometragem manual

### 🔹 Q5: Uso de Recursos
- **Métrica M5:** Porcentagem média de uso de CPU e memória  
- **Meta:** ≤ 70% CPU, ≤ 80% RAM  
- **Ferramenta:** Android Profiler / Chrome DevTools

### 🔹 Q6: Desempenho em Conexões Lentas
- **Métrica M6:** Tempo de resposta em rede 1 Mbps  
- **Meta:** ≤ 3 segundos para ações básicas  
- **Ferramenta:** Simulação via throttling

### 🔹 Q7: Tempo de Carregamento Inicial
- **Métrica M7:** Tempo médio de carregamento em diferentes redes  
- **Meta:** ≤ 5 s (10 Mbps), ≤ 8 s (1 Mbps)  
- **Ferramenta:** DevTools + cronômetro

---

## 🧪 Metodologia de Teste

### 1. Pré-Teste
- Apresentação do app
- Instruções em linguagem simples
- Ajuste da fonte/tamanho de tela se necessário

### 2. Execução
- Testes presenciais com gravação
- Cronometragem de tarefas
- Observação de comportamentos e hesitações
- Participante pode pensar em voz alta

### 3. Pós-Teste
- Coleta de opinião geral (oral)
- Perguntas simples:
  - “O que foi mais fácil?”
  - “O que foi mais difícil?”
  - “Você recomendaria esse app?”

---

## 🧠 Adaptações para o Perfil da Usuária
- Texto com fonte ≥ 14pt
- Ícones reconhecíveis e com rótulos
- Evitar jargões ou termos técnicos
- Feedbacks claros: "Salvo", "Enviado", "Erro"
- Fluxos curtos e bem segmentados
- Pausas entre tarefas para evitar fadiga

---

## Tabela de Contribuição

| Matrícula | Nome completo                       | Contribuição (%) |
| --------- | ----------------------------------- | ---------------- |
| 190102977 | Artur Ricardo dos Santos Lopes      | 16,7%            |
| 221007690 | Diego Carlito Rodrigues de Souza    | 16,7%            |
| 221008060 | Gabriel Moura dos Santos            | 16,7%            |
| 211029361 | João Pedro Nóbrega Fernandes        | 16,7%            |
| 221008300 | Marcos Antonio Teles de Castilhos   | 16,7%            |
| 221008481 | Víctor Moreira Almeida              | 16,7%            |

---

## Histórico de Versão

| Versão | Data       | Autor                                      | Descrição            | Revisor |
| ------ | ---------- | ------------------------------------------ | -------------------- | ------- |
| `1.0`    | 08/07/2025 | [Gabriel Moura](https://github.com/thegm445) | Criação do documento |  |