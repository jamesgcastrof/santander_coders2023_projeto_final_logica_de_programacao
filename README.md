# santander_coders2023_projeto_final_logica_de_programacao
# 💸 Projeto Final | Sistema de Controle Financeiro

O sistema deverá ser capaz de realizar as seguintes operações:

- **Criar** novos registros e identificar a data que o registro foi feito, qual tipo de movimentação, valor.

  - Os tipos podem ser:
    - Receita: o valor deve ser tratado como numérico e armazenado normalmente.
    - Despesas: o valor deve ser recebido como positivo, mas armazenado como negativo
    - Investimento: deve ter uma informação a mais de 'Montante', em que será calculado quanto o dinheiro rendeu desde o dia que foi investido.
    Para essa finalidade utilize a seguinte formula: $M = C * (1 + i)^t$ ([Saiba mais](https://matematicafinanceira.org/juros-compostos/)), considere tudo em dias.
- **Ler** registros: Deverá ser possível consultar os registros por data, tipo ou valor.
- **Atualizar** registros: No caso de atualização, pode-se atualizar o valor, o tipo e a data deverá ser a de atualização do registro.
- **Deletar**: Deverá ser possível deletar o registro (caso necessário, considere o indice do elemento como ID)

Outras funcionalidades:
- Crie uma função ```atualiza_rendimento``` que atualize os valores de rendimento sempre que chamada.
- Crie uma função ```exportar_relatorio```, que seja possível exportar um relatorio final em csv ou json.
- Crie pelo menos uma função de agrupamento, que seja capaz de mostrar o total de valor baseado em alguma informação (mes, tipo...)
- Crie valores separados para identificar a data (dia, mes, ano)
