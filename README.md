# weather_report

COMPANY: CODETECH IT SOLUTIONS

NAME: SHARMI S

DURATION: 4 WEEKS

INTERN ID:CT04DF1577

DOMAIN: PYTHON

****This project focuses on the integration of a public API and the development of visual insights through data visualization using Python. The main objective is to fetch weather forecast data using the OpenWeatherMap API and present it in an easy-to-understand graphical format using libraries such as Matplotlib and Seaborn. This hands-on task strengthens understanding of API interaction, JSON data parsing, and real-time visualization – crucial skills in data analytics and software development.

To begin with, we used the OpenWeatherMap API, which provides weather forecasts and current conditions for cities around the world. Access to this API requires an API key, which the user can obtain by signing up on the OpenWeatherMap website. In our project, we used a specific key tied to the city of Chennai as an example, though the script is flexible and can be adapted to other cities by simply changing the city name in the code.

Once the API connection was established, the script sent a GET request to the OpenWeatherMap forecast endpoint, retrieving 5-day weather forecast data at 3-hour intervals. The returned data is in JSON format, containing nested information about temperature, humidity, weather conditions, timestamps, and more. The script parsed the JSON data and extracted the necessary components—specifically, the date-time and temperature for each forecast entry.

Using the datetime module, timestamps were converted into readable formats to enhance visualization. The temperature data was stored in parallel arrays corresponding to their respective times. This structured data was then used to create a line plot showing temperature trends over time.

For visualization, the project employed Seaborn, a Python visualization library based on Matplotlib. Seaborn provides a high-level interface for drawing attractive and informative statistical graphics. A line plot was created with temperature on the Y-axis and date/time on the X-axis. Additional formatting like grid lines, marker points, title, axis labels, and rotation of date labels were applied to improve clarity and aesthetics.

The resulting graph gives an insightful representation of temperature fluctuations in Chennai over five days, updated every three hours. This enables users to anticipate weather patterns and plan accordingly. The code is modular and can be expanded to include other parameters like humidity, wind speed, or pressure, and can even be turned into an interactive dashboard using frameworks like Streamlit or Dash.

In conclusion, this project demonstrates a practical implementation of API integration and real-time data visualization. It combines programming skills with data analysis to deliver meaningful insights from external data sources. The ability to pull data from APIs and visualize it effectively is a fundamental skill in fields such as data science, meteorology, logistics, and more. By completing this task, the intern not only becomes proficient in handling REST APIs but also gains experience in translating raw data into visual formats that support interpretation and decision-making. The project also serves as a strong foundation for more complex applications, such as predictive modeling or real-time dashboards.****


****OUTPUT****

![Image](https://github.com/user-attachments/assets/72eb8608-2ae9-4b2e-88b0-23b5f0114dbe)

NO MORE WORRIES I GOT MY OUTPUT...
