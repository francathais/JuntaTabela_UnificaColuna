import pandas as pd

# Carregar os dados da primeira tabela
df1 = pd.read_excel('Pessoal_Reflexo_parelheiros.xlsx')

# Carregar os dados da segunda tabela
df2 = pd.read_excel('R001-MES10.xlsx')

# Realizar o merge com base nas colunas CARGO, UNIDADE e SERVIÇO
df_merged = pd.merge(df1, df2, on=['CARGO', 'UNIDADE', 'SERVICO'])

# Exibir o DataFrame resultante
print(df_merged)

# Salvar o DataFrame merge em um arquivo XLSX
df_merged.to_excel('df_merged.xlsx', index=False)
