# Python-Proramming
Learn Python 

sd=[]
for i in data:
    if i["Manufacturer"]=="Acura" and i["Model"]=="Integra":
        sd.append("1")
    else:
        sd.append("0")
        
data["sd"]=sd
