1- vegeta attack -targets=targets.txt -duration=5s -rate=10 -connections=10 | vegeta encode > results.bin

2- vegeta attack -targets=targets.txt -duration=5s -rate=10 -connections=10 | vegeta encode > results.json

3- vegeta attack -targets=targets.txt -duration=5s -rate=10 -connections=10 | vegeta encode > results.gob

4- vegeta plot results.bin > plot.html