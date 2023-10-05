# Event Modification for Victoria 2

This is a custom event for the game Victoria 2, which allows the player to conquer an enemy country during a war, if certain conditions are met.

## Event - Conquer an Enemy Country

The event, called "Conquest Event," will be triggered when the player meets specific conditions.

### Requirements for the Event

- The in-game year must be 1840 or later.
- The player's country must be a great power.
- The player must be at war with only one country.
- The player must have invaded at least one core of the enemy country.

### Available Options

The player will have three options to choose from:

1. **Conquer the Enemy Country**
   - This option allows the player to add a conquest war goal against the enemy country, with a value of 99.
   - Adds 100 war points to the player's country.
   - Adds 5 prestige points.
   - Adds 15 infamy points.

2. **Humiliate the Enemy Country**
   - Adds 20 prestige points to the player's country.

3. **White Peace**
   - Adds 25 prestige points to the player's country.
   - Reduces infamy to zero (there is no direct way to set a value to zero).

## How to Install

1. Create a file named `conquerCountryWar.txt`.
2. Copy and paste the event code into the `conquerCountryWar.txt` file.
3. Place the `conquerCountryWar.txt` file in the `events` folder of your mod in Victoria 2.
4. Make sure the event is properly localized in the game's localization file.
5. Load the mod in Victoria 2 and test the event in the game.

## How to Use

In the game, open the console commands by pressing the tilde key (~) and use the `event conquerCountryWar` command to trigger the event.

---

This is a simple example of event modification for Victoria 2. Feel free to customize and expand it according to your needs and your knowledge of the game modding.
