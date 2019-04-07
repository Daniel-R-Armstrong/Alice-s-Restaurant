- [Property Tax statistics (2017-1976)](https://www2.illinois.gov/rev/research/taxstats/PropertyTaxStatistics/Pages/default.aspx)  
- [State income tax paid by county](https://www2.illinois.gov/rev/research/taxstats/IndIncomeStratifications/SitePages/IITStratifications.aspx?rptYear=2016)
- [Ilinois L-tax Delinquency List (Updated weekly)](https://www2.illinois.gov/ilcc/All%20documents%20site%20wide/Divisions/Licensing/Delinq.pdf) 
  [(Info Page)](https://www2.illinois.gov/ilcc/Divisions/Pages/Other-Search-Features.aspx)
- [Street sweeping map](https://catalog.data.gov/dataset/street-sweeping-2018-map)(could this tell us the power of the word, compairing to to street length in word)
- [more data sets at data.gov](https://catalog.data.gov/dataset?tags=shapefiles&organization=city-of-chicago)
- [Toxics Release Inventory (TRI)](https://catalog.data.gov/dataset/toxic-release-inventory-tri-8162e)
- [USGS Water-Quality Data for the Nation - National Water Information System (NWIS)](https://catalog.data.gov/dataset/usgs-water-quality-data-for-the-nation-national-water-information-system-nwis)
-[aquifers](https://catalog.data.gov/dataset/aquifers)
- https://catalog.data.gov/dataset/fws-critical-habitat-for-threatened-and-endangered-species-dataset
- https://catalog.data.gov/dataset/u-s-geological-survey-gap-analysis-program-land-cover-data-v2-2
- https://catalog.data.gov/dataset/biodiversity-information-serving-our-nation-bison
- https://catalog.data.gov/dataset/mineral-resources-data-system
- https://catalog.data.gov/dataset/epa-facility-registry-service-frs-landfill
- https://catalog.data.gov/dataset/national-wetlands-inventory-wetlands
- https://catalog.data.gov/dataset/enviroatlas-average-annual-precipitation-1981-2010-by-huc12-for-the-conterminous-united-states
- https://catalog.data.gov/dataset/national-flood-hazard-layer-nfhle9690
- https://catalog.data.gov/dataset/usgs-water-use-data-for-the-nation-national-water-information-system-nwis
- https://catalog.data.gov/dataset/us-epa-2014-fine-particulate-pollution-pm2-5-season-review-by-city
- https://catalog.data.gov/dataset/data-from-population-dynamics-of-an-invasive-forest-insect-and-associated-natural-enemies-
- https://catalog.data.gov/dataset/demographics-for-us-census-tracts-2012-american-community-survey-2008-2012-derived-summary-tab36a06
-https://catalog.data.gov/dataset/enviroatlas-commute-time-to-work-by-census-block-group-for-the-conterminous-united-states
-https://catalog.data.gov/dataset/enviroatlas-business-vacancy-rate-by-census-tract-for-the-conterminous-united-states
- [Bureau of Labor Statistics, Quarterly Census of Employment and Wages](https://www.bls.gov/cew/datatoc.htm) [example](https://github.com/NYCPlanning/rp-USmetros_comparison/blob/6ba2b0bc7db5e9cc243f1d82e3e3d291fa772d27/.ipynb_checkpoints/4.0-BLS-QCEW_byIndustry-checkpoint.ipynb)
  - [QCEW Open Data Access: Sample Code](https://data.bls.gov/cew/doc/access/data_access_examples.htm#PYTHON)  
- [Equal Employment Opportunity Tabulation, race/education/occupation](factfinder2.census.gov)

```
#Consumer Expenditure Surveys - PUMD Data Files(1996 forward, public-use microdata (PUMD))
!wget --header="Host: www.bls.gov" --header="User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/73.0.3683.86 Safari/537.36" --header="Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3" --header="Accept-Language: en-US,en;q=0.9" --header="Referer: https://www.bls.gov/cex/pumd_data.htm" --header="Cookie: _ga=GA1.2.1970499942.1553336521; _gid=GA1.2.1184218799.1553336521; _gat_GSA_ENOR0=1; _4c_=fVBdj5swEPwrlfuKiHf9Ac5b1UpVn09VH09gm4JKjsg44apT%2FvsNJE2lu6o8GHt3ZnZ2XsTSxyexJ2OUUrU1zjIX4lf8PYv9i%2FDH9TxvxzAPOYaHU%2FuAP7rCx%2Bcin%2BbC903K%2BMVFFOKURrT6nI%2FzfrdblqVsx7n8OZ13gO%2BOp0N4DE1uyj4fPvr5DIafQgSFXKlLjXebpmWOCaXPfZoO8UOlUO3gRHjjWbKPZJpW%2BtrHSpKmyjtmdrpm4KbV2Y%2FhKUAEzxS7mNKmhte6AW43RyjkmA4rAdcjthRMuI2Tb8YVh2AK8fXT4%2FdvXzaDldTOOc3lNS1rNnhAfCLErjmNWVwK8XxNU7ORXCl2mJKRSW21XD8g0hBusYq2dco6G7wi07lWBkXSdqqtqppZk4X%2BpmeJiA0rqh0EjtDb%2BHQfp4x0rFjK2zjS93HrZhua%2F8I1g1Bj1nt31%2Fz%2FR%2FrHStj%2FhoeBu2MlrdFEax8hXTf%2Bk9RbmGHAhjvqbd%2BQvVwurw%3D%3D" --header="Connection: keep-alive" "https://www.bls.gov/cex/pumd/data/comma/intrvw17.zip" -O "intrvw17.zip" -c
```
