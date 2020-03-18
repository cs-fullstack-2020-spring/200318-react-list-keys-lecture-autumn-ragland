## Review
React Components: Passing Props/Lifting state
Create a NEW react app called 'click-counter-app'
1. Create a top level 'AppContainer' component that has:
    - An H1 element title 'Play the Game'
    - A 'grand_total' integer property in its state.
    - An H3 element that displays 'Total Score [WHATEVER_TOTAL_FROM_STATE]' from the component's state.
2. Create a 'Player' component that:
    - Accepts a 'playerName' and 'addToScorecallBack' function reference via properties
    - An H3 element that displays the name of the player (from 'playerName' prop)
    - A button that when clicked will call the callback function
3. From your top level AppContainer component:
    - Render the 'Player' component and pass in the 2 props
    - Each time the user clicks on the Player button, the top level AppContainer component should update it's 'total score' value/property in state which should result in the new total H3 to be updated.
