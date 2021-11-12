# Ask01
New Repo
import pandas as pd 
url = 'http://apmonitor.com/pdc/uploads/Main/tclab_data2.txt'
data = pd.read_csv(url)
data.to_csv('file.csv')
