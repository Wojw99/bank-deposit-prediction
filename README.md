# Bank telemarketing data analysis
Improvement of marketing campaign can product a bunch of different benefits, such as saving time of telemarketers and increasing satisfaction of clients. The goal of this analysis was to find key aspect of succesfull telemarketing campaign and implement and fine-tune a model to predict if the client of the bank will take a term deposit after telemarketer phone.

It's my study project for gaining new knowledge and polishing my skills. 

Dataset: https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset/data ...! 🤖 👽

### Conclusions
1. **Job Group**: Students and retirees more often opted for deposits compared to other job groups. Typically, they don't have outstanding debts, which is one of the primary reasons. Additionally, previous campaigns targeting these groups were also more successful. The bank should consider focusing on these demographics in the next campaign. 73% of the 291 students and 64% of retirees took deposits. 
2. **Obligations and Balance** - Clients with defaults, loans, or housing loans are significantly less likely to opt for deposits. On average, only 34% of clients with obligations took deposits. The bank should consider reducing telemarketing calls to these groups. Moreover, clients who opt for deposits, on average, maintain better account balances.
3. **Months** - Deposits were more frequently taken in the months of December, March, October, and September. More than 80% of contacted clients opted for deposits during these months. Interestingly, the number of calls made during these months was relatively low, with December having the lowest count. And December happened to be the most deposit-positive month (93%).
4. **Call Duration** - it is possible that a client who was considering making a deposit was more willing to talk longer and ask for details. It is also possible that the longer the conversation, the more willing the client is to make a deposit.
5. **Contact Count** - the highest the count of contact during campaign, the less willing the client is to make a deposit. Probably clients are slightly tired with multiple calls. Also, the median call duration is lower for subsequent calls. The bank should consider making limits for multiple calls to one client.

### Classification model
![image](https://github.com/Wojw99/bank-telemarketing-data-analysis/assets/42806302/b8ebc25f-0b46-442f-99f4-035b206f3a69)
- Tested models have performed quite well
- And conlusions after fine-tuning:
  - Standarization slightly improved the performance of all models
  - Hyperparameters tuning slightly improved the performance of XGB
  - Removing outliers slightly reduced the performance of decision tree based models and improved the performance of for ex. LinearSVC
  - Added features slighly reduced the performance of all models
