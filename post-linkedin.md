Quem cuida do equipamento que ninguém lembra que está na internet?

Na noite de domingo, 11 de outubro, alguém de fora assumiu o controle dos sistemas que comandam geladeiras e freezers de supermercados na França. O comando foi simples: acionar o ciclo de degelo e deixá-lo rodando. A temperatura subiu até 50 °C. Em cerca de 150 lojas do grupo Les Mousquetaires (Intermarché e Netto), o calor durou seis horas, segundo a Reuters, e os produtos foram descartados.

O ponto de virada veio da própria fabricante. A Danfoss, dona dos controladores atacados, disse que a maioria dos aparelhos era antiga e já sem atualizações: um modelo sem suporte desde 2021 e outro descontinuado em 2016. Eles eram administrados à distância, pela internet, por empresas de manutenção. E o problema não era segredo: em agosto, pesquisadores da Claroty já tinham publicado um estudo sobre falhas nesse tipo de equipamento. Como os invasores entraram? Nenhuma fonte oficial confirmou até agora.

Estudo gestão de TI, e este caso é um exemplo de manual de uma pergunta antiga: de quem é este ativo?

Pelo que se sabe até aqui, o que falhou não foi a geladeira. Foi a gestão, em três pontos:

1. O ativo sem plano de saída. O aviso de que os produtos antigos seriam encerrados existia. Faltou alguém do lado do cliente transformá-lo em decisão.
2. A exposição direta. O órgão francês de resposta a incidentes orientou desconectar os controladores ou liberar o acesso remoto só por VPN, uma conexão protegida.
3. O terceiro sem dono claro. Na hora da crise, descobre-se que desligar o acesso do prestador também tem contrato, custo e consequência.

Isso conversa com o que estudei: na ISO 27001, os controles 5.9 (inventário de ativos), 5.19 e 5.22 (fornecedores), 8.8 (vulnerabilidades) e 8.20 (redes); no ITIL 4, as dimensões "informação e tecnologia" e "parceiros e fornecedores"; no COBIT 2019, BAI09 e APO10.

Três ações para esta semana:
1. Monte o inventário invisível: liste o que não é computador, mas tem acesso remoto (refrigeração, ar-condicionado, nobreaks, câmeras, controle de acesso). Anote modelo, versão, se está fora de suporte, o dono interno e quem acessa de fora.
2. Procure o que está exposto: peça para verificar o que responde a partir da internet. Feche o acesso direto e exija VPN, com segundo fator e registro de acesso.
3. Decida antes da crise: para cada equipamento fora de suporte, defina destino, responsável e data (trocar, isolar ou aceitar o risco formalmente).

Se alguém perguntasse hoje qual equipamento fora de suporte tem acesso remoto na sua empresa, a resposta estaria num inventário, ou só na cabeça de um prestador?

#GovernançaDeTI #SegurançaDaInformação #ISO27001
