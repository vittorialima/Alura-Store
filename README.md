# 🏪 Análise de Lojas - Challenge Alura Store

Este projeto foi desenvolvido como parte do **Challenge da Alura para iniciantes em Python e Data Science**, com o objetivo de realizar uma **análise comparativa de desempenho entre quatro lojas virtuais**. Através da manipulação e visualização de dados, foram extraídos insights estratégicos para responder à pergunta principal:

> **"Em qual loja vale mais a pena investir?"**

---

## 📂 Sobre os dados

Os dados utilizados foram fornecidos pela própria Alura no desafio. Cada loja possui um arquivo `.csv` com colunas como:

- Produto  
- Categoria do Produto  
- Preço  
- Frete  
- Data da compra  
- Avaliação da compra  
- Tipo de pagamento  
- Quantidade de parcelas  
- Vendedor  
- Local da compra  

---

## 📊 Análises Realizadas

1. ### **Faturamento por Loja**
   - Soma total de preços por loja.
   - Resultados apresentados com formatação monetária e gráfico de barras.

2. ### **Vendas por Categoria**
   - Contagem dos produtos vendidos por categoria em cada loja.
   - Útil para identificar quais segmentos têm maior força em cada unidade.

3. ### **Avaliação Média das Lojas**
   - Cálculo da média da coluna “Avaliação da compra”.
   - Identificação da loja com melhor e pior avaliação pelos clientes.

4. ### **Produtos Mais e Menos Vendidos**
   - Análise dos produtos mais populares e com menor saída por loja.
   - Pode ajudar na tomada de decisão sobre estoques e promoções.

5. ### **Frete Médio por Loja**
   - Cálculo do custo médio de frete.
   - Ajuda a entender o impacto logístico sobre as vendas.

---

## 📌 Conclusão

Com base nas análises, foram avaliados os seguintes pontos:

| Critério         | Melhor Loja |
|------------------|-------------|
| Faturamento      | Loja 1      |
| Avaliação        | Loja 4      |
| Frete            | Loja 1      |
| Custo-benefício  | Loja 1      |
| Potencial futuro | Loja 4      |

A **Loja 1** foi recomendada como a melhor opção para investimento imediato, por apresentar o maior faturamento, o frete mais acessível e bom desempenho geral.  
Já a **Loja 4** se mostrou promissora pela ótima avaliação dos clientes, mas ainda limitada por custos logísticos elevados.

---

## 🛠️ Tecnologias Utilizadas

- Python
- Google Colab
- Pandas
- Matplotlib
- Tabulate
- Markdown

---

## 📁 Organização do Projeto
├── loja_1.csv ├── loja_2.csv ├── loja_3.csv ├── loja_4.csv ├── analise_lojas.ipynb ├── README.md └── graficos/

## ✨ Aprendizados

Durante este projeto, foram aplicadas habilidades como:
- Leitura e concatenação de arquivos CSV com Pandas
- Agrupamento e agregação de dados
- Visualização com Matplotlib
- Formatação numérica e textual
- Escrita de relatórios analíticos em Markdown
- Criação de conclusões baseadas em dados reais

---

## 📢 Créditos

Desenvolvido por **Vitória Lima**  
Desafio proposto pela plataforma [Alura](https://www.alura.com.br/)

---
