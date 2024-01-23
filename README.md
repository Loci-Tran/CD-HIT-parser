# CD-HIT-parser
This repo is to help parse the info in the CD-HIT results (e.g., output.fasta.clstr)

Synthesizing 8/10 solutions

=======
Suggestion 1


## Usage

### 1. Download the CD-HIT-parser.py script
```
wget https://raw.githubusercontent.com/zheminzhou/CD-HIT-parser/master/CD-HIT-parser.py
```

### 2. Run the script
```
python

=======
Suggestion 2

## Usage
```
python3 CD_HIT_parser.py -i input -o output
```
## Example
```
python3 CD_HIT_parser.py -i 1 -o 1
```
## Output
The output file will be a tab-delimited file with the following columns:
1. Cluster number
2. Cluster size
3. Representative sequence
4. Representative sequence length
5. Representative sequence description
6. Number of sequences in the cluster
7. Cluster members (sequence IDs)
8. Cluster members (sequence lengths)
9. Cluster members (sequence descriptions)
10. Cluster members (sequences)
## Reference

=======
Suggestion 3

## Usage
```bash
python CD-HIT-parser.py -i <input.clstr> -o <output.txt>
```
## Example
```bash
python CD-HIT-parser.py -i output.fasta.clstr -o output.txt
```
## Output
The output will be a tab-delimited file, containing the cluster ID, number of sequences in the cluster, and the cluster representative sequence.
## Note
This script is written in Python 3.6.1.

=======
Suggestion 4


## Usage
```
python CD_HIT_parser.py -i output.fasta.clstr -o output.txt
```

=======
Suggestion 5

## Usage
```
python CD-HIT-parser.py -i output.fasta.clstr -o output
```
## Output
- output.fasta.clstr.cluster
- output.fasta.clstr.no_singletons
- output.fasta.clstr.no_singletons.cluster
- output.fasta.clstr.no_singletons.singletons
- output.fasta.clstr.no_singletons.singletons.fasta
- output.fasta.clstr.no_singletons.cluster.count
- output.fasta.clstr.no_singletons.cluster.count.cluster
- output.fasta.clstr.no_singletons.cluster.count.cluster.count
- output.fasta.clstr.no_singletons.cluster.count.cluster.count.cluster
- output.fasta.clstr.no_singletons.cluster.count.cluster.count.cluster.count
- output.fasta.clstr.no_singletons.cluster.count.cluster.count.cluster.count.cluster
- output.fasta.clstr.no_singletons.cluster.count.cluster.count.cluster.count.cluster.count
- output.fasta.clstr.no_singletons.cluster.count.cluster.count.cluster.count.cluster.count.cluster
- output.fasta.clstr.no_singletons.cluster.count.cluster.count.cluster.count.cluster.count.cluster.count
- output.fasta.clstr.no_singletons.cluster.count.cluster.count.cluster.count.cluster.count.cluster.count.cluster
- output.fasta.clstr.no_singletons.cluster.count.cluster.count.cluster.count.cluster.count.cluster.count.cluster.count
- output.fasta.clstr.no_singletons.cluster.count.cluster.count.cluster.count.cluster.count.cluster.count.cluster.count.cluster
- output.fasta.clstr.no_singletons.cluster.count.cluster.count.cluster.count.cluster.count.cluster.count.cluster.count.cluster.cluster
- output.fasta.clstr.no_singletons.cluster.count.cluster.count.cluster.count.cluster.count.cluster.count.cluster.count.cluster.cluster.count
- output.fasta.clstr.no_singletons.cluster.count.cluster.count.cluster.count.cluster.count.cluster.count.cluster.count.cluster.cluster.count.cluster
- output.fasta.clstr.no_singletons.cluster.count.cluster.count.cluster.count.cluster.count.cluster.count.cluster.count.cluster.cluster.count.cluster.cluster
- output.fasta.clstr.no_singletons.cluster.count.cluster.count.cluster.count.cluster.count.cluster.count.cluster.count.cluster.cluster.count.cluster.cluster.cluster
- output.fasta.clstr.no_singletons.cluster.count.cluster.count.cluster.count.cluster.count.cluster.count.cluster.count.cluster.cluster.count.cluster.cluster.cluster.cluster
- output.fasta.clstr.no_singletons.cluster.count.cluster.count.cluster.count.cluster.count.cluster.count.cluster.count.cluster.cluster.count.cluster.cluster.cluster.cluster.cluster
- output.fasta.clstr.no_singletons.cluster.count.cluster.count.cluster.count.cluster.count.cluster.count.cluster.count.cluster.cluster.count.cluster.cluster.cluster.cluster.cluster.cluster
- output.fasta.clstr.no_singletons.cluster.count.cluster.count.cluster.count

=======
Suggestion 6


## Usage
```
python CD-HIT-parser.py -i <input> -o <output>
```
## Example
```
python CD-HIT-parser.py -i output.fasta.clstr -o output
```
## Output
```
output.cluster: cluster info
output.sequence: sequence info
output.cluster.sequence: cluster and sequence info
```

=======
Suggestion 7

## Usage
```bash
python parse_cd_hit.py -i output.fasta.clstr -o output.txt
```

## Output
The output file format is:
```
Cluster 1: 4 sequences
Cluster 2: 2 sequences
Cluster 3: 3 sequences
Cluster 4: 5 sequences
Cluster 5: 1 sequences
Cluster 6: 1 sequences
Cluster 7: 1 sequences
Cluster 8: 1 sequences
Cluster 9: 1 sequences
Cluster 10: 1 sequences
Cluster 11: 1 sequences
Cluster 12: 1 sequences
Cluster 13: 1 sequences
Cluster 14: 1 sequences
Cluster 15: 1 sequences
Cluster 16: 1 sequences
Cluster 17: 1 sequences
Cluster 18: 1 sequences
Cluster 19: 1 sequences
Cluster 20: 1 sequences
Cluster 21: 1 sequences
Cluster 22: 1 sequences
Cluster 23: 1 sequences
Cluster 24: 1 sequences
Cluster 25: 1 sequences
Cluster 26: 1 sequences
Cluster 27: 1 sequences
Cluster 28: 1 sequences
Cluster 29: 1 sequences
Cluster 30: 1 sequences
Cluster 31: 1 sequences
Cluster 32: 1 sequences
Cluster 33: 1 sequences
Cluster 34: 1 sequences
Cluster 35: 1 sequences
Cluster 36: 1 sequences
Cluster 37: 1 sequences
Cluster 38: 1 sequences
Cluster 39: 1 sequences
Cluster 40: 1 sequences
Cluster 41: 1 sequences
Cluster 42: 1 sequences
Cluster 43: 1 sequences
Cluster 44: 1 sequences
Cluster 45: 1 sequences
Cluster 46: 1 sequences
Cluster 47: 1 sequences
Cluster 48: 1 sequences
Cluster 49: 1 sequences
Cluster 50: 1 sequences
Cluster 51: 1 sequences
Cluster 52: 1 sequences
Cluster 53: 1 sequences
Cluster 54: 1 sequences
Cluster 55: 1 sequences
Cluster 56: 1 sequences
Cluster 57: 1 sequences
Cluster 58: 1 sequences

=======
Suggestion 8

```

## Usage
```
python CD_HIT_parser.py -i <input file> -o <output file> -t <threshold>
```
## Example
```
python CD_HIT_parser.py -i output.fasta.clstr -o output.txt -t 0.9
```
