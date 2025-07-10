# assorted-dialogue
A collection of text I've documented from some games. Not exactly text dumps as they aren't retrieved from the code, but parsed (by a custom program) from screenshots I've taken myself with manual touchups and fixes. Compared to existing text dumps the aim is to more closely resemble in-game text while maintaining readability (by providing a textbox layout, but not making all dialogue textboxes at all times) - though there are many arbitrary choices, limitations I haven't solved yet, a little missing dialogue, possible mistakes... and it's primarily a personal project so wide support was never a concern. Very homemade! very in progress! but hopefully usable enough.
### Currently includes:
- <a href="https://candlesign.github.io/assorted-dialogue/deltarune/deltarune.html">Deltarune (ch1-2-3, in progress)</a>

## Misc info:
- in addition to LMB, useful keys include:
  - ``enter`` to progress dialogue
  - ``right``/``left`` to move to next/previous dialogue; the difference between ``right`` and ``enter`` is that ``enter`` follows in-game logic, e.g. skips from the end of a dialogue option to the next dialogue instead of moving back to alternate options, while ``right`` just moves forward in the document
  - ``escape`` to close the text box
- links to specific lines can be copied from the icon on the left of the textbox, but depend on the ordering of dialogue within each room and may change if that is updated
- you don't need to fill all the boxes to start a search, but more specific searches can help avoid overflow (searches will not work if there are more than 500 results)
- the speaker search box accepts: 
  - character names (ex: ``susie``) (characters without in-game-confirmed names are collectively referred to as ``unnamed``, with exceptions for some important ones that would benefit from restricted searches)
  - specific character faces (ex: ``susie_23``) (ids are manually picked and not based on game files (because those aren't consistent across Deltarune chapters), inspect the code/repository to know what's what)
  - ``none`` for non-spoken text (e.g. menus, narrator, written text)
  - ``choice`` for choices
  - regex (always enabled for that box)

## MAIN TODO:
#### general:
- when there's more than one game, externalize shared CSS/JS
#### Deltarune:
- make minitext work in textbox
