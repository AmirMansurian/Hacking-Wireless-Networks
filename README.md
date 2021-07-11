# Hacking-Wireless-Networks
#### Hacking Wireless Networks via Evil Twin Attack

This is Wi-Fi Hacking using Airgeddon Wireless network Attacker Framework. before doing attack you need some Prerequisites :

## Prerequisites

- Kali Linux or another supported distributions . (I have used Ubuntu 16.04)
check for supported distributions here: [Airgeddon GitHub](https://github.com/v1s1t0r1sh3r3/airgeddon)

- a wireless network adaptor

- Airgeddon Framework



for this you need first install **ccze** tool :

```sh
apt-get install ccze
```

and then clone airgeddon project  :

```sh
git clone https://github.com/v1s1t0r1sh3r3/airgeddon.git
cd airgeddon/
sudo bash ./airgeddon.sh
```

## Attack Scenario

In this attack first we change our wireless network adaptor mode to **monitor** mode to eavesdrop the network traffic and then find wireless networks aroud us with connected clients. using airgeddon and Evil Twin attack menu we kick victims off from their trusted network by frequently sending **de-authentication** packets and then wait for victim to connect to fake network with similar name with actual network access point that we have created then using social engineering create **phishing** page that appears on victim device that wants victim to re-enter password. Scenario of attack is like image below :


![Alt Text](https://github.com/AmirMansurian/Hacking-Wireless-Networks/blob/main/Scenario.png)

##### Slides of this attack and complete explanation and step by step performing this attack are available at Presentation and Report file.
