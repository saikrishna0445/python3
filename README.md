# python3
calendar first and last date
import calendar
from datetime import date
year = 2025
month=5
fday=date(year,month,1)
lday=date(year,month,calendar.monthrange(year,month)[1])
print("firstday:",fday.strftime("%A,%Y-%M-%D"))
print("lastday:",lday.strftime("%A,%Y-%M-%D"))
