#AIRB_CLONE


HBNB - The Console
This repository contains the initial stage of a project to build a clone of the AirBnB website's command interpreter. This stage implements a backend interface, or console, to manage program data. Console commands allow the user functions as shown below. Using a system of JSON serialization/deserialization, storage is persistent between sessions.

To Start the Command Interpreter
A command interpreter is the part of the operating system that takes commands on the command line from the user and executes them. The Shell is a good example.

To start the command interpreter, first clone the repo to your local machine, and run the console: ./console Once running, the prompt will appear (HBNB), and you can enter your command. With this command line interpreter, the user can create a new User, Place, State, or City, as well as retrieve an object from a file. The user may also update any of these attributes as per below console functionality table or destroy them and manage file storage.

HBnB Commands

Command | Description
--------|----------------
create  | create a new instance of  a class with
show | show instances of a specified class or a class instances
all | prints all string representation of all instances
update | updates all instances of a class ,like email attribute of a user
destroy | deletes an instance based on class id and name

Classes and associated attributes

Class | Attributes |
----------------|----------------
User | email, password, first_name, last_name
State | name
City | state_id, name
Amenity | name
Place | city_id, user_id, name, description, number_rooms, number_bathrooms, max_guest, price_by_night, latitude, longitude, amenity_ids
Review | place_id, user_id, text