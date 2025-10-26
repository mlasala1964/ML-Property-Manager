------------------------ *Property Manager by Mark Lasal - ML -* --------------------------------------------


#                       ML-Property-Manager 


## Solution : 
   It loads the booking data from Google spreadsheets to a DWH featured by :-) **sqlite3** relational database in memory.
   
   Running simple SQL on the just created relational DB, the app presents interesting insights as like as:
   
   - Summary key metrics cross structures and by structure
       
   - Top 5 most profitable stays / bookings and bottom 5 least profitable ones
       
   - Top 5 most profitable months and bottom 5 least profitable ones
       
   - ....

   The solution wants as inputs:
   - GoogleSheets where are tracked all the historical bookings, past and future
   - "Structures": python list of Structures to manage. Each Structure is described (name, spreadsheet name, ... ) as a python dictionary  

   The user interaction and presentation is designed on **streamlit**.
   
   The tech stack is:
   - **gsspread**: to manage google sheets
   - **sqlite3**: to create and manage the relational DB. The initial version create it in memory
   - **streamlit**: to manage simple multi-page web app for sharing the insights with users    
   
   The target deploy is on streamlit cloud
   


