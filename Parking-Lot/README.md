# Problem Statement

### Design a Parking Lot with Below Specification

* Park a Vehicle(Car, Truck, Bike etc.)
* Unpark a Vehicle
* Get status of a parking spot
* Get total vehicles parked
* Get total revenue generated

### Functional Requirements

* A **ParkingLot** will have multiple floors.
* A **ParkingFloor** will have multiple **ParkingSpot**.
* A Parking spot can be of different type as per the vehicle it can accommodate.
* A Parking spot will have a status is **OCCUPIED** or **EMPTY**.
* A ParkingLot will show number of vehicles parked as per type.
* For simplicity lets make one **Entry** and one **Exit** universally for entire parking lot.
* At entry **Vehicles** are supposed to get **Tickets**.
* Ticket will show type of vehicle, registration number, entry time and allotted spot.
* At exit Vehicles are supposed to Pay and exit.
* **Payment** can be of multiple types(UPI, Credit Card etc.).
* Exit will store revenues generated.

### Non-Functional Requirements

* The **ParkingLot** should be able to handle uo to 10,000 Parking Spots.
* Each **ParkingSpot** has a Unique ID.
* **ParkingSpot** can be of different type(Four Wheeler, Big Vehcicle, Two Wheeler etc.).
* **Vehicles** can be of Different type(Car, Truck, Bike etc.).
* The **ParkingLot** should be able to handle concurrency.