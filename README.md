# Reverse-Polish-annotation
Este projeto implementa uma calculadora que converte expressões matemáticas da notação infixa para a Notação Polonesa Reversa (NPR) utilizando estruturas de dados, como pilhas e filas. O código é escrito em C++ e é organizado em funções para facilitar a compreensão e a manutenção.

Readme
Calculadora em C++ com Notação Polonesa Reversa (NPR)

Este projeto implementa uma calculadora que converte expressões matemáticas da notação infixa para a Notação Polonesa Reversa (NPR) utilizando estruturas de dados, como pilhas e filas. O código é escrito em C++ e é organizado em funções para facilitar a compreensão e a manutenção.

Funcionalidades

1. Ordenação de Operadores (ordenarOp)
Determina a ordem de precedência entre dois operadores. Retorna verdadeiro se o operador A tiver maior ou igual precedência ao operador B, permitindo um correto empilhamento dos operadores durante a conversão.

2. Conversão para Notação Polonesa Reversa (converterNPR)
Converte uma expressão matemática em notação infixa para notação polonesa reversa. Utiliza uma pilha para gerenciar operadores e parênteses, e uma fila auxiliar para armazenar a expressão convertida.

3. Verificação de Parênteses (verificarParenteses)
Verifica se todos os parênteses abertos possuem um correspondente fechado, garantindo que a expressão matemática esteja bem formada.

4. Verificação de Operador (isOperator)
Determina se um caractere é um operador válido (soma, subtração, multiplicação, divisão, potência). Facilita a identificação de operadores na expressão.

Estrutura do Código

O código é organizado em funções auxiliares que se comunicam entre si para realizar a conversão e a validação da expressão:

- ordenarOp: Compara a precedência de operadores.
- converterNPR: Realiza a conversão de infixo para NPR.
- verificarParenteses: Confere a validade dos parênteses na expressão.
- isOperator: Identifica se um caractere é um operador.

Como Usar

1. Compile o código utilizando um compilador C++.
2. Execute o programa e insira a expressão matemática na notação infixa.
3. O programa exibirá a expressão convertida em Notação Polonesa Reversa.

Exemplo de Uso

// Entrada: (3 + 4) * 5
// Saída: 3 4 + 5 *

Contribuição

Sinta-se à vontade para contribuir com melhorias ou correções. Para contribuir, crie um fork do repositório, faça suas alterações e envie um pull request.

Licença

Este projeto está licenciado sob a MIT License - veja o arquivo LICENSE para mais detalhes.
