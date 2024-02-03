# Fagun IP Information Tracker Documentation

## Overview
The IP Information Tracker is a Python script designed to provide detailed information about a specified IP address. It utilizes two different APIs, IP Stack and IP API, to gather geographical and network-related data. This documentation provides an overview of the script, its features, prerequisites, and instructions on usage.

## Features
- Fetches information such as IP type, continent, country, region, city, zip code, timezone, ISP, latitude, and longitude.
- Provides an option to find the exact location on Google Maps using latitude and longitude coordinates.
- User-friendly interface with colorful headers.

## Prerequisites
- Python 3
- Internet connection

## Installation
1. Clone the repository using the following command:
    ```bash
    git clone https://github.com/fagun18/Fagun_IP_Tracker.git
    ```
2. Navigate to the directory where the script is located.

3. Ensure that you have Python 3 installed on your system.


## Usage
- Run the script in a Python environment:
    ```bash
    python fagun.py
    ```
- The script will automatically fetch information about your own IP address using the ip-api.com service.
- Enter the target IP address when prompted.
- The script will fetch and display detailed information about the specified IP.

## Video Tutorial

[Watch the tutorial video](https://youtu.be/lH_hZS6zDjM)



## Documentation
For more in-depth information, examples, and advanced usage, please refer to our [documentation](https://github.com/fagun18/Fagun_IP_Tracker/wiki).


## Script Structure
The script is structured as follows:

1. Importing Libraries: The necessary libraries, including os, urllib.request, and json, are imported.
2. Fetching User's Own IP: The script starts by fetching information about the user's own IP address using the ip-api.com service.
3. Clearing the Screen: If the TERM environment variable is set, the script clears the screen.
4. Displaying Colorful Header: A colorful header is displayed to enhance the user interface.
5. User Input Loop: The script enters a loop, continuously prompting the user for a target IP address.
6. Fetching IP Information: For each input, the script uses two different APIs (IP Stack and ip-api.com) to fetch information about the specified IP.
7. Displaying Information: If the information retrieval is successful, the script formats and displays various details such as IP type, continent, country, region, city, etc.
8. Google Maps Integration: The script provides an option for users to find the exact location on Google Maps using latitude and longitude coordinates.
9. Error Handling: If the information retrieval is not successful, an error message is displayed, and the user is prompted to try again.

## Customization
Users can customize the script by modifying the code to suit their specific needs, such as changing the API key, adding more information display options, or enhancing the user interface.

## Contributing
If you encounter any issues or have suggestions for improvement, feel free to contribute by submitting pull requests or reporting issues on the script's GitHub repository.

## License
This script is open-source and is distributed under the MIT License.
