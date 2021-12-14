[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=6025932&assignment_repo_type=AssignmentRepo)
# Project Notes

Project Instructions: https://vuxcode.netlify.app/pr1/lessons/major-project-brief/

> You can use this section of the file to keep notes about your project as you work on it.

REMEMBER TO "COMMIT" YOUR CHANGES TO THIS FILE!

10/18 - I'm having a bit of trouble currently, it seems I've gotten a bit confused by how to write it.

10/22 - The beginning was a bit easier to structure but as soon as it came to math, it became a bit harder. I've been looking at other places than just vuxcode for better understanding of how I can write the code.

10/29 - It has gotten much easier once I began structuring the systems on which the game will be based on. Both attack, defend and ending the battle have been implemented. Even the levelling system is looking better by each change.

11/08 - Had a bit of trouble with what could be added onto the adventure but finally got around to getting started with the merchant.

11/15 - Found a bug with the healing system that had been there for a while. Fixed it.

12/02 - It has gotten a bit tiring to work on this project with only a few weeks left. My head is just full of new information.

12/06 - I am pretty much finished with the project, it has the implemented system and functions that I planned for. It also has an ending and the structure of the code seems semantic.

# Project Summary

> Remember that before the final submission date you should include a "PROJECT SUMMARY" in this section here. 

This project is a mostly text based adventure game. You play as a cultist where the purpose of the game is to level up your character until you can fight the final boss. For every battle that you enter, there is a random enemy that will be picked from a list. If you successfully defeat the enemy then there is a reward of 50 experience and a certain amount of money. This money, like the damage done in battle, is randomly assigned from a value between two numbers. Furthermore, after each battle you may level up which results in your health increasing by 100. This also means that each enemy after the level up will also have increased health, around 80% of the player's. You may travel to different destinations but the enemies you encounter will still be the same. There is however one unique destination where you can encounter a merchant. This merchant will trade you potions in exchange for the money you have acquired. You can click talk to bystanders to get hints about the game. The final boss has a set amount of health so if the player grinds for levels then they may have an easier time defeating it.

I've had quite a bit of fun with developing this project. The development did not have that many issues, everything I have done with it has felt very logical and less taxing than the web development course. Most issues I have had were mostly because of errors caused by me, things like brackets being put in the wrong place and bad grammar.

If I could improve something it would be the amount of content. It feels very short and the story is very barebones. There are also a number of features like different enemies in different locations, more shop items and a skill system. Regarding skills, it would have been more fun for the players to actually develop their characters themselves instead of the very basic system that is currently in place. I would also implement a save system so your character is stored in the browser.

When it comes to the budget, I have gone way lower than the expected time. I didn't manage to stick to the budget, if I had then there would have been way more things to do outside of the current content. Everything I wrote in the project plan has been added with some additions like the shop and money system. Like I said in the project summary for the other project and it is also way too hard to stick to a certain schedule when you're a fast writer. Even the time I said that I needed for the project was still 5 hours more than I have currently put in. 

# User Guide

> Write a clear user guide for how someone should use your program.
Write in your name in the text box, read through the text in the boxes and click okay each time you're done reading. After you have clicked away all the boxes, you may decide your next step. Right click and left click the 'Inspect' option to look at the console log.
Clicking locations will display all the available locations you may currently visit. 
Clicking move will display a box asking where you want to go, write in one of the locations from the locations button and you will be transported there. 
Clicking attack will make a random enemy appear, this will lead to a textbox asking which move you wanna use. Writing in attack will make you attack the enemy and vice versa resulting in both parties losing health. Writing in defend will negate some of the damage from the enemy attack. Writing in heal will ask you what kind of potion you wanna use, write in either small/small health potion or big/big health potion to heal yourself. This will result in you regaining some health to further minimalise the risk of death. If the enemy loses all their health then you win and gain some money plus experience. Hpwever, if you lose then you gain nothing.
Clicking character will display a box containing information about you, the player. Here you can see your name, class, current level, amount of experience, money and current health.
Clicking merchant will let you travel to the store. In the store there are potions that you can buy from the clerk in exchange for trypkels, this world's currency. She will ask you if you wanna buy some potions, writing yes will lead to a second screen while anything else will remove you from the store. After saying yes, she will ask you how many potions you wanna buy. Writing in a number will multiply that by the price and if you don't have enough then you will be kicked out. If you do have enough then the specified amount of money will be removed from your character and you will gain the amount of potions you wrote in.
Clicking talk to bystanders will lead to you speaking to an NPC (Non-Player Character). This character will give you a hint that is stored in the console log.
When you reach a certain level, a box will pop up asking you if you are ready to fight the final boss. Saying yes will start the final battle and anything else will let you continue on like earlier until the next level up. The final boss battle works like any previous battle, except that the boss has a set health and does not scale with the player. The boss also does not attack after the player heals compared to regular enemies.
Defeating the boss will lead to a sound playing and declaring you a winner that destroyed the world. After this the window will close.
