# SelfYourStuff
Background
A fictional website ‘sell-your-stuff.com’ allows clients to buy and sell items that are not being used
anymore (chairs, laptops, books, etc.). Some of the clients make their living by buying products
refurbishing and then reselling It. But most are only interested in selling things they don’t use
anymore or buying cheap stuff.
The process is quite simple, a client creates an account (choosing one of the possible account
types, each account type follows specific rules and legislations for different types of products and
countries). One client can have only one account.
After account creation clients need to deposit money to buy/sell products, as the website itself
works as a broker and guarantees that both clients will be satisfied.
Internally the company keeps information of every product bought and sold splitting them into
categories and socioeconomic factors. This data is then sold to third parties following data
protection legislations (no personal information is disclosed). As a rule of thumb, the company
sells the data by roughly 1% of the total clients have bought. (e.g. a client that buys US$ 100.00
worth of products will generate US$ 1.00 to the company ).
As the information contained on these tables can reach terabytes, summary tables were created
in order to help data analysts and managers to take decisions regarding marketing strategies and
resources allocation. The most used tables are:
● client: Basic anonymized information about clients and client’s account.
● transactions: Summary of transactions amounts of each account aggregated daily.
● campaigns: High level description of past marketing campaigns, dates and budget.

- A complete description of the columns can be found on Appendix 1.
- The SQLite3 database (company.db) attached contains a sample of the data for the
summary tables and should be used to answer the following question:

The management of sell-your-stuff.com wants to set up marketing strategies for the next fiscal year based on the summary tables. Your job is to analyse the performance of past campaigns, coupons, profit by countries, etc. and make a report showing information to support your insights.
