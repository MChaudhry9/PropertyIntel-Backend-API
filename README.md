<!--https://api-new-murex.vercel.app/api/complaints?bin_number=1080796-->

<h1 align="center">NYC PropertyIntel: Your Go-To Real Estate Insights Tool</h1>
<h1 align="center">Backend-RESTful API</h1>
<div align="center">
<a href="https://api-new-murex.vercel.app/api/complaints">Use the RESTful API</a>
</div>

This is the backend code for the web application that lets users explore and analyze building violations across New York City, it utilizes MVC software architecture and is built using real-time data from the NYC Department of Buildings (DOB), sourced from the [NYC Open Data](https://opendata.cityofnewyork.us/) platform.

## Tech Stack
* [![Python](https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
* [![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)](https://flask.palletsprojects.com/)

## API Endpoints and Query Parameters

- **GET `/api/complaints`**: Retrieve all violations.
- **GET `/api/complaints?address={}`**: Retrieve a violation by address.
- **GET `/api/complaints?zip_code={}`**: Retrieve a violation by zipcode.
- **GET `/api/complaints?bin_number={}`**: Retrieve a violation by the unique identifier: Building Identification Number (BIN Number).
- **GET `/api/complaints?address={}&zip_code={}`**: Retrieve a violation by both address and zipcode.
- **GET `/api/complaints?address={}&bin_number={}`**: Retrieve a violation by address and BIN number.
- **GET `/api/complaints?zip_code={}&bin_number={}`**: Retrieve a violation by both zip code and BIN number.
- **GET `/api/complaints?address={}&zip_code={}&bin_number={}`**: Retrieve a violation by address, zip code, and BIN number.
