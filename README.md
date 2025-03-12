for a in range(1,10): #取a的范围
    for b in range(1,a+1): #取b的范围
        result = a*b
        print(f"{b}*{a}={result}\t",end="") #end=""表示打印完不换行
    print()
    
