date_input=input("Enter Date in Format DD/MM/YYYY: ")
a=date_input[-2:]
y=int(a)
x=int(a)/4
leapyear=int(a) % 4
que=int(x)
date=int(date_input[:2])

month=int(date_input[3:5])
year=int(date_input[6:10])

if leapyear==0:
    if month==1:
        code=6
    if month ==2:
        code=2
else:
    if month==1:
        code=0
    if month ==2:
        code=3


if month==3:
    code=3
if month==4:
    code=6
if month==5:
    code=1
if month==6:
    code=4
if month==7:
    code=6
if month==8:
    code=2
if month== 9:
    code=9
if month==10:
    code=0
if month==11:
    code=3
if month==12:
    code=5

if year>=1600 and year<=1699:
    year_code=6
if year>=1700 and year<=1799:
    year_code=4
if year>=1800 and year<=1899:
    year_code=2
if year>=1900 and year<=1999:
    year_code=0
if year>=2000 and year<=2099:
    year_code=6

total=year_code+code+date+que+y
day=total % 7

if day==0:
    print( "Sunday")
if day==1:
    print( "Monday")
if day==2:
    print( "Tuesday")
if day==3:
    print( "Wednesday")
if day==4:
    print( "Thursday")
if day==5:
    print( "Friday")
if day==6:
    print( "Saturday")
