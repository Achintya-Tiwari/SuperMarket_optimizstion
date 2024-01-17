# SuperMarket_optimizstion
This Code demonstrates the normal working of an Apyori algorithm on market basket. This Algorithm is used to gain insights on cases like "people who liked this also liked" and strategize the advertising and placement of certaing items in a Super Market.
The code works on a dataset tha contains the data on what did customers chekout with from a Super Market. 
The model analyses and store the result in a pandas dataframe. The result shows the relation of various items with each other, this is quantized as support, confidence and lift.
Here Support means: refers to the frequency or proportion of transactions in a dataset that contain a particular itemset. For the Apriori algorithm, support is a crucial metric used to identify the significance of an itemset.
Confidence: confidence is a measure of the reliability or strength of a rule. Specifically, it refers to the probability that a rule holds true. For a given rule A → B (read as "A implies B"), where A is the antecedent and B is the consequent, confidence is calculated as the conditional probability of B given A.
Lift: "lift" is a measure that quantifies how much more likely a particular association rule is compared to random chance. It is used to assess the strength of a rule by comparing the observed support of the rule with the expected support under the assumption of independence.

This Repo also contains the code to a similar algorithm i.e. Eclat Algorithm on the same dataset.
