pip install phonenumbers

pip install opencage

pip install folium

# Phone Number Tracker Application 📱

This Python application allows users to track phone numbers to identify their location, service provider, and view the location on a map. It uses the Tkinter library for the GUI, phonenumbers for phone number parsing, OpenCage Geocoder API for geolocation, and folium for map generation.

---

## Features

- Identify the country and carrier (SIM provider) of a phone number.
- Generate a map with the approximate location of the number.
- View the generated map in a web browser.

---

## Requirements

Before running the application, ensure you have the following installed:

- Python 3.x
- Libraries:
  - tkinter
  - phonenumbers
  - folium
  - webbrowser
  - opencage

Install the required libraries using:
```bash
pip install phonenumbers folium opencage
```

---

## Setup Instructions

1. Clone or download this repository.
2. Replace the placeholder API key with your OpenCage Geocoder API key:
   ```python
   API_KEY = "your_opencage_api_key"
   ```
   Obtain your API key from [OpenCage Geocoder](https://opencagedata.com/).

3. Place the required assets (logo.png and search_icon.png) in the same directory as the script.

4. Run the application:
   ```bash
   python tracker_app.py
   ```

---

## Usage

1. Input a valid phone number in the entry field.
   - Format: Include the country code (e.g., +1 for USA, +91 for India).

2. Click the search button to fetch the country and SIM details.
3. Click View Location to open the generated map in your default web browser.

---

## Example Output

- Country: United States  
- SIM: AT&T  
- Map: Opens in the browser showing the approximate location.

---

## Screenshots

| Main Interface | Map View |
|-----------------|----------|
| ![Main UI](screenshot1.png) | ![Map View](screenshot2.png) |

---

## Error Handling

- Invalid Input: Displays an error for invalid or improperly formatted phone numbers.
- Location Not Found: Alerts the user if location data is unavailable.

---

## Credits

- Developed by: [Akarsh Chaturvedi](https://github.com/AkarshYash)
- Instagram: [@Akarsh Chaturvedi](https://instagram.com/AkarshChaturvedi)

---

## License

This project is licensed under the MIT License. Feel free to use and modify it for your own needs.  

---

Happy Coding! 🚀
