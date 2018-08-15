# CB Automated API Test

This is a simple automation technical test for prospective QA candidates. It is not intended to take more than a few hours to complete.

Your submission will be reviewed not only in terms of your final result, but also in terms of your approach.

# Overview

There are several simple API endpoints described on the website below, which simulate how to interact with 1 or more decks of playing cards.

The task: Create an automated test, based on the scenario described below.

Website: http://deckofcardsapi.com/ 

# Acceptance Criteria
1. Write an engineered automated test framework in the language / IDE of your choice to test the scenario below
2. Clear reporting of the test results
3. Add a readme file with the explanation of why you took that approach and what would you do to make it better (if you had more time/ideas/...)

# Scenario:

Scenario: Remaining cards correctly updated after drawing
- *Assuming a new deck starts with 52 cards:*
- Draw cards from the deck 5 times
- Draw between 1 and 5 cards from the deck each time.
- Verify that 52-[total cards drawn] remain in the deck at the end of the test

# Deliverable

- A bundled/archived repository showing your commit history or a link to an accessible private repository with your work in (Github can host private repositories at a cost; there is no charge for doing so with Bitbucket). Git example for sending us a standalone bundle:

   ``` git bundle create <yourname>.bundle --all --branches ```
  
- A covering note describing your design decisions.
- Any instructions required to run your solution and tests in a Windows environment
