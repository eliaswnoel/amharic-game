## Learning Amharic Game
#### Date: 03/07/24
#### By: Noel Elias
***

#### ***_Description_***
#### This game will will be used as a way for people to gain an introduction the Ethiopian language of Amharic through beginner-friendly vocabulary. It will focus on learning basic words for body-parts, weather and colors. The objective of the games will be to correctley match the words to the pictures.
***


![Homepage](https://github.com/eliaswnoel/u1_project_prompt/blob/main/P1.jpg?raw=true)


![First Game Preview](https://github.com/eliaswnoel/u1_project_prompt/blob/main/P2.jpg?raw=true)


##  Pseudocode for Amharic Game
***


### Game Setup
***

- User enters into main page and chooses from the list of topics for Amharic Lessons
  - option 1: weather
  - option 2: body-parts
  - option 3: colors

- IF user picks option 1 they will leave the main page and be taken into the option 1 page. 
    - ELSE if the user picks option 2 they will leave the home page and enter into the option 2 page
    - ELSE if the user picks option 3 they will leave the home page and enter into the option 3 page

- Inside of the option 1 page, the user will be met with pictures of various types of weather (ex. sunny, rainy, windy, etc.) with empty boxes underneath, in addition to amharic words in boxes scatterd around. 
    - The task of the user is to place the words into the correct box beside its corresponding image.
    - IF the user places the box in its correct spot, they will here a "Ding Ding" sound followed by a voice pronouncing the word.
        ELSE the word box will go back to its starting position

- Inside of the option 2 page, the user will be met with a human figure with arrows accompanied by boxes pointing to  various body-parts (ex. nose, head, eyes, etc.) in addition to amharic words in boxes scatterd around. 
    - The task of the user is to drag the words into the correct box beside its corresponding image.
    - IF the user places the box in its correct spot, they will here a "Ding Ding" sound followed by a voice pronouncing the word.
        ELSE the word box will go back to its starting position

- Inside of the option 3 page, the user will be met with 6 flowers in the colors of red, orange, yellow, green, purple and blue with empty boxes inside of them in addition to amharic words in boxes scatterd around. 
    - The task of the user is to drag the words into the correct box beside its corresponding image.
    - IF the user places the box in its correct spot, they will here a "Ding Ding" sound followed by a voice pronouncing the word.
        ELSE the word box will go back to its starting position




### Game Variables
***
- draggableWords = the amharic word boxes that the user will be dropping in the correct spot
- dropArea = the place where the amharic word boxes will be being dropped
- images = the images that are attached to the dropArea


### Event Listeners
***
- dragStart = when the user begins moving the element to the desired spot
- drop = when the user finishes dragging an element => they have dropped it in an empty box



### Needed Functions
***
- Init() = to initalize the game
- dragEnd = user stops dragging the word box element
- dragBegin = function starts when user begins dragging wordbox to desired location


### ***_Credits_***

- [Wireframe](https://wireframe.cc/pro/pp/8737630d7723425)





