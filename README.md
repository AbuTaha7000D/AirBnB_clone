# AirBnB Clone Command Interpreter

## Description

Welcome to the AirBnB clone project! This project aims to develop a command-line interpreter to manage AirBnB objects. Before starting, please familiarize yourself with the [AirBnB concept page](https://www.airbnb.com/).

The command interpreter serves as the first step towards building a full web application for the AirBnB clone. It plays a crucial role as it will be utilized in subsequent projects, including HTML/CSS templating, database storage, API development, and front-end integration.

## Command Interpreter

### How to Start

To start the AirBnB clone command interpreter, follow these steps:

1. Clone the repository to your local machine:

    ```bash
    $ git clone https://github.com/AbuTaha7000D/AirBnB_clone.git
    ```

2. Navigate to the project directory:

    ```bash
    $ cd AirBnB_clone
    ```

3. Run the command interpreter:

    ```bash
    $ ./console.py
    ```

### How to Use

Once the command interpreter is running, you can perform various operations on AirBnB objects using the following commands:

- **Create**: Create a new object (e.g., User, Place).
- **Retrieve**: Retrieve an object from a file, database, etc.
- **Operations**: Perform operations on objects (e.g., count, compute stats).
- **Update**: Update attributes of an object.
- **Destroy**: Destroy an object.

### Examples

Here are some examples of using the command interpreter:

1. **Create a new User**:
    ```bash
    (hbnb) create User
    ```

2. **Retrieve an object**:
    ```bash
    (hbnb) show User 1234-5678-9012
    ```

3. **Update an object**:
    ```bash
    (hbnb) update User 1234-5678-9012 name "Mahmoud Ehab"
    ```

4. **Destroy an object**:
    ```bash
    (hbnb) destroy User 1234-5678-9012
    ```
