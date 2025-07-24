# Descrição dos Dados

Esse conjunto de dados é resultado das atividades desenvolvidas durante o curso LCE5703 - Estatística Experimental (O.C.) (1º Semestre de 2025), oferecido pela Escola Superior de Agricultura Luiz de Queiroz da Universidade de São Paulo (ESALQ - USP).
______

**bi-species_culture.csv**

Número de colunas: 16, Número de Linhas: 1800

Base de dados com a exposição e efeitos de nanopartículas (NPs) em fitoplânctons.

A planilha inclui dados de: day: tempo após o início do cultivo bi-espécie, combination: a combinação de espécies presente em cada cultivo, NPs: concentração de nanopartículas, expressa em miligramas por litro (mg/L), replicate: número da repetição experimental. ANK_cell_ml: a densidade de espécies ANK no cultivo bi-espécie (se houver), expressa em unidades de indivíduos (ou células) por mL, CHLA_cell_ml: a densidade de espécies CHLA no cultivo bi-espécie (se houver), expressa em unidades de indivíduos (ou células) por mL, SCE_cell_ml: a densidade de espécies SCE no cultivo bi-espécie (se houver), expressa em unidades de indivíduos (ou células) por mL, SEL_cell_ml: a densidade de espécies SEL no cultivo bi-espécie (se houver), expressa em unidades de indivíduos (ou células) por mL, STA_cell_ml: a densidade de espécies STA no cultivo bi-espécie (se houver), expressa em unidades de indivíduos (ou células) por mL, ANK_biomass_ml: a biomassa da espécie ANK no cultivo (se houver), expressa em pg de carbono por mL (pg/mL), CHLA_biomass_ml: a biomassa da espécie CHLA no cultivo (se houver), expressa em pg de carbono por mL (pg/mL), SCE_biomass_ml: a biomassa da espécie SCE no cultivo (se houver), expressa em pg de carbono por mL (pg/mL), SEL_biomass_ml: a biomassa da espécie SEL no cultivo (se houver), expressa em pg de carbono por mL (pg/mL), STA_biomass_ml: a biomassa da espécie STA no cultivo (se houver), expressa em pg de carbono por mL (pg C/mL), cell_ml: a densidade total da comunidade biespécie, ou seja, a soma das densidades das duas espécies presentes em cada combinação, expressa em número de indivíduos (ou células) por mL, biomass_ml: a biomassa total da comunidade, equivalente à soma das biomassas das duas espécies, expressa em pg de carbono por mL (pg C/mL).

O conjunto de dados completo pode ser acessado [aqui](https://doi.org/10.5061/dryad.02v6wwq92).

______

**Ant_Colony_Data.csv**

Número de colunas: 9, Número de Linhas: 3901

Base de dados de colônias de formigas-lava-pés (*Solenopsis invicta*) encontradas em um pomar comercial de citros. 
A amostragem ocorreu em um pomar comercial de laranjas valência em Lake Wales, Flórida, EUA (27°50'34.55""N, 81°34'29.99""W).

"Plot" refere-se ao número da parcela no delineamento em blocos casualizados completo (DBC). Os números de parcela na casa dos 100 pertencem ao mesmo bloco, os números na casa dos 200 pertencem a outro bloco, e assim por diante. "Treatment" refere-se aos diferentes tratamentos de controle de formigas. "Control" é o controle sem tratamento; "Chlorpyrifos" é a aplicação de clorpirifós no solo na dose de 1 quarto por acre, seguida por bifentrina vários meses depois, na dose de 22,5 onças por acre; "Clinch" é o isca formicida com abamectina Clinch; "Extinguish" é a isca com S-metopreno Extinguish; e "Hot Water" são aplicações de água quente diretamente em colônias de formigas individuais. "Row" pode ser tratado como um fator e refere-se à fileira de árvores dentro da parcela onde a amostragem foi realizada (havia 5 fileiras de árvores por parcela). "Date" é a data em que as amostras foram coletadas, no formato mm/dd/aa ou mm/dd. Também há intervalos de datas em que a amostragem levou mais de um dia. Por exemplo, "2/22-2/24" significa que a amostragem ocorreu entre 22 e 24 de fevereiro de 2021. "With Brood" refere-se ao número de colônias de *S. invicta* encontradas por fileira que apresentavam crias (formigas imaturas). Isso foi determinado perturbando a colônia com o pé ou com um graveto e observando se havia formigas imaturas ou aladas presentes, o que classificava a colônia como contendo crias. "Without Brood" refere-se ao número de colônias de *S. invicta* encontradas por fileira que não apresentavam crias (formigas imaturas). Isso também foi determinado perturbando a colônia e observando a presença ou ausência de formigas imaturas ou aladas. Se nenhuma delas estivesse presente, a colônia era classificada como sem crias. "Added.Brood" é uma coluna na qual o número total de colônias com crias é somado nas 5 fileiras de cada parcela, resultando no total de colônias com crias por parcela. "NA"s foram inseridos em todas as linhas do conjunto de dados, exceto na última de cada parcela. "Added.No.Brood" é uma coluna na qual o número total de colônias sem crias é somado nas 5 fileiras de cada parcela, resultando no total de colônias sem crias por parcela. "NA"s foram inseridos em todas as linhas do conjunto de dados, exceto na última de cada parcela. "Days.Since.Start" é o número de dias decorridos desde o início da amostragem. O valor 0 representa o primeiro dia de coleta.

O conjunto de dados completo pode ser acessado [aqui](https://doi.org/10.25338/B8V06H).

______

**sp_responses.csv**

Número de colunas: 11, Número de Linhas: 30

Bases de dados sobre efeitos da diversidade nas respostas de crescimento em nível de espécie à aplicações fungicidas e inceticidas.

"site" é o sítio experimental (A ou B), "sp" é a espécie arbórea, taxa de variação do crescimento da área basal (2014–2016) em relação a log₂(riqueza de espécies), nas subparcelas: de controle (slopeC.BA), tratadas com fungicida (slopeF.BA), tratadas com inseticida (slopeI.BA). "slopeFC.BA" é a diferença entre slopeF.BA e slopeC.BA. "slopeIC.BA" é a diferença entre slopeI.BA e slopeC.BA. "effmono.F.deltaBA" é o efeito da aplicação de fungicida no crescimento da área basal em monocultivo, "effmono.I.deltaBA" é efeito da aplicação de inseticida no crescimento da área basal em monocultivo, "Fdamage" é o dano foliar por fungos (% da área foliar total) na parcela central de controle do monocultivo, "Idamage" é o dano foliar por insetos (% da área foliar total) na parcela central de controle do monocultivo.

O conjunto de dados completo pode ser acessado [aqui](https://doi.org/10.5061/dryad.3r2280gjp).

______

**altura_de_plantas_com_hidroretentor.csv**

Número de colunas: 5, Número de Linhas: 71

Base de dados do efeito da aplicação de diferentes concentração de um hidroretentor (Polyter) no crescimento da cultura florífera crisântemo.

"dose" refere-se à dose de hidroretentor aplicada por vaso (g/vaso), "reposicao_hidrica" é a reposição hídrica adotada, "data" é a data de verificação da altura, "dias" é a quantidade de dias corridos desde a primeira verificação de altura, e "altura" é a altura (cm) das plantas.

O conjunto de dados completo pode ser acessado [aqui](https://repositorio.ufu.br/bitstream/123456789/26157/7/UsoPol%c3%admeroHidroretentor.pdf).

______


## Informações adicionais

Tratamento dos dados no R disponíveis [aqui](https://posit.cloud/content/10568256).

Autor: Manoel M. C. Meira - [ORCID](https://orcid.org/0000-0002-6043-6370).

Contatos: manoelcmeira@gmail.com | manoelmeira@usp.br
