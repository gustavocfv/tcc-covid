# tcc-covid
# Modelo de Previsão de Novos Casos de COVID-19 e Mortes Relacionadas à Doença

Inicialmente, o objetivo deste trabalho era prever a curva de casos de COVID-19  e de mortes relacionadas à doença na população dos municípios do Brasil, a fim de municiar os entes governamentais de informações para tomada de decisão na saúde pública em meio à pandemia. Durante a análise exploratória, percebemos que a qualidade dos dados de vários estados brasileiros eram questionáveis, por isso, a partir da segunda entrega, reformulamos o objetivo para nos concentrar apenas nos municípios do estado de São Paulo, que além de terem dados mais confiáveis, também traziam um dado adicional: o índice de isolamento social.

A previsão será realizada por meio da análise do banco de dados histórico e uso de modelos estatísticos e algoritmos de Inteligência Artificial, que selecionarão as características mais relevantes que explicam os eventos de transmissão e mortes.

Desta forma, os governos municipais e estaduais poderão traçar estratégias de prevenção (distanciamento social, lockdown, retomada das atividades econômicas), de criação de leitos de UTIs públicos e de aluguel de leitos de UTI privados, de acordo com a fase da pandemia.

# Contextualização do Problema

A pandemia de COVID-19 teve início na cidade de Wuhan, na China, em dezembro de 2019.

Causada pelo SARS-CoV-2, uma variação do coronavírus que causou a Síndrome Respiratória Aguda Grave (SARS) na epidemia de 2002, a doença rapidamente se espalhou pelo mundo, com a Organização Mundial de Saúde (OMS) declarando em 30 de janeiro de 2020 que a epidemia era uma Emergência de Saúde Pública de Âmbito Internacional. Com a escalada de casos, em 11 de março de 2020 a OMS declarou estarmos vivendo uma pandemia. O primeiro caso registrado oficialmente no Brasil aconteceu na cidade de São Paulo, em 26 de fevereiro de 2020.

Com altos índices de contágio através de gotículas de saliva, a doença ataca primariamente os pulmões. Em casos graves, o paciente tem queda drástica de oxigenação no sangue e necessita internação em leito de Unidade de Terapia Intensiva (UTI) e entubação para receber ventilação mecânica. Como há oferta limitada de leitos de UTI, é necessário estimar a quantidade de novos casos de COVID-19 para direcionar políticas de enfrentamento que evitem o colapso do sistema de saúde, como isolamento social, criação de novos leitos de UTI e requisição de leitos de UTI privados pelo poder público.

Há que se levar em consideração as dificuldades de modelagem, a saber:
* É consenso entre os pesquisadores do tema de que há imensa subnotificação dos casos de COVID-19 no Brasil, devido a falta de testes em massa, vontade política e falta de bases de dados únicas e universais.
* Os números de casos e mortes confirmados disponibilizados pelas secretarias de saúde estaduais e municipais sofrem modificações históricas constantes, conforme os resultados dos testes são liberados, com casos e mortes passadas sendo agregados aos dados históricos. Além disso, alguns estados alteraram o critério de identificação do município durante o período de coleta de dados, de local de diagnóstico para local de residência do paciente.
* Não há padronização das informações disponíveis ao público, e em casos como  o histórico de taxa de isolamento e o histórico de ocupação dos leitos de UTI, variáveis importantes para prever a aceleração da epidemia e o colapso do sistema de saúde, as informações não estão disponíveis para a grande maioria dos municípios.

Portanto, o estudo a seguir não tem a intenção de ser um modelo definitivo e com altíssima precisão, mas um norte em termos de ordens de grandeza.

# Notebooks

Os notebooks do projeto foram criados em Python.


