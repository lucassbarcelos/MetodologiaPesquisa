# Metodologia - 4º BD

 

Professor da Disciplina: Giuliano Bertoti 

 

Aluno: Lucas Barcelos - 1460281923024

 

# 1ª Quinzena de maio

 - 1: Problema
 
    A falta de ajuste na bicicleta por parte ciclistas iniciantes que acarreta lombalgia.
    
 - 2: Motivação
 
O ciclismo está entre os esportes e atividades mais praticadas no mundo (SALA et al., 1999) no entanto, a prática do ciclismo, ou mesmo o uso de bicicleta como meio de transporte, muitas vezes é prejudicada por lesões, por esforço repetitivo e levando à diminuição da frequência de uso da bicicleta (CLARSEN; KROSS HAUG; BAHR, 2010). 
    
Dentre estas disfunções, a dor lombar (lombalgia) é uma das mais frequentes, podendo perdurar após o término da prática ciclística.
Se atribui a lombalgia em ciclistas a flexão de tronco prolongada por longos períodos (SANNER; O’HALLORAN, 2000) principalmente quando o ciclista porta-se visando a otimização de aspectos aerodinâmicos.

Uma postura adequada é essencial para o bom desempenho ou diminuir o risco de lesão (DE VEY MESTDAGH, 1998; SALAI et al., 1999; SANNER; O’HALLORAN, 2000).De acordo com Kronisch (1998b) e Trombley (2005), ter uma bicicleta com dimensões bem ajustadas é importante tanto para conforto quando para prevenir lesões musculotendíneas (Subtipo de músculo estriado fixado por TENDÕES ao ESQUELETO.). 

O desajuste dos componentes aumentam a chance de acarretar lesões por esforço repetitivo (KRONISCH, 1998b).Para manter uma postura adequada é de fundamental importância que as três áreas de contato do ciclista com a bicicleta estejam alinhadas entre si, são elas: pelve no selim, mãos no guidão e a sapatilha no pedal formando assim um triângulo (COHEN, 1993).
A falta de informação a respeito destes ajustes necessários pelos iniciantes na modalidade acarretam na aquisição por meio dos próprios de lesões como a citada lombalgia.

 
 
 - 3: Proposta de Solução
 
Para uma solução dinâmica que ofereça autonomia ao ciclista para obter os dados e identificar os ajuste e regulagens necessárias em seus equipamentos, precisa-se de uma ferramenta que obtenha as medidas das distâncias entre os pontos de contato do usuário com sua bicicleta. Feliciano, Souza e Leta (2005) As técnicas de Processamento Digital de Imagens, ou seja, sistema de Visão Computacional extrai características dos elementos na imagem para distingui-los, utilizando a inteligência computacional. Após a obtenção dos dados aproximados, outra etapa se inicia para refinar as amostras, realizando a medição/inspeção através de algoritmos computacionais sem contato com a superfície que define o conceito de Metrologia.
A solução consiste na obtenção da imagem através de uma câmera por qualquer dispositivo. Em posse da imagem o processamento será iniciado, utilizando mais especificamente o TensorFlow.js que é uma biblioteca para machine learning escrita em JavaScript que possui o modelo para estimação da pose de uma pessoa, chamado Posenet, em uma imagem ou vídeo podendo estimar as principais articulações do corpo, Feliciano, Souza e Leta (2005) realiza a obtenção através de uma matriz de pixel de tamanho NxM de inteiros positivos, cada pixel possui um valor numérico que representa a intensidade de iluminação na determinada área da imagem.
Objetivo é estimar a angulação obtida da medida dos pontos relativos ao joelho, quadril e ombro, o calculo será feito a partir da aresta resultante dos mesmos. Pode-se verificar o nível de flexão na lombar evidenciando para o ciclista a angulação da posição atual e sugestionando ajustes no equipamento, como a distancia em milimetragem da mesa de fixação do guidão no movimento central, altura e tamanho do canote de fixação do selim ao quadro, e a regulagem da distancia entre a ponta do selim e o movimento central.

    
 
 - 4: Referências
 
    CLARSEN, B.; KROSSHAUG, T.; BAHR, R. Overuse injuries in professional road cyclists. The American Journal of Sports Medicine, v. 38, n. 12, p. 2494-2501, 2010.
    
    SALAI, M. et al. Effect of changing the saddle angle on the incidence of low back pain in recreational bicyclists. British Journal of Sports Medicine, v. 33, n. 1, p. 398-400, 1999.

    KRONISCH, R. L. Mountain biking injuries: fitting treatment to the causes. The Physician Sportsmed, v. 26, n. 3, p. 64-70, 1998a.
    
    

