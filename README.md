{::comment}
***
  - SCRIPT: **FaceBoom**
  -    JOB: **Brute Force Attack On Facebook Accounts**
***

- **SCRIPT ScreeenShot**:

    - **Usage**:
    
      ![Options](https://user-images.githubusercontent.com/29546157/88088705-862dc900-cb93-11ea-8e9d-900c7fee0575.PNG)


    - **Brute Force On Facebook Account Without proxy**:
     
     * **Command**: python faceboom.py -t Oseid@gmail.com -w wlist.txt
     
         ![withoutProxy](https://user-images.githubusercontent.com/29546157/88088721-8af27d00-cb93-11ea-828c-b80f1996a234.PNG)
   
   - **Brute Force On Facebook Account With Proxy**:
   
    * **Command**: python faceboom.py -t Oseid@gmail.com -w wlist.txt -p 144.217.101.245:3129
    
         ![withProxy](https://user-images.githubusercontent.com/29546157/88088728-8f1e9a80-cb93-11ea-964e-930aeea10dcd.PNG)

   - **Get Target Facebook Profile ID**:
   
    * **Command**: python faceboom.py -g https://www.facebook.com/zuck
    
         ![getID](https://user-images.githubusercontent.com/29546157/88082079-f9cad880-cb89-11ea-894b-801e8c4fe369.PNG)

***

# For Install:

 - git clone https://github.com/Oseid/FaceBoom.git
 - cd FaceBoom/
 - pip install requests
 - pip install mechanize
***

# Supported Platforms:
- [x] Windows
- [x] Linux
- [x] Android~**Termux**
- [x] MacOs
- [x] **any Os has python(2.x, 3.x) with required modules**


# Protect yourself from this attack:
  * Use Strong Password which contains {letters(lower,upper),tokens,numbers} make it longest as possible, at least 10 letters
  * don't use your basic information in the password for example don't use your name or birthday\
        because the hacker can do a information gathering attack and get this information easily\
        then he will generate a wordlist based on this info.
  * Use 2F Authentication.
  
# Warning:
  * this script is only for educational purposes
  * i am not responsible for your actions.

# That's All :)
   * This Script Coded By Oseid Aldary
   * Thanks For Usage
   * Have A Nice Day...GoodBye :)
{:/comment}
#This script is no longer work
