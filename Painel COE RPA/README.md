# Painel COE RPA

Esse relatório foi desenvolvido para fazer a gestão da operação do COE RPA de uma empresa, dando maior visibilidade para que clientes e time interno sobre o trabalho executado.

São 3 visões:
1. Gerencial - informações de tempos de execução, status, tipos de falhas e programação, conversão das horas em FTE, KPI de execuções com sucesso.
2. Geral - quantidade de robôs por área cliente, complexidade de desenvolvimento, ocupação dos solobots, status e KPI de robôs em solobot.
3. Operacional - visão mais interna e detalhada da operação, contendo as volumetrias entregues às áreas, a quantidade de robôs por desenvolvedor, por ciclo de execução, farol de cumprimento de prazo e KPI das entregas dentro do prazo.

As bases de dados estão em excel (.xlsx), hospedadas no Google Drive e também disponíveis nesta pasta.
Em resumo, as etapas para realização da tarefa foram:
1. ETL das planilhas em excel;
2. Criação de uma tabela dcalendário e outras tabelas dimensão, baseadas nas tabelas físicas existentes;
3. Criação do relacionamento entre as tabelas;
4. Construção das medidas e dos visuais;
5. Construção da identidade visual (BG, cores...).


