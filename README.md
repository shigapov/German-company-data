# German company data

```
Providers of German company data.
```

## Official [commercial registers](https://en.wikipedia.org/wiki/German_Commercial_Register)
There are 120 official registers in Germany (local courts).
1. [Handelsregister - Common register portal of the German federal states](https://www.handelsregister.de/rp_web/welcome.do)
2. [Handelsregisterbekanntmachungen](https://www.handelsregisterbekanntmachungen.de) - announcements about companies
3. [Insolvenzbekanntmachungen](https://neu.insolvenzbekanntmachungen.de/ap/) - bankruptcy notices 

Instead of those 120 registers there will only one central register in future. See
* [Unternehmensbasisdatenregistergesetz](http://www.gesetze-im-internet.de/ubregg/__3.html)
* ["Firmen bekommen zentrale Nummer" by Tagesschau](https://www.tagesschau.de/wirtschaft/unternehmen/unternehmensregister-transparenz-bundestag-stammdaten-basisregister-101.html)

## Bundesanzeiger Verlag
Announcements that are made by the companies themselves are published on:
1. [Bundesanzeiger](https://www.bundesanzeiger.de) provides company reports
2. [Unternehmensregister](https://www.unternehmensregister.de) searches also over Bundesanzeiger & Handelsregisterbekanntmachungen

## Third-party providers of the same data

1. [OpenCorporates](https://opencorporates.com) & [Offeneregister](https://offeneregister.de) provide the data scraped from [Handelsregisterbekanntmachungen](https://www.handelsregisterbekanntmachungen.de). The [data quality issues](https://github.com/opencorporates/de_data_quality/issues) are collected separately.
2. [NorthData](https://www.northdata.de) [[data overview](https://www.northdata.de/_coverage)]
3. [Online-Handelsregister](https://www.online-handelsregister.de) 
4. [Unternehmen24](https://www.unternehmen24.info)
5. [WebValid](https://www.webvalid.de)
6. [Databyte](https://www.databyte.de)
7. [Companyhouse](https://www.companyhouse.de)

## Wrappers of the APIs & Scrapers

1. [Deutschland](https://github.com/bundesAPI/deutschland) Python library sends requests to Handelsregister and Bundesanzeiger

## Historical Data

1. [Hoppenstedt Aktienführer](https://de.wikipedia.org/wiki/Hoppenstedt_Aktienführer)
   * [Aktienführer Database](https://digi.bib.uni-mannheim.de/aktienfuehrer/data/index.php) contains full data from Hoppenstedt-Aktienführer from 1956 to 2018. Access is restricted, can be provided for research purposes only.
   * [Aktienführer Knowledge Graph](https://akf.kgi.uni-mannheim.de) is a (meta)data knowledge graph for Hoppenstedt-Aktienführer enriched with many company identifiers. License is CC0.
2. [Pressearchiv 20. Jahrhundert](https://de.wikipedia.org/wiki/Pressearchiv_20._Jahrhundert)
   * [Homepage](https://pm20.zbw.eu)
   * [Data dump at Zenodo](https://doi.org/10.5281/zenodo.1471430). License is CC0.
   * [SPARQL queries](https://github.com/zbw/sparql-queries/tree/master/pm20)
   * [Wikidata:WikiProject 20th Century Press Archives](https://www.wikidata.org/wiki/Wikidata:WikiProject_20th_Century_Press_Archives)


