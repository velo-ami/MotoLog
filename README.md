# 🏍️ MotoLog

**MotoLog** is a Python command-line application for managing motorbikes and their service records. It stores bike and service data in CSV files.

## Features

- **Add a motorbike** with its registration, brand, model, and mileage.
- **Log a service record** with the date, service type, and cost.
- **Search for a bike** by registration.
- **View all bikes** in the log.
- **Update a bike’s mileage.**
- **Delete a bike** after confirming the action.
- **View service analytics**, including the total number of services and average service cost.
- **Validate input formats:** registrations are checked against the `AB12 CDE` pattern, and service dates are checked for the `DD/MM/YYYY` format.

## Requirements

- Python 3
- `pytest` to run the tests

The application code uses Python’s standard library and the project’s own modules.

## Run MotoLog

Open a terminal in the project folder and run:

```bash
python3 main.py
