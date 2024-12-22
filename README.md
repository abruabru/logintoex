# JsonPowerDB Micro Project

## Description
This project is a micro project designed to showcase the usage of **JsonPowerDB (JPDB)** for managing simple forms. JsonPowerDB is a powerful, fast, and reliable database that works with JSON, offering easy RESTful APIs for managing data storage and retrieval.

This form interacts with the JsonPowerDB API to manage data entries. It allows the user to enter, save, update, and reset records from a form stored in a JSON-based database using the JsonPowerDB service.

## Benefits of using JsonPowerDB
1. **Fast and Powerful**: JsonPowerDB is based on JSON, making it fast and efficient for storing and retrieving data in real-time.
2. **Simple and Lightweight**: It is easy to integrate with your projects. It eliminates the need for complex setups and configurations.
3. **RESTful APIs**: JsonPowerDB provides easy-to-use REST APIs to interact with data, making it simple for developers to perform CRUD (Create, Read, Update, Delete) operations.
4. **Scalability**: JsonPowerDB is scalable and can handle large data sets efficiently without compromising speed.
5. **No Schema**: Unlike traditional databases, JsonPowerDB doesn’t require a predefined schema, giving flexibility to developers.

## Release History
- **v1.0.0**: Initial release with basic data entry and CRUD functionalities using JsonPowerDB.
- **v1.1.0**: Added support for updating and resetting data with detailed validation checks.
- **v1.2.0**: Improved error handling and added custom UI styling for better user experience.

## Table of Contents
1. [Description](#description)
2. [Benefits of using JsonPowerDB](#benefits-of-using-jsonpowerdb)
3. [Release History](#release-history)
4. [Example of Use](#example-of-use)
5. [Project Status](#project-status)
6. [Sources](#sources)
7. [Additional Information](#additional-information)

## Example of Use
To use the form, simply follow these steps:
1. Open the project folder in your web browser.
2. Enter the **Roll Number** and click **Save** to add new records.
3. If the record already exists, use **Update** to modify existing records.
4. You can always **Reset** the form if needed.

### Example JSON Data:
```json
{
  "rollNo": "12345",
  "fullName": "John Doe",
  "class": "10th",
  "birthDate": "2005-01-15",
  "address": "123 Main St, Cityville",
  "enrollmentDate": "2020-08-01"
}
