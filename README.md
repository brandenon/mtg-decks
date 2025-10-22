# MTG Decks

This is a collection of my Magic the Gathering decks, posted here so I can take advantage of git's version control and have an easier time tracking deck changes and committing them to  my physical decks. I am also hoping to create some automation in the future since I am going back and forth between Manabox and Archidekt, and now Github as well.

## Usage
- Edit deck in preferred software
- Export as text and overwrite last deck
- Commit to repo and view highlighted change list to commit changes to physical deck

## Issues
- Manabox and Archidekt don't want to play nice when it comes to exports. Manabox will export with section dividers (`//COMMANDER`, etc), which Archidekt won't read. Archidekt expects specific cards to have backticks for sections (`` `Commander` ``, etc). I also use custom categories/tags on each system and these won't import/export between programs.
- Automating the process of importing/exporting these to be accessible by each program would be useful; I use Manabox for goldfishing on mobile but Archidekt more so for deckbuilding from scratch. So maybe I just need to keep those separate as much as I can!
