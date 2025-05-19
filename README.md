# This code is taken entirely from 7given

In gameInformation.py :     
```
with open("info/tips.txt", "w", encoding="utf8") as f:
        for tip in Tips.tips[0].tips:
            f.write(tip)
            f.write("\n")
```
The number 0 in Tips.tips[0] can be replaced with 1 (another CN language), 2 (EN), 3 (JP) and 4(KR)

# Step-by-step how to export game (in visual studio): #
1. Add apk to the same folder as gameInformation.py and typetree.json
2. Run this command in terminal: *pip install UnityPy==1.10.18*
3. Run this command in terminal: *python gameInformation.py Phigros.apk*
   **Phigros.apk** is the name of apk file
