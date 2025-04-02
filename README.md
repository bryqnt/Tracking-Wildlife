# Tracking-Wildlife

# Wildlife Monitoring System

## Overview  
This program tracks animals using GPS data by analyzing their coordinates to detect repetitions.  
It will notify the user if a repetition is found.  

## Features  
- Prompts the user for the number of coordinates to be entered  
- Accepts exact coordinates of animal movements  
- Detects repeated coordinates (loops)  
- Handles invalid inputs and prompts for re-entry  

## Installation  
1. Open a terminal  
2. Run the following command:  
   ```bash
   python3 animal.py
## Example Runs  

### Example 1: No Loop Detected  
```bash
$ python3 animal.py
Enter the amount of coordinates: 3
Enter the coordinates / Ex: x y: 1 2
Enter the coordinates / Ex: x y: 3 4
Enter the coordinates / Ex: x y: 1 4
No loop detected

$ python3 animal.py
Enter the amount of coordinates: 5
Enter the coordinates / Ex: x y: 1 2
Enter the coordinates / Ex: x y: 3 r
Invalid input for coordinates, try again.
Enter the coordinates / Ex: x y: 1 5
Enter the coordinates / Ex: x y: 2 2
Enter the coordinates / Ex: x y: 1 2
Loop detected
