# API Documentation

This document provides an overview of the request and response structure for the prediction API.

## Base URL

The base URL for the API is: `http://[domain name / localhost]:8080`

## Endpoints

### 1. Endpoint 1

**Description:** This endpoint allows users to perform fire / no fire prediction.

**URL:** `/predict`

**Method:** POST

**Request:**

- Headers:
  - Content-Type: application/json

- Body:
  ```json
  {
    "Temperature": 0.0,
    "Humidity": 0.0,
    "Pressure": 0.0,
    "PM1": 0.0,
    "TVOC": 0,
    "eCO2": 0,
    "H2": 0,
    "Ethanol": 0,
  }
...

**Response:**

- Status:
  - 200 OK

- Body:
  - Fire / No Fire