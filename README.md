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

**mesocosm_understory.csv**

Número de colunas: 44, Número de Linhas: 121

Bases de dados sobre medições da biomassa do sub-bosque por gênero de alga realizadas no início e no final de cada ensaio em mesocosmo. Os seguintes códigos são usados para os gêneros de sub-bosque incluídos nos mesocosmos:

- CENT: *Centroceras spp.*

- CHON: *Chondracanthus spp.*

- CORA: *Corallina spp.*

- LAUR: *Laurencia spp.*

Número de colunas: 5, Número de Linhas: 61

A biomassa do sub-bosque (com aproximação de 0,01 g) foi registrada usando uma balança digital e posteriormente dividida em biomassa branqueada (coluna GENERA_b) e não branqueada (coluna GENERA_ub). A coluna GENERA_f representa a biomassa total (branqueada + não branqueada) para os respectivos gêneros. As colunas marcadas com +1 tiveram seus respectivos valores aumentados por uma variável dummy de Bray-Curtis igual a 1. A coluna GENERA_delt indica a diferença entre a biomassa final não branqueada e a biomassa inicial. A coluna GENERA_%loss representa a proporção de GENERA_delt em relação à biomassa inicial (GENERA_i). A coluna GENERA_%f é calculada como 1 - GENERA_%loss e representa a proporção da biomassa restante em relação à biomassa inicial.

O conjunto de dados completo pode ser acessado [aqui](https://doi.org/10.5061/dryad.05qfttf8b).

______

## Informações adicionais

Tratamento dos dados no R disponíveis [aqui](https://posit.cloud/content/10568256).

Autor: Manoel M. C. Meira - [ORCID](https://orcid.org/0000-0002-6043-6370).

Contatos: manoelcmeira@gmail.com | manoelmeira@usp.br
