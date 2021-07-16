# pattern-based-clustering
This repository contains results for the proposal described in "Pattern-based string alignment and clustering" by author1, author2 & author3.  

Results have been improved since the submission of the paper.


Current accuracy results:  

|OpenSSH  |                       | NP    |UP    |EP   |
|---------|-----------------------|-------|------|-----|
|         |  Pattern accuracy     |0.21   | 0.62 |0.93 |
|         |  Ajusted Rand index   |0.78   | 0.98 |0.996|

(NP: no prior, character based; UP: universal patterns; EP: extended patterns)


New experiment for infocom submission:
|OpenSSH  |                       |       |      |     |Zookeeper     |       |      |     |Andriod     |       |      |     |Apache     |       |      |     |
|---------|-----------------------|-------|------|-----|--------------|-------|------|-----|------------|-------|------|-----|-----------|-------|------|-----|
|         |                       | NP    |UP    |EP   |              | NP    |UP    |EP   |            | NP    |UP    |EP   |           | NP    |UP    |EP   |
|---------|-----------------------|-------|------|-----|--------------|-------|------|-----|------------|-------|------|-----|-----------|-------|------|-----|
|         |  Pattern accuracy     |0.21   | 0.62 |0.93 |              |       |0.916 |     |            |       |0.672 |     |           |       |1     |     |
|         |  Ajusted Rand index   |0.78   | 0.98 |0.996|              |       |0.998 |     |            |       |0.931 |     |           |       |1     |     |
