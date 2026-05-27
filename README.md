# weather

import requests

city = "London"
api_key = "YOUR_API_KEY"
url = f"https://api.openweathermap.org/data/2.5/weather?q={city}&appid={api_key}"

response = requests.get(url)
print(response.json())
