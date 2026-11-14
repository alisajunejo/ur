raw.isna().sum()
# date 0, item 0, city 0, price 0, unit 0, data_label 0It says 0 missing.
raw.duplicated()
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
Name / team: alisa junejo   Week: 2

Snapshot commit code (made before any AI use): __________

AI roles used this week (coach / reviewer / classmate / examiner / persona / proxy / none): coach

Late? (true) No   ☐ Yes, I used a grace token (tokens left: __)
Self-check (tick when true)
(true) 1_attempt.md holds my own predictions or draft, made before AI.
(true) Every number I kept from AI, I recalculated or checked (see log).
(true) I opened every source link the AI gave me.
(true) My reflection says something specific.
(true) I shared no personal, confidential or restricted data with an AI tool.