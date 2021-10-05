# charlesdoesjavascript
charles did a javascript ?? [javascript thing that I used to make the card and the interactive windows]


|| how to use ||

define plot() and add an event listener for mousemove, e=> { plot(e) }.
now, whenever you move the mouse the selected element ID is moved.

to select an element ID to make changes to, call toggle("id"). if it's already selected,
it will become unselected. if there is no currently selected element, toggle() assigns the provided ID
to the one that is being moved around.

to have a "click and move" functionality, you can bind toggle(id) to an onclick event or something like that.
to manually override the selected element ID, change the variable window.selectedid to the correct ID.

any element with absolute position and an id (container or otherwise) can be moved around. This includes elements 
such as divs, iframes, etc.
