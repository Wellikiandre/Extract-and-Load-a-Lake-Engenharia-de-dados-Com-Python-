
Artigo com mais detalhes: https://www.linkedin.com/pulse/extract-load-lake-engenharia-de-dados-com-python-wellikiandre%3FtrackingId=403c8PFoRrOeDJ01%252FXrUbg%253D%253D/?trackingId=403c8PFoRrOeDJ01%2FXrUbg%3D%3D

Primeiramente, gostaria de explicar qual era o problema que precisava ser solucionado. Precisava fazer uma conversão em massa de vários arquivos .parquet para .delta, onde as localizações dentro do data lake eram totalmente diferentes, e isso tudo em um único código.

Após analisar a estrutura dos diretórios, identifiquei 774 arquivos .parquet. No entanto, precisava trabalhar com 144 arquivos específicos, que continham dados e tipos diferentes.

Neste código, que consiste em 5 passos, explicarei como solucionar esse problema. Além disso, mostrarei como modificar o código, que é altamente escalável, para ser utilizado em aproximadamente 80% dos processos de engenharia de dados que envolvem transformação entre diferentes camadas (BRONZE, PRATA e GOLD).

Se ficou interessado, me chame no privado.
