# Log-Ingestor
A simple log ingestor system built using Flask and SQLAlchemy, capable of handling vast volumes of log data over HTTP.

Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

#Prerequisites
Python (version 3.x)
pip
#Installation
Clone the repository:
Change into the project directory
Install the required dependencies
#Usage
Run the log ingestor
The server will start on http://localhost:3000.
Ingest logs by sending POST requests to http://localhost:3000/ingest with JSON log data.

#Query Interface
#Log Query Interface
A simple query interface for logs built using Flask and SQLAlchemy, allowing users to filter logs based on specified criteria.
Run the query interface:
The server will start on http://localhost:4000.
Query logs by sending GET requests to http://localhost:4000/query with desired filters.

