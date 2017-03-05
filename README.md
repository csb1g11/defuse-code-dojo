# defuse-code-dojo
 -  Welcome to this code dojo!
 - The aim is to have fun, work with different people, and explore different approaches to a challenge over the next couple of hours
- You can use whatever language your team decides
- You will not be required to submit the code

### Layout
- 15 minute setup and introduction (refreshments will be available)
- 1 hour coding, ask questions, explore different techniques and try to meet the milestones
- 15 minute wash up, discuss different approaches and demos

### Challenge
- You need to cut the right wires! That is, cutting wires in the right order will defuse the bomb but cutting them in the wrong order or cutting none at all will make it explode

### Part 1
- If you cut a white cable you can't cut white or black cable
- If you cut a red cable you have to cut a green one
- If you cut a black cable it is not allowed to cut a white, green or orange one
- If you cut a orange cable you should cut a red or black one
- If you cut a green one you have to cut a orange or white one
- If you cut a purple cable you can't cut a purple, green, orange or white cable

- For each input, you should print out whether the bomb exploded or was safely defused
- 1)  ['white', 'red', 'green', 'white']
- 2)  ['white', 'orange', 'green', 'white']

### Part 2
- Start with either with a white or a red wire
- If you picked white wire you can either pick another white wire or you can take an orange one
- If you picked a red wire you have the choice between a black and red wire
- When a second red wire is picked, you can start from rule one again
- Back to the second rule, if you picked another white one you will have to pick a black or red one now
- When the red wire is picked, you again go to rule one
- On the other hand if you then picked an orange wire, you can choose between green, orange and black
- When you have to choose between green, orange and black, if you pick either green or orange then choosing the other one will defuse the bomb
- If you ever pick a black wire you will then have to choose between green, orange and black

- For each input, you should print out whether the bomb exploded or was safely defused
- 1)  ['white', 'white', 'red', 'white', 'orange', 'black', 'black', 'green', 'orange']
- 2)  ['white', 'white', 'green', 'orange', 'green']
- 3)  ['white', 'white', 'red', 'red', 'red', 'white', 'white', 'black', 'green', 'orange']
- 4)  ['white', 'black', 'black', 'black', 'black', 'green', 'orange']
- 5)  ['black', 'green', 'green']
- 6)  ['red', 'red', 'white', 'orange', 'black', 'green']

### Part 3
- Given a set of wires and their quantity, determine whether the bomb can be defused

- For each input, print out whether the bomb can be defused
- 1)  {'white': 4, 'red': 3, 'black': 4, 'green': 1, 'orange': 1}
- 2)  {'white': 4, 'red': 3, 'black': 4, 'green': 0, 'orange': 1}
- 3)  {'white': 3, 'red': 1, 'black': 48, 'green': 1, 'orange': 2}
- 4)  {'white': 3, 'red': 1, 'black': 48, 'green': 1, 'orange': 1}

### Where are these challenges from?
- These are reddit daily programmer challenges which I have consolidated into one place. You can visit the originals using the links below, but please don't do this until you've attempted them! 
-- https://www.reddit.com/r/dailyprogrammer/comments/5e4mde/20161121_challenge_293_easy_defusing_the_bomb/
-- https://www.reddit.com/r/dailyprogrammer/comments/5emuuy/20161124_challenge_293_intermediate_defusing_the/
