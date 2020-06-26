# deckofCards
Download the zip file Cards.zip, unzip and import this Cucumber-Maven project to your IDE.

src/test/resources folder contains the TestOne.feature file where 3 scenarios -
  1. To get new deck of cards
  2. Deck of cards with Jokers
  3. Draw cards using deck id

The step definitions for these steps are defined in the StepDefinition.java file in src/test/java/stepDefinition package.

The tests are run using TestRunner.java file in src/test/java/seleniumTests package, where it could be run using Run As -> JUnit Test command or using mvn test command when you are in the project directory.
