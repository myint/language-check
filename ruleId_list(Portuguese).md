
List with RuleId and exemples (Portuguese)
==========================================

 In this Markdown file I put some types RuleId with its description and examples for Portuguese language. I generated this list because I needed to know all possible errors for my NLP project. I ran 15k ads with errors using _language-tool-python_ and got the errors to do this list.  

# RuleId


* HUNSPELL_RULE

description: Encontrado possível erro de ortografia.

Example: ...ompre agora na moda Salvador BA Pituba, bijouterias, bolsas, vestidos, sapatos. e anurbaces...

* DOUBLE_PUNCTUATION

description: Pontuação duplicada

Example: ...alvador BA Pituba. tudo, anurbacessorios,, bijouterias, acessórios, bolsas, sapato...

* PUNCTUATION_PARAGRAPH_END

description: Por favor adicione uma pontuação ao fim do parágrafo

Example: ... Para Você Ficar na Moda com os Menores Cuidando

* PT_BARBARISMS_REPLACE

description: ‘Online’ é um estrangeirismo. É preferível dizer “ligado”, “com rede” ou “dentro de linha”

Example: ...e Bijouterias em Anurbacessorio. Compre Online! Bolsa, Sapatos e Muito Mais Na Loja On...

* SPACE_BEFORE_PUNCTUATION

description: Remova o espaço antes deste sinal de pontuação.

Example: ... By Carol Dias. Vestido Fórum Feminino. Marca : Fórum ; Tudo em até 10x S / Juros no Br...

* MULTIPLICATION_SIGN

description: Prefira o símbolo de multiplicação.

Example: ...ega Para Todo Brasil Em Até 10x Sem Juros*. As Melhores Marca é Aqui. Encontre Tudo...

* BARBARISMS

description: Os estrangeirismos devem estar entre aspas ou ser italizados.

Example: ...a nosso catálogo completo em nossa loja online on-line (aproveite). Pague no Boleto Ba...

* DASH_RULE

description: Se não pretende unir duas palavras, deve utilizar o travessão.

Example: ...a Anurbacessorios Você Encontra Brincos - Puls

* UPPERCASE_SENTENCE_START

description: Esta frase não inicia com um letra maiúscula

Example: ...brincos, pulseiras, acessórios, bolsas. acessórios. des. Pague no Boleto Bancário...

* INVARIABLE_NOUNS

description: Esta expressão é invariável.

Example: Calça flare Lee em Promoção Para Você. Confir...

* UPPERCASE_AFTER_COMMA

description: Utilize a palavra capitalizada somente se estiver a iniciar uma frase ou a escrever nomes próprios.

Example: ...eu!. Vestido detalhe: ombro único, FPSTU; Tecido elastano. Tamanho: P, M e G.

* GENERAL_NUMBER_AGREEMENT_ERRORS

description: Possível erro de concordância de número.

Example: ...s lindo com essa coleção de bijouteria! Peças exclusiva das mais conceituadas Joias, Bolsarias ...

* ABREVIATIONS_PUNCTUATION

description: Se é uma abreviatura, falta um ponto.

Example: ...patos femininos. Em Até 10x sem Juros * Comp, brincos e pulseiras,, bolsas femininas...

* ELLIPSIS

description: Utilize o caractér tipográfico de reticências em vez de: “...”.

Example: ...cessórios. des. Pague no Boleto Bancário...

* GENERAL_GENDER_AGREEMENT_ERRORS

description: Possível erro de concordância de género.

Example: ... S/Juros* Modelos: Vestido Site Oficial da Fórum em Até 10X E Praxe no Operador. Ombro Ú...

* PERCENT_WITHOUT_SPACE

description: Escreva a percentagem sem espaços (estilo padrão).

Example: ...té 5x s / Juros *. Tipo : Calça Flare ; 36 % Tamanho ; 36, 37, 38 e 40. Melhor Marca...

* COMMA_PARENTHESIS_WHITESPACE

description: Insira um espaço depois da vírgula

Example: ...néis, brincos, anéis, pulseiras,, bolsas,seis.

* PORTUGUESE_WORD_REPEAT_RULE

description: Possível erro de escrita: você repetiu uma palavra

Example: ...Os Melhores Preços e Ofertas. Tamanho : P P, M e G.. Marca : Rosa chá ; Azuls ; Tip...

* INFORMALITIES

description: Linguagem informal. Considere as alternativas.

Example: * Aproveite! Promo melhores anurbacessorios de moda Salvad...

* INTERNET_ABBREVIATIONS

description: Linguagem de Internet. Escreva por extenso.

Example: Aproveite agora mesmo!. Vestido curto P, M e G com a Qualidade que a sua marca ...

* PARENTESESE_AND_QUOTES_SPACING

description: Espaçamento incorreto.

Example: ...idos de noiva. trajes de festa em geral ( masculino e feminino ) e trajes profissionais. JA...

* CURRENCY_SPACE

description: Os símbolos monetários internacionais não são separados por um espaço: “$119”.

Example: ... ; Frete com frete grátis a partir de R $ 119.. Tipo : moleton destroyed ; Confira : ...

* ROMAN_NUMBERS_CHECKER

description: Número romano inválido.

Example: ...iões de Itatiba / SP. Kit esporte tênis xxxx, calça jeans e camisa @ carlosbrusman.....

* PT_COMPOUNDS_POST_REFORM

description: Esta palavra é hifenizada.

Example: ...onfira os Últimos Lançamento da Moleton Rosa chá. Frete Grátis a partir de R$ 119, Melho...

* AO90_MONTHS_CASING

description: Segundo o Acordo Ortográfico de 90, os meses e as estações do ano deixam de ser capitalizados.

Example: ...Não Perca! Descubra Nossas Promoções de Inverno. Compre na Leandro Modas. Entrega Rápid...

* PT_WEASELWORD_REPLACE

description: ‘Até 50%’ é uma expressão ambígua e evasiva. Reconsidere o seu uso, de acordo com o objetivo do seu texto.

Example: ...rete e Troca Grátis*! Regata Machão Com Até 50% algodão. Entrega Rápida. O Melhor da Li...

* SMART_QUOTES

description: Utilize aqui aspas inteligentes: ““”.

Example: Anúncio Conheça a coleção completa. " Esporte é Vida!. Chuteira Adidas Pelé E...

* FINAL_STOPS

description: Se não é um título, falta um ponto no final da frase.

Example: ... na Anurbacessorio. Bolsamos, Sapatoso, Brinquedos

* AO90_CARDINAL_POINTS_CASING

description: Segundo o Acordo Ortográfico de 90, os pontos cardeais deixam de ser capitalizados, excepto se se referem a uma região específica.

Example: ... de na Vila Casual em Itatiba SP Centro Oeste. Camiseta maquinetada manga longa ELEVE...

* HIPHEN_SPACE_RULES

description: Se pretende unir duas palavras, não deve espaçar e deve utilizar o hífen. Caso contrário, utilize espaços e um travessão.

Example: ...trega rápida e segura* de Camiseta 100% algodão- Modelagem Slim fit. Moda Masculina multimarcas! E...

* GENERAL_NUMBER_FORMAT

description: Se não é um ano, os algarismos devem ser agrupados em grupos de 3.

Example: ...Legging Fusô Spirit Evolution Co2 Preto 43429 Live. Calça Fusô de média compressão e ...

* ORDINAL_ABREVIATION

description: A abreviatura deste ordinal é: “100.o”. Note que graus não são ordinais.

Example: ...s,ss Regata machão Osklen 100 % algodão 100o. Entrega Rápida *. Um verdadeiro estilo...

* CACOPHONY

description: Cacofonia. Estas palavras, quando ouvidas, podem ser mal interpretadas.

Example: ...SP. 100 % algodão - modelagem slim fit. Forma mais ajustada ao corpo. Com abotoamento fron...

* SENT_START_NUM

description: Números no início de frases devem ser escritos por extenso.

Example: ...ans ; Preta. Pague em Até 5x s / Juros. 40 de Tamanho ; 36, 37, 38 e 40. Conf mode...

* UNITS_OF_MEASURE_SPACING

description: Deve dar um espaço entre o valor e a unidade de medida: “8 kg”

Example: ...ido ideal para bebês recém nascidos até 8kg... Vendo wrap sling 100 % algodão... De...

* FORMAL_PRA_PARA

description: Será que quis dizer “para”?

Example: ...moda masculina. Produtos Exclusivomente Pra Você. Buscador de moda Xxxx. Em tempo: ...

* SENTENCE_WHITESPACE

description: Adicionar um espaço entre as frases

Example: ... centroREN FASHION NOIVAS E ALFAIATARIA.M. JALECO EM JALECO EM GABARDINE GOLA PAD...

* ALÉM_AQUÉM_RECÉM

description: Esta palavra é hifenizada.

Example: ...Até 50 % Off *. Tecido ideal para bebês recém nascidos até 8kg... Vendo wrap sling 100 % algod...

* CHEMICAL_FORMULAS_TYPOGRAPHY

description: Os números nas fórmulas químicas devem estar em subscrito.

Example: Legging Fusô Spirit Evolution Co2 Preto 43429 Live. Calça Fusô de média c...

* REPEATED_WORDS_3X

description: Para melhorar o texto, procure variar mais os termos utilizados.

Example: ...os: Vestido curto, Vestido ombro único, Vestido Forno;

* E_NO_COMECO

description: Estilisticamente ‘e’ só deve ser utilizado no início da frase raramente, e para um efeito dramático.

Example: ...bijouterias, bolsas, vestidos, sapatos. e anurbacessorios e mais. Em Até 10x sem ...

* VERB_COMMA_CONJUNCTION

description: Esta locução deve ser separada por vírgulas.

Example: Aproveite Agora Mesmo! Além da Linha Completa Rosa Chá, Você Encontra Na Out...

* OLD_SPELLING_U

description: O trema deixou de ser utilizado em Português com o Acordo de 1945.

Example: ALUGÜEL DE VESTIDO DE NOIVA SEREIA MANGAS LONGA...

* ERRO_DE_CONCORDNCIA_DO_GÉNERO_MASCULINO_O

description: Possível erro de concordância de género.

Example: ... na Vila Casual. A partir de R $ 99, 99 o Hora de Entrega : Retirada na Loja ou fazemo...

* FRAGMENT_TWO_ARTICLES

description: Possível fragmento.

Example: ...Itatiba SP Centro. Camisa Details Arrow,o na Vila Casual... Entrega : Retirada na Lo...

* ARTICLES_PRECEDING_LOCATIONS

description: Este nome geográfico é precedido de um artigo.

Example: ...átis Brasil 299, 90 Envio Imediato para Brasil. Acesse Agora! Com Tecnologias Easy Car...

* INTERJECTIONS_PUNTUATION

description: As interjeições devem ser finalizadas com pontos de exclamação ou interrogação.

Example: ....óveis em São Paulo SP Jardim Paulista. Ó. Preço de Atacado.. Peça de orgonite qua...

* PORTUGUESE_WORD_REPEAT_BEGINNING_RULE

description: Três frases seguidas começam com a mesma palavra. Considere reformular a frase ou use um dicionário para encontrar um sinônimo.

Example: .... Conjunto Lira G. Malha 100 % algodão. Conjunto P veste 38 / 40. Até 30 Dias para Troca...

* FRAGMENT_TWO_PREPOSITIONS

description: Duas preposição seguidas. Verifique.

Example: ...Entre e Aproveite! Camre de Malha de lã de em Itatiba SP Centro Oeste, Vila Casual. T...

* UNPAIRED_BRACKETS

description: Símbolo sem par: ““” aparentemente está ausente

Example: ...ague em Até 5x s/ Juros e Entrega Rápida”. Essas muitas outras vantagens imperdív...

* A_WORD

description: Possível erro de concordância de género.

Example: ...gem Slim Fit. Moda Masculina Multimarca a Domicílio nas Regiões de Itatiba/SP

* UNLIKELY_OPENING_PUNCTUATION

description: Sinal de pontuação isolado.

Example: ...Suplex Grosso.. Em Até 10x Sem Juros *. : Modelos Exclusivos e Personalizáveis do...

* PT_WORDINESS_REPLACE

description: ‘Tipo de’ é uma expressão prolixa. É preferível dizer “APAGAR” ou “categoria de”

Example: ...s*: Variedade em Modelos. Não perca!!!. Tipo de Vestido Uniforme. Ombro único. Não Per

* GENERAL_VERB_AGREEMENT_ERRORS

description: Possível erro de concordância verbal.

Example: ...e com as pedras do sol e quartzo verde; As melhores ofertar você mesmo. Coleções Exclusivamente Pra...

* INTERROGATIVES_PUNTUATION

description: Se é uma interrogação, deve terminar com “?”, caso contrário, as orações deve ser separadas por vírgulas.

Example: ...de. Qual em São Paulo SP Jardim Paulista. Pingentes de Orgonite, personalizados e...

* PHRASE_REPETITION

description: Este segmento está duplicado. Talvez queira, apenas, dizer “JALECO EM”.

Example: ...ntroREN FASHION NOIVAS E ALFAIATARIA.M. JALECO EM JALECO EM GABARDINE GOLA PADRE COM ZIPER CENTRAL....

* ACCENTUATED_PARONYMS_DA

description: Nesta situação acentua-se a palavra.

Example: * Conheça os Modelos da. São Paulo SP Consolação. Loja. Outlet ...

* SEMICOLON_COLON_SPACING

description: Deve colocar um espaço após ‘;’.

Example: ...ços e Ofertas do Aqui. Marca : Rosa chá ;.

* CONTRACOES_OBRIGATORIAS

description: Será que quis dizer “à”?

Example: Acesse e Saiba Mais! A a Loja de Tenis do Thiago Boto em Barueri...

* TODOS_FOLLOWED_BY_NOUN_PLURAL

description: Se ‘Produtos’ é um substantivo, ‘Todos’ no plural exige um segundo artigo.

Example: ... no Car. A mais de dez anos no mercado. Todos Produtos Em Até 10X Sem Juros.. Conjunto moletom...

* WHITESPACE_RULE

description: Possível erro de escrita: você repetiu um espaço em branco

Example: ...dutos Originais. Compre Sem Sair de Casa  Tipo: Camiseta P/ M, GG e

* ENUMERATIONS_AND_AND

description: Sempre que possível, deve utilizar só um ‘e’ nas enumerações. Caso contrário, segmente a frase com pontuação ou considere utilizar a ‘Oxford Comma’.

Example: ... Laranja! Casaco De Legítima Qualidade, Conforto E Estilo e Preço Quentinho. Em Até 10x Sem Juros! Na DaE...

* HOURS_ABREVIATION

description: Se é uma indicação horária, não é pontuada.

Example: ...a Física - SEG - SÁB : 10 : 00 - 19 : 00 H. Consulte os Tamanhos e cores disponívei...

* ETC_USAGE

description: Deve-se utilizar a vírgula antes de ‘etc.’.

Example: ...eite Frete Grátis*, Promoções ExclusivaS etc. Aqui na Love Shoes você encontra a mai...

* PARONYM_SITIO_314

description: Esta palavra é um verbo. Se pretende referir-se a um nome ou adjetivo, deve utilizar a forma acentuada.

Example: ...as da Vila Casual em Até 10X Sem Juros* no Sitio. Confi

* DASH_ENUMERATION_SPACE_RULE

description: Em diálogos, deve dar espaço depois do travessão.

Example: ...lha 100 % algodão - modelagem slim fit. -ça mais ajustada ao corpo. - Com abotoamen...

* SPACE_AFTER_PUNCTUATION

description: Coloque um espaço depois das reticências

Example: ...asar no frio chama no zap pronta entrega...ira. Compre e receba em casa.

* ARCHAISMS

description: Esta palavra é uma palavra de português arcaico. Tente utilizar uma alternativa.

Example: ...a Loja Oficial Anurgbacessorio S/Juros. Esto

* HOMONYM_ASSO_10

description: Esta palavra refere-se a um tipo de fivela. Se pretende referir-se à ação de emocionar, deve utilizar a forma com ‘s’.

Example: ...o com Estampa, Moleton Shampoo, Moleton Toninho Aço.

* PT_BR_SIMPLE_REPLACE

description: ‘Metropolitana’ é uma expressão de Portugal, em Português do Brasil utiliza-se: metrô.

Example: ...io nas regiões de Itatiba / SP e Região Metropolitana, Até 30 Dias para Troca*

* TODOS_NUMBER_AGREEMENT

description: Possível erro de concordância de número.

Example: ...pre Online! Na Dalumodas, você encontra toda os estilos de Moda com a maior variedade e...

* PROFANITY

description: Esta palavra é de baixo calão. Considere as alternativas.

Example: ... Sapatos e Muito Mais na Loja Online de Rapidinhas em Até 10x

* PORTUGUESE_WRONG_WORD_IN_CONTEXT

description: Considere “Paço”, i.e. tipo de palácio real ou episcocal, em vez de ‘Passo’, i.e. movimento dos pés a andar; verbo passar?

Example: ...! São des Lojas Preço único e Grande em Passo Fundo RS Centro. Agasalho Completo é. O...

* PLURAL_IN_UNITS_OF_MEASURE

description: As abreviaturas de unidades de medida padrão não tem plural.

Example: ...l. Promoção Relâmpago compre 1 e leve 3 ems. Também disponivel na cor preta. Opira....

* YOUTUBE

description: Você quis dizer “YouTube”?

Example: ...sso site. Preço Baixo. Compre Online do You Tube. Chuteira A

* PORTUGUESE_ADDRESSES

description: Se é um código postal, deve ser escrito sem separadores.

Example: ...uros! Maior buscador da Europa. Mais de 2.000 Modelos. Vestidos de Noiva, Rou

* ALTERNATIVE_CONJUNCTIONS_COMMA

description: Conjunções alternativas ou disjuntivas devem ser separadas por vírgulas.

Example: ...osbrusman. Compre Agora na Vila Casual* ou Receba Em Casa Ou Retire na Loja*. Não Perca! O Melhor da...

* AO90_WEEKDAYS_CASING

description: Segundo o Acordo Ortográfico de 90, os dias da semana deixam de ser capitalizados.

Example: ...a Dalumodas! O Casaco De Lógico Que Vai Ter Bem-Humano Com Sua Mãe Aqui NaDalumOdas...

* NOS_VERBO

description: Substitua por “Nós Fazer”.

Example: ... Camiseta ou Veste Lego? Confira! Venha Nos Fazer uma Visita! Entrega Rápida e Segura. A ...

* LP_PARONYMS

description: Esta palavra é um verbo. Se pretende referir-se a um nome ou adjetivo, deve utilizar a forma acentuada.

Example: ..., Acesse e Confira Todos os Modeloes de Mascara Preta. Até 50% Off* em uma Loja Oficial...

* LINKING_VERB_PREDICATE_AGREEMENT

description: O predicativo tem de concordar em número com o verbo de ligação.

Example: ...quer Loja Física. Os tenis mais baratos estão Linha Air Jordan 1 Chicago. Milhões de produt...

* DENTRO_DE_DA_DAS_DO_DOS_EM_NA_NAS_NO_NOS

description: Substitua por “na”.

Example: ... Modelos de Bola De Futebol. Compre Já! Dentro da Loja Eurico Martins Você Encontra a Mai...

* GENERAL_PRONOMIAL_COLOCATIONS

description: As palavras de sentido negativo devem ser seguidas de próclise.

Example: ...produtos. Tipo: Máscara preta Em Geral, Não Perca-se da Deco

* EXCEL

description: Você quis dizer “Excel” (= Microsoft Excel)?

Example: ...Não Perca! Compre Agora na Loja Oficial EXCEL. Jogando para ir mais longe? Confira! A...

* MAU_MAL_CONFUSION

description: Confusão do adjetivo com o advérbio. Mau é adjetivo (tal como bom) e mal é advérbio (tal como bem).

Example: ...á Aqui na GUIDO COUROS. Encontre a Joia Más Variada e Estilo Para Seu Look. Frete Grátis Ac...

* VERB_QUE_É_VERB_SER

description: Em certos contextos, esta perífrase pode ser simplificada.

Example: ...ncontra na Espaço Ruah! LINHA HARMONIZA QUE É ESTOQUE. Tecido Ideal Para Bebês recém ...

* CHILDISH_LANGUAGE

description: Linguagem infantil. Considere as alternativas.

Example: ...ne! Bolsa nas cores nude caramelo - POM Pum. BELEZA MONDE. Produto Original JF. Des...

* A_NOUN_VERB

description: Erro de concordância de número: “conjunto”

Example: ...nfira? Acesse e inspire - se! Confira o Conjuntos Casa Francisco Morato SP Recanto Felizs...

* REDUNDANCY_MAR

description: Pleonasmo. Substitua por:

Example: ...tos. As Melhores Promoções. O Melhor do Mar Salgado.

* ESTAR_DE_ACORDO

description: Substitua por

Example: ...e. Venha conferir nossa as novidade que estão de acordo com o seu estilo. Confira todos os Lanç...

* FRENCH_HIPHENATED_NAMES

description: Pretende dizer “Pierre-Marie”?

Example: ...! Os Melhores Preços e Modelos de Bolsa Pierre Marie são da Forever Heather para Usar no Dia...

* REDUNDANCY_MAIS

description: Pleonasmo. Substitua por:

Example: ...heça a Linha Completa das Fábrica Já. A Mais Melhor Loja Online com Entrega em SP

* POR_QUE_PORQUE

description: ‘Por que’ pode ser substituído por ‘pelo qual’. Será que pretende dizer:

Example: ...res Preços Com a Qualidade da Dalumodas E Por que não, Renove Seu Guarda Roupa? Aqui Na D...

* PARONYM_SOFISTICA_567

description: Esta palavra é um verbo. Se pretende referir-se a um nome ou adjetivo, deve utilizar a forma acentuada.

Example: ...a modelo Texas é na GUIDRO COUTOS. Toda a Sofistica

* DAQUI_BR

description: O advérbio daqui é usado para indicar lugar ou tempo e pede a preposição a. Substitua «daqui» por “daqui a”.

Example: ...romoções. Mais de 200 marcas diferentes daqui até

* REDUNDANT_CONJUNCTIONS

description: Possível fragmento. Utilize apenas uma conjunção deste tipo.

Example: ...OIVA SEREIA. Aproveite! Modelo CLIQUEDO E OU DIY NOVAS/ALFAIATARIA, ALGUEL DE VESTID...

* CRASE_CONFUSION

description: Se não se refere a horas não se utiliza a crase.

Example: ...oveite Oferta de Remarita Da Marca Boff à uma ótima custo benefício - Personalize já ...

* JÁ_MAIS

description: Pretende dizer “jamais”? Caso contrário, é uma redundância.

Example: ...ncos. Pague no Boleto Bancário E Acesse Já Mais. Em Até 10x

* CONFUSÃO_E_É

description: Substitua por “é”.

Example: ...xclusivaS: Love Shoes, JF, Lojas Online e Fornecedor Livre da Mancha em Promoções...