
# Méně dětí, dražší bydlení: Co nám o Česku říkají data

Projekt jsme zpracovávaly ve dvojicích. Byl jedním z hodnocených výstupů v **Czechitas akademii Data**
*9.-12. / 2025*

Kódy i samotné metriky, které jimi vypočítávám, jsou výstupem mé části práce na projektu.


## Anotace
V roce 2024 klesl počet narozených dětí v České republice na historické minimum, což znovu otevřelo debatu o příčinách dlouhodobě nízké plodnosti. Jedním z často zmiňovaných faktorů je rostoucí finanční a bytová nejistota. Tento projekt zkoumá, zda lze v datech identifikovat souvislost mezi vývojem nákladů na bydlení (vlastnického i nájemního) a klesající úhrnnou plodností (TFR) v ČR. Analýza má na dvě dimenze:
A) Regionální srovnání v ČR, kde sledujeme možné rozdíly v reprodukčním chování v kontextu dostupnosti bydlení napříč kraji.
B) Mezinárodní kontext, v němž porovnáváme ČR se státy V4, jižní Evropou (Itálie, Španělsko, Portugalsko) a Skandinávií (Dánsko, Švédsko, Finsko, Norsko), a sledujeme vztah mezi vývojem TFR a indexem růstu cen nemovitostí. C) Jako bonus jsme obohatily data i o sociologickou reflexi rozhodování se o rodičovství v ČR.


## Použité nástroje

Keboola, Snowflake, Python pro přeformátování některých vstupních tabulek, Tableau, Excel


## Datové zdroje
Spojily jsme optimalizované datasety ze Statistických ročenek spolu s dalšími tabulkami od ČSÚ (kódy územních celků k propojení okresů na kraje, mediánové mzdy, počty živě narozených, věková struktura obyvatel) a také ISPV (informace a statistiky o průměrném výdělku) za roky 2017-2024 spolu se scrapovanými daty z realitních portálů, poskytnutými APIFY. Pro doplnění širšího evropského kontextu jsme využily data Eurostatu. Můžete se těšit i na přidanou sociologickou perspektivu díky datům GGS z roku 2022.


