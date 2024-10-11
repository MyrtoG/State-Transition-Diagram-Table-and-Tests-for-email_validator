  This project is part of the unit on Testing Techniques of the Maker's Academy QE course.
It is an intoduction to creating tests following a state and transition technique, where each state represents a page of the website,
and each transition/event represents an action you do to transition from one page to another (e.g. sign up).
  
  The project takes a simple website in which the only actions you can do is sign up and after you have signed up,
go back to the sign up page to try and sign up again.
If the email you enter is not valid, you get a message at the top of the sign up page that warns you that the email is invalid.
  This means that you have two states, one is the sign up page and the other is the signed up page.
You have three transitions/events; one for the invalid email entry, one for the 'sign up' action and one for the 'go back' action.
  
  According to the above, I have created a table displaying the connections between the states and the events and, based on that
I have created two tests. One covering all states at least once and one covering all transitions at least once.
  
  Thank you!
