## TSE/TOE Tech Test Solutions
###### by Kelly Williams

1. Question One: News Feature
  - For the fictional customer that wants to display their news on the app I would suggest creating a News Channel right from the Content section of their Administrator portal for Staffbase.  In addition to using the Staffbase GUI to manually create new Channels and Posts, the Staffbase API supports integration with the News section.  The API can be used to create new channels and publish new posts.
  - If their preexisting system generates news daily and they do not want to manually update it each day, the Staffbase procedure for Automatic CSV Imports almost certainly could be used to automatically update the News section of their app, not only for onboarding new users.  I would help them set up the Automatic CSV Import to automatically generate new posts to their New Channel or Channels.

2. Question Two: Mapping Issue
  - The customer attempting to set up Automatic CSV Imports is very close, they are just missing one item.  The mapping they are using accounts for first name, last name, position, and email, however they are missing one very important field: a unique ID.
  - As I was approaching the problem, I studied the Automatic CSV Import instructions carefully, as well as the other documentation on the Staffbase support and developer portals, specifically the CSV File Examples provided by Staffbase. It became clear to me that they were missing a unique ID.  It says plainly in the instruction manual, **“Please be aware that every user needs an unique identifier that will be used as external ID in Staffbase.”** I would instruct the customer to add that column to their CSV file and to update the mapping accordingly.

3. Question Three: Updating Profile Pictures
  - I chose to use Python to complete this task.  The script can be found in the file  upload_avatars.py, and these images I used are stored in the images folder.
  
Thank you once again for the opportunity, please do not hesitate to contact me with any questions, comments, or concerns about my solutions, my code, or any other aspects of my application to Staffbase.

Have a wonderful day!

Kelly Williams, 5/7/19
