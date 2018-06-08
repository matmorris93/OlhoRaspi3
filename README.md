# OlhoRaspi3
University of Madeira's internship project

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

Para documentação completa ler "Relatório.pdf".
