
    Hi Welcome to my Hall Booking API Task. Consider this as a complete guide for the same.



1) To get the all room Details I have written a get request in https://hallbooking12.herokuapp.com


2)  We can create a room with https://hallbooking12.herokuapp.com/create-room

Sample Body for Creating API :-

 {
     
        "name": "medium",
        "seats": 50,
        "roomid": 102,
        "amenities": [
            "internet_access",
            "food",
            "ac",
            "tv"
        ],
        "price": 500,
        "BookingStatus": "Available",
        "customerDetails": {
            "cutstomerName": "",
            "date": "",
            "start": "",
            "end": "",
            "roomId": ""
        }
    }



3) Booking a room made easy with a post request in https://hallbooking12.herokuapp.com/room-booking

Sample Body for Booking a room : -
            {
            
            
            "name": "ram",
            "date": "2022-09-23",
            "start": "10:00",
            "end": "20:00",
            "roomId": 101
            
            
        }


 4) We can get the Booked Room details using a get request in https://hallbooking12.herokuapp.com/booked-room-details


 5) We can get the Booked Customer details using a get request in  https://hallbooking12.herokuapp.com/booked-customer-details
