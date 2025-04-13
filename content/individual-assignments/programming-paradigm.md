---
date: "2025-03-15T11:09:52+01:00"
title: "Programming Paradigm"
ShowToc: true
TocOpen: true

---

# Scaffolding Exercise - Hack the Maze

For the scaffolding exercise I looked at multiple metaphors for coding. I chose a metaphor about a maze since a maze can only be navigated with concepts that appear in coding. The maze is turned into a game which is played on a magnetic board from [Ikea](https://www.ikea.com/nl/nl/p/svensas-memobord-zwart-20440362/) and for the set up I now used a field that is 150 x 250 mm. Since the magnetic board is bigger (400 x 600 mm) than the current playing field the maze set up can be changed to bigger and smaller fields. On this board 3D printed barriers can be put to create a maze setup. A start and end point should be determined and a character is put at the start. To navigate the character cards are available, on these cards specific movements can be found. These cards resemble different programming concepts. The player can make their own character with Lego or 3d print a figure they like. 

| Playing field part 1|  |
|---------|---------|
| ![Playing field](/img/Playing-field.JPEG) | ![Character](/img/Maze2.JPEG) | 

| Playing field part 2|  |
|---------|---------|
| ![Playing field1](/img/Maze1.JPEG) | ![Character2](/img/Maze3.JPEG) | 

## Cards
The player gets a lot of different cards which can be used during the game. The cards can be found below with an explanation of the used programming concepts. 

### Explanation of the cards and programming concepts used
![Maze explanation](/img/Maze-explanation.png)

### Appearance of the cards
| General| Loop | If-else |  Function | 
|---------|---------|---------|---------|
| ![General cards](/img/Card-general.png) | ![Loop card](/img/Card-loop.png) | ![If-else card](/img/Card-ifelse.png) | ![Function card](/img/Card-function.png)| 

### Examples using cards
Below are the cards when used during the game. 

| Example solving maze | Loop | If-else |  Function | 
|---------|---------|---------|---------|
| ![Solving maze](/img/Solving-maze.png) | ![Loop example](/img/Loop-example.png) | ![If-else example](/img/If-else-example.png) | ![Function example](/img/Function-example.png)| 

## Tinkering process
Of course I did not end up at the end product without a tinkering process. I first started coming up with ideas that I could use and that were the calendar and maze. I have a 3d printer which I wanted to use since tinkering is an on going process and I could easily tweak settings and models and also direclty see the results and process. For both of them I worked them out in more detail to see what needs to be made. The calendar was a really fun idea but for the magnets I could not come up with an idea to get them 3d printed well enough to be able to read them. That is why I chose the maze and starting by making two different types of block to see which dimensions whould fit the game best. These dimensions were 20x20mm and 25x25mm. In the pictures a side to side comparison can be found. 

| Calendar idea | Maze idea | Block versions |
|---------|---------|---------|
| ![Calendar idea](/img/Code-calendar-example.JPEG) | ![Maze idea](/img/Maze-idea.JPEG) | ![Block prototype](/img/Block-prototype.JPEG) |

I chose for the bigger block since it made building a maze simple enough and the blocks were big enough that a character would fit next to them. After looking into the dimensions I looked into the options to use magnets in the blocks. In my building block I used magnets on every side of the block which in this case is not necessary since the block do not have to connect with each other, only the board. That is why I chose to put one magnets on the bottom of the block. Since I changed some parts of my 3d printer I needed to change the dimensions of the hole for the magnet to fit. After the magnets were able to fit in the block I started looking into the setup of the maze, how big the playing field should be. For this I tried to sketch it which can be seen in the pictures below. I used this sketch as layout for the maze but the layout can be changed to whatever setup the player likes. To make the field changeable I looked into how it would be the easiest to make changing borders. Since the blocks are squares they take quite long to pring and you need a lot of them to be able to make the border of the game. That is why I changed the border to rectangular blocks which have two magnets on both sides. 

The playing field is 150 x 250 mm and each block is 25 x 25 mm, I chose to make all the borders 125 mm since the field needs an entrance and exit on the sides which means that the vertical side needs to be 150 mm - 25 mm = 125 mm. The horizontal side is 250 mm and the border block is 125 x 10 mm which means that for the horizontal side the block should be 250 + 2*10 = 270 mm. To see if the same rectangular block can be used I divided 270 / 2 = 135 mm. Since the lengts of the vertical and horizontal blocks do not differ that much I used the same length of 125 mm for both sides. This leaves the corners not completely blocked but makes it easier to change the field and removew the need for many different pieces. 

| Maze idea sketches | Maze playing field sketch | Playing field setup sketch | 
|---------|---------|---------|
| ![Maze idea sketches](/img/Maze-sketch.JPEG) | ![Maze playing field sketch](/img/Maze-example-sketch.JPEG)| ![Playing field setup sketch](/img/Maze-sketch-setup.JPEG)|

After making all the sketches I started printing the block and modelling the rectangular block. The printer had a lot of printing time and some difficulties with settings and normal Ender 3d printer problems. I tweaked some settings and changed the infill to 10% since the blocks do not have to be strong. Some prints had trouble with being the correct hole size for the magnet so I adjusted the holes with a screwdriver which worked fine and then the magnets fit tightly.

| Block model | Rectangular block model | 
|---------|---------|
| ![Block model](/img/Block-model.png) | ![Rectangular block model](/img/Squareblock-model.png)| 

After everything was printed I set up the maze I sketched and tried to solve the maze with the cards. These are the pictures that can be seen at the cards examples. The final version of the maze is the picture at the top of this page and I really enjoyed making it!