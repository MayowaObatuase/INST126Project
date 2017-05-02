# INST126Project
# Our Group Project


print("""

,--.   ,--.       ,--.                                  ,--------.
|  |   |  | ,---. |  | ,---. ,---. ,--,--,--. ,---.     '--.  .--',---.
|  |.'.|  || .-. :|  || .--'| .-. ||        || .-. :       |  |  | .-. |
|   ,'.   |\   --.|  |\ `--.' '-' '|  |  |  |\   --.       |  |  ' '-' '
'--'   '--' `----'`--' `---' `---' `--`--`--' `----'       `--'   `---'
                                                              ,---.
,--------.,--.                ,------.  ,--.   ,--.,--.   ,--.|   |
'--.  .--'|  ,---.  ,---.     |  .-.  \ |   `.'   | \  `.'  / |  .'
   |  |   |  .-.  || .-. :    |  |  \  :|  |'.'|  |  \     /  |  |
   |  |   |  | |  |\   --.    |  '--'  /|  |   |  |   \   /   `--'
   `--'   `--' `--' `----'    `-------' `--'   `--'    `-'    .--.
                                                              '--'
""")

Airport_Selection = input("""
Which airport would you like to view arrivals/departures for?
Reagan National - Input "Reagan"
Dulles International Airport?  - Input "Dulles"
Baltimore Washington-Thurgood Marshal International Airport? - Input "BWI"
For ALL please input "All"
:
""")

api_key = ""

def airport_display():
  if Airport_Selection == "Reagan":
    print("Welcome to Reagan Nation Airport")
  elif Airport_Selection == "Dulles":
    print("Welcome to Dulles International Airport!")
  elif Airport_Selection == "BWI":
    print("Welcome to Baltimore Washington Thurgood Marshall Internation Airport!")
  elif Airport_Selection == "All":
    print("Welcome to the DMV Area Arrival & Departures Page!")
  else:
      print("Error, please input a valid DMV Area airport!")

airport_display()
print("If you would like to ")
# def display_module():

