# Observações :sunglasses:

## Syntax
- A tag abreviada utilizada para ecoar (Ex: <?=$type?>) já vem habilitada por padrão a partir do PHP 5.4, porém, a tag abreviada (<? echo $type; ?>) deve ser ativada através do php.ini
- As tags asp (<%%>) e script (<script language="php"></script>) foram removidos no PHP 7

## Operators
- Operador exponencial ($a ** $b) inserido na versão 5.6
- A partir da versão 5.3, o operador `new` retorna uma referência (&) automaticamente, ou seja, não é necessário (e foi depreciado) atribuir um objeto por referência
- Último erro disparado é armazenado, automaticamente, na variável global `$php_errormsg`
- Operado backticks (``) pode ser utilizado para executar comandos externos (shell script)
- PHP segue a convenção de operações aritméticas em caracteres do PERL ao invés do C. No C, operações aritméticas em caracteres são incrementados de acordo com a tabela ASCII Ex: se eu der um loop incrementado uma variável de valor `A6`, a mesma teraá seu valor alterado para  A7, A8, A9, B1, B2 etc
- Operadores de comparação `||` e `&&` possuem maior precedência que `OR` e `AND`. Ex: $a = false || true ($a = (false || true))/$a = false OR true (($a = false) OR true)
- Quando um array é unido com outro ($array1 + $array2), as chaves são sobrescsitas, porém, prevalece as chaves do array da esquerda ($array1)