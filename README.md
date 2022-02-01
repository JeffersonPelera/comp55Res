# Adding character abilities
## Overview
<ol>
  <li>each character can correspond to a power up</li>
  <li>fire dragon: higher bonues points</li>
  <li>water dragon: better slow</li>
  <li>air dragon: longer multiplier duration</li>
  <li>earth dragon: longer invulnerability</li>
</ol>

## Pseudocode
To create functionality for characters first get the type <br />
Inside the determinePower method is where all of the coding will be done <br />
if the dragon is fire double the bonus points from the usual <br />
if the dragon is water make the movement 60 percent slower <br />
if the dragon is air make the multiplier power up last twice as long <br />
if the dragon is earth add 5 extra seconds of invulnerability <br />

## Implementation Checks
### Fire Dragon Implementation
<ol>
  <li>Initially all the other dragons in the beginning of game gain 100 points to score when picking up the bonus powerup item</li>
  <li>To test the fire dragon change we play the game and see that the points gained from the power-up is 200</li>
  <li>To make sure there is no other change we look at the other dragons to see if it's 100</li>
</ol>

### Water Dragon Implementation
<ol>
  <li>This was implemented in a way that modifies the movement modifier</li>
  <li>The movement modifier is 60% for the water dragon while the others where at 80%</li>
  <li>Through gameplay testing the change can be seen visually</li>
</ol>

### Air Dragon Implementation
<ol>
  <li>There is visual indicator for when the player has picked up a multiplier power up</li>
  <li>When coding a local duration variable was added to be changed depending on the player type</li>
  <li>When the character is an air dragon, the visual indicator for the score is pink, but red when it's the others</li>
  <li>This visual indication shows that the implimentation was complete</li>
</ol>

### Earth Dragon Implementation
<ol>
  <li>The invulbar was changed to show that the the dragon was invulnerable for 12 seconds instead of 7</li>
  <li>The visual change can be seen when playing the game because the invulnerability bar to show is longer when playing the earth dragon</li>
</ol>
