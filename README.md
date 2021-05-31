# Projeto: DEU POSITIVO
Projeto de Análise de Dados Abertos da Saúde do Brasil (SUS)

<p align= "center">
<img src="https://github.com/JuniorTorresMTJ/temp/blob/main/image/DEU_POSITIVO.png" min-width="300px" max-width="200px" width="750px" > <br>O PRECONCEITO QUE MATA MAIS QUE A DOENÇA
</p>
 




### **OBJETIVO** <img width="20px" src="https://github.com/JuniorTorresMTJ/Projeto_DeuPositivo/blob/main/image/red-ribbon.png" /> 
***
O objetivo desse projeto é a análisar os dados públicos da saúde, foi utilizado os dados de novos diagnósticos de HIV/ADIS no brasil.

### **ESCOPO** <img width="20px" src="https://github.com/JuniorTorresMTJ/Projeto_DeuPositivo/blob/main/image/red-ribbon.png" /> 
***
 
“Sabe quando as pessoas falam sobre HIV? Uma vez por ano, no Dia Mundial da Luta Contra a Aids”, resume a professora de inglês Aurea Carolina Coelho More, que convive com o vírus há mais de 12 anos.

Ouvir/ler deu positivo, dependendo do seu repertório,  suponho que você deve estar pensando que eu estou falando de gravidez né? Para muitos é uma benção e para outros um Deus me livre, mas não, mais 900 mil pessoas vivem com HIV no Brasil e quando essas pessoas fizeram o teste elas ouviram: ***Deu Positivo***. 

<p align= "center">
<img  src="https://empoderadxs.com.br/wp-content/uploads/2018/12/xaids.jpg.pagespeed.ic_.0sTkZeTA22-300x169.jpg" /> 
</p>

Você acha que HIV/AIDS está relacionado a homossexualidade? HIV/AIDS atinge só homossexuais? o objetivo desse estudo é desmistificar esse pensamento dos anos 80 igual a imagem acima. 

 ### **SOBRE O PROJETO** <img width="20px" src="https://github.com/JuniorTorresMTJ/Projeto_DeuPositivo/blob/main/image/red-ribbon.png" /> 
***

[Projeto DeuPositivo](https://github.com/JuniorTorresMTJ/Projeto_DeuPositivo/blob/main/notebook/Projeto_DeuPositivo.ipynb)

<div align = "left">
O projeto está estruturado da seguinte forma: <br>
 
   * Objetivo
   * Introdução
      * SUS - Sistema Único de Saúde
      * Dados Abertos
      * AIDS = HIV?
         * Indectável = Intransmissível
         * Linha do tempo do HIV/AIDS
   * Importação das Bibliotecas
   * Carregamento das Bases
   * Limpeza das Bases
   * Levantamento de Hipóteses
   * Criação das Visualizações
   * Conclusão
</div>


### **HIPÓTESES** <img width="20px" src="https://github.com/JuniorTorresMTJ/Projeto_DeuPositivo/blob/main/image/red-ribbon.png" /> 
***
1.   Em 2019 teve mais casos de HIV em homossexuais do que em heterossexuais.
2.   Na década de 90 os Homossexuais foram os que mais  adquiriram HIV/AIDS.
3.   A maioria dos casos de HIV/AIDS são em pessoas pardas.
4.   Os novos casos de HIV/AIDS ocorrem mais em pessoas com 1° a 4 ° série incompletas.
5.   Pessoas do sexo masculino adquirem mais HIV que pessoas do sexo feminino.
6.   Jovens de 20-34 anos são os que mais são contaminados pelos vírus do HIV.
7.   Menos Pessoas morrem de AIDS comparando com a quantidade de óbitos em 2008.
8.   Os gastos com o Tratamento de HIV/AIDS diminuiram 20% desde 2008.


### **CONCLUSÕES** <img width="20px" src="https://github.com/JuniorTorresMTJ/Projeto_DeuPositivo/blob/main/image/red-ribbon.png" /> 
***

Após toda a análise dos dados, podemos concluir que no começo houve um grande aumento nos casos HIV/AIDS, mas desde meados de 2013 esse número de casos vem diminuindo graças a disponibilização do tratamento para todos, vimos também que em 2019 o único estado brasileiro com mais casos em pessoas homossexuais do que em heterossexuais foi no Distrito Federal e em todos os anos desde 1990 os heteros são os que mais adquirem o diagnóstico de soropositivo. <br><br>
Antes, os brancos eram o que mais contraiam o HIV/AIDS, mas depois de 2013 esse cenário mudou, os pardos começaram a ter mais novos casos novos. Outra mudança foi de mais casos em pessoas com o ensino médio completo, antes tinham mais casos em ensino fundamental incompleto, mostrando que a conscientização nas escolas não está o suficiente, precisamos de mais campanhas, palestras e ensinamentos nas escolas brasileiras. <br><br>
Os homens sempre foram as maiores vítimas do HIV, pois desde 1980 sempre foi o sexo que teve mais casos.  <br><br>
Já analisando os dados pela faixa etária, vemos que o grande número de casos está entre 20-49 anos, é a fase da vida que a vida sexual se inicia e perdura por muito tempo ativa, onde se arriscam mais e não usam preservativos. <br><br>
 Algo positivo de apontar é que temos menos mortes no tratamento do HIV/AIDS, pois em 2008 tinhamos 4381 mortes e já em 2019 tivemos 3058 mortes, uma diminuição em 30%, já os gastos com o tratamento de HIV/AIDS, em 2008 para 2009 teve um grande aumento, mas nos últimos anos não teve um grande aumento significativo, pois as pessoas soropositivas sempre terão HIV/AIDS até a sua morte, pois não temos cura ainda. <br><br>
Portanto, graças ao SUS podemos ver que a os casos de HIV/AIDS vem diminuindo muito, pois é um privilégio todos terem o direito ao tratamento e coquetéis de graça, fora outros tratamentos caros, vacinas, remédios, consultas etc. Então, só podemos dizer:  **Viva ao SUS!**


<p align= "center">
<img src="https://github.com/JuniorTorresMTJ/Projeto_DeuPositivo/blob/main/image/giphy%20(1).gif?raw=true" min-width="300px" max-width="200px" width="200px" >
</p>

<p align= "left">
Qualquer feedback, elogio ou sugestão de melhoria eu ficaria muito grato!
</p>


### **BASES** <img width="20px" src="https://github.com/JuniorTorresMTJ/Projeto_DeuPositivo/blob/main/image/red-ribbon.png" /> 
***

*   **df_escolaridade** = Conjunto de dados que possui os dados de quantidade de diagnóstico de HIV por escolariadade por ano. <BR>
*   **df_etária** = Conjunto de dados que possui os dados de quantidade de diagnóstico de HIV por faixa etária por ano. <BR>
*   **df_raca **= Conjunto de dados que possui os dados de quantidade de diagnóstico de HIV por por raça. <BR>
*   **df_sexo** = Conjunto de dados que possui os dados de quantidade de diagnóstico de HIV por sexo por ano.<BR>
*   **df_sexualidade** = Conjunto de dados que possui os dados de quantidade de diagnóstico de HIV por orientação sexual e estado.<BR>
*   **df_sex_evo** = Conjunto de dados que possui os dados de quantidade de diagnóstico de HIV por orientação sexual por ano.<BR>
*   **df_gastos** = Conjunto de dados que possui os dados de quantidade de gastos em tratamento de HIV/AIDS por ano.
*   **df_obitos** = Conjunto de dados que possui os dados de quantidade mortes com Tratamento de HIV/AIDS


### **CONTATO** <img width="20px" src="https://github.com/JuniorTorresMTJ/Projeto_DeuPositivo/blob/main/image/red-ribbon.png" /> 
***
<p align="center"> <a  href="https://www.linkedin.com/in/marivaldotorres/">
    <img alt="Junior Torres" width="250px"  src="https://github.com/JuniorTorresMTJ/Projeto_DeuPositivo/blob/main/image/Perfil.png" />
  </a>
 </p>

 <p align="center">
<a  href="https://www.linkedin.com/in/marivaldotorres/">
    <img align="center"alt="Junior Torres | Linkedin" width="24px" src="https://github.com/JuniorTorresMTJ/Projeto_DeuPositivo/blob/main/image/linkedin.png" />
  </a>

  <a href="https://www.instagram.com/callmejuniorr/">
    <img align="center" alt="Junior Torres | Instagram" width="24px" src="https://github.com/JuniorTorresMTJ/Projeto_DeuPositivo/blob/main/image/instagram.png" />
  </a>
  <a href="mailto:juniortorres.mtj@gmail.com">
    <img align="center" alt="Junior Torres | Gmail" width="26px" src="https://github.com/JuniorTorresMTJ/Projeto_DeuPositivo/blob/main/image/gmail.png" />
  </a>
  <a href="https://github.com/JuniorTorresMTJ">
    <img align="center" alt="Junior Torres | Github" width="26px" src="https://github.com/JuniorTorresMTJ/Projeto_DeuPositivo/blob/main/image/github.svg" />
  </a>
 </p>


### **FONTES** <img width="20px" src="https://github.com/JuniorTorresMTJ/Projeto_DeuPositivo/blob/main/image/red-ribbon.png" /> 
***
 <img width="20px" src="https://github.com/JuniorTorresMTJ/Projeto_DeuPositivo/blob/main/image/red-ribbon.png" /> Alura: [Link](https://www.alura.com.br/)

<img width="20px" src="https://github.com/JuniorTorresMTJ/Projeto_DeuPositivo/blob/main/image/red-ribbon.png" /> Fonte dos Dados: [DATASUS](http://www2.datasus.gov.br/DATASUS/index.php?area=0202&id=11633&VObj=http://tabnet.datasus.gov.br/cgi/deftohtm.exe?sih/cnv/qi)

<img width="20px" src="https://github.com/JuniorTorresMTJ/Projeto_DeuPositivo/blob/main/image/red-ribbon.png" /> Fonte dos Dados:[AIDS.GOV](http://www2.aids.gov.br/cgi/deftohtm.exe?tabnet/br.def)
