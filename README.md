# CD-HIT-parser
This repo is to help parse the info in the CD-HIT results (e.g., output.fasta.clstr)

## Usage

### 1. Download the CD-HIT-parser.py script
```
wget https://github.com/Loci-Tran/CD-HIT-parser.git
```

### 2. Run the script
```python
clstr_file = 'c30_uniprot_output.fasta.clstr'
clstr = cdhit_parser(clstr_file, output_file='cdhit_parsed.csv')

import pandas as pd
df = pd.read_csv('cdhit_parsed.csv')
df = df.sort_values(by=['n_members'], ascending=False)
df, clstr
```

```
      cluster_no rep_member  rep_member_length  \
1423        1423     Q9Y337                293   
705          705     P50281                582   
246          246     P29323               1055   
1347        1347     P51857                326   
1231        1231     P10321                366   

                                              member_ID  \
1423  Q9Y337,O43240,P49863,P06870,P07288,P20151,O602...   
705   P50281,O60882,P08254,P09238,P45452,P39900,P039...   
246   P29323,P54756,P29322,Q15375,P54760,P54764,P547...   
1347  P51857,P14550,P17516,P42330,P52895,Q04828,O602...   
1231  P10321,P04439,P01889,P13747,Q30201,P30511,Q954...   

                                    member_length  \
1423  293,276,264,262,261,261,260,254,247,247,244   
705           582,483,477,476,471,470,469,467,267   
246        1055,1037,1005,998,987,986,984,983,976   
1347              326,325,323,323,323,323,316,316   
1231              366,365,362,358,348,346,341,298   

                                      member_similarity  n_members  
1423  100,33.33,30.68,34.35,37.54,37.16,42.69,50.39,...         11  
705    100,34.57,34.8,35.08,37.15,37.44,37.1,35.54,38.2          9  
246   100,54.58,50.54,56.91,54.91,58.31,72.25,55.84,...          9  
1347      100,44.61,56.03,54.79,57.27,57.27,50.94,50.31          8  
1231      100,72.05,75.13,64.52,30.74,71.38,34.01,32.88          8  
```