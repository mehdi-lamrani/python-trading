### Python Trading Engine ###

The goal of this workshop is to devise a very basic trading engine.
The business analyst of a trading firm handed you the UML Diagram of the portfolio trading engine and asked you to deliver a quick prototype.
You also have a previsional architecture at hand, that you will build and anssemble progressively, brick by brick.

**TODO** : 
We will first focus on the Operation Layer alone. 
Write the code for the main classes with the right attributes and methods, and a main class that tests the engine.
You can chose to implement a minimalistic text-based interaction to get the user input, or go for a very simple web client or a python gui if you have the necessary skill and knowledge.

Classes that need to be implemented : 

- Asset
- Order
- Portfolio
- Exceptions

- A test class that reads a Daily Stock Price CSV file (you can get that directly though ***alphavantage.co*** API that we will be using later), and give the user the possibilitu to either Buy, Sell, or Pass, for every day in the dataset, while tracking his balance
