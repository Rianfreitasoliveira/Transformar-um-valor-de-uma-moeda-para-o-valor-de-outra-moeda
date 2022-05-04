# Transformar-um-valor-de-uma-moeda-para-o-valor-de-outra-moeda
Exemplo: REAL para DOLAR
> var n1 = 1500.5
undefined
> n1
1500.5
> n1.toFixed(2)
'1500.50'
> n1.toFixed(2).replace('.', ',')
'1500,50'
> n1.toLocaleString('pt-BR', {style: 'currency', currency: 'BRL'})
'R$ 1.500,50'
> n1.toLocaleString('pt-BR', {style: 'currency', currency: 'USD'})
'US$ 1.500,50'
> n1.toLocaleString('pt-BR', {style: 'currency', currency: 'EUR'})
'€ 1.500,50'
