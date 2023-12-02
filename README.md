# Food Order Chatbot

This project is a chatbot application built with Dialogflow, Python, and FastAPI. It allows users to order food and track their food orders seamlessly.

## Features

- **Ordering System:** Users can interact with the chatbot to place food orders.
- **Order Tracking:** Users can check the status and details of their food orders.
- **User-Friendly Interface:** The chatbot provides a natural language interface for a smooth user experience.

## Prerequisites

Before running the chatbot, make sure you have the following installed:

- Python 3.x
- Dialogflow API credentials
- FastAPI and required dependencies

## Installation
Directory structure
===================
backend: Contains Python FastAPI backend code
db: contains the dump of the database. you need to import this into your MySQL db by using MySQL workbench tool
frontend: website code

Install these modules
======================

pip install mysql-connector
pip install "fastapi[all]"

To start fastapi backend server
================================
1. Go to backend directory in your command prompt
2. Run this command: uvicorn main:app --reload

ngrok for https tunneling
================================
1. To install ngrok, go to https://ngrok.com/download and install ngrok version that is suitable for your OS
2. Extract the zip file and place ngrok.exe in a folder.
3. Open windows command prompt, go to that folder and run this command: ngrok http 80000

NOTE: ngrok can timeout. you need to restart the session if you see session expired message.

