![image](https://github.com/user-attachments/assets/a7a7225e-4293-4c7c-b206-fa15c2af0057)

<h1>AIRBNB CLONE Project</h1>

### This project involves creating a basic clone of the AirBnB website, focusing initially on a backend console to manage data, similar to a shell interface. The console commands will enable users to create, update, and delete objects, as well as manage file storage.

### Console Tasks:
- Implement a parent class named `BaseModel` for handling initialization, serialization, and deserialization of instances.
- Establish a straightforward flow for serialization and deserialization: Instance <-> Dictionary <-> JSON string <-> file.
- Develop all necessary classes for AirBnB (such as User, State, City, Place, etc.) that derive from `BaseModel`.
- Create the project's first abstracted storage engine: File storage.
- Write unit tests to validate all classes and the storage engine.

### Command Interpreter Description:
The command interpreter facilitates the management of project objects by enabling:

- Creation of new objects (e.g., a new User or Place).
- Retrieval ofobjects from files, databases, etc.
- Performing operations on objects (like counting or computing statistics).
- Updating object attributes.
- Deleting objects.

- ### Starting the Interpreter
- To start the interpreter, run the `console.py` file. Once the interpreter is active, you will see the prompt `(hbnb)`.

### Basic Commands:
- **help**: Displays a list of available commands.
  
  Example usage:
  ```
  (hbnb) help
  ```

  This will show documented commands:
  ```
  Documented commands (type help <topic>):
  ========================================
  EOF  all  create  delete  destroy  exit  help  q  quit  show  update
  ```

- **quit** or **exit**: Ends the console session.

  Example usage:
```
  (hbnb) quit
```

You can type any of the commands at the `(hbnb)` prompt to interact with the console.

### Running Tests

To execute all the tests, use the following command:

```
$ python3 -m unittest discover tests
```

If you want to run a specific test file, you can do so by specifying the file name:

```
$ python3 -m unittest tests/test_models/test_city.py
```
