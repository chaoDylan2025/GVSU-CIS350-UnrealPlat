# Overview

The purpose of this document is to outline the software requirements for the platformer we are developing. The game should follow the software requirements and provide an enjoyable experience for the player.

# Software Requirements

This section is divided into functional and non-functional requirements that have 15 requirements for each category.

## Functional Requirements

### Player movement 

1. The system shall have a character that can jump 3 blocks and have an ability that allows the character to jump an additional 3 blocks mid air.
2. The system shall have the stamina bar regenerate after 5-10 seconds when player uses up the stamina bar.
3. The player shall dash when left shift is pressed.
4. The player shall dash 4 blocks forward when dashing. 
5. The player shall use 20 stamina units when player uses dashing.

### Combat

6. The player shall be able to attack enemies.
7. The player shall be able to deal damage to the deceased enemy AI.
8. The player shall be able to take damage from enemy AI.
9. The player shall be able to attack 2 blocks in front of the enemy AI.
10. The player shall be able to attack when left click has been pressed.

### Enemy AI

11. The enemy AI shall play an attack animation if player is within their sight.
12. The skeleton enemy AI shall be in an idle animation when the player is out of their sight.
13. The skeleton enemy AI shall be able to follow player when they see the player.
14. The deceased enemy AI shall take damage when player attacks it. 
15. The deceased enemy AI shall play a death animation and disappear when the health is less than or equal to 0. 

## Non-Functional Requirements

### Level requirements 

16. The level shall use a high quality tile set.
17. User interface layout must be simple for player health and stamina bar.
18. The level shall have enemies.
19. The level shall have platforms for the player to jump on.
20. The level shall have background elements.

### Player feature 

21. The player shall be able to move mid air.
22. The player shall have animations play correctly that reflect their current action.
23. The player shall not clip into walls when they dash.
24. The player character shall fit in the environment theme.
25. The player shall have an easy to use control scheme.

### Enemy AI Requirements 

26. The enemy AI shall be able to target and try to kill the player.
27. The enemy AI shall be able to move to the player.
28. The enemy AI shall have a path of movement that does not depend on the player.
29. The enemy AI shall move back to its path of movement when player is out of sight.
30. The enemy AI shall lose interest in the player after losing sight of the player.



# Software Artifacts

This section shall provide links to all of the artifacts that we have developed for this project.

* [Use case diagram for abilities](../artifacts/use_case_diagrams/Abilities-Usecase-Diagram.pdf)
* [Use case diagram for combat](../artifacts/use_case_diagrams/Combat-Usecase-Diagram.pdf)
* [Use case diagram for level mechanics](../artifacts/use_case_diagrams/Level-Mechanics-Usecase-Diagram.pdf)
* [Power up ideas for the platformer](../artifacts/Power_Up_Ideas_For_Platformer.pdf)
