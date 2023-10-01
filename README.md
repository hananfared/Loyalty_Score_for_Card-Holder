# Loyalty_Score_for_Card-Holder

> The data is a bank card transaction and user (card) loyalty analysis dataset
provided by a bank in Brazil. This assignment aims to practice on topics covered
in lectures 1-3, i.e., data quality analysis, statistical analysis, and regression
analysis given the dataset. The overall purpose of the analysis is to predict a
loyalty score for each card id represented in userscore.csv.
The dataset contains four files.
userscore.csv contain card ids and information about the card itself - the
first month the card was active. It also contains the predict/analysis target,
i.e., score, which is a score calculated by the bank, indicating the loyalty of
each card owner. Three features are provided, all of which are anonymized card
categorical features.
merchants.csv contains aggregate information for each merchant id represented in the data set. merchants can be joined with the transaction sets to
provide additional merchant-level information.
The historical transactions.csv and new merchant transactions.csv files contain information about each card’s transactions. historical transactions.csv contains up to 3 months’ worth of transactions for every card at any of the provided
merchant ids. new merchant transactions.csv contains the transactions at new
merchants (merchant ids that this particular card id has not yet visited) over
two months.
1
historical transactions.csv and new merchant transactions.csv are designed
to be joined with userscore.csv and merchants.csv. They contain information
about transactions for each card, as described above.
Given the dataset, answer the following questions. Your submission will be
judged based on your answer’s relevance and your regression model’s performa
