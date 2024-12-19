# vacina_x  
Esse pequeno programa permite visualizar a quantidade de doses de vacinas aplicadas nas notificações de atendimento antirrábico humano registradas no SINAN NET. Tabular essa informação atualmente não é possível no TabWin versão 3.6b, pois ao fazê-lo, o 
usuário obtém valores divergentes do que realmente contêm na base de dados.  
No TabWin, o próprio arquivo de tabulação informa que há problema no cálculo das doses de vacinas.  

![x](/img/image3.jpg)

Dessa forma, o "vacina_x" consegue informar a quantidade de doses de vacinas aplicadas distribuidas por mês de notificação, bastando ao usuário informar na linha de comando o código do município para que os dados possam ser processados.  

Dados de vacinação antirrábica processadas no TabWin.  
  
![x](/img/image2.jpg)

Os mesmos dados de vacinação antirrábica processados no "vacina_x".

![x](/img/image1.jpg)  

Sintaxe do executável:  

~~~
vacina_x.exe --total [código do município]

Usar o parametro --total para somar todas as doses de vacinas da base de dados.
Usar o parametro [codigo do municipio] para calcular as doses de vacinas de um municipio especifico.
[codigo do municipio] e o codigo IBGE de seis digitos do municipio escolhido.
~~~
