
    Hi Welcome to my Hall Booking API Task. Consider this as a complete guide for the same.



1) To get the all room Details I have written a get request in https://hall-booking-delta.vercel.app


2)  We can create a room with https://hall-booking-delta.vercel.app/create-room

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




3) Booking a room made easy with a post request in https://hall-booking-delta.vercel.app/room-booking

Sample Body for Booking a room : -



            {
            
            
            "name": "ram",
            "date": "2022-09-23",
            "start": "10:00",
            "end": "20:00",
            "roomId": 101
            
            
        }


 4) We can get the Booked Room details using a get request in https://hall-booking-delta.vercel.app/booked-room-details


 5) We can get the Booked Customer details using a get request in  https://hall-booking-delta.vercel.app/booked-customer-details
