# elt

Group: business_up_top

Proposal: ETL on Order Sales Data and Dow Jones Industrial Average

Transformation Type: (see below)
Data Base Type: Relational
Why This: Impact of the stock market on sales orders

Extract: your original data sources and how the data was formatted (CSV, JSON, pgAdmin 4, etc).
Data Source: Kaggle (but 2 different sources)
Data Format: .CSV

Transform: what data cleaning or transformation was required.
1. Read in both CSV files into JN
2. Converted all date(s) in both files to Pandas DateTime for consistentcy 
3. Dropped unnesscary columns
4. Set up schema in pgAdmin
5. Renamed column heads due to reserved SQL words

Load: the final database, tables/collections, and why this was chosen.

