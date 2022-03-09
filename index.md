Anne Louise Seekford
Social Network Analysis
Homework 1

## Data
For homework 1, I selected a dataset from a journal investigating the Association of Stress-Related Disorders with Subsequent Autoimmune Disease. As an individual with an autoimmune disorder, I am very familiar with the fact that people with autoimmune disorders are more likely to develop an additional autoimmune condition. I wanted to find a dataset to reflect the connections between different autoimmune disorders, but this was the closest I could get. In this study, researchers explored the correlation between specific autoimmune disorders and stress disorders. They also explored the relationship when multiple siblings had the same disorder (which I thought was super interesting because my sister also has celiac! - but it was too complex for this initial network). This dataset shows the “Hazard Ratio” for each of the 42 autoimmune disorders, in regards to the likelihood that the diagnosed individuals will develop some variation of stress disorder. 

Here is the head of the dataset: 

<img width="557" alt="Screen Shot 2022-03-09 at 3 23 41 PM" src="https://user-images.githubusercontent.com/71660299/157529562-0902214d-d8ea-430b-b84f-80cc7a8a48d4.png">



## Network - Metrics and Visualizations
The network I created is a directed network, with all nodes directed towards the ‘Stress Disorder’ node. This is the case because all individuals already had an autoimmune disorder, and were investigating the susceptibility of developing a stress disorder given disease type. It was very interesting and helpful to see the network visualized, because it is more obvious to see which are most correlated. It also is interesting to see visually how disorders within general groups (i.e. endocrine disorders, inflammatory arthritis disorders, etc.) varied from one another. I generated multiple network visualizations (spring, circular, etc), but I thought the spring was the best. 

### Spring Layout Visualization: 
Due to the nature of the network, it is evident for the degree distribution to be 1. In a similar way, the average shortest path for any node in the network will be the same - [‘specific autoimmune disorder’, ‘Stress Disorder’]. I think if I were to find the dataset I wanted, the most interesting metric would be the density. Calculated as the # of actual connections / the # of potential connections, the density in this dataset was ​​0.02325. That number would mean much more if I was exploring the susceptibility of one autoimmune disorder to any other autoimmune disorder. 

<img width="762" alt="Screen Shot 2022-03-09 at 3 24 05 PM" src="https://user-images.githubusercontent.com/71660299/157529616-b406bbe0-db52-4a8d-90f9-808f3cabde24.png">


## References
Song H, Fang F, Tomasson G, et al. Association of Stress-Related Disorders With Subsequent Autoimmune Disease. JAMA. 2018;319(23):2388-2400. doi:10.1001/jama.2018.7028

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
