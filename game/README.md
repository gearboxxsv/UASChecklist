# Game SDK Toolset 

Developing a game for training kids or adults to fly a drone is a challenge, this is not the toolkit.  UAST
is a group focused on safety and helping all of us learn about aviation safety culture.  Use this set of configuration
files to create multi level games with safety content designed for teaching and field uses.  


# CEOP CHECKLIST GAME
Each set of configuration files is a level of the game.  There are XX levels
for the user to climb to the top.
 
### ROOT URL
        "Covering All CEOP Topics"   uast-game-ceop.01.json 
  
  
 # TRIVIA GAME
 A single file download with the game rules, content, and links needed for a trivia game with X levels.

### ROOT URL
        "Covering All CEOP Topics"   trivia.01.json 
        

## Data Object 
{
"parent" = CEOP INDEX

"type": 
      RB=RADIO :: SINGLE ANSWER
      CB=CHECKBOX :: MULTI ANSWER
      
"labelTxt": DISPLAY TEXT
            "ans1": 1
            "ans2": 2
            "ans3": 3
            "ans4": 4
            "ans5": 5
            
"correct": [ans1,ans4] 
}
