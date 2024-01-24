# Vadis Game

## General Description
Example scripts developed as a member of Jelly Pidgeon Studios for medieval roguelike game based on the slavic mythology.

Recently I have implemented player's death feature, improved animations for hp/stamina bar, implemented multi-scene architecture

## Currently Developed Systems
Systems currently developed by me consist of (not all are included in the example code):
- Player's interaction with different objects
- Picking up items and adding them to an inventory
- Inventory with description of every item after pointing it
- Equipment of armors and weapons with a preview in the inventory
- Adding items to quick slots
- Bow managing with usage of Object Pooling for arrows
- Animation Rigging, Changing camera while aiming
- Dependency Injection with Zenject
- Multi-scene Architecture
- Animations for Pefect Aiming feature
- Player Death Management with Restarting Game after death occured
- Melee Fight with block possibility that reduces incoming damage
- Stamina regeneration over time
- UI Animations with DoTween

## Sample Code Description
Example code consist of seven classes:
- **UIBaseItemInventoryManager** - base class responsible for handling and displaying item slots
- **UIQuickItemInventoryManager** - class derived from UIBaseItemInventoryManager to handle quick items
- **UIItemSlot** - base class for all UI inventory slots
- **UIQuickItemSlot** - derived class from UIItemSlot to deal with logic dedicated to quick items
- **UIInventoryManager** - class responsible for displaying inventory tab in UI, as well as description of pointed item
- **Item** - base class for all created items
- **BaseFightManager** - base class for handling fight logic with different types of weapon

## Current Progress
### [Demo Movies](https://drive.google.com/drive/u/1/folders/1-9xJ1gSEDy4d149fdS8M07nTynlMtNPo)

### Screenshots
<img src="./Screens/Aiming.png" height=50% width=40%> <img src="./Screens/Boss Fight.png" height=50% width=40%>
<img src="./Screens/Interaction.png" height=50% width=40%> <img src="./Screens/Inventory.png" height=50% width=40%>
## Contact
- Developer: [bartosz.pokorski67@gmail.com](mailto:bartosz.pokorski67@gmail.com)
- Studio: [jellypidgeonstudios@gmail.com](mailto:jellypidgeonstudios@gmail.com)

