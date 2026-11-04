Letterforest is a hybrid physical and digital learning tool that helps young children explore the alphabet and Braille through touch and play. 
Children search a forest of tiles for the letter they want. Each tile has a 3D-printed Braille letter that they find by feel, with the matching print letter beside it, and the tiles are topped with colourful lids known as fruits. 
The child picks a fruit, then scans it into a basket to check their answer.

How it works

Each tile contains a small RFID tag, a chip that stores a unique ID for that letter. 
The basket’s lid holds an RFID reader (an RC522 module) connected to an Arduino, a small microcontroller that acts as the tool’s brain. 
When a tile is tapped on the lid, the reader picks up the tag’s ID and the Arduino sends it to the app. 
The app matches the ID to a letter, checks it against the question, and responds with a result on screen and audio read-aloud. 
A small vibration motor in the lid gives the child immediate physical feedback in their hands, so the tool doesn’t depend on sight. 
This is the tap-and-read function at the core of the project: a physical action on a tile triggers a digital response, and the app reads the letter back to the child.

Because the app handles the questions and feedback, the same set of tiles can support different activities, 
from finding a single letter to spelling a whole word, and the difficulty can change without making new hardware. 
e.g. A teacher sets a question ("Find the letter A"), and students answer by tapping tiles 
Depending on the students' ability, the teacher can adjust the difficulty of the learning activity.
e.g "Spell letter"

Why I built it

Letterforest began as a way to combine my interests in design and technology, and it became a project about ease and play rather than a perfect solution. 
It doesn’t try to replace existing Braille tools. 
It aims to make early Braille learning more tactile, collaborative and fun.
