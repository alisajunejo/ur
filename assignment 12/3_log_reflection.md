pythonraw.isna().sum()
# date 0, item 0, city 0, price 0, unit 0, data_label 0It says 0 missing.
Pic 2 + 3:pythonraw.duplicated()
# 0 to 95 = False, 96 = True, Length: 97

raw.info()
# RangeIndex: 97 entries, 0 to 96
# date        97 non-null  str
# item        97 non-null  str
# city        97 non-null  str
# price       96 non-null  str   <- ONLY 96, NOT 97
# unit        97 non-null  str
# data_label  97 non-null  str
# dtypes: str(6)