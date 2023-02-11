
# Project 9  - Forecast of client loss for the hospitality company 

Hospitality company "As home" wants to incrase the costumers flow. For that purpose company added an option to book the room without downpayment, hovewer company has faced the losses of income in a case of booking cancellation. To solve this issue company wants to develop the System which will predict the booking cancelation. In case of possible cancelation of booking hospitality company client has to make a downpayment of 80% of cost of booking.

## The main tasks for the project are following:
1) Import the data;

2) Prepare the data and conduct exploratory analysis:
- check the data and make an adjustments if necessary;
- make an exploratory analysis. Describe the aspects: nulls and peaks.

3) Calculate business metric. Estimate the profit before the intagration of prediction system.

4) Build the ML model:
- train several models;
- select the model with best score and test it;
- select the suitable metric for cross-validation;
- calclate the potential prfit after integration of prediction system.

5) Describe the inreliable client. (clients who potentially will cancel the booking).

Provided data includes tow datasets - hotel_train.csv and hotel_test.csv

## Datasets description: 

Datasets hotel_train and hotel_test have the same columns names:
- id - record number;
- adults - quantity of adults;
- arrival_date_year;
- arrival_date_month;
- arrival_date_week_number;
- arrival_date_day_of_month;
- babies;
- booking_changes;
- children - quantity of childred 3 to 14 years;
- country;
- customer_type:
    - Contract;
    - Group;
    - Transient;
    - Transient-party.
- days_in_waiting_list;
- distribution_channel;
- is_canceled;
- is_repeated_guest;
- lead_time - duration in days beetween booking and check in;
- meal:
-    SC;
-    BB;
-    HB;
-    FB;
- previous_bookings_not_canceled;
- previous_cancellations;
- required_car_parking_spaces;
- reserved_room_type;
- stays_in_weekend_nights;
- stays_in_week_nights;
- total_nights;
- total_of_special_requests.

## Additional conditions:

Deposit cost is 80% of booking;

Hotel has different types of rooms. Booking price is depend on th room type and quantity of the booked nights. The cost of cleaning should be considered. If room booked for a long period - cleaning to be made every two days.

Booking price and room types:
Type A: price per night - 1 000, one time cleaning - 400;
Type B: price per night - 800, one time cleaning - 350;
Type C: price per night - 600, one time cleaning - 350;
Type D: price per night - 550, one time cleaning - 150;
Type E: price per night - 500, one time cleaning - 150;
Type F: price per night - 450, one time cleaning - 150;
Type G: price per night - 350, one time cleaning - 150.

Hotel price police has a season increase coefficient:
- the price shall be increased on 20% in midseason (autumn and spring);
- the price shall be increased on 40$ in summer period.

If booking is cancelled - the hotel faced the losses: cost the one time cleaning and price per one night of the room considering season coefficient.

Prediction system budget is 400 000. The prediction system shall Th investments on the system shall be returned during the test period.