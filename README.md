# lab-03b-calculator


##Outcomes

Outcomes show WHAT, HOW we do that, HOW we validate, and WHY we are doing it (the next step?)


- Addition
    - SETUP: We should see 2 user input boxes, a plus sign, a button, and a sneaky hidden box where results are displayed
        - Why input boxes? That's where input lives
        - Why button? button triggers event
        - Why secret box? Place for answer to be displayed
        - Validation: look at screen -->
    1) WHAT: Grab the dom elements (input boxes and buttons) in js using id attribute
        - HOW: Make variables for each dom element, using getElementById
        - Validation: console.log the DOM elements
    2) Add event listener to button
        - Validation: console.log something on click
    3) Get access to what user typed in
        - How: get the .value property of the input element
        - Validation: console.log the user input on click -->
    4) Use input to calculate result
        - Validation: log out result to console
    5) Display result to user
        - We need to grab a secret box and input total into it
        - Validation: total shows on screen

