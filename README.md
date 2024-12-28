Joystick Junction
=================

Welcome to **Joystick Junction**, your premier destination for exploring the exciting world of gaming!

**About Us**\
Joystick Junction was developed as a project for **COSC 304** at the **University of British Columbia (UBC)**. Inspired by a passion for gaming and technology, this platform serves as a centralized hub for managing and exploring triple-A game titles.

**Key Features**

-   A sleek and intuitive user interface
-   Tools for organizing your gaming library
-   Updates on the latest industry trends

Whether you're a casual player or a dedicated gaming enthusiast, Joystick Junction enhances every aspect of your gaming journey.

* * * * *

Getting Started
---------------

Follow the steps below to set up and run the project locally.

### Prerequisites

Ensure the following software is installed on your system:

-   Docker
-   Docker Compose

### Installation and Usage

1.  **Clone the Repository**\
    Open your terminal and execute the following commands:

    bash

    Copy code

    `git clone https://github.com/Sami-Jaffri/JoystickJunction.git
    cd JoystickJunction`

2.  **Start the Application**\
    Use Docker Compose to build and launch the services:

    bash

    Copy code

    `docker-compose up -d`

3.  **Load the Database**\
    Open your browser and navigate to:\
    `http://localhost/shop/loaddata.jsp`

4.  **Access the Login Page**\
    Once the database is loaded, go to:\
    `http://localhost/shop/login.jsp`

5.  **Log In**\
    Use the following customer credentials to explore the site:

    | Username | Password |
    | --- | --- |
    | arnold | 304Arnold! |
    | bobby | 304Bobby! |

### Stopping the Application

To stop and clean up the application, run:

bash

Copy code

`docker-compose down`

* * * * *

File Structure
--------------

Key files and directories include:

-   **Dockerfile**: Instructions for building the application image.
-   **docker-compose.yml**: Configuration to orchestrate services.
-   **/shop**: Core web application files.

* * * * *

Contributing
------------

We welcome contributions to enhance Joystick Junction:

1.  Fork the repository.
2.  Create a feature branch.
3.  Submit a pull request with your proposed changes.

* * * * *

License
-------

This project is open source and licensed for public use.

* * * * *

Get ready to explore the latest games and elevate your gaming experience with Joystick Junction
