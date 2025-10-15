# studious-succotash
Data Analysis on Titanic Dataset using Python and Pandas

Input
# import library
import pandas as pd

# google drive file share url
url='https://drive.google.com/file/d/1UboBE3XwSg3NEED6OaoPqhqtFC0duoz-/view?usp=sharing'

# modify google drive url for pandas read function
url='https://drive.google.com/uc?id=' + url.split('/')[-2]

# read CSV file into pandas dataframe
df = pd.read_csv(url)

# display first 5 rows
df.head()

Output:
pclass
survived
name
sex
age
sibsp
parch
ticket
fare
cabin
embarked
boat
body
home.dest
1
1
Allen, Miss. Elisabeth Walton
female
29.0
0
0
24160
211.3375
B5
S
2


St Louis, MO
1
1
Allison, Master. Hudson Trevor
male
0.92
1
2
113781
151.55
C22 C26
S
11


Montreal, PQ / Chesterville, ON
1
0
Allison, Miss. Helen Loraine
female
2.0
1
2
113781
151.55
C22 C26
S




Montreal, PQ / Chesterville, ON
1
0
Allison, Mr. Hudson Joshua Creighton
male
30.0
1
2
113781
151.55
C22 C26
S


135.0
Montreal, PQ / Chesterville, ON
1
0
Allison, Mrs. Hudson J C (Bessie Waldo Daniels)
female
25.0
1
2
113781
151.55
C22 C26
S




Montreal, PQ / Chesterville, ON


