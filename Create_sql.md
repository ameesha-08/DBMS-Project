All the tables
  Room ( id, No, type, price)
  Guestinfo ( id, name, email, phoneNo, room_booked)
  Admininfo ( id, name, email, phoneNo)
  Foodinfo ( id, name, price, type)

1) Room table creation
      Create table Room (id int NOT NULL, No int NOT NULL PRIMARY KEY type varchar(255) NOT NULL, price DECIMAL(10,2));
 
2)Guest_Info table creation
      Create table Guestinfo(id int NOT NULL, name varchar(255) NOT NULL, email varchar(255) NOT NULL ,phoneNo varchar(255) NOT NULL PRIMARY KEY,
                    room_booked int NOT NULL);
3)Admin_Info table creation                    
      Create table Admininfo(id int NOT NULL, name varchar(255) NOT NULL, email varchar(255) NOT NULL ,phoneNo varchar(255) NOT NULL PRIMARY KEY);

4)Food_Info table creation
      create table Foodinfo (id int NOT NULL, name varchar(255) NOT NULL PRIMARY KEY,  price DECIMAL(10,2),  type varchar(255) NOT NULL);
      
