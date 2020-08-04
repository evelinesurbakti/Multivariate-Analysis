# Multivariate Analysis
consists of clustering methods such as hierarchical and kmeans, metric scaling for high dimensional data and also poLCA one of the clustering methods for binary data. 

## Clustering 
The Glass.csv dataset (attached) examines the chemical compositions of 15th-17th century
archaeological glass vessels excavated in Antwerp. The data record the concentrations of 13 elements,
determined by x-ray methods, in 180 glass vessels. The data consist of measurements on four different types
of glass (detailed in the Group variable in the data set). To cluster the data, we used:

- Hierarchical Clustering
- K-means Clustering

## Metric Scaling
Ireland is a parliamentary democracy. The National Parliament (the Oireachtas) consists of the President
and two Houses: Dáil Éireann (House of Representatives) and Seanad Éireann (the Senate). The members of
Dail Éireann, called Teachtaí Dála (TDs), are directly elected by the people. More information may be found
at www.oireachtas.ie.


The votes of TDs are recorded and posted on www.oireachtas.ie. During the 5th session of the 32nd Dáil
Éireann (7 September 2019 - 14 January 2020 inclusive) there were a number of votes in Dáil Éireann by the set
of elected TDs. Data on whether each TD voted yes or not for six of these votes have been downloaded from the
Oireachtas website and are attached in the file 32ndDail_FifthSession_BinaryVotes.Rdata.
The data record if a TD was voted yes (coded 2) or not (coded 1). The main topic of each vote is summarised
in the column headings; for example, ‘HousingMinister’ relates to a vote on a motion of no confidence in the
current Minister for Housing. (See the linked websites above for further details on the 6 votes which took
place on November 28th and December 3rd, 4th, 5th, 12th and 18th 2019 respectively). To cluster the data, we used:

- Latent class analysis (LCA) 

## Metric Scaling
A sample of 30 wild growing and flowering Hyptis suaveolens plants were collected in El Salvador, and
the concentrations of 7 terpenes (sabinene, beta- pinene, 1.8-cineole, gamma-terpinene, fenchone, alpha-terpinolene and fenchol) were measured. Interest lies in uncovering different chemotypes of plant (if any)
using the terpene measures. The geographical region from which each plant was collected was also recorded,
either north, south or east. For the eastern plants, a distinction was made whether the plants grew at low or
high altitude. 

We have done:

- Classical Metric Scaling

- Sammon’s Metric Least Squares Scaling 

- Kruskal’s Non-metric Scaling

- Procrustes Analysis

- Model-Based Clustering 
