# Descrição dos Dados

Esse conjunto de dados é resultado das atividades desenvolvidas durante o curso LCE5703 - Estatística Experimental (O.C.) (1º Semestre de 2025), oferecido pela Escola Superior de Agricultura Luiz de Queiroz da Universidade de São Paulo (ESALQ - USP).
______

**bi-species_culture.csv**

Base de dados com a exposição e efeitos de nanopartículas (NPs) em fitoplânctons.

Número de colunas: 16, Número de Linhas: 1800

A planilha inclui dados de: day: tempo após o início do cultivo bi-espécie, combination: a combinação de espécies presente em cada cultivo, NPs: concentração de nanopartículas, expressa em miligramas por litro (mg/L), replicate: número da repetição experimental. ANK_cell_ml: a densidade de espécies ANK no cultivo bi-espécie (se houver), expressa em unidades de indivíduos (ou células) por mL, CHLA_cell_ml: a densidade de espécies CHLA no cultivo bi-espécie (se houver), expressa em unidades de indivíduos (ou células) por mL, SCE_cell_ml: a densidade de espécies SCE no cultivo bi-espécie (se houver), expressa em unidades de indivíduos (ou células) por mL, SEL_cell_ml: a densidade de espécies SEL no cultivo bi-espécie (se houver), expressa em unidades de indivíduos (ou células) por mL, STA_cell_ml: a densidade de espécies STA no cultivo bi-espécie (se houver), expressa em unidades de indivíduos (ou células) por mL, ANK_biomass_ml: a biomassa da espécie ANK no cultivo (se houver), expressa em pg de carbono por mL (pg/mL), CHLA_biomass_ml: a biomassa da espécie CHLA no cultivo (se houver), expressa em pg de carbono por mL (pg/mL), SCE_biomass_ml: a biomassa da espécie SCE no cultivo (se houver), expressa em pg de carbono por mL (pg/mL), SEL_biomass_ml: a biomassa da espécie SEL no cultivo (se houver), expressa em pg de carbono por mL (pg/mL), STA_biomass_ml: a biomassa da espécie STA no cultivo (se houver), expressa em pg de carbono por mL (pg C/mL), cell_ml: a densidade total da comunidade biespécie, ou seja, a soma das densidades das duas espécies presentes em cada combinação, expressa em número de indivíduos (ou células) por mL, biomass_ml: a biomassa total da comunidade, equivalente à soma das biomassas das duas espécies, expressa em pg de carbono por mL (pg C/mL).

O conjunto de dados completo pode ser acessado [aqui](https://doi.org/10.5061/dryad.02v6wwq92).

______

**Ant_Colony_Data.csv**

Base de dados de colônias de formigas-lava-pés (*Solenopsis invicta*) encontradas em um pomar comercial de citros. 
A amostragem ocorreu em um pomar comercial de laranjas valência em Lake Wales, Flórida, EUA (27°50'34.55""N, 81°34'29.99""W).

Número de colunas: 9, Número de Linhas: 3901

"Plot" refere-se ao número da parcela no delineamento em blocos casualizados completo (DBC). Os números de parcela na casa dos 100 pertencem ao mesmo bloco, os números na casa dos 200 pertencem a outro bloco, e assim por diante. "Treatment" refere-se aos diferentes tratamentos de controle de formigas. "Control" é o controle sem tratamento; "Chlorpyrifos" é a aplicação de clorpirifós no solo na dose de 1 quarto por acre, seguida por bifentrina vários meses depois, na dose de 22,5 onças por acre; "Clinch" é o isca formicida com abamectina Clinch; "Extinguish" é a isca com S-metopreno Extinguish; e "Hot Water" são aplicações de água quente diretamente em colônias de formigas individuais. "Row" pode ser tratado como um fator e refere-se à fileira de árvores dentro da parcela onde a amostragem foi realizada (havia 5 fileiras de árvores por parcela). "Date" é a data em que as amostras foram coletadas, no formato mm/dd/aa ou mm/dd. Também há intervalos de datas em que a amostragem levou mais de um dia. Por exemplo, "2/22-2/24" significa que a amostragem ocorreu entre 22 e 24 de fevereiro de 2021. "With Brood" refere-se ao número de colônias de *S. invicta* encontradas por fileira que apresentavam crias (formigas imaturas). Isso foi determinado perturbando a colônia com o pé ou com um graveto e observando se havia formigas imaturas ou aladas presentes, o que classificava a colônia como contendo crias. "Without Brood" refere-se ao número de colônias de *S. invicta* encontradas por fileira que não apresentavam crias (formigas imaturas). Isso também foi determinado perturbando a colônia e observando a presença ou ausência de formigas imaturas ou aladas. Se nenhuma delas estivesse presente, a colônia era classificada como sem crias. "Added.Brood" é uma coluna na qual o número total de colônias com crias é somado nas 5 fileiras de cada parcela, resultando no total de colônias com crias por parcela. "NA"s foram inseridos em todas as linhas do conjunto de dados, exceto na última de cada parcela. "Added.No.Brood" é uma coluna na qual o número total de colônias sem crias é somado nas 5 fileiras de cada parcela, resultando no total de colônias sem crias por parcela. "NA"s foram inseridos em todas as linhas do conjunto de dados, exceto na última de cada parcela. "Days.Since.Start" é o número de dias decorridos desde o início da amostragem. O valor 0 representa o primeiro dia de coleta.

O conjunto de dados completo pode ser acessado [aqui](https://doi.org/10.25338/B8V06H).

______

**mesocosm_silvetia_weights.csv**

Bases de dados sobre o impacto na biomassa da alga *Silvetia compressa* a diferentes condições de temperatura e pCO<sub>2</sub> que refletem cenários da emissão de gases de efeito estufa [RCP 2.6 (baixa) e RCP 4.5 (moderada)].

Número de colunas: 5, Número de Linhas: 61

"Season" é a estação do ano do teste, "Replicate" refere-se à replicata do ensaio, "Climate	SILV_i" é a massa inicial (g) de *S. compressa* e "SILV_f" é a massa final (g) de *S. compressa*.


______

## Informações adicionais

Tratamento dos dados no R disponíveis [aqui](https://posit.cloud/content/10568256).

Autor: Manoel M. C. Meira - [ORCID](https://orcid.org/0000-0002-6043-6370).

Contatos: manoelcmeira@gmail.com | manoelmeira@usp.br
