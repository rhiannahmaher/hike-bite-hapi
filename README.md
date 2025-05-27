<!-- Table of Contents -->
# Table of Contents

- [About the Project](#about-the-project)
  * [Tech Stack](#tech-stack)
  * [Features](#features)
- [Getting Started](#getting-started)
  * [Environment Variables](#environment-variables)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
  * [Deployment](#deployment)
- [Usage](#usage)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)
  
<!-- About the Project -->
## About the Project

**Hike&Bite** is a web application designed for hikers to log and discover food stops across Ireland. The platform provides detailed information on various stop types including cafes, restaurants, and pubs, helping users find great places to eat around the country. 
The application is built using Hapi, which handles data management, user data, and the retrieval of food stop information to ensure a seamless user experience.
<!-- TechStack -->
### Tech Stack

<details>
  <summary>Client</summary>
  <ul>
    <li><a href="https://handlebarsjs.com/">Handlebars.js</a></li>
    <li><a href="https://bulma.io/">Bulma CSS</a></li>
    <li><a href="https://studio3t.com/">Studio 3T</a></li>
  </ul>
</details>

<details>
  <summary>Server</summary>
  <ul>
    <li><a href="https://hapi.dev/">Hapi.js</a></li>
    <li><a href="https://nodejs.org/">Node.js</a></li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://www.mongodb.com/">MongoDB</a></li>
  </ul>
</details>

<!-- Features -->
### Features

- Stop Information: Users can add stops and each stop allows users to provide useful details such as operating hours, location, and description.
- User-specific Data: Stops and POIs are associated with the users who added them, allowing personalized data management.
- User Authentication: Users can sign up, and log in.

<!-- Getting Started -->
## Getting Started

<!-- Env Variables -->
### Environment Variables

To run this project, you will need to add the following environment variables to your .env file:

- `cookie_name=hikebitetime`
- `cookie_password=COOKIE_EMCRYPTION_KEY_HERE_MUST_BE_32_CHARCTERS_OR_MORE`
- `db=mongodb+srv://<username>:<password>@<cluster-url>/?retryWrites=true&w=majority&appName=<your-app-name>`

To do so, create a `.env` file in the root directory of the project. You can copy the content from the `.env_example` file and modify it with your own details:

    ```bash
    cp .env_example .env
    ```
    
Update the following fields in your `.env` file:

- `cookie_password`
- `db`: Link to your cloud database

<!-- Prerequisites -->
### Prerequisites

Before you begin, ensure that you have the following:

- **Node.js** (version 16.0 or higher) – Your project requires Node.js to run the server. You can download and install Node.js from [here](https://nodejs.org/).
- **MongoDB** – You can either set up a local MongoDB server or use a cloud instance like [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).

### Installation

Follow these steps to get your environment set up:

**Clone the repository**:
Open your terminal or command prompt and run the following command to clone the repository:

    ```bash
        git clone https://github.com/rhiannahmaher/hike-bite.git
    ```

**Navigate to the project directory**:

    ```bash
        cd your-project-name
    ```

**Install the dependencies**:
Run the following command to install all the necessary packages:

    ```bash
        npm install
    ```

**Set up environment variables**:
 Create a `.env` file and update `env_example`

**Run the application**:
Once everything is set up, you can start the development server:

    ```bash
        npm start
    ```

This will start the Node.js server, and you should be able to access the application at `http://localhost:3000`

### Deployment

Application is available to view via Glitch [here](https://iced-alkaline-feeling.glitch.me/)

<!-- Usage -->
## Usage

**Hike&Bite** is a web application designed to assist users in discovering key food stops around Ireland, such as cafes, restaurants, and other points of interest.

### Purpose
The primary goal of Hike&Bite is to help users plan their trips more efficiently by providing access to key stops along areas. 

### Target Audience
**Hike&Bite** is perfect for anyone who enjoys discovering new food stops.
Additionally, it can be useful for developers who wish to integrate food stop data into their own applications or websites.

<!-- Contact -->
## Contact

Rhiannah Maher - 20085527@mail.wit.ie

Project Link: [https://github.com/rhiannahmaher/hike-bite](https://github.com/rhiannahmaher/hike-bite-hapi.git)

<!-- Acknowledgments -->
## Acknowledgements

 - [Awesome README](https://github.com/matiassingers/awesome-readme)
