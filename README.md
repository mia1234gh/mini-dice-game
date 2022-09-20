State exercise:
![image](https://user-images.githubusercontent.com/91407952/191259328-f6004d23-5d4b-4bbf-b0c3-db3409a5c206.png)
1. Make two components:
RollDice - a parent component (rendered by App) that renders the dice and a button to roll.
Die - an individual die that takes props and displays the correct face of the die based on props.
2.Dice.js
Font Awesome : https://fontawesome.com/icons/dice-one?style=solid
<i class="fas fa-dice-one"></i>
3.Rolldice.js
the state for both of the dice
a roll() method that rolls them to randomly get a new result-->Math.floor(Math.random())=>use defaultProps to set an array of six possible faces for each die
4.Animation
@keyframes makes two dices shakeing when user click button.
