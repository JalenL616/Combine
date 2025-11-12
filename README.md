# Combine: A Middle School Coding Journey
Welcome to the Combine repository! This project is more than just a game; it's a chronicle of my first real journey into programming, starting in middle school. Coded in Python with Pygame, this Minecraft-inspired resource-gathering game was my sandbox for learning some of the fundamental concepts of software development.

The repository is structured into three main iterations, each marking a significant milestone in my understanding of code:
 - **Combine 1:** The brute-force beginning, with no functions.
 - **Combine 2:** The introduction to data structures and better loops.
 - **Combine 3:** The breakthrough moment of using functions and organized files.

**About the Game**

Combine is a 2D game inspired by Minecraft. The core gameplay loop involves:
1. **Acquiring Resources:** Gather basic materials from the game world.
2. **Combining & Crafting:** Use the resources you've gathered to combine into more complcated items.
3. **Progressing:** Unlock new abilities and recipes as you create better equipment.

The goal was to build a simple but expandable crafting system and see how far I could realize my ideas.

**The Story of Each Version**

**Combine 1: The Brute-Force Beginnings**

This was my first attempt at building anything substantial. I had a vision but a very limited toolbox.

Characteristics:
 - **No Functions:** The entire game logic was written in a single, massive script.
 - **Hard-Coding & Copy-Pasting:** Every new item, resource, or interaction was manually copied, pasted, and slightly altered.
 - **Painful Debugging:** A bug in one part of the code often meant it was secretly repeated in dozens of other places. Fixing things was a long and frustrating process.

**What I Learned:** I learned that while you can make something work this way, it's impossible to maintain or expand. This experience taught me the value of not repeating code.

**Combine 2: Discovering Data Structures**

Frustrated with the limitations of the first version, I started learning about how to handle collections of data more effectively.

Characteristics:
 - **Lists and Loops:** I rebuilt the core logic using lists to manage inventory, recipes, and resources. This allowed me to add new items without copying hundreds of lines of code.
 - **Magic Numbers:** While better, the code was still littered with "magic numbers", which made it hard to understand and easy to break.
 - **Expansion:** Despite its flaws, this structure allowed me to expand the game much further than before, adding more items and complexity.

**What I Learned:** This was my first real taste of the power of data structures. I learned that how you organize your data is just as important as the logic that operates on it.

**Combine 3: The Power of Abstraction**

This is where everything finally started to click. After learning about functions and modularity, I was able to approach the problem like a real programmer.

Characteristics:
 - **Functions:** I broke down the massive script into reusable functions with clear purposes (draw_inventory(), check_crafting(), handle_player_input()).
 - **Separate Files:** I organized the code into multiple files. A file for gameplay, graphics, and functions.
 - **Rapid Progress:** This organization was a game-changer. Debugging was easier, adding features was faster, and the code was finally readable. This version saw the most progress by far.

**What I Learned:** I learned that abstraction is the key to managing complexity. By breaking a huge problem into smaller, manageable pieces, I could build things easily and efficiently.

**Technologies Used**

 - Language: Python
 - Library: Pygame (for graphics, sound, and user input)

**Final Reflections**

My middle school programming journey went mostly unguided without specific programming courses. I didn't take an optimal path, I restarted my code each version and wrote everything from scratch. I dealt with painful debugging and slow trial and error growth.
But the experience I came out of it with was totally worth it. I now have seared in my mind the instinct to not copy and paste code in a way an acronym like DRY could never affect me. And I've seen firsthand how essential functions are for creating an expandable program. These are lessons I keep with me everytime I code.


