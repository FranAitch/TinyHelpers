# AC-FreeC
Auto reminder for when you should close the window in the summer when you've got no AC.

The script helps you to cool down your appartment in the summer when you've got no automatic air conditioning system. You open the windows in the morning when it's (hopefully) still a bit cooler. The script then compares outside temperature to an indoor temperature provided by you that shouldn't be exceeded. It messages you when either the outside temperature reaches the critical level or when other factors (e.g. rain) may force you to close the windows. 

## How to Use
1. install the dependencies:
```pip install -r requirements.txt```

2. Set up accounts with *twilio* and *OpenWeatherMap*

3. Add your information to "textmyself.py" (twilio) and "acfreec.py" (OpenWeatherMap)

4. For this to be useful, you might want to set up the script in a way that it runs automatically every half hour or so.

If you don't know how to do the latter, no worries. You can check <a href="https://automatetheboringstuff.com/schedulers.html" target="_blank" />here</a> for tutorials (there are no links, google the titles). *Or* you can just use the "in-script scheduler". That means, you execute the script and it keeps running until you manually tell it to stop (hopefully when you got your "close the windows!" reminder) by causing a KeyboardInterrupt error. You cause a KeyboardInterrupt error by pressing the keys ctrl + c.


# 
*__Please Note__: my free trial account expired, so I can't test this anymore for the time being.*
