A docstring to show how users might book a desk at the office

Description:
This function asks for the users desk_number that they want to book, the time they want to start the booking time_start and time_end to book a desk at the office.
The function will calculate the duration and whether that spot will be free.

def book_desk(desk_number, time_start: int, time_end: int, email):
  """ Get the desk reservation details
  Args: 
    desk_number: The number of the desk that they got 
    time_start: The time they want to book from
    time_end: The time the booking ends
    email: email they want the booking sent to
  Returns:
      int: time_end - time_start = booking 
      if booking =! to a booking on the database then:
      return booking and desk_number to email
  Raises:
    Error: if time_start > time_end
    DuplicateError: if another user already has booked the desk_number in the booking times
    
  """

  
  
