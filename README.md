# OlhoRaspi3
University of Madeira's internship project

Disclaimer: Todos os códigos vindos de outras fontes senão de mim estão devidamente referenciados nos ficheiros ".py" e também no relatório. Este projeto não foi feito com intenções profissionais e sim como um projeto de avaliação universitário, logo o código poderá possuir algumas partes com programação "amadora". Seu uso é exclusivamente pessoal, se desejar utilizá-lo profissionalmente fale comigo antes ;)

------>Para documentação completa ler "RelatorioProjeto.pdf"<------

Existe uma lista de bibliotecas a inserir, estando todas estas listadas no Relatório. 
Incluído neste projeto estão dois ficheiros zip, um contendo os ficheiros para o Raspberry Pi e outro contendo os ficheiros + bibliotecas necessárias para o Arduino. Deverás extrair os ficheiros dos arquivos zip antes de utilizar o projeto (DUH!).

Cada um dos processos deve ser inicializado manualmente utilizando os seguintes comandos:
1.	Primeiro deverá abrir a consola do Raspbian;
2.	Após isso, deverá ir para a pasta onde está o projeto executando por exemplo:
“cd PastaProjeto”;

3.	Para executar o processo BotTelegrama execute o seguinte comando:
“python3 BotTelegrama.py”;
4.	Agora para o processo leitor execute o seguinte comando:
“python3 leituraSomTempLuxPrjEstagio.py”;
5.	Por fim para executar o processo servidor deverá executar o comando:
“python3 manage.py runserver {IP do Raspberry}:8000”;
Uma observação importante: para conhecer o IP do Raspberry deverá executar o comando “ifconfig”. Se o Raspberry estiver conectado à uma rede WI-FI deverá procurar por “wlan0” e encontrar o campo “inet”. O IP atribuído estará aí. Se estiver conectado à uma rede Ethernet o procedimento é semelhante, mas em vez de “wlan0” deverá procurar por “eth0”. 

That's all, happy codding :D

Obs: O projeto pode ser melhorado pois algumas implementações (como a câmara) não estão completas. O código da captação de som foi removido do projeto assim como os cálculos de níveis de luminosidade.

