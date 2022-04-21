 Class 14: Psych Safety and Reinstantation 

## Psychological Safety

- Safety among teammates.


## Code Review
- All your javascript data about Products needs to survive a page refresh:
  - Using localStorage
    - Implementing was not a huge ask
      - Required storing an object as string
      - and converting that string back into an object using:
        - localStorage.getItem
        - localStorage.setItem
        - JSON.stringigy
        - JSON.parse
  - What places are continuing to struggle or previous features.

- Code organization: 
  - Global variables at the top of the page
  - Functions have their own space in your code
  - Constroctors have their own space
  - Leave comment blocks to help me organize 
  - Write stuff in README.md (now and in the future)
    - Document my code, how it should be used and how you name variables. Helps others decipher my code 

README.md
  # Lab - Class XX
  ## Project: Project Name Here
  ### Author: Student/Group Name
  ### Links and Resources:
    - www.whatever.com

  ### UML (Universal Modeling Language)
  - Diagram how the project fits together
    - What features your project completes

  ## Javascript

  ## Global Variables
  - Product.allImage: this is an array that stores all our ProductImages that get rendered to the HTML




## Re-Instantiation
- An object literal is not quite the same thing as an object from a constructor.
  - If there is anything associated with the prototype we need to "re-instantiate"


Constructor Object vs Object Literal 
Constructor builds a house, object literal is smaller scope more like an individual 


USE 'TODO' in js
use css
do not modify html
one person forks, and we add other as collaborator , whomever forked the repo needs to push to the repo
Going to have to use DOM methods to create methods in the html.index #1 
cart.html - delete this item button will erase from the DOM
to clear the feilds, do something to the event object itself
- Focus mostly on getting the button click to add and store quantities 
- and get remove button to work!

