# Exercicios e Testes JS

1 - Converter velocidade da luz m/s para cm/nano   
2 - Converter "audacity" em "Udacity"   
3 - Adicionar mais '1 ao ultimo elemento de um array  

```
var meuArray = [1, 2, 3, 4, 5];
var ultimoElemento = meuArray.pop();
meuArray.push(ultimoElemento +1);
```
4 - Formatar string CaMEron PittMan  em Cameron PITTMAN

```
function inName(name) {
    name = name.trim().split(" ");
    name[1] = name[1].toUpperCase();
    name[0] = name[0].slice(0,1).toUpperCase() + name[0].slice(1).toLowerCase();
    return name[0] + " name[1];
}
```