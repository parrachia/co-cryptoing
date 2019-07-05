# Como Fazer Perguntas Inteligentes

{% embed url="http://clipart-library.com/perguntas.html" %}

### Sobre direitos autorais e cópias deste guia

Todos os direitos deste guia pertencem a [Eric Steven Raymond](mailto:esr@thyrsus.com). De uma forma geral, seu desejo é que o maior número de pessoas o leiam, portanto você é livre para linkar e copiar este conteúdo. Entretanto, cópias estáticas não podem ser produzidas sem sua autorização. Se algum leitor vir seu nome em um documento, ele precisa ver todas as atualizações que este documento sofreu. Nada de cópias abandonadas e desatualizadas espalhadas pela Internet.

A versão em português deste guia foi produzida por Marcos Machado. Da mesma forma, você é livre para copiar ou linkar este documento. Da mesma forma, mantenha sua versão atualizada \(traduções também sofrem revisões!\). O modo mais fácil de fazer isso é apenas linkar este documento, mas se preferir copiá-lo, visite regularmente esta página para se certificar de que possui a última versão.

Jamais remova estes avisos de direitos autorais e os links para o documento original.

### Introdução

No mundo dos [hackers](http://www.catb.org/~esr/faqs/hacker-howto.html), o tipo de resposta que você obtém as suas perguntas técnicas depende muito mais de como você faz a pergunta do que da dificuldade em preparar a resposta. Este guia ensinará a você como fazer perguntas do jeito mais indicado para conseguir uma resposta satisfatória.

Agora que o uso do open source está bastante difundido, é mais comum você encontrar respostas de outros usuários, mais experientes, do que dos hackers. Isto é uma Coisa Boa: usuários tendem a ser um pouco mais tolerantes com os tipos de problemas que os novatos enfrentam. E ainda, tratar estes usuários como hackers, da maneira como recomendamos aqui é, geralmente, a maneira mais efetiva de conseguir respostas úteis deles também.

A primeira coisa que você deve saber é que hackers realmente gostam de problemas difíceis e questões boas e intrigantes sobre estes problemas. Senão, nós não estaríamos aqui. Se você nos der uma questão interessante para mastigar nós ficaremos gratos à você; boas perguntas são um estímulo e um presente. Boas perguntas nos ajudam a desenvolver nosso entendimento, e freqüentemente revela problemas que não conhecíamos ou sobre os quais nunca pensamos. Entre hackers, "boa pergunta" é um forte e sincero elogio.

Apesar disso, hackers têm a reputação de encarar perguntas simples com arrogância e hostilidade. De vez em quando aparentamos ser rudes com novatos e ignorantes. Mas isto não é verdade.

Nós somos, sim, hostis com pessoas que não querem pensar nem fazer seu dever de casa antes de fazer perguntas. Pessoas assim são dissipadoras de tempo - elas pegam e não devolvem, elas desperdiçam tempo que pode ser usado em questões de gente que que merece uma resposta. Nós chamamos pessoas assim de "losers" \(e por uma razão histórica, algumas vezes grafamos como "lusers"\). N.T.: "Luser" é um trocadilho com as palavras "user" \(usuário\) e "loser" \(perdedor, otário\).

Nós percebemos que existem muitas pessoas que querem apenas usar os softwares que escrevemos e não têm nenhum interesse em aprender detalhes técnicos. Para muitas pessoas, um computador é apenas uma ferramenta, um meio para um fim; eles têm coisas mais importantes para fazer nas suas vidas. Nós reconhecemos isso e não esperamos que todos tenham interesse nas questões técnicas que nos fascinam. Entretanto, nosso estilo de resposta é ajustado para aqueles que possuem este tipo de interesse e que desejam participar da solução de problemas. Isto não vai mudar. Nem deveria; se isso acontecesse, nós nos tornaríamos menos eficazes naquilo que sabemos fazer de melhor.

Nós somos \(na maioria dos casos\) voluntários. Nós reservamos um tempo nas nossas ocupadas vidas para responder perguntas e, às vezes, ficamos sobrecarregados delas. Então nós as filtramos sem dó nem piedade. Em particular, nós jogamos fora questões de pessoas que aparentam ser "losers", para que possamos gastar nosso tempo de forma mais eficiente, em questões de "winners". \(N.T.: vencedores\)

Se você acha essa atitude condenável ou arrogante, reveja seus conceitos. Nós não estamos pedindo que se curve diante de nós - na verdade, o que muitos de nós mais queremos é tratá-lo como igual e recebê-lo em nossa cultura, se você fizer o esforço necessário para que isso seja possível. Mas é simplesmente inútil para nós tentar ajudar pessoas que não estão dispostas a ajudar a si mesmas. Tudo bem ser ignorante; mas não é legal bancar o estúpido.

Portanto, mesmo que não seja necessário ser tecnicamente competente para receber nossa atenção, você precisa apresentar atitudes que te levem a esta competência - mostrar-se preparado, atencioso, observador e disposto a ser um participante ativo no desenvolvimento de soluções. Se você não suporta este tipo de discriminação, sugerimos que você pague a alguém por um suporte comercial ao invés de pedir ajuda através de doações de hackers.

Se você decidir vir até nós para pedir ajuda, você não quer ser um perdedor. Você não quer nem se parecer com um perdedor. A melhor maneira de conseguir uma resposta rápida e precisa é perguntar como uma pessoa que possui confiança, inteligência e dicas, e que precisa de ajuda em um problema bem específico.

\(Melhorias neste guia são bem-vindas. Você pode enviar suas sugestões - em inglês - para [esr@thyrsus.com](mailto:esr@thyrsus.com) ou [respond-auto@linuxmafia.com](mailto:respond-auto@linuxmafia.com). Note, entretanto, que o objetivo deste documento não é ser um guia de [netiqueta](http://www.catb.org/~esr/faqs/hacker-howto.html), e eu geralmente descarto sugestões que não estejam especificamente relacionadas a produzir respostas úteis em um fórum técnico\)

### Antes de perguntar

Antes de fazer uma pergunta por email, em um newsgroup ou em um fórum na web, faça o seguinte:

1. Tente achar uma resposta pesquisando na Web.
2. Tente achar uma resposta lendo o manual.
3. Tente achar uma resposta lendo o FAQ.
4. Tente achar uma resposta por tentativa e erro.
5. Tente achar uma resposta perguntando a um amigo experiente.
6. Se você é programador, tente achar uma resposta lendo o código-fonte.

Quando você faz uma pergunta, demonstre que você fez todas estas coisas antes; isto irá ajudar a estabelecer que você não está sendo uma esponja preguiçosa fazendo as outras pessoas perderem tempo. Melhor ainda, mostre o que você aprendeu fazendo todas estas coisas. Nós gostamos de responder questões de pessoas que demonstram que podem aprender com as respostas.

Use táticas como pesquisar no Google com o texto de qualquer mensagem de erro que você receba \(e pesquise no Google Groups assim como na web\). Isto pode levá-lo diretamente ao documento ou à thread da lista que irá responder à sua pergunta. Mesmo que isto não aconteça, é legal dizer "Eu pesquisei no Google a seguinte frase mas não encontrei nada útil" na sua mensagem quando pedir ajuda.

Prepare sua pergunta. Pense além. Perguntas corridas recebem respostas corridas, ou nenhuma. Quanto mais você demonstrar que investiu tempo e neurônios na solução do seu problema antes de pedir ajuda, mais provável será que você consiga nossa ajuda.

Tome cuidado com perguntas erradas. Se você fizer uma pergunta baseada em pressupostos equivocados, um hacker qualquer vai enviar uma resposta literal inútil enquanto pensa "Que pergunta idiota...", esperando que a resposta ao que você perguntou, mesmo que não seja a resposta que você espera, te ensine alguma coisa sobre como fazer perguntas.

Nunca assuma que você merece uma resposta. Você não merece; você não está, afinal de contas, pagando por este serviço. Você irá ganhar uma resposta, se ganhar, fazendo perguntas substanciais, interessantes e intrigantes - uma que contribua com a experiência da comunidade ao invés de apenas extrair conhecimentos dos outros.

Por outro lado, deixar claro que você pode e quer ajudar no processo de desenvolver uma solução é um ótimo começo. "Alguém pode me indicar uma direção?", "O que está errado no meu exemplo?" e "Qual site eu devia ter verificado?" é mais provável de receber uma resposta do que "Por favor, envie o procedimento exato que eu devo usar", pois assim fica claro que você está disposto a completar o processo se alguém apenas indicar a direção certa.

### Quando você perguntar

#### Escolha cuidadosamente seu fórum

Seja cuidadoso ao escolher onde você vai enviar sua pergunta. Você será ignorado ou tachado de idiota se você:

* enviar sua pergunta em um fórum que não trata do assunto
* enviar uma questão muito básica em um fórum onde são esperadas questões tecnicamente mais avançadas, ou vice-versa.
* enviar a mesma pergunta para diversos fóruns ou newsgroups.
* enviar um email pessoal para alguém que não seja seu conhecido nem responsável direto por resolver seu problema.

Hackers detonam questões que estão inapropriadamente direcionadas para evitarem que seus canais de comunicação de se tornem irrelevantes. Você não quer que isso aconteça contigo.

O primeiro passo é, portanto, escolher o fórum certo. Novamente, Google e outros mecanismos de pesquisa são seus amigos. Use-os para encontrar os sites dos projetos que estejam mais intimamente relacionados aos softwares ou hardwares que estão lhe causando problemas. Normalmente eles possuem links para um FAQ \(Resportas à Perguntas Freqüentes\), para listas de discussão e seus respectivos históricos. Estas listas de discussão são o último lugar onde pedir ajuda se seus esforços anteriores \(incluindo ler o FAQ\) não lhe trouxerem uma solução. A página do projeto também pode descrever como reportar um bug; se for o caso, siga as instruções.

Enviar uma mensagem para uma pessoa ou um fórum com o qual não está familiarizado é o mais arriscado. Por exemplo, não pense que o autor de uma página informativa quer ser seu consultor gratuitamente. Não faça projeções otimistas sobre sua mensagem ser bem aceita - se você não tiver certeza, envie sua mensagem em outro lugar, ou não envie.

Quando escolher um fórum web, um newsgroup ou uma lista de discussão, não leve estes nomes a sério tão rapidamente; dê uma olhada no FAQ ou na descrição da lista para ter certeza de que sua mensagem faz parte do tipo de assunto tratado no local. Ler algumas mensagens antigas antes de enviar a sua pode lhe ajudar a descobrir como as coisas funcionam na comunidade. Na verdade, é uma excelente idéia fazer uma pesquisa sobre as palavras-chaves relacionadas ao seu problema antes de enviar uma mensagem. Se isto não lhe ajudar a encontrar uma resposta, vai lhe ajudar a formular melhor sua pergunta.

Não dê uma rajada de perguntas em todos os canais de comunicação de uma só vez, isto é o mesmo que sair gritando e acaba irritando as pessoas. Vá com calma.

Saiba como classificar sua mensagem! Um dos erros clássicos é enviar perguntas sobre interface de programação Unix ou Windows em um fórum sobre a linguagem de programação, que é portável para ambas as plataformas. Se você não compreende o problema neste exemplo, é melhor não fazer nenhuma pergunta até cair a ficha.

Em geral, questões enviadas para um fórum público bem selecionado conseguem melhores respostas do que as mesmas questões enviadas para um fórum fechado. Existem muitas razões para isto. Uma é a quantidade de pessoas que podem responder. Outra é o tamanho da audiência. Hackers preferem ensinar algo que seja útil para muitas pessoas do que para poucas.

É compreensível que hackers experientes e autores de softwares populares recebem mais do que sua parcela de mensagens mal direcionadas. Ao enviar sua mensagem você pode, em casos extremos, ser a gota d'água - algumas vezes, colaboradores de projetos populares desistiram de dar suporte por causa do efeito colateral que o tráfego de emails inúteis causou nas suas caixas-postais, tornando-as intoleráveis.

#### Fórum web e IRC freqüentemente dão aos novatos as respostas mais rápidas

Seu grupo local de usuários, ou sua distribuição de Linux, deve divulgar um fórum web ou um canal de IRC onde os iniciantes podem conseguir ajuda. Estes são bons lugares para começar, especialmente se você imagina ter topado com um problema relativamente simples e comum. Canais de IRC, quando divulgados, são um convite para entrar, fazer perguntas e receber ajuda em tempo real.

Se você está encontrando problemas em um programa proveniente de uma determinada distribuição de sistema \(muito comum atualmente\), é melhor fazer perguntas no fórum/lista da distribuição antes de tentar ir direto ao grupo do projeto. Os hackers de lá vão dizer "use nossa versão".

Antes de enviar mensagem para um fórum web, verifique se ele não tem um mecanismo de pesquisa. Se tiver, tente encontrar algumas palavras-chaves sobre o seu problema; isto pode ajudar. Se você fez uma pesquisa genérica em uma ferramenta de pesquisa na web, tente a mesma pesquisa no fórum, pois as ferramentas genéricas podem não ter indexado todo o conteúdo do fórum ou já tê-lo feito há muito tempo, não mostrando tópicos recentes.

Existe uma tendência crescente nos projetos em usar fórum web e canais de IRC para suporte, deixando o tráfego de email destinado para o desenvolvimento. Então, procure por estes canais primeiro quando estiver procurando ajuda em um projeto específico.

#### Como segundo passo, use a lista de discussão do projeto

Quando um projeto possuir uma lista de discussão, escreva para a lista, não para um determinado desenvolvedor, mesmo que você acredite saber quem melhor pode responder sua pergunta. Procure na documentação do projeto e visite seu site para descobrir o endereço da lista. Existem várias boas razões para se fazer isso:

* Qualquer questão que seja boa para um determinado desenvolvedor tem muito valor também para o resto do grupo. Por outro lado, se você acha que sua questão é idiota demais para enviar ao grupo, isto não é uma desculpa para atormentar um determinado desenvolvedor.
* Fazer perguntas na lista divide o trabalho entre os desenvolvedores. Um único desenvolvedor \(especialmente se ele for o líder do projeto\) pode estar muito ocupado para responder suas perguntas.
* Muitas listas são arquivadas e indexadas por ferramentas de pesquisa na web. Alguém pode encontrar sua pergunta e a resposta apenas pesquisando ao invés de perguntar a mesma coisa na lista.
* Se algumas perguntas são feitas com muita freqüência, os desenvolvedores podem usá-las para melhorar a documentação ou modificar o próprio sistema para torná-lo menos confuso. Mas se a pergunta for feita individualmente, ninguém poderá ter uma visão geral do problema.

Se um projeto possui um fórum ou lista dividido entre usuários e desenvolvedores \(hackers\), se você não está modificando o código \(hacking\), use o fórum/lista para usuários. Não pense que você será bem-vindo na lista de desenvolvedores, pois eles considerarão sua mensagem como um ruído atrapalhando o tráfego de desenvolvimento.

Entretanto, se você tem certeza de que sua questão não é banal e você não conseguiu ajuda na lista de usuários por vários dias, tente a de desenvolvedores. Uma boa recomendação é dar uma olhada na lista por alguns dias, antes de enviar sua mensagem, para aprender os modos do pessoal que a freqüenta \(esta dica é válida para qualquer lista privada ou semi-privada\).

Se você não encontrar um endereço do fórum/lista de um determinado projeto, mas encontrar o endereço do mantenedor do projeto, vá em frente e faça sua pergunta a ele. Mas, mesmo neste caso, não assuma que a lista não existe. Deixe claro na sua mensagem que você tentou mas não encontrou a lista apropriada. Diga também que você não se importa de ter sua mensagem encaminhada para outras pessoas. \(Muitas pessoas acreditam que emails devem permanecer privados, mesmo que não tenham nenhuma informação secreta neles. Permitindo que sua mensagem seja encaminhada você dá ao destinatário a opção de como tratá-la.\)

#### Use um subject específico e com significado

Em listas de discussão, newsgroups ou fórum web, o título da mensagem é sua chance de ouro para atrair, com 50 caracteres ou menos, a atenção de especialistas qualificados. Não desperdice este oportunidade com "Por favor, me ajudem" \(muito menos "PRECISO DE AJUDA!!!"; mensagens assim são descartadas por reflexo\). Não tente nos impressionar com sua angústia; ao invés, use este espaço para uma descrição super-concisa do seu problema.

Uma boa convenção para títulos/assuntos de mensagens, usada pelo suporte técnico de muitas organizações, é o "objeto - anomalia". A parte "objeto" especifica o que está com problemas e a "anomalia" descreve como o comportamento diverge o esperado.

**Estúpido**:

> AJUDA! Vídeo não funciona direito no meu laptop!

**Inteligente**:

> XFree86 4.1 cursor do mouse distorcido, Fooware MV1005 vid. chipset

**Mais inteligente**:

> XFree86 4.1 cursor do mouse na Fooware MV1005 vid. chipset - distorcido

O processo de organizar o título no modelo "objeto - anomalia" vai ajudar você a organizar seu raciocínio sobre o problema. O que é afetado? Só o mouse ou outros gráficos também? Isto é específico do XFree86? Só da versão 4.1? Será que é específico do chipset Fooware? Só no modelo MV1005? Um hacker que olha esta mensagem pode imediatamente entender, de uma tacada só, o que está lhe causando problema e qual o problema que você está enfrentando.

De uma maneira geral, se imagine olhando para um índice de um arquivo de perguntas, só com o título delas sendo exibido. Faça seu título refletir sua questão de forma que o próximo cara com uma pergunta semelhante a pesquisar o arquivo de perguntas consiga seguir esta thread até a resposta final, ao invés de enviar a mesma pergunta novamente.

Se você faz uma pergunta através de uma resposta, certifique-se de trocar o título \(assunto\) da mensagem para indicar que você está perguntando. Um título que contenha "Re: teste" ou "Re: novo bug" atrairá bem menos atenção. Além disso, cite trechos da mensagem original o mínimo possível para que os novos leitores a entendam.

Não responda uma mensagem em uma lista para começar uma nova thread. Isto irá limitar sua audiência. Alguns programas leitores de email, como o "Mutt", permite ao usuário ordenar a mensagem por thread \(assunto\), encadeando sua mensagem dentro de outras. Pessoas que usam esse tipo de software e não estão interessados no tópico original jamais verão sua mensagem.

Trocar o assunto não é suficiente. O Mutt, e provavelmente outros leitores de email, procuram por outras informações no header, e não o campo de assunto, das mensagens para associá-la a uma determinada thread. Ao invés de responder, se quiser começar um novo assunto, crie uma mensagem completamente nova.

Em fórum web as regras para boa prática são um pouco diferente, pois as mensagens são fortemente ligadas a um determinado assunto e muitas vezes invisíveis fora de suas threads. Trocar o assunto quando perguntar alguma coisa através de uma resposta não é essencial \(nem todos os fóruns permitem fornecer um assunto específico para cada mensagem da thread, e mesmo quando fazem, ninguém dá atenção a eles\). Mas fazer uma pergunta em resposta a outra é uma prática controversa por si só, pois ela só será vista por quem está acompanhando a thread. Então, a não ser que você queira atingir somente os participantes ativos nesta thread, inicie uma nova.

#### Torne a resposta mais fácil

Terminar sua pergunta com "Favor enviar resposta para..." tornará mais difícil conseguir uma resposta. Se você não quer se incomodar em tirar alguns segundos para configurar o "Reply-to" no seu programa de email, nós não vamos nos incomodar em tirar alguns segundos para sequer pensar no seu problema. Se seu programa não permite isso, use um programa melhor. Se seu sistema operacional não lhe permite usar nenhum outro programa, use um sistema operacional melhor.

Em fóruns web, pedir para responder para um endereço de email é extremamente rude, a menos que a resposta contenha dados confidenciais \(e alguém irá, por alguma razão, deixar você - mas não todo o fórum - ler a mensagem\). Se você deseja receber um email quando alguém responder sua mensagem, configure o fórum para fazer isso. Esta função está presente em quase todos os fóruns sob o nome de "Monitorar tópico", "Enviar email de aviso de resposta" etc.

#### Escreva de modo claro, gramatical e sintaticamente correto

Nós descobrimos, por experiência, que pessoas que são preguiçosas e não tomam cuidado com a escrita são, em geral, preguiçosas e sem cuidado com o ato de pensar ou programar \(pode apostar nisso\). Responder perguntas de preguiçosos descuidados não é compensador; preferimos gastar nosso tempo em outro lugar.

Expressar sua dúvida bem e de forma clara é importante. Se você não quer se importar com isso, nós não queremos nos importar com você. Gaste algum tempo aprimorando seu linguajar. Ela não precisa ser dura ou formal - na verdade, a cultura hacker dá valor à linguagem informal, casual e com humor usada com precisão. Mas ela deve ser precisa; ela deve indicar que você está pensando e prestando atenção.

Soletre, pontue e use maiúsculas e minúsculas corretamente. Não DIGITE TUDO EM MAIÚSCULAS, isto é lido como grito e é considerado grosseria. \(Tudo em minúsculas é só um pouco menos chato, pois é difícil de ler\)

De uma forma geral, se você escreve como um semi-analfabeto muito provavelmente será ignorado. Escrever como "l33t script kiddie hax0r" é o absoluto beijo da morte e garante que você não receberá resposta nenhuma \(ou, no máximo, uma pilha de escárnios e sarcasmos\).

Se você está fazendo perguntas em um fórum que não está na sua língua natal, você tem direito de errar um pouco na gramática ou na sintaxe das palavras - mas não nos casos de preguiça \(e sim, nós conseguimos perceber a diferença\). Além disso, a não ser que você saiba que idioma seu correspondente fala, escreva em inglês. Hackers atarefados costumam descartar mensagens em línguas que não entendem, e inglês é a língua padrão da Internet. Escrevendo em inglês você minimiza as chances de ter sua mensagem descartada sem ser lida.

#### Envie perguntas em formatos acessíveis e padronizados

Se você tornar sua mensagem difícil de ser lida, é muito provável que ela seja passada para trás em prol de mensagens mais fáceis de se ler. Então:

* Envie mensagens em plain text, não em HTML. \(não é difícil [desligar o HTML](http://expita.com/nomime.html)\)
* Anexos no formato MIME tudo bem, desde que eles contenham algo realmente útil \(como um código-fonte ou um patch\), não uma bugiganga qualquer gerada pelo seu programa de email \(como uma cópia da sua mensagem em outro formato\).
* Não envie mensagens em que os parágrafos são muito longos e sem quebras de linhas. \(Isto torna difícil responder apenas parte da mensagem\) Considere que seus correspondentes lerão seus emails em telas com no máximo 80 colunas e configure a quebra de linha para este valor ou menos.
* No entanto, não quebre linhas de dados \(como trechos de log ou transcrições de sessões\). Dados devem ser incluídos como eles são, pois seus correspondentes terão certeza de estar vendo o que você viu.
* Não envie mensagens codificadas em MIME Quoted-Printable para uma lista em língua inglesa. Esta codificação é necessária quando você está enviando em uma língua que não pode ser representada pela codificação ASCII, mas muitos programas de email não a suportam. Quando isso acontece, aqueles =20 espalhados pelo texto atrapalham a leitura - ou podem sabotar a semântica.
* Nunca, jamais espere que hackers leiam documentos criados em aplicações proprietárias como o Microsoft Word ou Excel. Muitos hackers reagem a isso da mesma forma que você reagiria se jogassem uma montanha fedorenta de esterco de porco na sua porta. Mesmo que eles possam escalar a montanha, eles não vão querer fazer isso.
* Se você está enviando sua mensagem de uma máquina Windows, desligue os estúpidos "Smart Quotes" da Microsoft. Com isto você vai evitar espalhar lixo pelo seu email.
* Em fóruns web, não abuse dos "smiles" e das formatações HTML \(quando forem permitidas\). Um smile ou dois tudo bem, mas um texto colorido e cheio de carinhas fazem as pessoas pensarem que você é um retardado. Abuse de cores, fontes e smiles e você será tratado como uma adolescente cacarejando, o que não é uma boa idéia a não ser que esteja mais interessado em sexo do que em respostas.

Se você está usando um programa de email com interface gráfica \(como o Netscape Messenger, o MS Outlook ou semelhantes\) saiba que você pode estar violando estas regras com as configurações default. Quase todos estes programas possuem a função de ver os fontes da mensagem. Dê uma olhada na pasta de mensagens enviadas e veja se você está mandando texto puro ou mensagens incrustadas de lixo.

#### Seja claro e preciso sobre seu problema

* Descreva os sintomas do seu problema ou bug cuidadosamente e de forma clara.
* Descreva o ambiente em que isto ocorre \(máquina, OS, aplicação etc.\). Forneça a distribuição usada e o respectivo release \(por exemplo: "Fedora Core 4", "Slackware 9.1" etc.\).
* Descreva a pesquisa que você fez para tentar entender o problema antes de fazer sua pergunta.
* Descreva os passos que você deu para diagnosticar e tentar resolver o problema antes de fazer sua pergunta.
* Descreva qualquer mudança recente no seu sistema possa ser relevante para o problema.

Faça o máximo possível para antecipar as perguntas que um hacker lhe faria, e tente respondê-las antecipadamente no seu pedido de ajuda.

Simon Tatham escreveu um excelente tratado sobre "[Como reportar bug de forma efetiva](http://www.chiark.greenend.org.uk/~sgtatham/bugs.html)" \(em inglês\). Eu recomendo fortemente que você o leia.

#### Quantidade não é precisão

Você deve ser preciso e informativo. Isto não é conseguido apenas despejando uma grande quantidade de código ou dados no seu pedido de ajuda. Se você tem um grande e complicado caso de teste que está causando problemas em um programa, tente podá-lo e torná-lo o menor possível.

Isto é útil por pelo menos três razões. Um: demonstrar ter feito um esforço para tornar a pergunta mais simples aumenta sua chance de conseguir uma resposta, Dois: simplificar a pergunta aumenta sua chance de receber uma resposta realmente útil, Três: durante o processo de simplificação do pedido, você pode encontrar a solução ou desenvolver um remendo por conta própria.

#### Não diga que você encontrou um bug

Quanto você estiver com problemas em um determinado trecho do software, não diga que você encontrou um bug a não ser que esteja completamente certo disso. Dica: a menos que você possa fornecer um patch que resolva o problema, ou um teste de regressão contra uma versão anterior que demonstre o comportamento estranho, você provavelmente não tem certeza o suficiente. Isto se aplica também a páginas web e a documentação; se você encontrou um "bug" na documentação, você deve fornecer um texto para substituição e em quais páginas a correção deve ser feita.

Lembre-se, existem muitos outros usuários que não estão passando pelo mesmo problema que você. Do contrário você teria notado isso lendo a documentação ou pesquisando na Web \(você já fez isso, [não fez](http://clipart-library.com/perguntas.html#before)?\). Isso significa que é muito provável que é você quem está fazendo algo de errado, não o software.

O pessoal que escreveu o software se dedicou muito para fazer o melhor possível. Se você diz que encontrou um bug, isto significa que eles fizeram algo de errado, e você quase sempre irá ofendê-los - mesmo que você esteja certo. Não é nada diplomático gritar "bug" no assunto da mensagem.

Ao escrever sua mensagem, é melhor escrever imaginando que você fez algo de errado, mesmo que intimamente você saiba que encontrou um bug. Se for mesmo um bug, você vai ouvir isso na resposta. Faça dessa maneira e os desenvolvedores irão se desculpar com você no caso de um bug, ao invés de você ter que se desculpar com eles caso você tenha bagunçado as coisas.

#### Curvar-se não é um substituto para fazer o dever de casa

Algumas pessoas, quando percebem que não podem ser rudes ou arrogantes são o extremo oposto, submissos e suplicantes. "Eu sei que sou um patético novato, mas...". Isto não ajuda em nada. Pior ainda quando isto é acompanhado de informações vagas sobre o problema.

Não perca seu tempo, nem o nosso, com comportamento primata. Ao invés, apresente o histórico e os fatos da forma mais clara possível. Isto é bem melhor do que curvar-se.

Algumas vezes os fóruns web possuem áreas específicas para novatos. Se você acha que tem uma pergunta muito elementar, se encaminhe para lá. Mas também não chegue lá se curvando.

#### Descreva os sintomas do seu problema, não o que você "acha"

Não ajuda em nada dizer a hackers o que você acha que está causando problema. \(Se suas teorias sobre o diagnóstico fossem tão boas, você estaria pedindo ajuda?\) Portanto, certifique-se de que está relatando apenas os sintomas como eles se apresentam e não sua interpretação dos fatos ou teorias. Deixe eles interpretarem e darem o diagnóstico. Se você acha que é importante dar sua opinião, deixe isto claro e explique porque esta resposta não serve para você.

**Estúpido**:

> Estou tendo erros aleatórios de SIG11 na compilação do kernel, e suspeito que alguma trilha da minha placa-mãe está quebrada. Como posso verificar isso?

**Inteligente**:

> Meu K6/233 em uma placa-mãe FIC-PA2007 \(chipset VIA Apollo VP2\) com 256MB Corsair PC133 SDRAM está provocando erros de SIG11 aproximadamente 20 minutos depois de ligado durante a compilação do kernel, mas nunca antes de 20 minutos. Um reboot não afeta essa contagem de tempo, mas deixá-la desligada de noite sim. Troquei todos os pentes RAM e não ajudou. Os logs relevantes da sessão de compilação seguem abaixo.

**Falta traduzir:** Since the preceding point seems to be a tough one for many people to grasp, here's a phrase to remind you: "All diagnosticians are from Missouri." That US state's official motto is "Show me" \(earned in 1899, when Congressman Willard D. Vandiver said "I come from a country that raises corn and cotton and cockleburs and Democrats, and frothy eloquence neither convinces nor satisfies me. I'm from Missouri. You've got to show me."\) In diagnosticians' case, it's not a matter of skepticism, but rather a literal, functional need to see whatever is as close as possible to the same raw evidence that you see, rather than your surmises and summaries. Show us.

#### Descreva os sintomas do seu problema em ordem cronológica

As melhores dicas do que está acontecendo quando algo dá errado estão em eventos imediatamente anteriores. Portanto, sua mensagem deve conter o que você fez e o que a máquina fez, do início ao fim. No caso de processos via linha de comando, ter um log da sessão \(ex.: utilitário script\) e citar as 20 principais linhas é muito útil.

Se o programa que está apresentando problemas possui uma opção de diagnóstico \(tipo -v para verbose\), tente selecionar opções que adicionarão informações úteis de debug. Lembre-se de que mais não é necessariamente melhor. Escolha um nível de debug que irá informar ao invés de afogar o leitor em lixo.

Se sua mensagem, com isso, ficar muito grande \(mais do que quatro parágrafos\), pode ser útil criar um resumo bem sucinto no início, seguido do relatório cronológico. Com isso, hackers poderão saber o que procurar quando estiverem lendo sua mensagem.

#### Descreva seu objetivo, não um único passo

Se você está tentando descobrir como fazer alguma coisa \(ao contrário de relatar um bug\), inicie descrevendo o objetivo. Só então descreva os passos executados para alcançá-lo e onde você está empacado.

Geralmente, pessoas que precisam de uma ajuda técnica possuem um objetivo maior e empacam no que elas acham que é um caminho para este objetivo. Elas vêm procurar ajuda sobre este passo que está causando problema sem, muitas vezes, perceber que o caminho inteiro é que está errado.

**Estúpido**:

> Como eu faço para a paleta de cores do programa FooDraw me mostrar o código hexadecimal?

**Inteligente**:

> Estou tentando trocar a tabela de cores em uma imagem com valores que eu escolhi. Só que a única maneira que eu vejo para fazer isso é editar a entrada na tabela, mas eu não consigo fazer com que o FooDraw me mostre o código hexadecimal.

A segunda versão da questão é mais inteligente. Ela permite que seja sugerida uma ferramenta mais útil do que a vem sendo tentada até então.

#### Não peça as pessoas para responderem em seu email particular

Hackers acreditam que a solução de um problema deve ser um processo público e transparente onde desde a primeira tentativa até a resposta final possa ser corrigida caso alguém com mais conhecimento descubra que ela está incompleta ou incorreta. Além disso, eles são recompensados em parte por serem reconhecidos como competentes por seus semelhantes.

Quando você pede para responderem de forma particular, você está quebrando tanto o processo quando a recompensa. Não faça isso. Esta é uma escolha de quem está respondendo - e, se ele assim o fizer, provavelmente é porque considerou a questão muito mal feita ou óbvia demais para ser útil aos demais participantes.

Existe uma única exceção à esta regra. Se você acha que o tipo de pergunta fará com que você receba diversas respostas parecidas, então as palavras mágicas são "mandem para meu email e farei um resumo para o grupo". Isto é bem visto por tentar salvar a lista de uma avalanche de mensagens substancialmente idênticas - mas você precisa cumprir a promessa de mandar o resumo.

#### Seja específico com relação à sua pergunta

Perguntas vagas tendem a ser consideradas perda de tempo. As pessoas que melhor podem te dar uma resposta são, geralmente, as mais ocupadas \(justamente por fazerem todo o trabalho\). Pessoas assim são alérgicas à perda de tempo, e conseqüentemente as perguntas vagas.

É mais provável que você consiga uma resposta sendo específico com relação ao que você espera que seus correspondentes façam \(dar dicas, enviar um código, verificar seu patch etc.\). Isto vai fazer com que eles concentrem seus esforços e estabeleçam um limite sobre o tempo e energia necessários para te ajudar. Isso é bom.

Para entender o mundo em que os especialistas vivem, imagine que a sabedoria é um recurso abundante e o tempo é muito escasso. Quanto menos tempo for necessário para atender seu pedido, maior a chance de conseguir uma resposta de alguém realmente bom e realmente ocupado.

Portanto, é melhor posicionar sua pergunta de forma que ela exija o menor tempo possível para um especialista analisar - mas isto não é mesma coisa que simplificar a questão. Por exemplo, "Você pode me mostrar onde encontro informações sobre X?" é uma pergunta mais inteligente do que "Você pode me explicar X?". Se você tem algum código que não está funcionando, é mais inteligente perguntar o que está errado nele do que pedir para que o consertem.

#### Não mande seus deveres de casa

Hackers são bons em descobrir perguntas feitas nos deveres de casa; muitos de nós fizemos os nossos próprios deveres. Estas questões existem para que você faça o trabalho, para que você aprenda com a sua experiência. Tudo bem pedir dicas, mas não a resposta completa.

Se você suspeita de ter enviado uma questão do seu dever de casa, mas mesmo assim não souber resolvê-la, tente perguntar em um grupo de usuários ou \(como último recurso\) em uma lista usuários de um projeto. Mesmo que os hackers percebam este tipo de questão, alguns usuários avançados podem pelo menos lhe dar umas dicas.

#### Remova as perguntas inúteis

Resista à tentação de terminar sua mensagem com perguntas semanticamente nulas, como "Alguém pode me ajudar?" ou "Existe uma resposta?". Primeiro: se você descreveu seu problema razoavelmente bem, estas questões são, na melhor das hipóteses, supérfluas. Segundo: por elas serem supérfluas, hackers as consideram irritantes - e tendem a enviar resposta logicamente impecáveis mas igualmente inúteis como "Sim, posso te ajudar" e "Não, não há ajuda aqui para você".

Evite perguntas de "sim/não" a não ser que queira uma resposta do tipo "[sim/não](http://homepages.tesco.net/~J.deBoynePollard/FGA/questions-with-yes-or-no-answers.html)".

#### Não marque sua mensagem como "Urgente", mesmo que ela o seja para você

Isso é problema seu, não nosso. Alegar urgência é normalmente contra-producente: muitos hackers simplesmente apagarão a mensagem por causa do egoísmo na tentativa de atrair atenção especial e imediata.

Existe uma "semi-exceção". Se você estiver com problemas em alguma lugar de alto-nível, onde um hacker se interessaria em ajudar; neste caso, se você estiver com o prazo sob pressão, e se você disser isso educadamente, o pessoal talvez se interesse o suficiente para acelerar a ajuda.

No entanto, isto é muito arriscado, pois a métrica dos hackers sobre o que é ou não interessante provavelmente difere da sua. Mensagens vindo da Estação Espacial Internacional podem ser qualificadas como interessante, por exemplo, mas mensagens sobre caridade ou causa política quase certamente não. Vejamos, enviando "Urgente: Me ajudem a salvar a pele dos bebês focas!" fará você ser evitado ou insultado mesmo por hackers que consideram os bebês focas importantes.

Se você acha isso um mistério, releia todo este documento repetidamente até entendê-lo, antes de enviar qualquer mensagem.

#### Boas maneiras não atrapalham, e algumas vezes ajudam

Seja cortês. Use "Por favor" e "Obrigado pela atenção". Deixe claro que você ficou grato pelo tempo que as pessoas gastaram te ajudando gratuitamente.

Para ser honesto, isso não é tão importante quanto a correção gramatical, clareza, ser preciso e dar boas descrições, evitar arquivos proprietários etc. \(tampouco substituto\); Hackers em geral preferem uma descrição rude mas precisa do que uma mensagem educada e vaga. \(Se isto confunde você, lembre-se de que damos valor a uma questão de acordo com o que ela nos ensina\)

No entanto, se você estiver com suas questões técnicas em ordem, boa educação aumenta sua chance de conseguir uma resposta útil.

\(Informamos que recebemos uma séria objeção dos hackers veteranos com relação ao "Desde já, agradeço a atenção". Alguns hackers dão, a esta frase, a conotação de que não existirá um agradecimento posterior. Nossa recomendação aos que desejam agradecer antecipadamente é de que façam um agradecimento pessoal aos que ajudaram na solução do problema.\)

#### Mande uma breve mensagem com a solução

Envie um resumo da solução a todos que ajudaram você; faça-os saber que a ajuda foi útil e agradeça-os novamente. Se o problema atraiu muito interesse na lista/fórum, envie esta mensagem diretamente para lá.

A melhor maneira é responder a própria mensagem, adicionando "RESOLVIDO", "SOLUÇÃO" ou outra coisa igualmente óbvia no assunto da mensagem. Em listas muito dinâmicas, um participante que lê uma mensagem sobre "Problema X" e logo abaixo "Problema X - RESOLVIDO" pode pular esta questão \(a não ser que ele julgue o problema X interessante\) e usar seu tempo resolvendo outros problemas.

Sua mensagem não precisa ser longa; um simples "Era um problema no cabo de rede! Obrigado a todos!" é melhor do que nada. Na verdade, uma mensagem curta e simples é bem melhor, a não ser que a solução para o problema tenha realmente uma profundidade técnica muito grande. Diga apenas que passo resolveu o problema, não precisa recriar todo o processo de solução.

Para problemas mais complexos é interessante criar um sumário da solução do problema. Descreva o seu problema final. Descreva o que funcionou para solucionar o problema e deixe os "tiros n'água" para o final. As tentativas que não deram certo devem vir por último, depois da solução correta e do sumário. Evite transformar sua mensagem em uma história de detetive. Dê nome as pessoas que te ajudaram; assim você fará muitos amigos.

Além de ser cortês e informativo, este tipo de mensagem ajudará outras pessoas que estejam procurando no histórico da lista/grupo/fórum a conhecerem que solução foi útil para você e qual será útil para elas.

Por último, mas igualmente importante, esta mensagem faz com que todos os que ajudaram se sintam satisfeitos por terem ajudado a solucionar seu problema. Se você não é um techie ou um hacker, confie em nós quando dizemos que este sentimento é importante para os gurus e experts a quem pediu ajuda. Narrativas de problemas que não levam a nenhuma solução são frustrantes; hackers se coçam até ver isto resolvido. Você acumulará uma bom karma se ajudá-los a se sentirem bem, o que será muito, mas muito importante na próxima vez que precisar de ajuda.

Considere fazer com que outras pessoas não passem pelo mesmo problema que você. Se você achar que criando um patch ou um FAQ ajudará o próximo, faça-o e mande para o fabricante.

Entre os hackers, este tipo de atitude é mais importante do que uma boa educação. É assim que você adquire uma reputação, o que pode ser um bem muito valioso.

### Como interpretar respostas

#### RTFM e STFW: Como dizer que você está realmente enrolado

Existe uma antiga e sagrada tradição que diz: se você recebe uma resposta com as letras RTFM, a pessoa que as enviou acha que você precisa "ler a porra do manual" \(Read The Fucking Manual\). Ele deve estar certo. Vá ler o manual.

RTFM tem um irmão mais novo. Se você recebe uma resposta com as letras STFW, a pessoa que as enviou acha que você precisa "procurar na porra da web" \(Search The Fucking Web\). Ele deve estar certo. Vá procurar na web. \(Uma versão mais leve é "Google é seu amigo!"\)

Em fóruns web, você também pode ser convidado a pesquisar nos arquivos de mensagens anteriores. De fato, alguém pode até mesmo lhe indicar o link da conversa onde seu assunto já foi discutido. Mas não dependa deste comportamento. Faça sua própria pesquisa antes de perguntar.

Muitas vezes a pessoa que te mandou ler o manual ou procurar na web está com o manual aberto na página que você precisa ler ou tem o link de onde a resposta pode ser encontrada enquanto digita sua mensagem. Estas respostas significam que ele acha que \(a\) a informação que você precisa é fácil de encontrar, e \(b\) você irá aprender mais se procurar a informação por contra própria do que se recebê-la de mão beijada.

Não se sinta ofendido por causa disso; para os padrões do hacker, ele está demonstrando um certo tipo de respeito por não ignorar você. Você deve agradecê-lo por tamanha generosidade.

#### Se você não entender...

Se você não entender a resposta, não mande imediatamente um pedido de explicação. Use as mesmas ferramentas que você usou antes de fazer sua pergunta \(manuais, FAQ, web, amigos experientes\) para entender a resposta. Então, se você ainda assim precisar de explicações, demonstre que você aprendeu.

Por exemplo, suponha que eu te diga: "Me parece que você ficou preso no zentry; você precisa limpá-lo." Aqui está uma péssima réplica: "O que é um zentry?" E aqui está uma boa réplica: "Ok, eu li o manual e zentries são mencionados apenas nas opções -z e -p. Nenhuma delas diz como limpar o zentry. É alguma dessas opções ou deixei passar alguma coisa?"

#### Lidando com grosserias

Muito do que se parece com grosserias no círculo hacker não tem o objetivo de ofender. Pelo contrário, isto é um produto de um estilo de comunicação direta, sem rodeios, que é natural em pessoas que estão mais preocupadas em resolver problemas do que fornecer carinho e afeto.

Se você se sentir agredido, tente reagir calmamente. Se alguém está realmente te agredindo é mais provável que um membro sênior da lista ou do fórum acalme o atacante. Se isto não acontecer e você revidar, é provável que seu suposto agressor esteja agindo de acordo com as normas da comunidade hacker e então você será o errado na história. Isto afetará suas chances de conseguir a ajuda que procura.

Por outro lado, você ocasionalmente verá agressões no grupo. Esta é uma forma aceitável de rebater os que realmente ofendem o grupo, dissecando seu comportamento de forma ríspida, como se o escalpelassem verbalmente. Entretanto, muito cuidado ao fazer isso. A linha que separa uma correção de incivilidade de uma guerra sem sentido é tão tênue que os próprios hackers têm medo de chegar perto; se você é um novato ou não pertence ao grupo, sua chance de acertar é muito baixa. Se você está procurando informação e não entretenimento, é melhor manter os dedos fora do teclado e não arriscar.

\(Algumas pessoas afirmam que os hackers possuem uma forma moderada de autismo ou da Síndrome de Asperger e que, na verdade, apresentam uma deficiência no cérebro que os impedem de terem um comportamento social "normal". Isto pode ou não ser verdade. Se você não é um hacker, isto pode ajudá-lo a colaborar com nossa excentricidade ao achar que temos o cérebro danificado. Vá em frente, não importa; nós gostamos de ser o que somos, e geralmente possuímos um saudável ceticismo quanto a diagnósticos médicos.\)

Na próxima seção falaremos de um assunto um pouco diferente; do tipo de grosseria que você vai ver quanto se comportar mal.

### Não reaja como um otário

Algumas vezes você irá fazer besteira em uma comunidade hacker - de forma descrita neste artigo ou similar. E você será avisado onde exatamente você errou, geralmente sem papas na língua. Em público.

Quando isso acontecer, a pior coisa que você pode fazer é ficar chiando, alegar que foi violentado verbalmente, exigir desculpas, gritar, prender a respiração, ameaçar ir para a justiça, reclamar com o patrão das pessoas, deixar a tampa do vaso levantada, etc. Invés disso, eis o que deve fazer:

Supere. Isso é normal. Na verdade, isto é saudável e muito apropriado.

Normas de comunidades não as sustentam: elas são mantidas por pessoas que as aplicam na prática, visivelmente, em público. Não reclame que todas as críticas devam ser feitas em particular: Não é assim que isto funciona. Também não é útil insistir que você foi insultado quando alguém comentar que uma afirmação sua está errada ou que ele pensa diferente. Isto é uma atitude deplorável.

Existem alguns fóruns por aí onde, por causa de um errático senso de super-cortesia, os participantes são banidos por delatarem erros na forma como a mensagem é enviada, dizendo "não diga nada se você não vai ajudar o usuário". Isto impede que importantes dicas de comportamento sejam passadas para a comunidade e tornam o fórum inútil.

Exageradamente amigável \(como descrito acima\) ou útil: escolha um.

Lembre-se: Quando aquele hacker diz que você pisou na bola e \(não importa quão ríspido\) ele diz que você não deve fazer isso novamente, ele está preocupado com \(1\) você e \(2\) sua comunidade. Seria muito mais simples ele ignorar você e deixá-lo de fora da sua vida. Se você não consegue se sentir grato por isso, pelo menos tenha um pouco de dignidade, não esperneie, não espere ser tratado como uma boneca de porcelana só porque você é um novato com uma alma teatralmente sensível.

De vez em quando alguém irá atacar você, de forma gratuita e sem nenhuma razão aparente, mesmo que você não tenha feito nada de errado \(ou tenha feito somente na imaginação do seu agressor\). Neste caso, ficar reclamando é uma maneira de realmente pisar na bola.

Estes atiçadores são ou lamers que não sabem de nada mas acreditam serem experts ou pretensos psicólogos testando o quanto você suporta. Os outros leitores ignoram-os, ou encontram maneiras próprias de lidar com essas pessoas. Este comportamento traz problemas por si só e isso não deve preocupar você.

Não caia no joguinho de guerra de insultos. Estas brigas devem ser ignoradas - uma vez que você se certificou de que são apenas brigas sem sentido, não atacam nenhum ponto em que você realmente errou nem tenta, de nenhuma forma, elucidar sua questão.

### Perguntas que não devem ser feitas

Pergunta: Onde eu encontro o programa ou o recurso X?

Pergunta: Eu posso usar X para fazer Y?

Pergunta: Como eu configuro meu prompt da shell?

Pergunta: Eu consigo converter um documento do formato AcmeCorp em arquivo TeX usando o conversor de arquivos Bass-o-matic?

Pergunta: Meu {programa, configuração, statement SQL} não funciona.

Pergunta: Estou com problemas no meu Windows. Você pode me ajudar?

Pergunta: Meu programa não funciona. Acho que o sistema X está ruim.

Pergunta: Estou com problemas para instalar o Linux ou X. Pode me ajudar?

Pergunta: Como invadir/roubar op de um canal/ler o email de outra pessoa?

**Pergunta**:

> Onde eu encontro o programa ou o recurso X?

**Resposta**:

> No mesmo lugar onde nós encontramos, mané - na outra ponta de uma pesquisa web. Meu Deus, ninguém aprendeu como usar o [Google](http://www.google.com.br/), ainda?

**Pergunta**:

> Eu posso usar X para fazer Y?

**Resposta**:

> Se o que você deseja fazer é Y, você deveria perguntar sem pressupor um método que pode não ser o apropriado. Questões assim indicam que a pessoa não é apenas ignorante com relação a X, mas também confusa sobre o problema Y e muito apegada aos detalhes de uma situação particular. Normalmente é melhor ignorar essas pessoas até que elas melhor definam seus problemas.

**Pergunta**:

> Como eu configuro meu prompt da shell?

**Resposta**:

> Se você é esperto o suficiente para fazer esta pergunta, é esperto o suficiente para [RTFM](http://clipart-library.com/perguntas.html#rtfm) e descobrir por conta própria.

**Pergunta**:

> Eu consigo converter um documento do formato AcmeCorp em arquivo TeX usando o conversor de arquivos Bass-o-matic?

**Resposta**:

> Tente e descobrirá. Se você fizer isso você \(a\) vai descobrir a resposta e \(b\) não vai desperdiçar meu tempo.

**Pergunta**:

> Meu {programa, configuração, statement SQL} não funciona.

**Resposta**:

> Isto não é uma pergunta, e eu não estou disposto a brincar de perguntas e respostas até conseguir extrair a pergunta certa de você - tenho coisas melhores para fazer. Ao ver coisas assim, minha reação é, normalmente, uma destas:
>
> * Você tem algo a acrescentar?
> * Ah, que pena, espero que resolva este problema.
> * E o que eu tenho a ver com isso?

**Pergunta**:

> Estou com problemas no meu Windows. Você pode me ajudar?

**Resposta**:

> Sim, jogue fora esse lixo da Microsoft e instale um sistema operacional open-source como o Linux ou BSD.
>
> Nota: Você pode fazer perguntas relacionadas a máquinas Windows se elas forem sobre programas que possuem uma versão oficial para ele ou interaja com ele \(p.ex.: Samba\). Apenas não se surpreenda com a resposta de que o problema é no Windows e não no programa, pois o Windows é tão problemático que geralmente é isto o que acontece.

**Pergunta**:

> Meu programa não funciona. Acho que o sistema X está ruim.

**Resposta**:

> Mesmo que seja possível você ser o primeiro a perceber uma deficiência óbvia de uma system call ou uma biblioteca de sistema usada por centenas ou milhares de pessoas, é mais provável que você esteja fazendo alguma coisa errada. Declarações extraordinárias precisam de evidências extraordinárias. Quando você afirma uma coisa dessas, você precisa se preparar com uma documentação clara e completa sobre o problema.

**Pergunta**:

> Estou com problemas para instalar o Linux ou X. Pode me ajudar?

**Resposta**:

> Não. Eu preciso estar em frente ao seu computador para fazer isso. Pergunte para o seu grupo local de usuários Linux. \(você encontra uma lista de grupos de usuários [aqui](http://www.linux.org/groups/index.html)\).

**Pergunta**:

> Como invadir/roubar op de um canal/ler o email de outra pessoa?

**Resposta**:

> Você é uma forma de vida inferior por querer fazer esse tipo de coisa e um idiota por pedir ajuda a um hacker.

### Boas e más perguntas

Finalmente, irei demonstrar como fazer perguntas de forma inteligente através de exemplos; pares de questões sobre o mesmo problema, uma pergunta feita de forma estúpida e outra de forma inteligente.

**Estúpida**: Onde posso encontrar informações sobre o Foonly Flurbamatic?

Esta pergunta está implorando por uma resposta do tipo "[STFW](http://clipart-library.com/perguntas.html#rtfm)".

**Inteligente**: Usei o Google para procurar por "Foonly Flurbamatic 2600" mas não obtive nenhum resultado satisfatório. Alguém sabe onde encontrar informações sobre programação para este device?

Esta passou pelo "STFW" e parece que tem realmente um problema.

**Estúpida**: Não consigo fazer o código do projeto foo compilar. Porque ele está ruim?

Ele assume que alguém fez besteira. Muito arrogante da parte dele.

**Inteligente**: O código do projeto foo não compila sob um Nulix version 6.2. Já li o FAQ, mas não existe nenhuma referência a problemas com sistemas Nulix. Aqui está uma transcrição da minha tentativa de compilar o código; fiz alguma coisa errada?

Ele especificou o sistema, ele leu o FAQ, ele mostrou o erro e ele não está assumindo que o problema é de ninguém além dele mesmo. Este cara merece alguma atenção.

**Estúpida**: Estou tendo problemas com minha placa-mãe. Alguém pode me ajudar?

O hacker Fulano de Tal normalmente exclama, ao ler uma mensagem assim, "Certo, quer tapinha nas costas e que troque a fraldinha também?", e logo depois dá um soco na tecla delete.

**Inteligente**: Eu tentei X, Y e Z na placa-mãe S2464. Não funcionou, então tentei A, B e C. Note o curioso sintoma quanto tentei C. Obviamente o problema está na rebimboca da parafuseta, mas os resultados não são os que eu esperava. Quais são as causas mais comuns para isso acontecer em placas Athlon MP? Alguém tem alguma idéia de como posso resolver o problema?

Esta pessoa, por outro lado, parece ter se esforçado por uma resposta. Ele demonstrou uma lógica de quem está batalhando pela solução e não quer que alguém jogue a resposta no seu colo.

Na última pergunta, atente para a súbita mas importante diferença entre pedir "Me dê uma resposta" e "Por favor me ajude a descobrir que diagnósticos preciso rodar para encontrar uma luz".

Na verdade, o formato desta última questão é baseada em um incidente real que aconteceu em agosto de 2001 na lista linux-kernel \(lkml\). Eu \(Eric\) estava fazendo a pergunta desta vez. Eu estava observando travamentos misteriosos em uma placa-mãe Tyan S2462. Os membros da lista me forneceram informações críticas que eu precisava para resolver o problema.

Fazendo a pergunta do jeito que eu fiz, eu dei as pessoas algo no que fuçar; Eu tornei o problema fácil e atrativo para que eles se envolvessem. Eu demonstrei respeito pela habilidade dos meus companheiros e os convidei a me consultarem como um participante do grupo. Também demonstrei respeito pelo tempo que gastariam comigo, dando informações sobre os becos escuros por onde andei antes de pedir ajuda.

Ao final, quando eu agradeci a todos e enfatizei o quão bem o processo havia funcionado, um membro da lista comentou que o processo funcionou não por causa do meu "nome" na lista, mas porque eu propus a questão da forma correta.

Hackers são algumas vezes impiedosamente meritocratas; Tenho certeza de que ele tinha razão e, se eu tivesse me comportado como uma esponja eu seria atacado ou ignorado não importando quem eu era. Sua sugestão de que eu escrevesse sobre este episódio como uma forma de instruir os outros me levou diretamente à confecção deste guia.

### Se você não conseguir uma resposta

Se você não conseguir uma resposta, por favor, não leve para o lado pessoal achando que não queremos ajudar você. Algumas vezes os membros do grupo simplesmente não sabem a resposta. Ficar sem resposta não é o mesmo do que ser ignorado, apesar de admitir ser difícil notar a diferença estando do lado de fora.

Em geral, apenas reenviar sua pergunta é uma péssima idéia. Isto será encarado como uma irritante perda de tempo. Tenha paciência: a pessoa com a sua resposta pode estar dormindo, em um fuso-horário diferente.

Existem outras fontes de ajuda que você pode consultar, geralmente fontes mais adequadas as necessidades de novatos.

Existem muitos grupos locais e online de usuários que são entusiastas pelo software, mesmo que eles nunca tenham escrito um. Estes grupos são geralmente formados para que seus usuários ajudem uns aos outros, inclusive novos usuários.

Existem também diversas empresas que você pode contratar para te ajudar, tanto grandes quanto pequenas \(Red Hat e Linuxcare são as mais conhecidas; mas existem muitas outras\). Não fique desanimado se você tiver que pagar por alguma ajuda! Comparando, se o motor do seu carro estiver com algum problema, é muito provável que você tenha que ir a um mecânico e comprar algumas peças para que ele seja consertado. Mesmo que o software não lhe tenha custado nada, não espere que todo o suporte seja sempre gratuito.

Para sistemas populares como o Linux, existem cerca de 10 mil usuário para cada desenvolvedor. Não é possível para uma pessoa atender chamados de 10 mil usuários. Lembre-se que, se você tiver que pagar pelo suporte, você ainda vai estar pagando bem menos do que se tivesse que comprar o software \(e o suporte para sistemas de código fechado são geralmente mais caros e menos competentes do que suporte em sistemas de código aberto\).

### Como responder perguntas de forma útil

Seja gentil. Stress relacionado a problemas podem fazer as pessoas parecerem rudes ou estúpidas mesmo que elas não sejam.

Responda à uma primeira falta offline. Não há necessidade de humilhar publicamente alguém que tenha honestamente cometido um erro. Um novato de verdade pode não saber como pesquisar o histórico da lista ou onde o FAQ está localizado.

Se você não tem certeza, deixe isto claro! Uma resposta errada mas cheia de autoridade é pior do que nenhuma resposta. Não indique a ninguém um caminho errado só porque é divertido falar como um expert. Seja humilde e honesto; dê um bom exemplo para os seus companheiros.

Se você não pode ajudar, não atrapalhe! Não faça piadas sobre procedimentos que podem bagunçar o sistema do usuário - o pobre coitado pode interpretar isto como instruções sérias.

Faça perguntas para levantar mais informações. Se você for bom nisso o usuário irá aprender alguma coisa - e talvez você também. Tente transformar uma pergunta ruim em uma pergunta boa; lembre-se que todos nós fomos novatos um dia.

Enquanto mandar um RTFM é algumas vezes justificável quando você está respondendo uma pergunta de um preguiçoso, uma indicação do local exato da documentação \(ou a frase correta para pesquisar no Google\) é bem melhor.

Se você for responder uma pergunta, responda direito. Não sugira gambiarras para fazer funcionar a ferramenta errada. Sugira a ferramenta certa. Refaça a pergunta.

Ajude sua comunidade a aprender com a pergunta. Quando você responder a uma pergunta pense: "Como a documentação ou o FAQ podem ser melhorados para que ninguém precise perguntar isso novamente?" E então envie um patch ao mantenedor da documentação.

Se você teve que pesquisar para encontrar uma resposta, demonstre como você encontrou a resposta ao invés de fazer parecer que você a tirou de dentro de uma cartola. Responder a uma boa pergunta é como dar um prato de comida a um faminto. Mas ensiná-lo a plantar o próprio alimento é lhe garantir comida para o resto da vida.

### Fontes relacionadas

Se você precisa de instruções sobre o básico dos computadores, sistemas Unix e Internet consulte o [HOWTO Fundamentos do Unix e da Internet](http://en.tldp.org/HOWTO/Unix-and-Internet-Fundamentals-HOWTO/). \(em inglês\)

Quando você distribuir um software ou escrever patches para um, tente seguir o guia [HOWTO Software Release Practice](http://en.tldp.org/HOWTO/Software-Release-Practice-HOWTO/index.html). \(em inglês\)

### Agradecimentos

Evelyn Mitchell contribuiu com alguns exemplos de perguntas estúpidas e inspirou a seção "Como responder perguntas de forma útil".  
Mikhail Ramendik contribuiu com valiosas sugestões de aprimoramento deste guia.

### Notas do tradutor

Este texto foi traduzido, para o português do Brasil, do original "How to ask questions - The smart way". Alguns trechos foram reescritos pois \(a\) a tradução literal seria incompreensível e \(b\) algumas adaptações de linguagem foram necessárias para que o público-alvo pudesse se identificar com os termos comumente usados no Brasil.

Se você tiver alguma dúvida sobre a tradução ou encontrar divergências entre o significado original e a versão em português, por favor,entre em contato. Obrigado!  


