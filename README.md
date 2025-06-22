# Flight Club Project

This Python application helps users find and track flight deals by monitoring prices for specific destinations.
The application uses external APIs to fetch flight data and notifies users when prices drop below a certain threshold.

## Key Features

**Data Management with Sheety API:**
  - The application uses the Sheety API to manage flight data, allowing users to store and retrieve information about flight prices and destinations.

**Flight Search with Tequila API:**
  - The application integrates with the Tequila API to search for flights based on user-defined parameters, such as origin and destination cities and travel dates.

**Price Monitoring and Notifications:**
  - The application checks flight prices and compares them to the stored prices. If a flight's price drops below the threshold, it sends a notification to the user.

**Data Classes for Flight Information:**
  - The application uses a `FlightData` class to encapsulate flight information, making it easier to manage and access flight details.

**User Interaction and Data Updates:**
  - The application allows users to update destination codes and manage their flight preferences through a simple interface.
