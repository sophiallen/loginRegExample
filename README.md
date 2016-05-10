# loginRegExample
Notes:
- new empty website, add ado data entities model, **remember to add stored proceedures!* and save the data entities diagram right away. 
- Add new WCF Service
- In the interface, declare the methods that you want (we added contracts for registerReviewer and reviewerLogin. 
- In the service, hover over interface name to implement interface, and create new instance of bookreview db entities. 
  - use the stored proceedures from the db entity to do the work you want. Remember to pass in arguments in the correct order. 
- Note for assignment: it might be helpful to create a datacontract class for the venue, to make for easier access later. Don't name it venue, but something else that's descriptive. 
