# seasons-greetings2021





#a seasons greetings message you can edit it to serve your purpose!
#!/usr/bin/env python3
# -*- coding: utf-8 -*-
"""
A New year Felicitation Program
Created on Thu Dec 31 23:54:07 2020
robotekworkspace@gmail.com
robotekzero.business.site
@author: techgod
"""
#needed module for current date and time
import datetime
#data variables
hallmark="..we re-invent the wheel"
message="Happy New Year Folks"
of="From RoboTek"
new_year=2021
old_year=2020
scope={1:"Artificial Intelligence",2:"Cryptanalysis",
	   3:"Research and Development",4:"Fabrication" ,
	   5:"Computing Technology",6:"UAV"}
print("*"*14)
#say goodbye to past year
if new_year:
	print("Good Bye:",old_year)
print("*"*14)
#converse with new year
if old_year<2021:
	print("Hello :",new_year)
print("*"*13)
#felicitations,with date,time, asterisks after new line,then scope &hallmark,asterisks
print(message,of,"\n","*"*34)
print("Its",datetime.date.today(),"*"*20)
print(scope[1],scope[2],scope[3],scope[4],scope[6],sep="|")
print("*"*79,"\n",hallmark,"*"*53)

