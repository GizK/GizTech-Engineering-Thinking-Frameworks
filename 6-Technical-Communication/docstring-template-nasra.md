# Example docstring for cleaning data: a community centre's online sign ups

## clean_signups

### Description:
The `clean_signups` function is used to process signups with a simple script that applies title case to the names of users and converting their data into an excel spreadsheet.

    def clean_signups(last_name, first_name, email, phone):
        lastname = lastname.title()
        firstname = firstname.title()
        # pseudocode: transfer into an excel sheet using a separate function, output is a sheet with all the signups
        return signup_sheet
### Input:
Form with **full names** of users, **email addresses** and **phone numbers**.

### Returns: 
Excel sheet with names, emails and phone numbers of users that signed up all placed in rows, with names in title case.

### Example use: 
Use for signups to community programs as there is not enough data to justify the use of a large SQL database, plus Excel is simpler to use for the community centre director who has limited technological use and will need to be able to pass on this data to funding bodies.
