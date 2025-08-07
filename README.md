# Weather Forecasting

A Python-based weather forecasting application that fetches real-time weather data and presents forecasts in a user-friendly manner.

## Features

- Fetches real-time weather data using a public API.
- Displays current weather conditions (temperature, humidity, wind speed, etc.).
- Supports weather forecasts for multiple locations.
- User-friendly command-line interface (CLI).
- Error handling for invalid locations or API failures.
- Extendable for more features (visualization, history, etc.).

## Requirements

- Python 3.7 or higher
- `requests` library
- (Optional) `matplotlib` for visualization

Install dependencies using pip:

```bash
pip install -r requirements.txt
```

## How to Run

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Rishika03-03/Weather_Forecasting.git
   cd Weather_Forecasting
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application:**

   ```bash
   python g.py
   ```

   Follow the on-screen instructions to enter a city or location and receive the weather forecast.

## Example Usage

```bash
$ python main.py
Enter the city name: London
Current temperature: 18°C
Humidity: 60%
Wind speed: 4 m/s
Forecast for next 3 days:
 - Day 1: 20°C / 12°C, Rain
 - Day 2: 22°C / 14°C, Cloudy
 - Day 3: 19°C / 10°C, Clear
```

## Future Enhancements

- Add graphical visualization of forecasts.
- Support for hourly forecasts.
- Save and compare weather history.
- Web-based interface.
