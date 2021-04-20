# Flight-Ticket-Booking

An airline operates multiple flights from Chennai to Mangalore. The aim is to write a basic
ticket booking program for their flights.

A database is created locally and the details from the file inputs are stored in the database.
Two files are used as sample inputs with flightname as file name.

## Modules involved 
1) Welcome
2) Login
3) Flight Details
4) Dashboard
5) Check Availability
6) Book Ticket
7) Cancel Ticket
8) View Ticket Details

### Welcome page
The basic landing page which allows one to login or add in flight details in th form of file 
input. Initially, run the file "Welcome.java"

![1](https://user-images.githubusercontent.com/58515646/115336273-83144780-a1bc-11eb-880f-93a894985b2b.JPG)

### Login
The User can use his username and password to login to the airline ticket reservation system.

![2](https://user-images.githubusercontent.com/58515646/115336363-b7880380-a1bc-11eb-9c98-49a295448443.JPG)

### Flight Details
Flight seats are categorized under two types namely Economy and Business Class.The number of seating arrangements and 
the number of seats in business class and economy class are given as file input. The name of the file corresponds to the 
name of the flight. Once the file is uploaded, the details from the file are fetched and stored in the database.

Sample file format:
A114.txt has the data
Business : {2, 3, 2}, 12
Economy : {3, 4, 4}, 20
This means, flight A114 has 12 rows of business class tickets and 20 rows of Economy class tickets.

![4](https://user-images.githubusercontent.com/58515646/115336866-9ecc1d80-a1bd-11eb-8902-802d7136c8dc.JPG)'

![atach4](https://user-images.githubusercontent.com/58515646/115336941-bd321900-a1bd-11eb-820c-1859dbda0926.JPG)

### Dashboard
Upon successful login, the user is provided with the dashboard where the user can check the availability of seats, book and
cancel tickets.

![3](https://user-images.githubusercontent.com/58515646/115337188-26199100-a1be-11eb-8d53-5e7dace50994.JPG)

### Check availability
Once the flight ID or the file name is entered, the number of seats and details regarding availability of flight is displayed.
Available seats for each flight ID is printed.

![5](https://user-images.githubusercontent.com/58515646/115337519-c079d480-a1be-11eb-90ca-69c36f9d50a8.JPG)

![6](https://user-images.githubusercontent.com/58515646/115337543-ce2f5a00-a1be-11eb-8cb8-025f5fc4fa59.JPG)

![7](https://user-images.githubusercontent.com/58515646/115337570-d8e9ef00-a1be-11eb-8804-0b01d8416c56.JPG)

### Book Tickets
The users can book tickets after checking availability for a particular flight. A unique ID is generated upon successful
booking of tickets which is later used to identify the booking. Base price for economy, business class tickets and for window , aisle 
seats are assigned. Surge pricing and meal preference is provided.

![8](https://user-images.githubusercontent.com/58515646/115338165-e489e580-a1bf-11eb-8bba-44b01488c9a3.JPG)

![9](https://user-images.githubusercontent.com/58515646/115338220-fd929680-a1bf-11eb-9141-c44b6276e6c2.JPG)

### View Ticket
The generated booking ID is used to view the individual tcikets being booked.

![10](https://user-images.githubusercontent.com/58515646/115338316-392d6080-a1c0-11eb-8cd9-0c560b7451f0.JPG)

![11](https://user-images.githubusercontent.com/58515646/115338352-4b0f0380-a1c0-11eb-839b-ffe5297057e4.JPG)

![14](https://user-images.githubusercontent.com/58515646/115338395-60842d80-a1c0-11eb-80bd-41f690a2fd7f.JPG)

### Cancel Ticket
On specifying the booking ID, the ticket is cancelled. The cancellation fee is charged.

![12](https://user-images.githubusercontent.com/58515646/115338676-f4ee9000-a1c0-11eb-8723-994d39567c03.JPG)

![13](https://user-images.githubusercontent.com/58515646/115338866-544ca000-a1c1-11eb-8c96-3cc8056b90b4.JPG)

### Table Schema

![Schema](https://user-images.githubusercontent.com/58515646/115339089-ba392780-a1c1-11eb-878e-22588da2e234.JPG)

Cd to AirlineReservation/src run Welcome.java

### Sample DB from file and user inputs

![f1](https://user-images.githubusercontent.com/58515646/115339588-b5c13e80-a1c2-11eb-9b13-426f96c30ce3.JPG)

![f2](https://user-images.githubusercontent.com/58515646/115339612-c07bd380-a1c2-11eb-95c1-9103f5b822ab.JPG)
