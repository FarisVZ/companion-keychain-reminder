# companion-keychain-reminder

a keychain to help poeple with disability that requires reminders every few hours, it also a little companion with oled display face that can be put on belt loop

# Work In Progress...

## Timeline

### June 22th 2025

**The first version on the project**
the first design was just a simple design to make a minimum req for esp12F to work and 3.3v regulator.

![V1](/Media/V1design.jpg)

### June 26th 2025

Changing some layout and adding more component to the board, that include:
- vibrator motor module
- oled display
    
![V1.1](/Media/V1.1design.jpg)

### June 29th 2025

Adding 2 button for RST and Boot

![V1.2](/Media/V1.2design.jpg)

### June 30th 2025

Trying to make version 2 by rerouting everything and uses bigger component

### July 4th 2025

try to test it with real component and breadboard and find several issue:
- the module doesnt get enough current from the esp so it need a transistor
- only had few gpio to work with (3 for button, 1 for vibrator, and 2 for 12c address)

![Prototype_1](/Media/Prototype_1.jpg)

### July 5th 2025

trying the prototyping again to find another issue, by tweak something:
- adding a menu to oled display
- temporarily change to buzzer for the vibrator
- change into just two button for navigating up and down and implementing press both button to select menu

### July 8th 2025

- adding RTC to prototype
- adding 2n222 transistor so it can run the vibrator module
- go back use 3 button to navigating (up, down, select)
- add time in menu

![Protype_2](/Media/Prototype_2.jpg)
