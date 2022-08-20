# Hotel-Booking-Prediction
By taking hotel booking dataset, machine learning model has been created to predict whether the guests will cancel their bookings or not.

Required Columns descriptions are given below
1) hotel : Hotel (H1 = Resort Hotel or H2 = City Hotel)

2) is_canceled : Value indicating if the booking was canceled (1) or not (0)

3) lead_time : Number of days that elapsed between the entering date of the booking into the PMS and the arrival date

4) meal :Type of meal booked.Undefined/SC – no meal package; BB – Bed & Breakfast; HB – Half board (breakfast and one other meal – usually dinner); FB – Full board (breakfast, lunch and dinner)

5) country : Country of origin. Categories are represented in the ISO 3155–3:2013 format

6) market_segment :Market segment designation. In categories, the term “TA” means “Travel Agents” and “TO” means “Tour Operators”

7) distribution_channel : Booking distribution channel. The term “TA” means “Travel Agents” and “TO” means “Tour Operators”

8) is_repeated_guest : Value indicating if the booking name was from a repeated guest (1) or not (0)

9) previous_cancellations : Number of previous bookings that were cancelled by the customer prior to the current booking

10) previous_bookings_not_canceled : Number of previous bookings not cancelled by the customer prior to the current booking

11) reserved_room_type : Code of room type reserved. Code is presented instead of designation for anonymity reasons.

12) assigned_room_type : Code for the type of room assigned to the booking. Sometimes the assigned room type differs from the reserved room type due to hotel operation reasons (e.g. overbooking) or by customer request. Code is presented instead of designation for anonymity reasons.

13) booking_changes : Number of changes/amendments made to the booking from the moment the booking was entered on the PMS until the moment of check-in or cancellation

14) deposit_type : Indication on if the customer made a deposit to guarantee the booking. This variable can assume three categories: No Deposit – no deposit was made; Non Refund – a deposit was made in the value of the total stay cost; Refundable – a deposit was made with a value under the total cost of stay.

15) agent : ID of the travel agency that made the booking

16) company : ID of the company/entity that made the booking or responsible for paying the booking. ID is presented instead of designation for anonymity reasons

17) customer_type : Type of booking, assuming one of four categories: Contract - when the booking has an allotment or other type of contract associated to it; Group – when the booking is associated to a group; Transient – when the booking is not part of a group or contract, and is not associated to other transient booking; Transient-party – when the booking is transient, but is associated to at least other transient booking

18) adr : Average Daily Rate as defined by dividing the sum of all lodging transactions by the total number of staying nights

19) total_of_special_requests : Number of special requests made by the customer (e.g. twin bed or high floor)

20) reservation_status :Reservation last status, assuming one of three categories: Canceled – booking was canceled by the customer; Check-Out – customer has checked in but already departed; No-Show – customer did not check-in and did inform the hotel of the reason why

21) reservation_status_date :Date at which the last status was set. This variable can be used in conjunction with the ReservationStatus to understand when was the booking canceled or when did the customer checked-out of the hotel
