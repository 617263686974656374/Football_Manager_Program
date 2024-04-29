# Football_Manager_Program
This Java-based Football Manager program allows users to simulate the management of football clubs, teams, players, and trainers through a comprehensive menu-driven interface.
It facilitates operations such as creation, modification, and display of football entities, making it ideal for enthusiasts looking to understand the basics of sports management in a controlled environment.

### Key Features
- **Club Operations:** Users can create new clubs by specifying a name and the year of establishment. Clubs act as containers for multiple teams and provide a structured approach to manage various aspects of a football club.
- **Team Operations:** Within each club, users can add or remove teams. This feature allows for detailed management of a club's internal structure, including assigning players and trainers to teams.
- **Player Management:** The program allows for adding players to a free pool or directly into a specific team within a club. Users can manage player transfers between teams or clubs, as well as remove players from teams.
- **Trainer Management:** Similar to player management, trainers can be added to teams, transferred, or removed. This feature ensures that each team can be equipped with the appropriate coaching staff.
- **Dynamic Interaction:** Through various menus, users can interactively manage all aspects of the clubs, teams, players, and trainers. This includes transferring players and trainers between teams or clubs based on the user's decisions.

### Program Structure
- **Main Class:** Serves as the entry point for the program, initiating the user interface and handling the main menu interactions.
- **Entity Classes (Club, Team, Player, Trainer):** These classes define the properties and methods for the main entities managed within the program. Each class contains methods for adding, removing, and listing its respective entities.
- **Function Class:** This class is central to the application's functionality, providing mechanisms to handle all operations related to clubs, teams, players, and trainers. It manages the lists of each entity and controls the flow of the program based on user input.

### Usage Example
When the program is run, it displays a main menu with options to manage different entities:
```
Welcome in Football Manager
[1] Club
[2] Team
[3] Player
[4] Trainer
[0] Exit program
Enter index of your choice:
```
Users can navigate through these options to access specific sub-menus for each entity type, allowing them to perform detailed management tasks such as adding new teams to clubs, assigning players to teams, or managing trainers.

By following the prompts and selecting appropriate options, users can simulate a comprehensive football management experience from their terminal.
