# Aquaponics System Control

This is a web application for controlling an aquaponics system. The application allows you to toggle the status of various components, such as the water pump, air pump, and light. You can also set system parameters like water level, temperature, and pH level.

## Prerequisites

- Python 3.7 or above
- Microdot, pandas, and numpy libraries

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/your_username/aquaponics-system-control.git
   cd aquaponics-system-control
Install the required libraries:

shell

pip install microdot pandas numpy
Usage
Prepare the system state CSV file:

Create a CSV file named state.csv in the project directory.

The file should have the following structure:

csv

water_pump,air_pump,light,water_level,temperature,pH_level
OFF,OFF,OFF,0,0,0
Run the application:

shell

python app.py
Open your web browser and visit http://localhost:8008 to access the Aquaponics System Control web app.

The web app interface will display the current state of the system components and parameters.

To toggle the status of a component, click on the respective button. For example, click on the "Water Pump" button to turn it on or off.

To set a system parameter, use the following URL format: http://localhost:8008/set_parameter/parameter/value. Replace parameter with the desired parameter (water_level, temperature, or pH_level) and value with the new value.

The web app will automatically update the system state in the state.csv file.

Contributing
Contributions are welcome! If you find any issues or want to add new features, please submit a pull request.

License
This project is licensed under the MIT License.

vbnet

Please note that I've made some assumptions about the repository name and lice
