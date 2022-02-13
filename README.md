# Fifa-22-data-analysis (PCA, Clustering)

 ![Image1](https://user-images.githubusercontent.com/71329302/153768327-151c9e53-5e41-41d6-ad81-08219ff9a979.jpg)

<b> This dataset contains information and statistics about football players' in FIFA 2022 </b>.

The first part was dedicated to <b> understanding and manipulating data </b> (Player ratings' distribution, ratings' distribution by player characteristic, top10 nationalities present in the game, best player statistics...)

NB: I concentrated on players with overall ratings >=80

Secondly, I performed a <b> PCA </b> and projected data on the first two components (<b>85% of the initial information</b>).  

![Capture2](https://user-images.githubusercontent.com/71329302/153767762-7728088b-05ed-494f-a716-364309f0cf77.JPG)

Then, based on the <b> inertia </b> (according to the number of clusters),

![Capture3](https://user-images.githubusercontent.com/71329302/153767845-bedf94cd-5683-42b1-8afe-5188042eb376.JPG)

we can consider a partition into <b> 4 clusters </b> (which seems logical as in football there are 4 categories of players: Strikers, midfielders, defenders, goalkeepers).

![Capture](https://user-images.githubusercontent.com/71329302/153767656-cecbf55a-1457-491e-9874-69f46d55d32e.JPG)

After performing clustering, the objectif is to define our clusters based on the means of the different characteristics of the cluster. For example, given the high mean of "finishing", "Dribbling", "BallControl"... we can deduce that we are dealing with the strikers' cluster.

I also performed other <b> methods of dimension reduction (Isomap, t-SNE, mds) </b> and compared the different results of clustering

![capture4](https://user-images.githubusercontent.com/71329302/153768231-78b5d612-0803-4b8c-a375-b522d454c692.JPG)

![Capture5](https://user-images.githubusercontent.com/71329302/153768275-1164138e-5077-4309-9513-6535a9cf748b.JPG)

Finally, I compared the performances of the top 10 strikers, midfielders and defenders in the game using <b> radar charts </b>.

![newplot (1)](https://user-images.githubusercontent.com/71329302/153767917-5bbd6b66-69d6-42ae-a72e-c75b785893e6.png)

![newplot (3)](https://user-images.githubusercontent.com/71329302/153767934-ab262858-63e1-4c2e-a751-6cbc45e3819c.png)
