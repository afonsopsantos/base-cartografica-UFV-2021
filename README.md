# Geração da base cartográfica de referência para o campus Viçosa - UFV


- [Introdução](https://github.com/afonsopsantos/base-cartografica-UFV-2021/blob/main/README.md#introdu%C3%A7%C3%A3o)
- [Justificativa](https://github.com/afonsopsantos/base-cartografica-UFV-2021#justificativa)
- [Objetivos](https://github.com/afonsopsantos/base-cartografica-UFV-2021/blob/main/README.md#objetivos)
- [Metodologia](https://github.com/afonsopsantos/base-cartografica-UFV-2021/blob/main/README.md#metodologia)
- [Resultados Obtidos](https://github.com/afonsopsantos/base-cartografica-UFV-2021/blob/main/README.md#resultados-obtidos)
- [Produtos Desenvolvidos](https://github.com/afonsopsantos/base-cartografica-UFV-2021/blob/main/README.md#produtos-desenvolvidos)




## Introdução
A cartografia é uma ciência milenar que representa qualquer informação que possa ser espacializada na superfície terrestre. Logo, fica caracterizado que a "cartografia tem por objetivo o estudo de todas as formas de elaboração, produção e utilização da representação da informação geográfica" [1]. Assim, os produtos resultantes da Cartografia são aplicáveis a quaisquer campos de atuação que necessitem de planejamento territorial ou de informações espacializadas. 

Na cartografia há diversas subdivisões e classificações quanto ao tipo de dados representados, finalidade de uso, caráter informativo, entre outros. Aqui, diferencia-se a Cartografia de Referência e a Cartografia Temática: a primeira se caracteriza pela disponibilização de informações genéricas, de uso geral; já a segunda foca na representação/comunicação de um ou mais fenômenos, sem grandes preocupações com a parte geométrica dos dados. 

No Brasil, a cartografia de referência é normatizada por leis e decretos. Em 2008, foi editado o Decreto n° 6.666, que instituiu a Infraestrutura Nacional de Dados Espaciais (INDE). De acordo com a norma, a INDE é definida como “conjunto integrado de tecnologias; políticas; mecanismos e procedimentos de coordenação e monitoramento; padrões e acordos, necessário para facilitar e ordenar a geração, o armazenamento, o acesso, o compartilhamento, a disseminação e o uso dos dados geoespaciais de origem federal, estadual, distrital e municipal” [2]. Para possibilitar a interoperabilidade dos dados, a INDE estabelece diversas especificações técnicas para realizar a padronização dos dados cartográficos de referência. 

Vale ressaltar que o Decreto n° 6.666 de 2008 em seu art 3° diz: “o compartilhamento e disseminação dos dados geoespaciais e seus metadados é obrigatório para todos os órgãos e entidades do Poder Executivo federal”. Logo, dispor de uma base cartográfica de referência é essencial para o planejamento e gestão da administração do campus da Universidade Federal de Viçosa, além de cumprir as obrigatoriedades do Decreto n° 6.666.

 Referências
[1] MENEZES, P.M.L.; FERNANDES, M. C. Roteiro de Cartografia. São Paulo: Oficina de Textos, 288, 2013. 
[2] BRASIL. Decreto nº 6.666, de 27 de novembro de 2008. 
[3] SANTOS, A. P.; RODRIGUES, D. D.; SANTOS, N. T.; GRIPP JÚNIOR, J. Avaliação da acurácia posicional em dados espaciais utilizando técnicas de estatística espacial: proposta de método e exemplo utilizando a norma brasileira. Boletim de Ciências Geodésicas, v. 22, n. 4, 2016. pp. 630-650.

[Topo](https://github.com/afonsopsantos/base-cartografica-UFV-2021/blob/main/README.md#gera%C3%A7%C3%A3o-da-base-cartogr%C3%A1fica-de-refer%C3%AAncia-para-o-campus-vi%C3%A7osa---ufv)


## Justificativa
O projeto denominado “Geração de uma base cartográfica de referência para o campus Viçosa da UFV” destina-se a proporcionar diversos benefícios para os segmentos a seguir relacionados:

Para a Universidade, os ganhos referem-se principalmente à obtenção de uma base cartográfica única e que poderá se transformar em oficial, servindo para aprimorar o planejamento e gestão da administração, além de benefícios para toda a comunidade acadêmica em termos de ensino, pesquisa e extensão. 

Em relação a EJEAG, a realização do projeto proporcionará “know-how” na execução deste tipo de atividade, além do aprimoramento da carta de serviços da empresa, possibilitando a captação de novos clientes e projetos. Além disso, trará melhorias em relação à infraestrutura da empresa, pela aquisição dos bens de capital solicitados no apoio, que auxiliarão no aperfeiçoamento e otimização da execução dos projetos da empresa a longo prazo. A execução de um projeto desta proporção e importância, aliada a um case de sucesso desenvolvido pela EJEAG pode contribuir para que novos alunos venham a integrar a equipe da EJEAG, aumentando, desta forma, o número de colaboradores na empresa. Além disto, estimula o interesse dos alunos do curso em empreendedorismo, uma opção de carreira bastante favorável para graduandos do curso de Engenharia de Agrimensura e Cartográfica. 

Para os alunos que já são membros da EJEAG, os benefícios podem ser traduzidos na viabilização do contato prático com uma atividade específica da profissão, agregando experiência com o mercado profissional, além de uma visão empreendedora no nicho de negócios na área de geotecnologias. 

Para o Departamento de Engenharia Civil, que abriga o curso de Engenharia de Agrimensura e Cartográfica, o projeto representa uma importante iniciativa de articulação entre a empresa júnior, alunos e professores, contribuindo para a execução de um projeto que proporcionará notoriedade em toda a UFV. Além disso, a divulgação do trabalho chamará atenção para um nicho de mercado atrativo para a profissão, podendo despertar interesse dos alunos da UFV para questões de empreendedorismos nesta área.

[Topo](https://github.com/afonsopsantos/base-cartografica-UFV-2021/blob/main/README.md#gera%C3%A7%C3%A3o-da-base-cartogr%C3%A1fica-de-refer%C3%AAncia-para-o-campus-vi%C3%A7osa---ufv)

## Objetivos

### Objetivo Geral
Produzir uma base cartográfica de referência na escala 1:2.000 do campus Viçosa da Universidade Federal de Viçosa.


### Objetivos Específicos
- Realizar um aerolevantamento no campus Viçosa da UFV, compatível para escala 1:2.000; 
- Realizar o controle de qualidade posicional da ortofoto gerada pelo aerolevantamento; 
- Estruturar os planos de informações que compõem a base cartográfica do campus Viçosa da UFV de acordo com as especificações da Infraestrutura Nacional de Dados Espaciais (INDE) - Decreto 6.666/2008; 
- Restituir feições cartográficas de acordo com as especificações técnicas da INDE; 
- Produzir um metadados para a base cartográfica vetorial da UFV de acordo com as especificações da INDE.

[Topo](https://github.com/afonsopsantos/base-cartografica-UFV-2021/blob/main/README.md#gera%C3%A7%C3%A3o-da-base-cartogr%C3%A1fica-de-refer%C3%AAncia-para-o-campus-vi%C3%A7osa---ufv)


## Metodologia

A execução do projeto foi realizada em etapas, sendo dividida em: 
(i) aerolevantamento da área do campus Viçosa da UFV; 
(ii) capacitação dos membros da EJEAG; 
(iii) controle de qualidade dos produtos gerados a partir do aerolevantamento; 
(iv) restituição das feições cartográficas com base na ortofoto e no MDS; 
(v) validação prévia da base cartográfica gerada e; 
(vi) geração do metadados da base cartográfica vetorial. 



#### (i). AEROLEVANTAMENTO: GERAÇÃO DE ORTOFOTOS E MDS 

Para realizar a etapa do aerolevantamento, foi contratada uma empresa especializada com todas as autorizações necessárias para este fim. Os requisitos para o aerolevantamento foram: 
- Aerolevantamento com Aeronave Remotamente Pilotada (RPA/VANT/DRONE) do campus Viçosa da Universidade Federal de Viçosa, com aproximadamente 1.800ha de cobertura; 
- Requisição e Autorização do voo junto à ANAC; 
- Recobrimento fotogramétrico com GSD médio melhor ou igual a 10 cm; 
- Apoio terrestre suplementar com receptores GNSS dupla frequência; 
- Produtos a serem gerados: Ortomosaico e Modelo Digital de Superfície, compatíveis na escala de 1:2.000; 
- Entrega dos dados brutos, relatórios de processamentos e produtos gerados em meio digital. 

Após contratação dos serviços, foram realizadas 3 tentativas de aerolevantamento. Na primeira (outubro de 2020), as condições meteorológicas não estavam favoráveis e, na segunda (novembro de 2020), o RPA apresentou falha mecânica. A terceira tentativa, em janeiro de 2021, foi realizada com sucesso. Neste levantamento, foram tomadas as fotografias e seus parâmetros de aquisição, bem como pontos de controle e checagem a partir de posicionamento geodésico realizado com receptores GNSS. Todos os voos realizados tiveram autorização do DECEA (Departamento de Controle do Espaço Aéreo – Comando da Aeronáutica), Prefeitura Municipal de Viçosa (administradora do aeroporto em Viçosa) e da UFV. 

Para a geração dos produtos cartográficos do aerolevantamento, foi realizado o processamento aerofotogramétrico, obtendo uma ortofoto e um modelo digital de superfície (MDS) do campus Viçosa da UFV.



#### (ii). CAPACITAÇÃO DOS MEMBROS DA EJEAG 

Para a integral realização do projeto pelos membros da EJEAG, foi necessária a capacitação da equipe em relação aos temas associados à execução das etapas do projeto. A capacitação foi direcionada para normatização da cartografia nacional, Infraestrutura Nacional de Dados Espaciais (INDE), controle de qualidade cartográfica e aquisição e estruturação de dados cartográficos. O treinamento da equipe ficou sob responsabilidade do professor orientador da EJEAG, Afonso de Paula dos Santos, sendo realizado de forma remota entre novembro de 2020 a fevereiro de 2021. O conteúdo foi abordado de forma teórica e prática. 



#### (iii) CONTROLE DE QUALIDADE DOS PRODUTOS DO AEROLEVANTAMENTO 

A partir da ortofoto gerada na etapa (i), foi realizado o controle de qualidade cartográfica deste produto. Inicialmente, a EJEAG planejava a coleta dos pontos de checagem em campo para poder validar o produto. Entretanto, devido às restrições da pandemia da Covid-19, não foi possível realizar este processo. Assim, foram utilizados alguns pontos de checagem disponibilizados pelo prof. Afonso P. Santos e pela empresa contratada para realizar o aerolevantamento. De posse dos pontos de checagem, foi avaliada a qualidade posicional a partir do cálculo das discrepâncias posicionais. Para tanto, foram aplicados testes estatísticos e a avaliação da acurácia tanto pelo Decreto 89.817, que contém as tolerâncias para análise da qualidade posicional de produtos cartográficos, quanto pela ET-CQDG, especificação que instrui o procedimento de controle de qualidade cartográfica no âmbito da INDE. Estes procedimentos foram realizados utilizando o software livre GeoPEC 3.5.2 e os procedimentos metodológicos expostos em Santos et al. (2016) [3] 


#### (iv). RESTITUIÇÃO DAS FEIÇÕES CARTOGRÁFICAS COM BASE NA ORTOFOTO E NO MDS

Esta etapa consistiu na elaboração da base cartográfica. Para isto, foi realizada a aquisição dos dados cartográficos a partir de uma restituição (vetorização) dos elementos identificados nas ortofotos e MDS e, através desta, foram gerados os planos de informações de acordo com as recomendações das normas da INDE. Foram utilizadas como base as seguintes especificações: 
- EDGV – Estruturação de Dados Geoespaciais Vetoriais – Versão 3.0 
- ADGV – Aquisição de Dados Geoespaciais Vetoriais – Versão 3.0 
- PCDG – Produtos do Conjunto de Dados Geoespaciais – 2ª edição. 

Todo o procedimento de aquisição e estruturação dos dados cartográficos foram executados no software livre QGIS 3.16. Para otimização dos trabalhos, os membros da EJEAG foram separados em cinco equipes, onde cada grupo ficou responsável pela aquisição e estruturação dos dados referentes às categorias de informação a ela atribuídas. Devido às restrições da pandemia, não foi possível aos membros da EJEAG percorrer o campus presencialmente para identificação de algumas feições, como fontes d’água, dutos, entre outros, que não são bem identificáveis na ortofoto. O preenchimento de atributos de alguns dados cartográficos foi também prejudicado pelas restrições da pandemia. 

#### (v). VALIDAÇÃO PRÉVIA DA BASE CARTOGRÁFICA 

Após a geração da base cartográfica, foi realizada uma avaliação prévia da mesma, analisando elementos de completude, consistência lógica e temática. Este processo foi realizado separando os membros da EJEAG em equipes, conforme apresentado no item (iv). Cada grupo avaliou a qualidade do produto da outra equipe. Ao final, produziu-se um relatório de inconsistência, para que cada equipe efetivasse as correções necessárias. 

#### (vi) GERAÇÃO DO METADADOS DA BASE CARTOGRÁFICA VETORIAL 

Por fim, foi realizado o preenchimento dos metadados de acordo com a INDE, utilizando o Perfil de Metadados Geoespaciais Brasileiros (Perfil MGB) 1ª edição. Metadados são informações sobre o produto, e serve como elemento central dentro de um Infraestrutura de Dados Espaciais.

[Topo](https://github.com/afonsopsantos/base-cartografica-UFV-2021/blob/main/README.md#gera%C3%A7%C3%A3o-da-base-cartogr%C3%A1fica-de-refer%C3%AAncia-para-o-campus-vi%C3%A7osa---ufv)

## Resultados Obtidos 

Base cartográfica vetorial do campus Viçosa. A UFV pode utilizar a base cartográfica gerada para denominar como oficial, servindo para aprimorar o planejamento e gestão da universidade, desenvolver sua própria Infraestrutura de Dados Espaciais (atendendo o art. 3° do Decreto n. 6.666), além de benefícios para toda a comunidade acadêmica em termos de ensino, pesquisa e extensão. 

A EJEAG adquiriu “know-how” na execução deste tipo de atividade, possibilitando o aprimoramento da carta de serviços da empresa, consequentemente, a captação de novos clientes e projetos. Melhorias da infraestrutura da EJEAG, devido aos bens de capital adquiridos para o desenvolvimento deste projeto, e que auxiliarão na execução dos trabalhos da empresa a longo prazo.

[Topo](https://github.com/afonsopsantos/base-cartografica-UFV-2021/blob/main/README.md#gera%C3%A7%C3%A3o-da-base-cartogr%C3%A1fica-de-refer%C3%AAncia-para-o-campus-vi%C3%A7osa---ufv)

## Produtos Desenvolvidos

- Ortofoto de todo o limite territorial do campus Viçosa - UFV, compatível na escala 1:2.000 e resolução espacial de 10 cm; 
- Modelo Digital de Superfície de todo o limite territorial do campus Viçosa - UFV; 
- Base Cartográfica vetorial de referência do Campus Viçosa - UFV contendo classe de informações referentes à: Hidrografia; Limites; Energia; Economia; Edificações; Pontos de Referência; Relevo; Saneamento Básico; Sistema de Transportes; Vegetação; Área Verde; Cultura e Lazer; Estrutura de Mobilidade Urbana. 
- Metadados das informações cartográficas produzidas e disponibilizadas;

[Topo](https://github.com/afonsopsantos/base-cartografica-UFV-2021/blob/main/README.md#gera%C3%A7%C3%A3o-da-base-cartogr%C3%A1fica-de-refer%C3%AAncia-para-o-campus-vi%C3%A7osa---ufv)
