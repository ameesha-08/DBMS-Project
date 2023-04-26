bookguestroom(roomNo, Pno)
UPDATE Guest
SET room_booked = roomNo
WHERE phoneNo = Pno 

getadminbyid(Id)
SELECT * FROM AdminInfo WHERE Id = 2

getguestbyId(Id)
SELECT * FROM GuestInfo WHERE Id = 4

deleteadminbyid(Id)
DELETE FROM AdminInfo WHERE Id = 1

Update FoodInfo by ID :

UPDATE FoodInfo
SET Name ='Fried Okra' AND Price = 100
WHERE ID = '12';


Delete FoodInfo by ID :

deletefoodinfobyid(Id)
DELETE FROM FoodInfo WHERE Id = 4

Get Room Info by Room ID:
SELECT * FROM Room WHERE Id = 2

