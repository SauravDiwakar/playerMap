# playerMap
1. READ CSV FILE 

1.1. write the following code in google collab and hit run - 
'
from google.collab import files 
uploaded = files.upload()
'
the above code will ask you to choose file from your local drive to uplaod on the google drive.

1.2. After the above task, write the following code to import it into pandas - 
'
import pandas as pd 
import io 

df = pd.read_csv(io.BytesIO(uploaded['file.csv']))
print(df)
'
