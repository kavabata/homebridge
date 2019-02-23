
## GENERAL

> sudo apt-get install git

## redis
[git](https://github.com/cjus/hydra-cluster/wiki/Redis-on-a-Raspberry-Pi)

> sudo apt-get update
> sudo apt-get install redis-server
The redis configuration file is stored in /etc/redis.


## php



## INSTALL Homebridge
[git](https://github.com/nfarina/homebridge)



## INSTALL MQTT
[instructables](https://www.instructables.com/id/Installing-MQTT-BrokerMosquitto-on-Raspberry-Pi/)


> wget http://repo.mosquitto.org/debian/mosquitto-repo.gpg.key

> sudo apt-key add mosquitto-repo.gpg.key

Then make the repository available to apt

> cd /etc/apt/sources.list.d/

Enter the following

for wheezy

> sudo wget http://repo.mosquitto.org/debian/mosquitto-wheezy.list

for jessie

> sudo wget http://repo.mosquitto.org/debian/mosquitto-wheezy.list

### install

> sudo apt-get update
> sudo apt-get install mosquitto

### add client 

> sudo apt-get install mosquitto-clients

### test 
listen:
> mosquitto_sub -t test_topic

say:
> mosquitto_pub -t test_topic -m "ok"
> mosquitto_pub -t test_topic -m "wf"


## ESP MQTT
[habr](https://habr.com/ru/post/393277/)
[homes-smart](http://homes-smart.ru/index.php/oborudovanie/bez-provodov-wi-fi/62-besprovodnoj-datchik-na-baze-esp8266-dlya-servisa-narodmon-ru)

