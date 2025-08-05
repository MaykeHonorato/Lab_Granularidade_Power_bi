# 📊 A Importância da Granularidade dos Dados

## 📌 Visão Geral

Neste módulo, vimos a importância da **granularidade dos dados**, que desempenha um papel fundamental na construção de modelos analíticos eficientes e na geração de informações relevantes para a tomada de decisão.

Granularidade se refere ao **nível de detalhe** com que os dados são armazenados ou analisados. Escolher a granularidade adequada é um passo essencial em projetos de Business Intelligence, bancos de dados relacionais e modelagem dimensional.

---

## 🔍 O Que é Granularidade?

A granularidade define **quão detalhado ou resumido** é o dado disponível. Por exemplo:

- 📅 **Alta granularidade** (fina): vendas por produto, por cliente, por dia.
- 📆 **Baixa granularidade** (grossa): vendas totais por mês ou por região.

---

## 🎯 Por Que Isso é Importante?

✅ **Performance e armazenamento**  
Granularidades mais finas resultam em maior volume de dados, o que pode impactar o desempenho de consultas.

✅ **Flexibilidade analítica**  
Granularidade fina permite análises mais específicas e insights mais profundos.

✅ **Consistência no modelo dimensional**  
No modelo estrela (Star Schema), a tabela fato deve ter uma granularidade bem definida para garantir integridade com as dimensões.

✅ **Qualidade na tomada de decisão**  
A granularidade influencia diretamente a **qualidade, precisão e utilidade** dos dados disponíveis para análise.

---

## 🧠 Exemplo Prático

Imagine um projeto de análise de vendas. Dependendo da granularidade da tabela fato, você poderá:

- 🎯 Analisar vendas **por item e por hora** (alta granularidade);
- 📈 Ver o total de vendas **por mês** (baixa granularidade).

A escolha errada pode limitar ou até inviabilizar certas análises.

---

## 🧩 Conclusão

A definição da granularidade deve ser feita **logo no início do projeto**, pois ela impacta diretamente a estrutura do modelo de dados, a performance das consultas e a profundidade das análises.  

> Um modelo bem planejado começa com uma **granularidade bem definida**.

---

## 📁 Sobre o Repositório

Este repositório tem como objetivo registrar conteúdos teóricos e práticos sobre modelagem de dados, com foco na granularidade e boas práticas em projetos de BI e Data Warehousing.

---

## 📚 Referências

- Kimball, R. (The Data Warehouse Toolkit)
- Microsoft Learn – Modelagem Dimensional no Power BI
- Oracle Data Warehouse Concepts

---
