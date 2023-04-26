Tables: 

Room ( id, No, type, price)
Guestinfo ( id, name, email, phoneNo, room_booked)
Admininfo ( id, name, email, phoneNo)
Foodinfo ( id, name, price, type)

Fds for the above relations:

Room - Room No->type, price, status

Guestinfo - phoneNo->id, name, email, room_booked, due_amount

Admininfo - phoneNo->id, password, name, email

Foodinfo - name-> id, price, type

Primary Keys: 

Room table - No

Guest table - phoneNo

Admin table - phoneNo

Food table - name


All Relation are in 3NF
