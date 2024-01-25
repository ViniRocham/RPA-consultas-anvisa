# RPA Consultas ANVISA

## O que fazemos?

O projeto RPA de consultas ANVISA foi desenvolvido para automatizar tarefas no site da ANVISA ([https://consultas.anvisa.gov.br/#/genericos/](https://consultas.anvisa.gov.br/#/genericos/)). Consiste no preenchimento do número de registro de cada produto e, em seguida, armazena dados específicos (nome técnico, registro, situação, processo, fabricante legal, classificação de risco, vencimento do registro) em uma planilha Excel.

## Por que esse projeto é útil?

Este projeto foi criado para automatizar tarefas, proporcionando economia de tempo e redução de atividades repetitivas. O responsável por essa tarefa economizará tempo, podendo se concentrar em outras atividades enquanto a automação roda em segundo plano.

## Como os usuários podem começar a usar o projeto?

Para obter acesso ao projeto, o usuário deve ter o Google Chrome instalado em sua máquina. Em seguida, o download dos arquivos disponibilizados neste projeto deve ser feito, o usuário deverá criar uma pasta e botar somente os 3 arquivos.

- **Registro:** Neste arquivo Excel, o usuário deve fornecer os números de registro a serem consultados pelo programa, colocando um registro em cada linha. A primeira linha (preenchida com "Registro") não deve ser alterada, começando pela segunda linha. (foram colocados algumas linhas de exemplos no excel, exclua os exemplos antes de realizar as consultas)

- **Dados:** Neste arquivo, inicialmente vazio, o usuário receberá o retorno da consulta em uma planilha Excel com os dados específicos. (foram colocados algumas linhas de exemplos no excel, exclua os exemplos antes de realizar as consultas)

- **Automação ANVISA:** Este arquivo deve ser executado após o preenchimento dos números de registro no arquivo "Registros". Ao ser iniciado, o programa realizará a tarefa em primeiro ou segundo plano. Após o tempo necessário, os dados de cada produto estarão disponíveis na planilha Excel "Dados" (que não deve estar aberta durante a execução do programa).

## Quem mantém e contribui com o projeto?

O projeto é mantido e desenvolvido por Matheus Canel e Vinicius Rocha, estagiários de STI no Real Hospital Português. Utilizamos a linguagem de programação Python, e as principais tecnologias empregadas incluem o framework de automação web Selenium e o chromedriver para integração com o navegador Google Chrome.
