import pandas as pd

data = {
    "Name": ["Alice", "Bob", "Charlie", "David"],
    "Age": [27, 22, 23, 24],
    "Dept": ["HR", "Finance", "IT", "Marketing"],
    "Salary": [50000, 60000, 55000, 65000]
}
df1 = pd.DataFrame(data)

print("Employee Data Frame:")
print(df1)

print("\nEmployee Names:")
print(df1["Name"])

df2 = pd.read_csv(r"C:\Users\Shaeera Shadha\Downloads\student-dataset.csv")
print("\nStudent Data Frame:")
print(df2)

print("\nStudent Names:")
print(df2["name"])

print("\nStudent Nationalities:")
print(df2["nationality"])

print("\nRows from index 10 to 14:")
print(df2.iloc[1:3])

print("\nFirst 3 Rows:")
print(df2.head(3))

print("\nLast 5 Rows:")
print(df2.tail())

print("\nDataset Info:")
df2.info()  

print("\nDataset Description:")
print(df2.describe())

print("\nMinimum Language Grade:", df2["language.grade"].min())
print("Maximum English Grade:", df2["english.grade"].max())
print("Average English Grade:", df2["english.grade"].mean())
print("Total Math Grade:", df2["math.grade"].sum())

