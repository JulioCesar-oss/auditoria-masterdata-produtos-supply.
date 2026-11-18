# Auditoria de Master Data, Higienização de Portfólio e Otimização de Picking (Supply Chain)

## 🎯 Visão Geral do Projeto
Este projeto detalha a iniciativa de mapeamento, auditoria e limpeza da base de produtos cadastrados em um Centro de Distribuição (CD 801). Diante da poluição de portfólio e da retenção de itens obsoletos nas áreas nobres de separação, foi desenvolvido um estudo analítico cruzando dias sem movimentação, última data de entrega, saúde do estoque e ocupação física. O objetivo principal foi fornecer insumos consolidados para alinhar os setores de Cadastro e Comercial, viabilizando a descontinuação ou remanejamento de SKUs improdutivos para liberar capacidade e mitigar riscos logísticos.

---

## 🔍 O Problema
Na operação diária de armazenagem, identificou-se um gargalo sistêmico e físico provocado pela falta de governança sobre o ciclo de vida dos produtos cadastrados:
* **Poluição de Espaço no Picking:** Ocupação de endereços nobres de separação por itens de baixíssimo giro ou obsoletos, dificultando o fluxo operacional e reduzindo a eficiência da mão de obra.
* **Risco Elevado de Vencimento e Perdas:** Acúmulo de mercadorias paradas sem saída programada, elevando o risco de perdas financeiras por validade vencida (*shelf life* comprometido).
* **Desalinhamento entre Áreas (Comercial x Operação):** Ausência de dados analíticos claros para confrontar o setor Comercial e de Cadastro sobre o impacto operacional de manter itens sem giro ativos no armazém.

---

## 🛠️ A Abordagem e Solução

Para resolver o problema de ponta a ponta e forçar uma tomada de decisão gerencial, o projeto foi estruturado em frentes estratégicas:

1. **Mapeamento Analítico Setor por Setor (Item a Item):**
   * Varredura completa da base de cadastros e do estoque físico em todo o CD.
   * Cruzamento de variáveis críticas: **dias sem movimentação**, **última data de entrega no CD** e nível de "sujeira" ou ociosidade no cadastro.
2. **Construção de Indicadores de Saúde de Portfólio:**
   * Segmentação dos SKUs por criticidade de giro para evidenciar quais itens estavam apenas ocupando espaço físico sem trazer retorno financeiro proporcional.
3. **Governança e Reuniões de Alinhamento (Comercial vs. Cadastro vs. Operação):**
   * Apresentação dos dados consolidados para os gestores comerciais e de cadastro, pautando discussões orientadas a dados sobre quais itens deveriam ser rigorosamente limpos ou inativados da operação.
4. **Alinhamento do Perfil de Separação:**
   * Redenominação e reestruturação do layout de endereçamento para garantir que apenas itens ativos e de alto giro permaneçam nas zonas de fácil acesso.

---

## 📈 Resultados Esperados e Impactos de Negócio

* **Maximização do Espaço de Picking:** Liberação expressiva de endereços nobres para produtos com real demanda de mercado, otimizando o tempo de percurso dos separadores.
* **Aprimoramento do Perfil de Separação:** Redução da quantidade de itens dispersos em cada endereço, aumentando a assertividade e reduzindo erros de separação.
* **Aumento do Giro de Mercadorias:** Aceleração do fluxo de estoque dentro do CD.
* **Mitigação de Riscos de Vencimento:** Prevenção de prejuízos com mercadorias paradas e estagnadas, garantindo maior saúde financeira para a operação.

---

## 🛠️ Tecnologias e Conceitos Aplicados
* **Sistemas:** WMS / ERP integrados.
* **Conceitos:** Gestão de Master Data, Higienização de Portfólio, Otimização de Picking, Gestão de Giro de Estoque (*Inventory Turnover*), Mitigação de Rupturas e Validades, Supply Chain Analytics.
