# TIPAGEM

A tipagem funciona como uma regra de uso de dados, quanto mais forte for a tipagem, mais obrigatório é a declaração do tipo de dado.

A tipagem em JS é fraca, a declaração dos dados acontece de modo dinâmico.

Ex: Ao criarmos uma variável com valor entre aspas ("valor") o JS já converte o dado para o tipo String.

# TIPOS PRIMITIVOS

As variáveis em JS podem guardar tipos de dados que chamamos de tipos primitivos.

Variáveis podem guardar valores dos tipos: boolean; null; undefined; number; string; array; object; function.

## DECLARAÇÃO DE VARIÁVEIS

- var: escopo global e local, pode ter seu valor alterado, se não tiver um valor inicial será tratada como null;
- let: escopo local de bloco, pode ter seu valor alterado, se não tiver um valor inicial será tratada como null;
- const: escopo local de bloco, somente leitura, o valor inicial é obrigatório e não pode ser alterado.

## Escopo

O escopo em JS define a limitação e visibilidade de um bloco de código.

- escopo global: quando a variável é declarada fora de qualquer bloco, sua visibilidade fica disponível em todo o código.
- escopo local: quando a variável é declarada dentro de um bloco, sua visibilidade pode ficar disponível ou não.