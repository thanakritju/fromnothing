# fromnothing
List of projects for learning using [python](https://www.python.org/).

## Assignment 1

### objectives
- learn about **json** using python standard library called [json](https://docs.python.org/3/library/json.html)
- learn simple http protocol using [requests](https://2.python-requests.org/en/master/)

### project
create a command line program using python that reports 7 days weather of a provided province name by using [API](https://data.tmd.go.th/api/index1.php) from Thailand Meteorological Department.
```
python main.py
Please input a province: Chiang Rai
Date 29/5/2019 maximum temperature is 35 celcius minimum temperature is 25 celcius.
Date 30/5/2019 maximum temperature is 34 celcius minimum temperature is 24 celcius.
...
```
1. You need to read [WeatherForecast7Days](https://data.tmd.go.th/api/doc/reference/WeatherForecast7Days.pdf) api document and try to get data based on its api specs (**hint**: it provides two formats, xml and json try to use json).
2. Use python [requests](https://2.python-requests.org/en/master/) to get json data from url got from reading document.
3. Use python [json](https://docs.python.org/3/library/json.html) to parse data into python dictionary.
4. Understand data sturcture of the api response by reading document.
5. Get a province from user and response by telling maximum and minimum temperature for the next 7 days. 