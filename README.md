# DNA Stutter-errors Clustering 
The algorithm developed by Omer Yerushalmi, Nadav Falicovich and supervised by Dvir Ben Shabat, Gadi Chaykin, Eitan Yaakobi 
from the Technion Israel Institute of Technology, to enable high accuracy rate of clustering DNA strands under the stutter synthesis error noise.

## Background
### Stutter noise (add mathematical defintion && example ACCTG -> AAACCCGG)

### clustering dna strands (add graph from eitans presentation)
graph before cluster ->(our algorithm) graph after clustering

## Implementation
### metrics 
links for distances function (levenstein function)
### parallelism
using pythons multiprocessing library.
הדאטא מחולק באופן שווה בין תהליכים שונים שרצים במקביל ויוצרים קלאסטרינג מהמידע שברשותם
לאחר סיום הריצה של כל התהליכים, נבצע איחוד של כל שתי תוצאות מתהליכים שונים. באמצעות תור משותף, תהליכים ירוצו במקביל וישלפו זוגות של סטים של קלאסטרים, יאחדו, ויחזירו אותם לתור. התהליך יסתיים כשהתור יתרוקן.
.
## Usage (add code examples)
### Create Dataset

### Run stutter clustering

### examin results

## Dependencies
can be seen in requirments.txt
