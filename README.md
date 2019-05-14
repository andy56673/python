# python
第三章練習題
第一題
rain = input("今天會下雨嗎?")
if(rain=="Y" or rain=="y"):
    print("出門記得帶傘!") 
第二題
n = int(input("請輸入正整數："))
if((n % 2)==0):
    print(n, "為偶數!") 
else:
    print(n, "為奇數!")     
第三題
month = int(input("請輸入月份："))
if (month>=1 and month<=3):
    print(month,"月是春天!")    
elif (month>=4 and month<=6):
    print(month,"月是夏天!")
elif (month>=7 and month<=9):
    print(month,"月是秋天!")
elif (month>=10 and month<=12):
    print(month,"月是冬天!")
else:
    print(month,"月份不在範圍內!")    
第四題
income = int(input("請輸入今年收入淨額："))
print("付稅金額：",end="")
if(income >= 2000000):
    print(income*0.3, end=" 元\n")  
elif(income >= 1000000):
    print(income*0.21, end=" 元\n")
elif(income >= 600000):
    print(income * 0.13, end=" 元\n") 
elif(income >= 300000):
    print(income * 0.06, end=" 元\n") 
else:
    print(income *0, end=" 元\n")
