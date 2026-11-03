Pseudocode solution

INPUT Username:
INPUT Password:

READ database
READ office layout 

IF username & password == username & password on database THEN
  PRINT access granted
  DISPLAY office layout 
  PRINT please select your seat
  INPUT user selects seat/rooms for the day
  PRINT what times do you need the booking for
  INPUT user types in times in 24hour form
  PRINT duration of booking automatically calculated
  PRINT confirm booking?
  INPUT user says yes or no
  DISPLAY office layout with updated settings
ELSE:
  PRINT please retry your password

  
