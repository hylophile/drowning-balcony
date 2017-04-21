# drowning-balcony

This project aims to realize a watering system for a balcony.
## Questions:
### Do we need multiple humidity sensors?
Different plants have different needs. It's okay to use one sensor for one large pot if there's only one type of plant.
### Do we need multiple water pipes?
- If the plants are in one row in multiple balcony troughs :seedling::seedling::seedling::seedling:, we will use a servo motor to move one single pipe along them. Of course the pipe is connected to water supply and a pump. The motor and the pump are both controlled by a microcontroller.
- ~~Use one pipe with multiple valves that are opened electronically.~~ This is way too expensive.
  
- If we want to water multiple:seedling:pots, we can either use multiple pipes or control one pipe with a:seedling:motor and spray the plants, knowing:seedling:the angle and pressure needed. This:seedling:has been done [here](http://www.instructables.com/id/Arduino-Automatic-Watering-System-For-Plants/?ALLSTEPS).
