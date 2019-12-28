# My conky configuration

update the weather.py with your own api key and city id
API_KEY="YOUR_API_KEY"
CITY_ID=YOUR_CITY_ID

You can get your API key from [Openweathermap](https://home.openweathermap.org/api_keys).

Also your city ID is in a URL like this : `https://openweathermap.org/city/2643743`, Search for your city and get that ID.

## Requirements

- Conky
- Python > 3.6
- Openweathermap free account

## Installing

```bash
cd ~/.config/

git clone https://github.com/The-afroman/conky_files.git

cd conky_config/

pip3 install --user -r requirements.txt

conky -c system.conf && conky -c weather.conf

make sure to create ~/.conky & ~/.conky/data directories if they do not already exist
```
