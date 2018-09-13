# pandas-data-Preprocessing
pandas-data Preprocessing


#one step data import
dataset = pd.read_csv('r4.2/big-dataset.csv',
usecols=['activity','date','pc', 'user','day','time','user_id',
'user_role','user_functional_unit','user_department','insider'],
dtype={'activity':int, 'pc':int, 'day':int,'time':float,'user_id':int,'user_role':int,'user_functional_unit':float,
'user_department':float,'insider':int}
)
