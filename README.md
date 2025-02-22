# Book Recommender System (Sistema de Recomendação de Livros)

## 📌 Descrição
Este projeto tem como objetivo a construção de um **Sistema de Recomendação de Livros**, utilizando técnicas de **Aprendizado Não Supervisionado** e **agrupamento de dados**. O sistema sugere livros para os usuários com base nas escolhas e avaliações de leitura de outras pessoas com interesses semelhantes.

## 🏢 Problema de Negócio
A proposta é desenvolver um modelo preditivo que personalize recomendações e aumente a satisfação dos clientes. Com recomendações mais precisas:

- A chance de compra de um livro recomendado aumenta significativamente;
- O aumento de vendas gera maior faturamento para a empresa;
- Os clientes se sentirão mais valorizados ao perceberem que o site entende suas preferências e oferece sugestões relevantes.

## 🔍 Metodologia
O sistema foi construído utilizando o algoritmo **Nearest Neighbors (Vizinhos Mais Próximos)**, que agrupa usuários com base na **distância euclidiana**. A abordagem adotada inclui:

1. **Transposição de Usuários**: 
   - Cada usuário é representado como uma coluna, e cada linha corresponde a um livro avaliado.
   - As avaliações são utilizadas como variáveis para a máquina preditiva.
   
2. **Matriz Esparsa**:
   - A tabela dinâmica gerada contém muitos valores zerados, o que pode impactar no custo computacional.
   - Para otimizar os cálculos, a tabela foi convertida para uma matriz esparsa, reduzindo o armazenamento de valores zero e melhorando o desempenho na análise de similaridade.

## 🛠️ Tecnologias Utilizadas
- **Python** 🐍
- **Bibliotecas:** Pandas, NumPy, Scikit-learn, Scipy

## 📈 Resultados Esperados
- Melhor experiência do usuário por meio de sugestões personalizadas.
- Aumento na taxa de conversão de recomendações em compras.
- Maior fidelização de clientes devido a recomendações mais assertivas.

## 📌 Contribuição
Fique à vontade para contribuir com melhorias, sugestões ou reportar problemas via **Issues** ou **Pull Requests**.
