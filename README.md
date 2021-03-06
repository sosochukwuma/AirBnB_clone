## Synopsis

This is an Airbnb clone project, [Airbnb](https://www.airbnb.com/).
Implemented features are listed below.

### Features

#### Command Interpreter

The Command Interpreter was used to manage the whole application's functionality from the command line, such as:
+ Creating a new object.
+ Retrieving an object from a file, database, etc.
+ Executing operation on objects. e.g. Count, compute statistics, etc.
+ Updating object's attributes.
+ Destroying an object.

##### Usage

To launch the console application in interactive mode simply run:

```console.py ```

or to use the non-interactive mode run:

```echo "your-command-goes-here" | ./console.py ```

Commands | Description | Usage
-------- | ----------- |-------- |
**help** or **?**| Displays the documented commands. | **help**
**quit**     | Exits the program. | **quit**
**EOF**      | Ends the program. Used when files are passed into the program. | N/A
**create**  | Creates a new instance of the \<class_name\>. Creates a Json file with the object representation. and prints the id of created object. | **create** \<class_name\>
**show**    | Prints the string representation of an instance based on the class name and id. | **show** \<class_name class_id\>
**destroy** | Deletes and instance base on the class name and id. | **destroy** \<class_name class_id\>
**all** | Prints all string representation of all instances based or not on the class name | **all** or **all** \<class_name class_id\>
**update** | Updates an instance based on the class name and id by adding or updating attribute | **update** \<class_name class_id key value\>

### Tests

If you wish to run at the test for this application all of the test are located under the **test/** folder and all can be executed by simply running:

```python3 -m unittest discover tests ```

from the root directory.


### Bugs

+ No known bugs at this time.