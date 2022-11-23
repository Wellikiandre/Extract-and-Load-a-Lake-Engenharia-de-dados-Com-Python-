
Artigo com mais detalhes: https://www.linkedin.com/pulse/extract-load-lake-engenharia-de-dados-com-python-wellikiandre%3FtrackingId=403c8PFoRrOeDJ01%252FXrUbg%253D%253D/?trackingId=403c8PFoRrOeDJ01%2FXrUbg%3D%3D

Primeiramente gostaria de falar qual era o BO(Problema que deveria ser solucionado).
Eu precisava fazer uma conversão em massa🐱 👓 de vários arquivos .parquet para .delta onde as localizações são totalmente diferentes dentro do data lake em um único código. Analisando o maior ramo dos diretório listei 774 arquivos parquet porém precisa trabalhar alguns específicos que no final das contas são 144 arquivos com 144 arquivos com dados diferentes , tipo diferentes etc....
Com este código em 5 STEP irei explicar como solucionar este problema, não só isso irei explicar, como explicarei como modificar o código que está altamente escalável para ser reproduzindo em quase 80% dos códigos que são utilizado em engenharia de dados no processo de transformação entre qualquer camada (BRONZE, PRATA E GOLD).
