# 🌤️ weather

Command Line Weather Information Tool with wttr API

![Weather](./static/weather_image.jpg)

## 📦 Install

```bash
dir=`$pwd` && cd /tmp && wget https://github.com/KooshaYeganeh/weather/archive/refs/heads/main.zip && unzip main.zip && cd weather-main && sudo cp weather /usr/bin && cd ..&& sudo rm -rf weather-main && echo "weather Installed Successfully [ OK ]" && cd $dir
```

or

```bash
wget https://github.com/KooshaYeganeh/weather/archive/refs/heads/main.zip && unzip main.zip && cd weather-main && sudo rpm -ivh weather-0.0.1-1.noarch.rpm
```

## 🌐 Use

```bash
weather <city name>
```

**Example:**

```bash
weather tabriz
```

## 🗑️ Remove

```bash
sudo rm /usr/bin/weather && echo "weather Removed Successfully [ OK ]"
```


