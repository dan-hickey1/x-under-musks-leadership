We show 3 files:

- Coordination.ipynb: how to replicate results on the frequency of coordinated accounts (also known as information operation drivers). We have some helper functions useful for other files, such as how to convert JSON to CSV, and how to find coordinated networks that will be used in Botometer.ipynb
- Botometer.ipynb: how to replicate results on the bot scores for each account. We plug all account IDs into https://botometer.osome.iu.edu/ and record these results. Because there was no API, we did this by hand. To ensure all results were correct, we made 2 passes for each account, and would rerun a 3rd time if there was a discrepancy between botometer results between pass 1 and 2
- Cashtags.ipynb: the frequncy of cashtags over time
