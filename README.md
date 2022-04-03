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
