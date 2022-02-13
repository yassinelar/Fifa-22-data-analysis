# Fifa-22-data-analysis (PCA, Clustering)

<b> This dataset contains information and statistics about football players' in FIFA 2022 </b>.

The first part was dedicated to <b> understanding and manipulating data </b> (Player ratings' distribution, ratings' distribution by player characteristic, top10 nationalities present in the game, best player statistics...)

NB: I concentrated on players with overall ratings >=80

Secondly, I performed a <b> PCA </b> and projected data on the first two components (<b>85% of the initial information</b>).  

Then, based on the <b> inertia </b> (according to the number of clusters),
we can consider a partition into <b> 4 clusters </b> (which seems logical as in football there are 4 categories of players: Attackers, midfielders, defenders, goalkeepers).

After performing clustering, the objectif is to define our clusters based on the means of the different characteristics of the cluster. 

Finally, I compared the performances of the top 10 attackers, midfielders and defenders in the game using <b> radar charts </b>.

