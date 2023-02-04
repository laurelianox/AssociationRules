
# Regras de Associação
Prática com itens de compra de um supermercado.


## O que é ?
É um algortimos de **aprendizado supervisionado**. 
Seu principal objetivo é encontrar padrões relevantes nos dados. 
Padrões que possam ser usados para definir a estratégia do negócio ou para identificar um comportamento pouco usual.

## Versões:
AssociationRules - versão com comentários sobre as bibliotecas e métodos usados. Aconselhado para estudantes.<br>
AssociationRules_ClearVersion - versão só com a aplicação.

## Nesta prática utilizamos:
TransactionEncoder
Pandas
Apriori
Association Rules


## Processo
1. Importação das bibliotecas Pandas, MLExtend Processing (TransactionEncoder), 
2. Informar a base de dados
3. Conhecendo a base de dados (head, shape, describe, unique)
4. Criar uma lista com cada item do dataset
5. Criando lista de produtos com indicador de true or false
6. Criando dataframe com itens do mercado
7. Excluindo coluna 'nan' do dataframe
8. Gerando os itens frequentes no dataset 
9. Criando as regras de associação
10. Reajustando o dataset
11. Filtrando as melhores regras baseado no LIFT
12. Avaliando resultados


## Documentação
http://rasbt.github.io/mlxtend/user_guide/preprocessing/TransactionEncoder/
http://rasbt.github.io/mlxtend/user_guide/frequent_patterns/apriori/
http://rasbt.github.io/mlxtend/user_guide/frequent_patterns/association_rules/
https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.sort_values.html
https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.drop.html?highlight=drop#pandas.DataFrame.drop


## Final
Agradecimento ao Prof Leandro Lessa pelo aprendizado.
Repositório original: https://github.com/ProfLeandroLessa/association-rules

Aulas ofertadas pela IGTI (atual XP Educação) em parceria com o Banco Pan

Alterações e acréscimos: Lidiane Aureliano
https://github.com/laurelianox
