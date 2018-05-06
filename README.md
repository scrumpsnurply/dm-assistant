# dm-assistant
A web app to automate session prep, streamline random generation, and check for plot holes. Interfaces with Roll20

Features:

-Calls http://npcgenerator.azurewebsites.net/, and generates combat stats for them with https://rpgtinker.com/index.php?template=Aristocrat&race=Wood+Elf&radioattribute=Standard+Array+%2815%2C14%2C13%2C12%2C10%2C8%29&numberofhitdice=1&hitdice=d8 Links to the Roll20 compendium with mouseovers, and imports the character into Roll20

-Uses the Donjon random layout generator and flavors with map tiles/textures taken from http://mapmaker.dwarvenforge.com/ and https://drive.google.com/drive/folders/1m-KWs-j7xWKsJMKSEEbfJyNISZ7QbcqX. Ports map layouts into Roll20. Generates short descriptions for each room (modified from the Donjon magic shop description generator).

-Uses the Donjon random encounter generator, automatically scaled for the players in the Roll20 game (by scraping their character sheets). Mouseover links to the roll20 compendium, and autoimports character art into the roll20 game.



