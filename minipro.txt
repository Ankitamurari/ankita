name=(input("enter your name:"))
classname=(input("enter your class :"))
section=(input("enter section:"))
schoolname=(input("enter your schoolname:"))
classteachername=(input("enter your class teacher name:"))
date=(input("enter the date:"))
sub=(input("enter subject:"))
dateofleave=(input("enter date of leave:"))
reason=(input("enter reason:"))
address=(input("enter your address:"))

newstring =f'''To {classteachername} ,
{schoolname}
{address}

{date}

{sub}

Dear sir,

{reason}

Thanking you.

Yours obediently.
{name}
{section}



'''
print(newstring)