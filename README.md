# AlgoTading
Hi Everyone,

This repo ideally works for kotak stock trader api users, to integrate with any other platform, one should have
minimal experience to incorparate code changes  wrt to interesed trading broker 

Before start running the main file "nt.py", make sure that you are meeting below requirements.

1. kindly make sure enter all the credinitals, token, specified in the creds.json file

2. Enter the holiday list in holiday_finder function in the "nt_aft.py" 

3. This scripts works for only Banknifty token, inorder work for other indices, token symbol and token
needs to be updated across various places in the python files

4. Current framework may not work as it is, there might some compatibility issues with some packages, make
sure it is free from my any kind of issues

5. In the file name called 'tbs_rules.xlsx", there are six columns mentioned below,
Day: (it can be any day b/w monday to friday)
Depth: (0=atm straddle, 100=otm strangle, -100 = itm_strangle, '-' indicates itm and no sign indicates otm)
Entry/exit-time : Time should be b/w (9:15 to 3:30)
quantity = should be a multiplier of quantity
sl = should in percentage
kindly refer to the sample file 'tbs_rules.xlsx" to add/update your parameteres and make sure to follow the sample format

6. For the current framework, Trailing sl, wait and entry, hedges are not implemented but it can be incorporated

7. Cns folder contains (todays scripts list with date as file name), logs folder contains logs of today algo flow

8. IF any issues/bugs in existing code flow or functionality feel free to rise the issues, i'll try to resolve at earliest possible time

9. Make sure to install all the dependencies and also broker packages

10. Once all the prerequisites are met, make sure to run the main file 'nt.py' and <<<<<Boom>>>


note: Kindly use this code at your own risk, I'm not responsible for any kind of execution issues, gains/loses or for you mental trauma!!!

Cheers <3 <3 <3
