CondensedNotes:

Model: 
  - stores the rating. 
  - Will get updated upon click. 
  - trigger event if no further interaction

View-model, or controller
- fsWidget.interaction: 
  -onMouseOver, behave this way. 
  -onMouseLeave, behave as above.
  -onClick, behave this way.
    -if no further actions, trigger a 'rate' event and send POST

View:
-view with spans
-attach listeners
-logic to find the index (or parent div first)
