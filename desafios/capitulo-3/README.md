# Desafio Capítulo #3

```php
/*
Na função date(), experimente mudar o Y para y. O que acontece?
*/
// Exibirá o ano atual com dois dígitos.

/*
Você consegue exibir a hora no formato de 12 horas, A.M. e P.M.?
*/
// Sim, basta usar echo date('h:i:s A');

/*
E se você tivesse que exibir o dia da semana em formato númerico, como 1 para segunda, 2 para terça etc.? Como faria?
*/
// Basta usar echo date('w'); 

/*
Exiba quantos dias faltam para o próximo sábado. Por exemplo, se hoje for quarta, então faltam 3 dias para sábado.
*/
// echo "Faltam " . (6 - date('w')) . " para sábado.";

/*
Exiba também o nome do mês atual.
*/
// echo date('F');
```