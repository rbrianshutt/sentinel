<h1>Deploying Microsoft Sentinel and configuring security connectors</h1>

Pull up Microsoft Sentinel, go to Configuration -> Watchlist  <br/>
Click New to create a new Watchlist <br/>

![](https://github.com/rbrianshutt/azure_honeypot_live_cyber_attack/blob/main/SOC%20Lab/4.1%20sentinel%2C%20configuration-%20watchlist%2C%20create%20new.png)
<br />

Enter geoip for Name and geoip for Alias<br/>
Click Next: Source <br/>

![](https://github.com/rbrianshutt/azure_honeypot_live_cyber_attack/blob/main/SOC%20Lab/4.2%20name%20geoip%2C%20alias%20geoip.png)
<br />

Set source type to local file<br/>
Upload the geo-ip summazied.csv file (provided by Josh Madakor) <br/>
Set searchkey to network<br/>
Click review and create  <br/>

![](https://github.com/rbrianshutt/azure_honeypot_live_cyber_attack/blob/main/SOC%20Lab/4.3%20source%20type-local%20file%2C%20upload%20file%2C%20searchkey-network%2C%20review%20and%20create.png)
<br />

Click Create under Review and create  <br/>

![](https://github.com/rbrianshutt/azure_honeypot_live_cyber_attack/blob/main/SOC%20Lab/4.4%20create%20watchlist.png)
<br />

Our watchlist created <br/>

![](https://github.com/rbrianshutt/azure_honeypot_live_cyber_attack/blob/main/SOC%20Lab/4.5%20watchlist%20created%20.png)
<br />
