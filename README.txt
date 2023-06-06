Hortinha Amiga - Sistema de Arduino

//************************************************************************
// Hortinha amiga (descritivo)
//************************************************************************

Este é o projeto da Horta Amiga, que visa fornecer informações sobre produtos cultivados em diferentes escolas e parques comunitários. 
Através dessa plataforma, os usuários podem verificar a disponibilidade de produtos, aprender sobre os vegetais e legumes cultivados e obter detalhes técnicos sobre cada uma das hortas das escolas. 

//************************************************************************
// Objetivo
//************************************************************************

O objetivo deste sistema é automatizar a irrigação das hortas das escolas, tornando o processo mais eficiente e reduzindo a necessidade de atenção constante dos responsáveis pela horta.

//************************************************************************
// Componentes hardware
//************************************************************************

Para montar o sistema de irrigação automatizada, serão utilizados os seguintes componentes:
1 Arduino Uno R3 + Cabo USB
1 Sensor de Umidade de Solo para Arduino
1 Mini Bomba de Água (d'água) para Arduino RS-385
1 Módulo Relé 5V 10A 1 Canal com Optoacoplador
1 Fonte de Alimentação Chaveada 12VDC 1A
1 Adaptador Fêmea com Bornes para plug P4 (2,1x5,5mm)
30 cm de Mangueira para Aquário
Protoboard
Case de proteção para o Arduino
Cano de PVC para montagem da horta

//************************************************************************
// Componentes software
//************************************************************************
Para montar o sistema de irrigação automatizada, será utilizado:
Arduino IDE
Codigo providenciado no repositorio

//************************************************************************
// Montagem
//************************************************************************

O sistema de irrigação automatizada será montado da seguinte forma:
Crie uma caixa d'água para manter a água do sistema
Acima da caixa d'água, coloque a mini bomba de água e conecte a mangueira de aquário a ela e à caixa d'água.
conecte a bomba de água em alguma fonte de alimentação elétrica próxima utilizando a fonte de alimentação
Monte o Arduino na parte superior da caixa. Utilize o case de proteção para garantir a segurança do Arduino.
Conecte o sensor de umidade de solo ao Arduino. Posicione o sensor na terra da horta, permitindo que ele monitore a umidade do solo.
Utilize a protoboard para realizar as conexões elétricas necessárias entre o Arduino, o módulo relé, a fonte de alimentação e a bomba d'água.
Conecte a outra ponta da mangueira de aquário a um cano de PVC. Este cano terá cerca de 1 metro de comprimento devido à potência da bomba de água.
Faça diversos pequenos furos ao longo do cano de PVC. Esses furos permitirão que a água escape, irrigando o solo da horta de maneira uniforme.
Após a montagem completa do sistema, teremos uma irrigação automatizada do solo, que exigirá mínima atenção após a sua configuração.


//************************************************************************
// Funcionamento do sistema
//************************************************************************

O sensor de umidade de solo irá monitorar constantemente o nível de umidade no solo da horta. Quando o solo atingir uma porcentagem de umidade abaixo do recomendado para as plantas, o sensor enviará um sinal ao Arduino.
O Arduino, por sua vez, acionará o módulo relé, que fornecerá energia à mini bomba de água. A bomba de água será ativada, bombeando água da caixa d'água através da mangueira de aquário e do cano de PVC perfurado.
A água liberada pelos pequenos furos no cano de PVC irá irrigar o solo, fornecendo a quantidade necessária de água para as plantas crescerem saudáveis.
Com esse sistema automatizado de irrigação, espera-se que as hortas comunitárias do projeto "Hortinha Amiga" sejam mais eficientes, promovendo o crescimento saudável dos vegetais e legumes cultivados



Integrantes do grupo:
Enricco Rossi de Souza Carvalho Miranda rm551717
Gabriel Marquez Trevisan rm99227
Silvia Kavabata rm97650


