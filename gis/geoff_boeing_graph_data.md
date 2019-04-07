## Geoff Boeing
> Geoff has some truely amazing work on his [blog](https://geoffboeing.com/publications/), were he talks about urban planning, his 
[OSMnx library]() which describes the methods for acquiring, constructing, analyzing, and visualizing complex street 
networks(using networkX and other spatial data from OpenStreetMap)
### Data
- He also shares some great data sets on [harvards dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/CUWWYJ) which contains over 110,000 processed, cleaned street network graphs (which in turn comprise over 55 million nodes and over 137 million edges) at various scales—comprehensively covering the entire U.S.
- [U.S. Street Network Analytic Measures](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/F5UNSK)



```
#street stats
!wget https://dataverse.harvard.edu/api/access/datafile/:persistentId?persistentId=doi:10.7910/DVN/F5UNSK/G0VOOJ
```

```
# get rail network
# note this is rail *infrastructure* and thus includes crossovers, sidings, spurs, yards, etc
# for station-based rail network, you should prob download a station adjacency matrix elsewhere
G = ox.graph_from_place('New York City, New York',
                        retain_all=False, truncate_by_edge=True, simplify=True,
                        network_type='none', infrastructure='way["railway"~"subway"]')

fig, ax = ox.plot_graph(G, fig_height=10, node_size=0)
```
