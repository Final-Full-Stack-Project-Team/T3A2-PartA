WORKING DRAFT:

‌

Grocery shopping list app - Share your shopping list with your household!

There are existing apps out there but they are bloated and have intrusive ads .

The idea is pretty simple. It's a grocery shopping list that you can share with someone.

In a shared shopping list, all people can create, read, update and delete items on their shopping list.

It allows someone to add something to the list when they think of it but if another person in the house pops into the supermarket on their way home, they can check the list and don't have to make contact with other members of the household.

There are many nice-to-haves for this project but it will need to be scaled down in order to meet the deadline of the project.

After the project is submitted I want to add more such as auto adding items - weekly items like bread and milk get auto added to the list, ability to add images to an item, refined UI etc.

Looking to implement the following:

User signup using bcrypt for passwords

User signin page

Users can invite people to share their shopping list via email address.

Email sent to new users has a link to the signup/signin page.

User accounts are stored in Mongo

Shopping lists are stored in Mongo if applicable

Users can create new shopping lists and delete

Users invited to a list can create, read, update and delete items on the shopping list (would like to implement a way for the owner of the list to be the only person who can invite people but this may be dropped if it can't be done in time)

Each item in a list to have a tick box and when ticked, the item is lined out to represent it no longer being needed

The entire shopping list has the ability to be marked as "completed" which will be moved to the "completed" section of the app.