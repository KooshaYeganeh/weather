# weather

command Line weather Information tool with wttr API


## Install

```
dir=`$pwd` && cd /tmp && wget https://github.com/KooshaYeganeh/weather/archive/refs/heads/main.zip && unzip main.zip && cd weather-main && sudo cp weather /usr/bin && cd ..&& sudo rm -rf weather-main && echo "weather Installed Successfully [ OK ]" && cd $dir
```

or

```
wget https://github.com/KooshaYeganeh/weather/archive/refs/heads/main.zip && unzip main.zip && cd weather-main && sudo rpm -ivh weather-0.0.1-1.noarch.rpm
```



## use

*weather < city name >*


Example : 

```
weather tabriz
```


## Remove

```
sudo rm /usr/bin/weather && echo "weather Removed Successfully [ OK ]"
```


