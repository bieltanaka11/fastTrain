### fastTrain




*Área de domínio do projeto:* Transporte
 
*Justificativa*: Acreditamos que é uma demanda que afeta milhões de pessoas diariamente e que seria uma solução muito útil.
Algumas referências que comprovam os problemas relatados nas linhas do transporte metropolitano:
https://www.reclameaqui.com.br/viamobilidade/trem-lento-e-demorando-nas-estacoes_W2Pq0fz7ThFkM1bF/
https://www.mobilize.org.br/noticias/11658/google-mostra-linhas-de-tremmetro-mais-cheias-do-mundo-sp-na-lista.html
https://g1.globo.com/sp/mogi-das-cruzes-suzano/noticia/2023/09/25/trens-lotados-e-estrutura-precaria-entenda-principais-reclamacoes-de-passageiros-que-usam-a-linha-11-coral-da-cptm.ghtml

*Pesquisa de reuso*: Outros sistemas de software utilizados pela prefeitura, que utilizam os mesmos conceitos que abordaremos neste projeto.

O sistema de sinalização ferroviária engloba o gerenciamento de trens, controle de velocidade e garantia da segurança contra colisões. Pode-se compará-lo ao tráfego de veículos e semáforos, onde a velocidade é influenciada pelo sinal, posição e velocidade dos veículos próximos. Esse sistema opera com base no controle clássico, caracterizado por baixa flexibilidade, mas alta segurança. Sua principal premissa é evitar que trens entrem em seções de via já ocupadas por outros trens.

A introdução do sistema de posicionamento global (GPS) eliminou a necessidade de circuitos de via, reduzindo custos de manutenção e tempo de parada, apesar de gerar um alto custo operacional. Esse sistema permite a comunicação entre os trens e um servidor no Centro de Controle Operacional (CCO). Os dados de posição do trem são transmitidos via satélite para esse servidor, que armazena informações sobre trechos e a localização de outros trens. Por meio de um software de gerenciamento, os trens recebem dados sobre as condições da via, limites de velocidade e outros parâmetros relevantes.

Assim sendo, a base do sistema seria praticamente a mesma e apenas fariamos melhorias nesse sistema. Por isso utilizaremos o reuso no nível de componentes, usando como técnica o desenvolvimento baseado em componentes.
