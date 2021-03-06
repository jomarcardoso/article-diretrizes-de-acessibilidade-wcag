# [Diretrizes de Acessibilidade para Conteúdo Web (WCAG) 2.1](https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/)

Um website é uma página, ou um conjunto delas, escritas em formato HTML, com seu conteúdo organizado em seções. É importante que a sintaxe e as regras de tal sejam seguidas para correta interpretação dos navegadores. Sendo de uma ou mais páginas, para ambos, é útil que tenham um título que descreva claramente a sua finalidade, assim quando isolado serve para identificar o nome do website e para um conjunto de páginas serve também para ajudar na localização. Geralmente o cabeçalho e o rodapé possuem os links para que se possa navegar para as demais páginas do grupo.

Uma página web pode ser apresentada de várias formas, para pessoas com conhecimentos e facilidades diversas. Dentre as telas pode haver várias resoluções, tamanhos, quantidade de cores, contraste, ou então pode não haver uma e o conteúdo ser apenas lido. As formas de navegar são várias, também a de acessar e compreender o conteúdo é diferente de um pessoa para outra, por isso, ao se desenvolver uma página web, é importante estar esperando por toda essa gama de variações e oferecer a todos a possibilidade de leitura e compreensão e a capacidade de navegação pelo conteúdo. Para atender a todos é preciso garantir que a ordem do conteúdo faça sentido para todas as formas de acesso, que todo componente na sua forma visual, tenha o mesmo entendimento em áudio ou braile.

Há várias formas de percorrer uma página, com toques na tela, através do teclado, apenas com o mouse, entre outros, e todas essas formas devem ser possíveis. Os maiores desafios estão no acesso com o teclado, para que toda funcionalidade seja operável através dele, sem que haja bloqueio nas teclas de navegação, e o elemento onde estiver focado deve ser percebido visualmente. Para a navegação com teclado ser mais rápida e confortável, os blocos, principalmente os que se repetem, podem ser pulados, por isso é importante a identificação deles, também seguirem um padrão na organização dos seus elementos.

Pensando em uma web sem barreiras e no grande aumento do uso e dos variados tipos de aparelhos móveis, para garantir que as páginas funcionem adequadamente nessa variedade de tamanhos de telas que surgiram, a W3C recomenda que o conteúdo mostrado não deve apresentar duas rolagens simultâneas, horizontal e vertical, se em resolução de largura mínima de 320px, valor de 1280px com zoom de 400% ou resolução de um Iphone 5, e altura mínima de 256px que é o valor de 1024px, altura de telas mais antigas, também com 400% de zoom. A orientação da tela não deve ser restringida, contando o fato de que o acesso pode ser feito tanto por um celular normalmente usados em retrato ou em um computador com uma tela em paisagem. Para algumas pessoas com deficiências motoras e outras com dificuldades de visão, os alvos a serem pressionados, seja por clique ou toque, pode oferecer dificuldades, então, por recomendação, o tamanho mínimo de largura e altura deve ser de 44px.

Os deficientes visuais têm grandes dificuldades para compreender os conteúdos na internet, visto que a maioria das pessoas que usam e as que desenvolvem não compreendem as necessidades desse público. As alternativas textuais são as formas mais comuns de descrever as informações visuais para serem convertidos em outros formatos, assim conteúdos como vídeo, imagens, gráficos, animações e outros podem ser transformados em outras mídias, tais como impressão, braile, fala, símbolos ou uma linguagem mais simples, porém mantendo um significado equivalente e ser corretamente compreendido por deficientes visuais. Os vídeos, para os deficientes visuais, precisam ter seu conteúdo descrevendo o que está sendo exibido, seguindo corretamente as sequências reproduzidas, para este a W3C exige apenas para vídeos pré-gravados.

Os deficientes auditivos encontram menores dificuldades, em relação aos cegos, quanto a navegação e velocidade no acesso às informações, visto que os áudios são geralmente usados apenas para reprodução de mídias. Para que uma mídia, seja áudio ou vídeo, seja compreendida por grande parte dos deficientes auditivos é preciso que estes sejam legendados e para ambos pode ser útil também a descrição do sequencial do conteúdo.

No geral qualquer componente não deve depender apenas de suas características sensoriais para transmitir sua informação. A web possui vários elementos, técnicas e boas práticas, desenvolvidas pela W3C, que foram pensadas para atender a todas ou a maioria das necessidades de quem a acessa. É importante o entendimento do desenvolvedor quanto as recomendações dos criadores e mantenedores da web, para que não cometam erros como criar componentes substituindo os que já existem, por exemplo uma caixa de seleção personalizada, porém não mantendo todas as suas características, como seu nome, seu valor e a função, que neste caso é marcar e desmarcar, apesar do resultado ser visualmente entendido, não seria o mesmo para um deficiente visual. Características de um componente como forma, cor, tamanho, localização visual, orientação ou som, podem não ser percebidos por todos os usuários, por isso deve sempre ser fornecido em paralelo a informação seguindo o que a W3C recomenda. Alguns exemplos:
-	Uma barra visual de progressão, como as carregamento, ter uma descrição para dizer o seu valor;
-	A importância de um título não ser definida apenas no seu estilo, mas também no seu elemento semântico.
-	Não apenas a cor de uma mensagem representar o seu tipo, por exemplo vermelho para erro, mas também sua descrição textual, por exemplo “campo inválido”.

Com a grande variedade de idiomas no mundo, fazer uma página escrita para cada um destes, torna-se um desafio alcançado por poucas grandes empresas. As diretrizes da W3C, então, não exigem que sejam feitas várias traduções do conteúdo, mas apenas identificar em que o idioma a página, ou alguma parte dela, foi feita, para que os navegadores possam renderizar corretamente os caracteres e os leitores de tela pronunciarem corretamente as palavras. Além do idioma, como um empecilho para a compreensão de uma leitura, as palavras incomuns ou termos científicos, principalmente se usados em demasia, também tem o mesmo efeito, por isso, termos pouco conhecidos, que sejam específicos ou então abreviaturas, precisam ser explicados. Caso o texto inteiro tenha uma leitura avançada, de nível técnico ou superior ao ensino fundamental, uma alternativa textual suplementar mais simples pode ser a forma mais fácil de se fazer entender por todos.

A relação de contraste determina o quanto uma cor se diferencia de outra em sua luminescência, a taxa é descrita da cor mais clara comparada a outra mais escura (clara:escura), esse número varia de 1:1, que são cores iguais, e vai até 21:1, no caso do branco ao preto. Para uma melhor visualização dos textos ampliados, com, pelo menos, 18 pontos ou 14 pontos negrito, podem ter um contraste mínimo de 4,5:1, para os demais textos, o contraste mínimo é de 7 para 1. Para elementos da interface, entre os seus adjacentes, a relação é de no mínimo 3 para 1. Na figura 1 foram seguidos os limites permitidos de contraste[1] mencionados, usando escalas de cinza.

**Figura 1: demonstração de limites de contraste**

 ![image](https://user-images.githubusercontent.com/27368585/80716249-cd914580-8acd-11ea-956e-d447ff24bdbc.png)

**Autor: próprio**

Quanto a entrada de dados, são feitas através de campos bem identificados, que são preenchidos ou marcados pelo usuário. A finalidade destes é variada, seja para preenchimento de algum e-mail ou telefone, ou para marcar uma das opções de estado civil. Para melhor funcionamento, a finalidade, que é definida pelo tipo e pelo nome do campo, deve ser corretamente informada, assim o navegador pode sugerir o autopreenchimento ou também mostrar o teclado adaptado para o respectivo conteúdo do campo. Se algum dos campos não estiver correto, o envio do formulário deve ser evitado. Antes, todo campo que estiver inválido deve ser informado ao usuário da forma mais específica possível, para assim ele saber como consertar, e se for necessário, para o correto entendimento, são fornecidas dicas e instruções para preenchimento do campo. 

Alguns deficientes visuais, não cegos, usam ampliadores de tela ou aproximam o conteúdo para conseguir ser visualizado, por isso todo texto deve poder ser redimensionado em até 200 por cento sem gerar uma rolagem horizontal. Para pessoas com algumas dificuldades cognitivas, a leitura de um texto tem o desafio de não haver confusão entre as palavras, então é importante o texto não ter linhas muito extensas. A W3C recomenda até 80 caracteres em alinhamento não justificado e, quando selecionado, para ficar mais claro, é preciso tanto o texto como o fundo trocarem de cor, por isso deve ser evitado usar imagens de texto, que quando selecionadas ou ampliadas não terão o mesmo resultado do texto. Um texto com boa leitura deve ter os seguintes espaçamentos:
-	Altura da linha de pelo menos 1,5 vezes o tamanho da fonte;
-	Espaçamento dos parágrafos seguintes de pelo menos 2 vezes o tamanho da fonte;
-	Espaçamento de letras (rastreamento) de pelo menos 0,12 vezes o tamanho da fonte;
-	Espaçamento de palavras de pelo menos 0,16 vezes o tamanho da fonte.

Dentre os problemas mais comuns dos deficientes intelectuais, está o de manter a atenção para compreender o conteúdo. Para não haver distrações, qualquer animação ou alteração de contexto deve ser iniciada apenas a pedido do usuário, isso não inclui acionamento automático através do foco do mouse ou do teclado. Quando uma mensagem tiver de ser apresentada ao usuário, ele deve ficar sabendo sem que o foco de onde ele está seja movido. Áudios também podem ser causadores de distrações, por isso, por recomendação, quando um som for tocado por mais de 3 segundos, o usuário dever ter o controle deste, seja de aumentar ou diminuir o volume ou então parar a reprodução. Caso o áudio seja a informação principal a ser passada, como uma audiodescrição, um tutorial, parte de um vídeo, entre outros, se houver um som de fundo tocando, este deve ter no mínimo 4 vezes menos volume, assim evitaria comprometer o entendimento e diminuiria a distração.

Muito já foi mencionado nesse trabalho da web sendo uma quebradora de barreiras, que democratiza a informação, porém, há também a possibilidade de pessoas mal-intencionadas usarem essa tecnologia para seu bem a demérito de outros, seja roubando dados do usuário, passando informações falsas ou qualquer outra prática que fira os direitos do cidadão. Em poucos casos ela pode ser algo diretamente nociva a saúde física do indivíduo que a acessa, o único caso assistido pela W3C são para pessoas com epilepsia por fotossensibilidade, problema que ficou popularmente conhecido, quando na reprodução de filme “Pokemon”, onde pelo 618 crianças japoneses tiveram convulsões, vômitos e outros sintomas (CNN, 1997). Um conteúdo na internet não deve piscar mais de três vezes no período de um segundo. Os usuários devem poder desabilitar qualquer animação causada por suas interações, como quando colocam o mouse sobre algum elemento e ele se transforma. Para as demais animações, as que durarem mais de 5 segundos, elas poderão ser paradas ou se possível ocultadas da tela.

Para as empresas que têm seus negócios na internet, um termo que teve grande foco nos últimos anos é a Experiência do Usuário. É de grande valia para um ecommerce que seu cliente visite seu site com prazer e conclua a compra sem obstáculos e novamente é perceptível a importância das diretrizes da W3C para um maior alcance destes usuários. Para um maior conforto de quem acessa, após autenticação, este pode continuar as atividades sem perder os dados e caso haja a inatividade deste usuário por mais de 20 minutos, ele deve ficar sabendo se haverá perda de dados após isso. Quanto as temporizações, dar um tempo limite para a leitura ou a resposta, pode não compreender as necessidades de cada indivíduo, seja suas capacidades ou sua disponibilidade de atenção, então, também para maior conforto e entendimento, é melhor ser evitado.

Para uma experiência aprimorada, podem ser criados atalhos que se bem aplicados irão facilitar o acesso e a navegação. Conforme o usuário vai usando a página ele vai se acostumando com esses mecanismos e suas interações tornam-se mais práticas. Quando um atalho for criado e ele precisar usar teclas de caracteres, deve ter disponível alguma forma de desliga-lo ou então esse mecanismo funcionar apenas sob foco de um componente da interface. Se for querido uma funcionalidade que atue sob movimentação do aparelho, deve ser oferecido também um elemento na interface com a mesma função e assim garantir que em aparelhos que não possuam sensores de movimento e posição também sejam usados. Outro tipo de atalho, muito comumente usado em aparelhos móveis, é o de gestos, geralmente utilizado na navegação entre telas, mas assim como os de movimentação do aparelho. É recomendado deixar um elemento na tela fazendo o mesmo, para no caso de usuários com alguma deficiência motora não encontrem dificuldades para utilizar. Para qualquer acionamento, seja dos atalhos de teclas, gestos e movimentos ou então os de interface, a W3C recomenda que o disparo da função seja feito apenas no final, quando despressionar ou acabar o gesto ou movimento, para que antes disso o usuário possa ter a possiblidade de cancelar. 

----

[1] Para calcular foi usado o site https://contrast-ratio.com/

----

## Índice das diretrizes

| ÍNDICE | NOME | NÍVEL DE CONFORMIDADE |
|---|---|---|
| 1 | Perceptível |
| 1.1 | Alternativas em Texto |
| 1.1.1 | Conteúdo Não Textual | A |
| 1.2 | Mídias com base em tempo |  |
| 1.2.1 | Apenas Áudio e Apenas Vídeo (Pré-gravado) |  |
| 1.2.2 | Legendas (Pré-gravadas) |  |
| 1.2.3 | Audiodescrição ou Mídia Alternativa (Pré-gravada) |  |
| 1.2.4 | Legendas (Ao Vivo) |  |
| 1.2.5 | Audiodescrição (Pré-gravada) |  |
| 1.2.6 | Língua de sinais (Pré-gravada) |  |
| 1.2.7 | Audiodescrição Estendida (Pré-gravada) |  |
| 1.2.8 | Mídia Alternativa (Pré-gravada) |  |
| 1.2.9 | Apenas Áudio (Ao Vivo) | AAA |
| 1.3 | Adaptável |
| 1.3.1 | Informações e Relações  | A |
| 1.3.2 | Sequência com Significado  | A |
| 1.3.3 | Características Sensoriais  | A |
| 1.3.4 | Orientação | AA |
| 1.3.5 | Identificar o Objetivo de Entrada | AA |
| 1.3.6 | Identificar o Objetivo | AAA |
| 1.4 | Discernível |
| 1.4.1 | Utilização de Cores | A |
| 1.42 | Controle de Áudio | A |
| 1.4.3 | Contraste Mínimo | AA |
| 1.4.4 | Redimensionar Texto | AA |
| 1.4.5 | Imagens de Texto | AA |
| 1.4.6 | Contraste (Melhorado) | AAA |
| 1.4.7 | Áudio de fundo baixo ou sem Áudio de fundo | AAA |
| 1.4.8 | Apresentação Visual | AAA |
| 1.4.9 | Imagens de Texto sem exceção | AAA |
| 1.4.10 | Realinhar | AA |
| 1.4.11 | Contraste Não textual | AA |
| 1.4.12 | Espaçamento de Texto | AA |
| 1.4.13 | Conteúdo em foco por mouse ou teclado | AA |
| 2 | Operável |
| 2.1 | Acessível por Teclado |
| 2.1.1 | Teclado | A |
| 2.1.2 | Sem Bloqueio do Teclado | A |
| 2.1.3 | Teclado Sem Exceção | AAA |
| 2.1.4 | Atalhos de teclado por caractere | A |
| 2.2 | Tempo Suficiente |
| 2.2.1 | Ajustável por Temporização | A |
| 2.2.2 | Colocar em Pausa, Parar, Ocultar | A |
| 2.2.3 | Sem Temporização | AAA |
| 2.2.4 | Interrupções | AAA |
| 2.2.5 | Nova Autenticação | AAA |
| 2.2.6 | Limites de Tempo | AAA |
| 2.3 | Convulsões e Reações Fisicas |
| 2.3.1 | Três Flashes ou Abaixo do Limite | A |
| 2.3.2 | Três Flashes | AAA |
| 2.3.3 | Animação de Interações | AAA |
| 2.4 | Navegável |
| 53 | 2.4.1 Ignorar Blocos | A |
| 54 | 2.4.2 Página com Título | A |
| 55 | 2.4.3 Ordem de Foco | A |
| 56 | 2.4.4 Finalidade do Link Em contexto | A |
| 57 | 2.4.5 Várias Formas | AA |
| 58 | 2.4.6 Cabeçalhos e Rótulos | AA |
| 59 | 2.4.7 Foco Visível | AA |
| 60 | 2.4.8 Localização | AAA |
| 61 | 2.4.9 Finalidade do Link (Apenas o Link) | AAA |
| 62 | 2.4.10 Cabeçalhos da Sessão | AAA |
| 63 | 2.5 Modalidades de Entrada |
| 64 | 2.5.1 Gestos de Acionamento | A |
| 65 | 2.5.2 Cancelamento de Acionamento | A |
| 66 | 2.5.3 Rótulo em Nome Acessível | A |
| 67 | 2.5.4 Atuação em Movimento | A |
| 68 | 2.5.5 Tamanho da Área Clicável | AAA |
| 69 | 2.5.6 Mecanismos de Entrada Simultâneos | AAA |
| 70 | 3. Compreensível |
| 71 | 3.1 Legível |
| 72 | 3.1.1 Idioma da Página | A |
| 73 | 3.1.2 Idioma das Partes | AA |
| 74 | 3.1.3 Palavras Incomuns | AAA |
| 75 | 3.1.4 Abreviaturas | AAA |
| 76 | 3.1.5 Nível de Leitura | AAA |
| 77 | 3.1.6 Pronúncia | AAA |
| 78 | 3.2 Previsível |  |
| 79 | 3.2.1 Em Foco | A |
| 80 | 3.2.2 Em Entrada | A |
| 81 | 3.2.3 Navegação Consistente | AA |
| 82 | 3.2.4 Identificação Consistente | AA |
| 83 | 3.2.5 Alteração Mediante Solicitação | AAA |
| 84 | 3.3 Assistência de Entrada |  |
| 85 | 3.3.1 Identificação do Erro | A |
| 86 | 3.3.2 Rótulos ou Instruções | A |
| 87 | 3.3.3 Sugestão de Erro | AA |
| 88 | 3.3.4 Prevenção de Erros (Legal, Financeiro, Dados) | AA |
| 89 | 3.3.5 Ajuda | AAA |
| 90 | 3.3.6 Prevenção de Erros (Todos) | AAA |
| 91 | 4. Robusto |  |
| 92 | 4.1 Compatível |  |
| 93 | 4.1.1 Análise | A |
| 94 | 4.1.2 Nome, Função, Valor | A |
| 95 | 4.1.3 Mensagens de Status | AA |

