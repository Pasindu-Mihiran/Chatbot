# Aladdin Chatbot
**Overview**

Aladdin Chatbot is designed to interact with users seamlessly using Dialogflow for natural language understanding. This chatbot can track orders, take new orders, remove items from the order, and complete the order process. The front end is developed using HTML, CSS, and JavaScript, while the back end leverages FastAPI to handle API requests. Orders are stored in a MySQL database.

https://github.com/Pasindu-Mihiran/Chatbot/assets/76475458/09735d60-6f56-45f8-9173-adac3e5e8e0e


**Features**

  * Track Orders: Users can check the status of their existing orders.
  * Take New Orders: Users can place new orders through the chatbot interface.
  * Remove Items from Orders: Users can modify their orders by removing items.
  * Complete Orders: Users can complete their orders and receive a confirmation.

**Technologies Used**

  * Front End: HTML, CSS, JavaScript
  * Back End: FastAPI
  * Database: MySQL
  * Natural Language Processing: Dialogflow

# Getting Started

**Prerequisites**

Ensure you have the following installed:

  * Python 
  * MySQL

# Installation

Clone the repository:

  * git clone https://github.com/Pasindu-Mihiran/aladdin-chatbot.git
  * cd aladdin-chatbot

Set up the MySQL database:

  * Create a database and update the database connection settings in the FastAPI application.

Install dependencies:

 * pip install -r requirements.txt

Run the FastAPI server:

  * uvicorn main:app --reload
    
Set up the front end:

  * Open index.html in your preferred browser or use a local server to serve the HTML file.

# Dialogflow Configuration

**Create a Dialogflow agent:**

Follow the [Dialogflow documentation](https://cloud.google.com/dialogflow?hl=en) to set up an agent.

**Import Intents:**

Import the provided intents and entities into your Dialogflow agent to enable order tracking, placement, modification, and completion functionalities.

**Connect FastAPI with Dialogflow:**

Ensure your FastAPI server can handle webhook calls from Dialogflow. Update webhook URLs in Dialogflow settings accordingly.

# Usage

  * Interact with the chatbot through the front-end interface.
  * Use natural language to place orders, check order statuses, remove items, and complete orders.
