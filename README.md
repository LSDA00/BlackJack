# BlackJack
This C++ program allows the user to face-off against the computer at a high stakes game of blackjack!
Description: This program uses the random generation of numbers to play a game similar to Blackjack. 
Input: The user will input y to indicate yes and any other character to indicate no. 
Output: Outputs a first set of numbers, a second set of numbers, a prompt for the player to add to their total, bust messages for both the computer and the player, numbers the computer has drawn, computer and player final totals, winner of the game. 
Algorithm: 1. Welcome, 2. Give first number to player & computer. Computer first number=hidden, 3. Give second set of numbers, show both, 4. Loop until answer given by player is no: "player: total=x. Another number? (y/n)". *Make total reflect addition of subsequent numbers*
,5. Computers turn, 6. Reveal computer "hidden" number, 7. computer draws until computer total is greater than or equal to 17, 8. Compare totals from player and computer, 9. If player total is closer to 21 than computer total than player wins, 10. Give error messages if either computer or player exceeds 21.
