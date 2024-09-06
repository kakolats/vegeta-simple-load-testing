1- vegeta attack -targets=targets.txt -duration=10s -rate=10 -connections=100 | vegeta encode > results.bin

2- vegeta attack -targets=targets.txt -duration=10s -rate=10 -connections=100 | vegeta encode > results.json

3- vegeta plot results.bin > plot.html