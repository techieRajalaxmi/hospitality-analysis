# hospitality-analysis
## README for Hotel Booking Data Analysis Project

### Project Overview

This project involves analyzing hotel booking data to gain insights into customer behavior, booking trends, and hotel performance. The dataset consists of five CSV files containing various dimensions and facts related to hotel bookings.

### CSV Files Description

The project includes the following CSV files:

1. **dim_date**: Contains metadata about dates relevant to the booking data.
2. **dim_hotels**: Contains information about different hotels.
3. **dim_rooms**: Contains details about room types available in the hotels.
4. **fact_aggregated_bookings**: Contains aggregated booking data for analysis.
5. **fact_bookings**: Contains detailed booking records for individual customers.

### Column Descriptions

#### dim_date
- **date**: Represents the specific dates in May, June, and July.
- **mmm yy**: Displays the date in the format of "monthname year."
- **week no**: Unique week number corresponding to each date.
- **day_type**: Indicates whether the day is a Weekend or Weekday.

#### dim_hotels
- **property_id**: Unique identifier for each hotel.
- **property_name**: Name of the hotel.
- **category**: Class of the hotel (e.g., Luxury, Business).
- **city**: Location of the hotel.

#### dim_rooms
- **room_id**: Identifier for each type of room (e.g., RT1, RT2).
- **room_class**: Classification of room types (e.g., Standard, Elite).

#### fact_aggregated_bookings
- **property_id**: Unique identifier for each hotel.
- **check_in_date**: Dates when customers check in.
- **room_category**: Type of room booked (e.g., RT1, RT2).
- **successful_bookings**: Count of successful bookings for each room type on a specific date.
- **capacity**: Maximum number of rooms available for each room type on a given date.

#### fact_bookings
- **booking_id**: Unique identifier for each booking.
- **property_id**: Unique identifier for each hotel.
- **booking_date**: Date when the booking was made.
- **check_in_date**: Date when the customer checks in.
- **check_out_date**: Date when the customer checks out.
- **no_guests**: Number of guests staying in a room.
- **room_category**: Type of room booked (e.g., RT1, RT2).
- **booking_platform**: Method used to book the room (e.g., website, app).
- **ratings_given**: Customer ratings for hotel services.
- **booking_status**: Status of the booking (e.g., Cancelled, Checked Out, No Show).
- **revenue_generated**: Total revenue generated from a booking.
- **revenue_realized**: Final revenue received by the hotel after considering booking status.

### Usage

This dataset can be utilized for various analyses including:

- Booking trends over time
- Performance comparison between different hotels
- Revenue analysis based on booking statuses
- Customer behavior insights based on ratings and platforms used

### Requirements

To work with this dataset, ensure you have the following tools:

- Python or R for data analysis
- Libraries such as Pandas, NumPy, and Matplotlib for data manipulation and visualization

