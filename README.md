# Weekly/monthly mortality 2015--2021

This repository contains country-level data on all-cause mortality collected from various sources, see below. Please note:

* Our aim is to provide data from 2015 onwards. In some cases the coverage starts later, but we require at least full 2019 data.
* Countries are only included if the data exist until at least June 2020. 
* We only collect weekly, monthly, or quarterly data. 
* We only provide all-cause mortality numbers, without splitting by age or gender.
* We only provide country-level data, without splitting it by regions or individual cities.
* The data for the European countries are sourced from the EuroStat **(LINK NEEDED)**.
* The Short Term Mortality Fluctuations (STMF) dataset from the [Human Mortality Database](https://www.mortality.org) (HMD) is integrated into this dataset.

We welcome any contributions.

Weekly data mostly follow ISO8601 standard, when weeks are calendar weeks, Monday to Sunday, and the weeks on the year boundaries are assigned to the year in which they have more days (four or more). Most years have 52 weeks but some years, such as 2015, will have 53 weeks. Some countries provide weekly data starting weeks from January 1st, irrespective of week day. This is specified in the data table.

## Sources

### Armenia (monthly)

2015: https://www.armstat.am/file/article/sv_12_15r_520.pdf  
2016: https://www.armstat.am/file/article/sv_12_16r_520.pdf  
2017: https://www.armstat.am/file/article/sv_12_17r_520.pdf  
2018: https://www.armstat.am/file/article/sv_12_18r_520.pdf  
2019: https://www.armstat.am/file/article/sv_12_19r_520.pdf  
2020: https://www.armstat.am/file/article/sv_10_20r_520.pdf  


### Azerbijan (monthly)
2015 to 2017: http://data.un.org/Data.aspx?d=POP&f=tableCode%3a65%3bcountryCode%3a31&c=2,3,6,8,10,12,13,14&s=_countryEnglishNameOrderBy:asc,refYear:desc,areaCode:asc&v=1

2019 to 2020: https://www.stat.gov.az/news/source/2020_11ay.zip


### Bolivia (monthly)
New York Times Excess Mortality: https://github.com/nytimes/covid-19-data/tree/master/excess-deaths


### Brazil
All years - Brazilian Population Registry: https://transparencia.registrocivil.org.br/registros


### Colombia (weekly)

https://www.dane.gov.co/index.php/estadisticas-por-tema/demografia-y-poblacion/informe-de-seguimiento-defunciones-por-covid-19  
Direct link to the latest table in XLS (November 2020): https://www.dane.gov.co/files/investigaciones/poblacion/defunciones-covid19/anexos-defunciones-covid-nal-2020-02mar-01nov.xlsx.  
Here we sum values in three categories: Natural, Violenta, and En estudio (unclassified deaths). 


### Ecuador (weekly)

2017: https://www.ecuadorencifras.gob.ec/nacimientos-y-defunciones-2017/
2018: https://www.ecuadorencifras.gob.ec/category/poblacion-y-demografia/
2019: https://www.ecuadorencifras.gob.ec/defunciones-generales-2019/
2020: https://www.registrocivil.gob.ec/cifrasdefuncion/
Direct link to the latest table in XLS (January 2021):
https://www.registrocivil.gob.ec/wp-content/uploads/downloads/2021/01/Defunciones_Generales_2020_act_03_ENE_2021.xlsx


### Egypt (monthly)

2015 to 2019: http://data.un.org/Data.aspx?d=POP&f=tableCode%3a65%3bcountryCode%3a818&c=2,3,6,8,10,12,13,14&s=_countryEnglishNameOrderBy:asc,refYear:desc,areaCode:asc&v=1

2020: Monthly Bulletin of the Egyptian NSO (CAPMAS) - https://www.capmas.gov.eg/Pages/Publications.aspx?page_id=5107&Year=23518


### Georgia (monthly)

2015--19: https://www.geostat.ge/media/34261/დემოგრაფიული-ვითარება-საქართველოში-2019.pdf, page 67  
2020: https://www.kavkaz-uzel.eu/blogs/83781/posts/45084 (values digitized from an official plot)


### Hong Kong (monthly)
2015 to 2018: https://www.censtatd.gov.hk/hkstat/sub/sp160.jsp?productCode=FA100094
2019 to 2020: Hong Kong Monthly Digest of Statistics -  https://www.censtatd.gov.hk/hkstat/sub/sp110.jsp?productCode=B1010002


### Iran (quarterly)

https://www.sabteahval.ir/avej/Page.aspx?mId=49826&ID=2182&Page=Magazines/SquareshowMagazine  
The data are provided in Solar Hirji seasons (Spring, Summer, Autumn, Winter). Winter starts on Dec 22, so we count it as the next calendar year (e.g. Winter 1393 as the first entry for 2015).

### Ireland (quarterly)
Central Statistics Office: https://data.cso.ie/table/VSQ01


### Japan (monthly)

All years: https://www.e-stat.go.jp/stat-search/files?page=1&layout=datalist&toukei=00450011&kikan=00450&tstat=000001028897&cycle=1&tclass1=000001053058&tclass2=000001053059&tclass3val=0


### Mexico (weekly)
Mexican Ministry of Health Excess deaths: https://coronavirus.gob.mx/exceso-de-mortalidad-en-mexico/


### Moldova (monthly)
2015 to 2020: UNData: http://data.un.org/Data.aspx?d=POP&f=tableCode:65;countryCode:498&c=2,3,6,8,10,12,13,14&s=_countryEnglishNameOrderBy:asc,refYear:desc,areaCode:asc&v=1

2020: UNData MBS (as crude death rates): https://unstats.un.org/unsd/mbs/app/DataView.aspx?tid=3&cid=498&yearfrom=2015&yearto=2020&p=A

Crude death rates were transformed to mortality counts by using the UNDATA Mid-Year Population estimate for Moldova 2020 which is 2,640,000. 




### Mongolia (monthly)
Mongolian Statistical Information Service: http://www.1212.mn/tables.aspx?tbl_id=DT_NSO_2100_027V2&SOUM_select_all=0&SOUMSingleSelect=_0&YearM_select_all=0&YearMSingleSelect=_202011_202010_202009_202008_202007_202006_202005_202004_202003_202002_202001_202012&viewtype=table


### Peru (weekly)
2017 onward: Peruvian Ministry of Health - National Deaths Registration System (SINADEF): https://www.minsa.gob.pe/reunis/data/defunciones_registradas.asp


### Philippines (monthly)
Philippines Statistics Authority: https://psa.gov.ph/vital-statistics/table


### Romania (monthly)
National Institute of Statistics: 
https://insse.ro/cms/en/comunicate-de-presa-view?field_categorie_value_i18n%5B%5D=15&created=8&field_cuvinte_cheie_value=&items_per_page=10


### Russia (monthly)

https://www.fedstat.ru/indicator/33556 (data available from 2006)  
The latest month is published on *rosstat.gov.ru* first and it takes several days for the data to appear on *fedstat.ru*. The exact URL is always different. For November 2020, the URL is https://rosstat.gov.ru/storage/mediabank/ldMWepjj/edn11-2020.htm.

### Serbia (monthly)

Statistical Office of the Rebublic of Serbia: https://www.stat.gov.rs/en-us/oblasti/stanovnistvo/rodjeni-i-umrli/


### Singapore (monthly)
Department of Statistics Singapore: https://www.tablebuilder.singstat.gov.sg/publicfacing/createDataTable.action?refId=15167


### South Africa (weekly)
South Africa Medical Research Council (SARMC): https://www.samrc.ac.za/reports/report-weekly-deaths-south-africa

SAMRC do not publish weekly data for years prior to 2020. Instead, the raw figures for 2018-2019 are used to forecast expected weekly mortality using the excel forecast function. **HOW TO INDICATE THIS IN THE DATA?**.


### Thailand (monthly)
Official Statistics Registration Systems:
https://stat.bora.dopa.go.th/stat/statnew/statMenu/newStat/home.php


### Ukraine (monthly)
2014 to 2018: http://data.un.org/Data.aspx?d=POP&f=tableCode%3a65%3bcountryCode%3a804&c=2,3,6,8,10,12,13,14&s=_countryEnglishNameOrderBy:asc,refYear:desc,areaCode:asc&v=1

2020: State Statistics Office of Ukraine: http://www.ukrstat.gov.ua/
Statistical Information -> Population and migration -> Number of live births, deaths, by region











