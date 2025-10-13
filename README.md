------------------------ Property Manager by Mark Lasal - ML - --------------------------------------------

#                                   ML-Property-Manager 

# Solution : 
   It loads the booking data from Google spreadsheets to a DWH featured by :-) sqlite3 relational database in memory.
   On this database are executed SQL in order to have interesting  insights as:
       - Summary key metrics cross structures and by structure
       - Top 5 most profitable stays / bookings and bottom 5 least profitable ones
       - Top 5 most profitable months and bottom 5 least profitable ones
       ....

   The user interaction and presentation is designed on streamlit
   The target deploy is on streamlit cloud
   
   The solution is based on:  
    - GoogleSheets where are tracked all the historical bookings, past and future
    - "Structures": python list of Structures to manage. Each Structure is described (name, spreadsheet name, ... ) as a python dictionary  
