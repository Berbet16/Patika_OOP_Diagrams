# Patika_OOP_Diagrams Homeworks


## [University Management System](https://github.com/Berbet16/Patika_OOP_Diagrams/blob/main/ZooManagementSystem.png)

- There are classrooms, study offices and departments belonging to the university.
- There are offices belonging to the departments.
- There are employees belonging to the university. These employees can be professors or civil servants.
- Every employee works in an office.

**Draw the Class diagram describing this system.**

**(Note: It is not necessary to specify the attributes and behaviors of the classes.)**

![uml-diagram](https://github.com/Berbet16/Patika_OOP_Diagrams/blob/main/UniversityManagementSystem.png)



---
## [Zoo Management System](https://github.com/Berbet16/Patika_OOP_Diagrams/blob/main/ZooManagementSystem.png)
You design a system to track information about animals in a zoo.
Animals:
- Horses (horses, zebras, donkeys, etc.),
- Felines (tigers, lions, etc.),
- It is characterized by species in groups such as rodents (rats, beavers, etc.).
- Most of the information stored about animals is the same for all groupings.
- species name, weight, age, etc.
- The system should also be able to get the dosage of specific drugs for each animal => getDosage()
- System should be able to calculate Feed times => getFeedSchedule()

The logic for the system to perform these functions will be different for each grouping. For example, the feeding algorithm will be different for horses and different for tigers.

Using the polymorphism model, design a class diagram to handle the situation described above.

**Draw the Class diagram describing this system.**

![uml-diagram](https://github.com/Berbet16/Patika_OOP_Diagrams/blob/main/ZooManagementSystem.png)

---


## [Flight Management System](https://github.com/Berbet16/Patika_OOP_Diagrams/blob/main/FlightManagementSystem.png)
Design a system for the management of flights and pilots.

- Airline companies operate the flights. Every airline has an identity.
- The airline has different types of aircraft.
- Airplanes may be in working or repair condition.
- Each flight has a unique ID, departure and landing airport, departure and landing times.
- Every flight has a pilot and co-pilot, and they operate the plane.
- Airports have unique IDs and names.
- Airlines have pilots and each pilot has a level of experience.
- An aircraft type may need a certain number of pilots.

**Draw the Class diagram describing this system.**

![uml-diagram](https://github.com/Berbet16/Patika_OOP_Diagrams/blob/main/FlightManagementSystem.png)

---

## [Online Movie System](https://github.com/Berbet16/Patika_OOP_Diagrams/blob/main/OnlineMovieSystem.png)
Design the system of the application that sells or rents movies online.

- Movies can be listed and sorted in the app and users can subscribe to the app.
- Users purchase credits through the system for subscription.
- Only subscribed users can rent movies with their credits and the credit amount of the rented movie is deducted from their account.
- Regular users and subscribers can purchase movies.
- If the film is not available, it can be requested.
- Draw the Class diagram describing this system.

**Draw the Class diagram describing this system.**

![uml-diagram](https://github.com/Berbet16/Patika_OOP_Diagrams/blob/main/OnlineMovieSystem.png)

---

## [Elevator Simulation](https://github.com/Berbet16/Patika_OOP_Diagrams/blob/main/ElavatorSimulationDiagram.png)

**Design a class diagram based on the following problem statement.**

- Try to use the principles of Object Oriented Programming and relations between classes. (Encapsulation, Inheritance, Polymorphism, Abstraction)

- We Code The Insurance Company wants to build a 12-storey office building and equip it with the latest elevator technology. The company wants you to create a software simulator that models the operations of the building's elevators to see if they can meet the traffic flow needs within the building.

- The building will have five elevators, each of which can go up to 12 floors of the building. Each elevator has a capacity of approximately six adult passengers. Elevators are designed to be energy efficient, so they only move when needed. Each elevator has its own door, floor indicator light and control panel. The control panel has target buttons, door open and close buttons, and an emergency signal button.

- Each floor in the building has a door for each of the five elevator shafts and an arrival bell for each door. The arrival bell indicates that the elevators have arrived at a floor. A signal light on each door indicates the arrival of the elevator and the direction the elevator is moving. Each floor also has three sets of elevator call buttons.

- A person calls an elevator by pressing the appropriate call button (up or down). A scheduler assigns one of five elevators to go to the floor where the search started. Upon entering the elevator, a passenger typically presses one or more of the destination buttons. As the elevator moves from floor to floor, an indicator light inside the elevator informs passengers about the location of the elevator. The arrival of an elevator to a floor is indicated by the lighting of the indicator lamp above the outer elevator door and the ringing of the floor bell. When an elevator stops at a floor, both sets of doors open automatically for a predetermined time, allowing passengers to enter and exit the elevator.

- The simulator uses a "clock" to simulate real time lapse and timestamp and log events that occur in the simulation. A random number generator is used by the simulator to generate passengers and determine the departure and arrival floors for each passenger.

![uml-diagram](https://github.com/Berbet16/Patika_OOP_Diagrams/blob/main/ElavatorSimulationDiagram.png)
