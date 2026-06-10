# 🍽️ Cardápio Interativo Inteligente

O **Cardápio Interativo** é um sistema inteligente projetado para automatizar e otimizar o planejamento de refeições diárias. O programa seleciona pratos de forma aleatória combinando as preferências do usuário, restrições calóricas, tempo disponível e os ingredientes que ele já possui em casa.

---

## 🎯 Objetivo do Projeto

Criar uma solução prática para a organização alimentar, permitindo que o usuário monte refeições completas personalizadas sem desperdício de tempo ou de ingredientes.

---

## ⚙️ Parâmetros de Seleção

Para gerar uma refeição, o sistema cruza os seguintes dados do usuário:
* **Número de pratos:** Quantidade de opções desejadas na mesma refeição.
* **Tempo disponível:** Tempo máximo que o usuário tem para o preparo.
* **Limite de calorias:** Teto calórico total estipulado para a refeição.

---

## 🚀 Funcionalidades Principais

### 1. Histórico e Gerenciamento de Refeições
O programa mantém um registro ativo para referência onde é possível:
* **Inserir** novas refeições.
* **Editar** refeições já parametrizadas.
* **Remover** refeições antigas.
* **Fazer ou refazer** combinações de pratos.

### 2. Banco de Receitas
* Lista completa com receitas cadastradas para a escolha e sorteio do sistema.

### 3. Despensa Interativa
* Sistema inteligente que verifica quais ingredientes o usuário tem disponíveis antes de sugerir ou selecionar qualquer prato.

### 4. Gestão de Pratos Prontos
* Opção de marcar pratos que já estão preparados (sobras ou marmitas prontas).
* Pratos marcados como "prontos" são automaticamente excluídos do cálculo de tempo de preparo da nova refeição.

---

## 💡 Ideias de Melhorias Futuras

O projeto prevê a implementação das seguintes atualizações:

* **Filtros Alimentares Avançados:** Função para excluir ou especificar grupos de alimentos (ex: vegetariano, sem glúten, sem lactose).
* **Vínculo Automatizado com o Histórico:** Permitir que o programa analise o histórico para marcar automaticamente pratos anteriores como "já preparados".
* **Categorização por Ocasião:** Criar tipos específicos de refeições (Café da Manhã, Almoço, Café da Tarde, Jantar) com pratos exclusivos para cada momento do dia.

---
## 🎲 Banco de dados
 * Banco de dados escolhido: **MariaDB**
### Tabelas do Banco
  * **Grupos** Grupos alimentares para guiar os ingredientes, criados para guiar as funções futuras de exclusão e inclusão de grupos especificos
  * **Ingredientes** Guarda todos os ingrediente cadastrados bem como a quantidade informada para a dispensa, as calorias contidas em uma porção e o grupo alimentar.
  * **Pratos**
