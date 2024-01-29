# AdaFinTech - Grupo 6

Sejam todos bem-vindos ao AdaFinTech, nosso sistema financeiro fácil e descomplicado.

O **AdaFinTech** é um sistema financeiro criado para o Projeto Final do Módulo Python do Bootcamp Engenheiro de Dados Santander Coders 2023.2 em conjunto com a Ada Tech.

O Grupo 6 é composto por:

- João Victor da Silva Sabino
- Lauana Rodrigues da Silva
- Thaísa Magalhães Elvas
- Thiago de Almeida Breves

---

Seguem instruções do **projeto final**:

Para finalizarmos nosso módulo de **Lógica de Programação II**, vamos desenvolver um pequeno "sistema financeiro" para gerenciar algumas operações! Este sistema deverá receber movimentações financeiras e armazená-las em um arquivo csv, ou json (à escolha de vocês)!

O sistema deverá ser capaz de realizar as seguintes operações:

- **Criar** novos registros e identificar a **data** em que o registro foi feito, qual foi **tipo** de movimentação, e seu **valor**.
  - Os tipos de registros são três: despesas, receita ou investimento.
    - No caso de **receita**, o valor deve ser tratado como numérico e armazenado normalmente.
    - no caso de **despesas**, o valor deve ser recebido como positivo, mas armazenado como negativo.
    - No caso de **investimento**, deveremos ter algumas informações adicionais: o valor que foi investido e a taxa de juros do investimento. Lembre-se de que o montante (M) para uma dada taxa de juros _i_ após _t_ dias pode ser calculado pela seguinte relação: $M = V * (1 + i)^t$ ([Saiba mais](https://matematicafinanceira.org/juros-compostos/)), considere o tempo em dias.
- **Ler** registros: Deverá ser possível consultar os registros por data, tipo ou valor. Ou seja, se a pessoa usuária quiser consultar todos os registros do dia "20/03/2023", o sistema deve ser capaz de imprimir tudo que foi registrado naquela data. (Ou seja, neste caso, é necessário que o arquivo seja aberto e lido, filtrando resultados, quando necessário)
- **Atualizar** registros: No caso de atualização, pode-se atualizar o valor e o tipo. Automaticamente, a nova data deverá ser a de atualização do registro.
- **Deletar**: Deverá ser possível deletar o registro (caso necessário, considere o indice do elemento como ID).
- Crie uma função que atualize os valores de rendimento sempre que chamada
- Crie uma função 'exportar_relatorio', que exporte um relatorio final em csv ou json .
- Crie pelo menos uma função de agrupamento, que seja capaz de mostrar o total de valor baseado em alguma informação (mês, tipo...). Esta função é de livre escolha do grupo. Pode ser, por exemplo, a média de receitas/despesas em um determinado mês, o rendimento médio dos investimentos em um dado período etc.
- Crie valores separados para identificar a data (dia, mês, ano).

---

Atenção:

- Não utilize a biblioteca pandas para resolução desse exercício!
- Deem um nome criativo para a aplicação de vocês :)
