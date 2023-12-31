# Brian's Virtual Pet Shelter

In this project, I created a VirtualPetShelter class that uses a HashMap to hold multiple pets a user creates and can interact with. This includes a tick method that effect's the pet object's elements such as: Hunger, Thirst, Mood, and Tiredness/Rest levels. Those stats can then be raised by the user interacting with their pets; feeding them, watering them, etc.  User can also have pets be adopted/removed from the shelter and end the game whenever they're finished. There are a few more features I would love to add, but will have to be added at a later time. Below are required tasks that have been checked to show completion. Hope you enjoy the Application!

# Required Tasks
## VirtualPetShelterApp Class
Create a main method that…
- [X] Implements a game loop.
- [X] Asks for user input.
- [X] Writes output to the console.
- [X] Calls VirtualPetShelter's tick method after each interaction
- [X] Action that feeds all the pets
- [X] Action that waters all the pets
- [X] Playing with an individual pet, which should display a list of pet names and descriptions, allowing a user to select one.
- [X] Allow the adoption of a pet, which should display a list of pet names and descriptions, allowing a user to select one.
- [X] Allow intake of a pet, prompting the user for the pet's information, requiring the user to (at minimum) specify name and description.
      
## VirtualPetShelter Class
- [X] Include appropriate instance variable(s) to store the pets who reside at the shelter.
- [X] Include methods that:
  - Return a Collection of all of the pets in the shelter
  - Return a specific VirtualPet given its name
  - Allow intake of a homeless pet (adding a pet to the shelter)
  - Allow adoption of a homeless pet (removing a pet from the shelter)
  - Feed all of the pets in the shelter
  - Water all of the pets in the shelter
  - Plays (or performs some other interaction(s)) with an individual pet in the shelter
  - Include a tick method that calls the tick method for each of the pets in the shelter, updating their needs
      
## VirtualPet Class
 - [X] Include instance variables representing:
   - Name (from the above example, this might be "Tommy")
   - Description (from the above example, this might be "smells like a Stargazer lily fresh with morning dew")
   - Include a constructor that accepts a name and description
   - Include a constructor that, in addition to name and description, accepts default values for the pet's attributes (hunger, boredom, etc)
   - Do not include a default (zero arguments) constructor.
