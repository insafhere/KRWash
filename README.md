# KRWash

**KRWash Telegram Bot**

<img src="https://user-images.githubusercontent.com/84378807/139176869-05353a02-45ec-4a49-a0c4-3324a2a90540.png" width=25% height=25%>

Check status of your hall washing machines with simple commands on Telegram.

We used photoresistors to detect light on washing machine to check if it is in operating (ON) or non-operating mode (OFF). Our washing machine does not vibrate significantly for us to use vibration sensors, hence we used Photoresistors to detect light on the Washing Machine instead.

**Circuit Setup**

<img src="https://user-images.githubusercontent.com/84378807/139177801-e923c506-7900-41a5-a0ec-196ee645a42f.jpg" width=50% height=50%>

Arduino will be connected to Telegram using a WIFI Module, ESP8266. After collecting information from sensors, it will be sent to a telegram bot in which users will be able to check the status of their block's washing machine anytime, anywhere.

To learn more about the circuit, head over to https://github.com/insafhere/NodeMCUmultiplexer

