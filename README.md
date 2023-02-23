# MSO_E5_Dev_AutoRenew_Modified
This is a python program based on Git Actions modified to automatically generate development actions via Microsoft Graph API like a real developer in order to active Microsoft Office 365 E5 Developer Trail subscription auto renew.

# Notice
This repo may lead to unknown issues, problems, information leaks, etc. 

Use at your own risk.

The author DO NOT provide help or further assistance for personal reasons.

Please DO NOT open issues or PR over this project, I do not have enough time to respond due to personal reasons, thanks for understanding.

# Update
## 2023-02-24 0:36
GitAction skipp problem(https://github.com/zhtok/MSO_E5_Dev_AutoRenew_Modified/issues/4) fixed. (thanks for notifying)
- Nodejs version is incompatible with the code in ```main.py```. 
- Certain MS Graph APIs are updated with slightly changes.

Major changes are made:
- Remove ```main.py``` 
- New ```test.py```
- New ```autoTestApi.yml```
- Import ```random``` to generate the number of tests instead of fixed 10 times for each action.
- From ```ubuntu-latest``` to ```ubuntu-22.04```
- From ```actions/setup-python@v2``` to ```actions/setup-python@v4```
