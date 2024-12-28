🎮 Joystick Junction 🎮
=======================

[](https://github.com/Sami-Jaffri/JoystickJunction#-joystick-junction-)

Welcome to Joystick Junction, your ultimate gateway to the thrilling universe of gaming!

Born out of a passion for gaming and technology, this platform was developed as a project for COSC 304 at the University of British Columbia (UBC). Designed to be a one-stop hub for exploring and managing triple-A game titles, Joystick Junction offers:

-   🌟 A sleek and user-friendly interface.
-   🕹️ Tools to organize your gaming library.
-   📰 Updates on the latest industry trends.

Whether you're a casual player or a hardcore enthusiast, Joystick Junction is here to amplify your gaming experience.

* * * * *

🚀 Getting Started
------------------

[](https://github.com/Sami-Jaffri/JoystickJunction#-getting-started)

Follow these steps to set up and run the project locally.

### Prerequisites

[](https://github.com/Sami-Jaffri/JoystickJunction#prerequisites)

Ensure the following are installed on your system:

-   🐳 [Docker](https://www.docker.com/)
-   ⚙️ [Docker Compose](https://docs.docker.com/compose/)

* * * * *

### Installation and Usage

[](https://github.com/Sami-Jaffri/JoystickJunction#installation-and-usage)

1.  Clone the Repository:\
    Open your terminal and run:

    ```source-shell
    git clone https://github.com/Sami-Jaffri/JoystickJunction.git
    cd JoystickJunction
    ```

2.  Start the Application:\
    Use Docker Compose to build and run the services:

    ```source-shell
    docker-compose up -d
    ```

3.  Load the Database:\
    Open your browser and navigate to:

    ```
    http://localhost/shop/loaddata.jsp

    ```

4.  Access the Login Page:\
    Once the database is loaded, go to:

    ```
    http://localhost/shop/login.jsp

    ```

5.  Log In:\
    Use the following customer credentials to explore the site:

    | Username | Password |
    | --- | --- |
    | arnold | 304Arnold! |
    | bobby | 304Bobby! |

* * * * *

### 🛑 Stopping the Application

[](https://github.com/Sami-Jaffri/JoystickJunction#-stopping-the-application)

To stop and clean up the application, run:

```source-shell
docker-compose down
```

* * * * *

📂 File Structure
-----------------

[](https://github.com/Sami-Jaffri/JoystickJunction#-file-structure)

Here's an overview of the key files and directories:

-   `Dockerfile`: Instructions for building the application image.
-   `docker-compose.yml`: Configuration to orchestrate services.
-   `/shop`: Contains the core web application files.

* * * * *

💡 Contributing
---------------

[](https://github.com/Sami-Jaffri/JoystickJunction#-contributing)

We welcome contributions to improve Joystick Junction!

-   Fork the repository.
-   Create a feature branch.
-   Submit a pull request with your proposed changes.

* * * * *

📜 License
----------

[](https://github.com/Sami-Jaffri/JoystickJunction#-license)

This project is open source. Do as you wish :)

* * * * *

### 🎉 Happy Gaming!

[](https://github.com/Sami-Jaffri/JoystickJunction#-happy-gaming)

Grab your controller, explore the latest games, and let the fun begin! 🚀
