# **CTEC 121 Assignment: Fetching Weather Data by ZIP Code Using Python and Requests**

## **Assignment Overview**  
In this assignment, you will create a **command-line Python application** that retrieves weather data from an external JSON file. Your program will:  
1. **Fetch and parse** weather data from a remote source.  
2. **Display a list of available ZIP codes** if no ZIP code is provided.  
3. **Allow the user to enter a ZIP code as a command-line argument** and display the corresponding weather information.  
4. **Handle errors gracefully**, ensuring the program does not crash if an invalid ZIP code is entered.  

This program must be run **exclusively from the command line**.  

## **Retrieve Weather Data**  
Your script must fetch weather data from the following endpoint:  

**`https://raw.githubusercontent.com/belgort-clark/ctec-121-json/refs/heads/main/weather.json`**  

## **Display Available ZIP Codes**  
- If the user runs the program without providing a ZIP code, it should print a list of available ZIP codes.  
- The program should also display a message instructing the user how to enter a ZIP code.  

## **Retrieve and Display Weather Data for a ZIP Code**  
- If a ZIP code is provided as a command-line argument, your script should:  
  - Look up the corresponding weather details.  
  - Display the temperature, humidity, air quality index, conditions, and wind speed.  

## **Handle Invalid ZIP Codes**  
- If the user enters a ZIP code that is not in the dataset, display an appropriate error message.  
- The program should also remind the user to check the list of available ZIP codes.  

## **Command-Line Execution**  
- Your script must be executed with a ZIP code as an argument.  
- If no ZIP code is provided, the program should display the available ZIP codes.  

## **Valid ZIP Codes for Testing**  
Your program should work with any of the following ZIP codes from the dataset:  

```
98663, 10001, 94105, 60601, 73301, 85001, 30301, 48226, 15201, 20001,  
98101, 33101, 55401, 37201, 90001, 80202, 21201, 89101, 32801, 19101
```

If a user enters a ZIP code **not in this list**, your program should display an error message.

## **Hints & Tips**  
- Use the `requests` library to fetch the JSON data.  
- Use `sys.argv` to handle command-line arguments.  
- Extract ZIP codes by iterating over the dataset.  
- Store data in a dictionary for **fast lookup**.  
- If no ZIP code is provided, **print the available ZIP codes**.  
- If an invalid ZIP code is entered, **print an error message**.  

## **Submission Requirements**  
- Submit your Python script (`weather.py`).  
- Your code should be **well-commented** to explain each step.  
- Ensure that your script runs **without errors** before submitting.  

## **Bonus Challenge**  
Modify your program to allow multiple ZIP codes as arguments so that the weather details for each ZIP code are displayed.  

---

Happy coding! 🚀
