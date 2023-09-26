# Calculation-of-the-user-s-birth-year
import datetime
now = datetime.datetime.today()
age = int(input("Enter age: "))
a = int(now.year)
year = a - age
print("your year of birth: {}".format(year))
