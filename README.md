𝗧𝗮𝘀𝗸-𝟮(𝗖𝗮𝗹𝗰𝘂𝗹𝗮𝘁𝗼𝗿):-

In the Task-2 , there are several functions defined to perform basic arithmetic operations such as addition, subtraction, multiplication, division, and exponentiation on two numbers. After defining these functions, the code prompts the user to input two numbers and an operation choice. Based on the user's choice, the code then performs the calculation using the defined functions and displays the result. If the user chooses an invalid operation, an error message is displayed. This code essentially acts as a simple calculator allowing users to perform basic arithmetic operations on two numbers.

𝐓𝐚𝐬𝐤-𝟑(𝐏𝐚𝐬𝐬𝐰𝐨𝐫𝐝 𝐆𝐞𝐧𝐞𝐫𝐚𝐭𝐨𝐫):-

 It starts by prompting the user to input the desired length for the password. This input is then stored in the variable length after being converted to an integer using the int() function. Following this, the script presents the user with a menu to select the character set for their password. The available options include letters, numbers, special characters, and an option to exit. The user's selections are then used to build a character list, which is represented by the variable characterList.

To construct the password, the script utilizes a loop that runs for the specified length. Within the loop, it picks a random character from the characterList using the random.choice() function and appends it to the password list. Once the loop finishes, the random characters in the list are joined together as a string using the "".join(password) syntax and then printed as the final random password. The user is then provided with the generated random password for their use.

Overall, this script enables users to create unique, randomized passwords based on their specified preferences for length and character set.

𝗧𝗮𝘀𝗸-𝟰(𝗥𝗼𝗰𝗸-𝗣𝗮𝗽𝗲𝗿-𝗦𝗰𝗶𝘀𝘀𝗼𝗿𝘀):-

 This game begins by displaying the rules for winning in the game, providing a clear explanation of the potential outcomes for each combination of choices. It then enters an infinite loop, allowing the user to repeatedly play the game until they choose to stop.

Within this loop, the user is prompted to input their choice, represented by the numbers 1 for Rock, 2 for Paper, and 3 for Scissors. The code includes input validation to ensure that the user's choice falls within the specified range. It then assigns the corresponding text labels (ROCK, PAPER, or SCISSOR) to the user's input and displays their choice.

Next, the computer makes a random choice using the random.randint() function for the numbers 1, 2, or 3. Similar to the user's choice, the computer's selection is mapped to the corresponding text labels and presented to the user.

Following this, the game evaluates the choices to determine the winner. It calculates the result based on the combinations of the user's and computer's choices, incrementing the score for the winner and providing an option to play again. The game continues indefinitely until the user chooses to stop.

At the conclusion of the game, the code thanks the user for playing and gracefully exits. 
