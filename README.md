# InLab3GameEngine
Laith Ghannam 100895645
Bumper car! - Get to the exit while avoiding contact with the maze walls or else you die!
Using Observer Design pattern, this is the diagram:
<img width="732" height="547" alt="image" src="https://github.com/user-attachments/assets/23b8fb14-382a-48c6-988b-ec90889080cf" />

Reflection answers:
1. The IHealthObserver and PlayerHealth files both successfully implement the Observer design pattern where IHealthObserver contains the list of observer variables(currentHealth, maxHealth) and changes whenever called inside PlayerHealth (OnCollision the currentHealth decreases) and by using a singleton GameManager the UI inside the game displays any changes to the health whenever called on collide in text form.
2. The reason why the Observer Design pattern is the best design pattern to use for my game is because the game is very simple and does not require any input changes that can be processed by using a Command design pattern, and by using the Observer design pattern I can implement multiple variables in the future that can allow the player to take more damage from specific surfaces or the ability to heal by touching powerups, which will allow me to develop more levels that are even harder than the first level. It also helps since this is the simplest way to create a health system for a player.

