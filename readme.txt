
# Flight Scheduler

    Flight Scheduler is a Python application that allows users to search for flight information, receive delay notifications, 
    and book flights. The project integrates with a flight information API to provide real-time data.

## Features

    - **Search Flights**: Users can search for flights based on departure airport, date, and optional destination airport.

    - **Display Flight Information**: The application displays detailed information about the searched flights, including 
       departure time, arrival time, aircraft type, and more.

    - **Book Flights**: Users can book flights by providing their name, phone number, and email. A confirmation email is 
       sent upon successful booking.


## Prerequisites
Before running the application, make sure you have the following installed:

    - Python 3.x
    - PyQt5
    - MySQL Connector
    - Requests library



## Setup

1. Clone the repository:
    ```bash
   git clone https://github.com/your-username/flight-scheduler.git


1.Install dependencies:
    pip install -r requirements.txt

2.Run the application:
    python main.py



Configuration
    1.API Key: Obtain an API key from the flight information API and replace the placeholder in flight.py with your key.

    2.Database: Update the database connection details in user.py with your MySQL server credentials.



Usage
    1.Launch the application.

    2.Enter the departure airport, date, and optional destination airport.

    3.Click "Search Flight" to retrieve flight information.

    4.Optionally, click "Get flight Update" to book a flight.




Contributing
If you'd like to contribute to the project, follow these steps:

1.Fork the repository.

2.Create a new branch:
    git checkout -b feature/new-feature

3.Make your changes and commit them:
    git commit -m "Add new feature"

4.Push to the branch:
    git push origin feature/new-feature

5.Open a pull request.

