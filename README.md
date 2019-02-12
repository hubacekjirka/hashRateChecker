# hashRateChecker
Mining pool hashrate checkert using Apache NiFi and Pandas

## NiFi
Periodically queries the mining pool's API to retrieve a JSON file. In the flow, is the file transformed to a CSV format and stored on the filesystem

## Pandas
So far exists a POC in Jupyter Notebook

Is supposed to load CSV files, calculate min, max, mean. If any deviation from expected value occurs, sends an email with metrics and plot chart.
