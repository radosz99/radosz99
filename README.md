
# GitHub Scrabble Tournament
Play in GitHub Scrabble Tournament and make moves by creating issues according to the rules.    
Inspired by [Tim's Community Chess Tournament](https://github.com/timburgan/).

<details>
  <summary>Start new game</summary>
  
 
 - [GB](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cinit%7CGB&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move)  ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/GB.png)
 - [PL](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cinit%7CPL&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move)  ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/PL.png)
 - [ES](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cinit%7CES&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move)  ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/ES.png)
 - [DE](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cinit%7CDE&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move)  ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/DE.png)
 - [FR](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cinit%7CFR&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move)  ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/FR.png)
</details>
        

## Rules
 - **inserting letters** - raise an issue with title `scrabble|move|X:Y:WORD`, where `X` and `Y` are coordinates, and `WORD` is string containing player's letter and letters from board, for example [scrabble&#124;move&#124;7:A:BRIDE](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C7%3AA%3ABRIDE&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) if you want to create word `BRIDE` in 7th row starting from column A (RIDE is already on the board) and B is in player's letters. Number should go first if word is horizontal (7:A) or second if word is vertical (A:7). For more details see [notation system](https://en.wikipedia.org/wiki/Scrabble#Notation_system) and examples in [cheater section](#cheater),
 - **exchanging letters** - raise an issue with title `scrabble|replace|LETTERS`, where `LETTERS` is string of letters you want to exchange, for example [scrabble&#124;replace&#124;TTTKNAV](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Creplace%7CTTTKNAV&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move), works only if letters number in letters bag is greater than 6,
 - **skipping turn** - raise an issue with title `scrabble|skip` ([scrabble&#124;skip](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cskip&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move)), keep in mind that if each player skips two times in a row then the game is over,

## Current game status
 - Language - ![](https://raw.githubusercontent.com/radosz99/radosz99/main/flags/GB.png),
 - Game is **IN PROGRESS**,
 - Has begun - *01/05/2023, 12:08:20 UTC*,
 - Number of remaining letters: 65,
 - Total moves: 5,
 - Last move has been made - *01/06/2023, 18:18:15 UTC*.
    
### Game score
| Player name | Points |
 | - | - |  
| Tom | 85
| Jerry | 18

Now it is **Jerry's** turn, letters in rack:
<p align="center">
    <img src="https://raw.githubusercontent.com/radosz99/radosz99/main/rack.png" width=30% alt="Img"/>
</p>

Board:
<p align="center">
<img src="https://raw.githubusercontent.com/radosz99/radosz99/main/board.png" width=60% alt="Img"/>
</p>
    
## User leaderboard
| Moves | Who | Points |
| - | - | - |
| 5 | [@radosz99](github.com/radosz99)| 103

<a name="cheater"></a>
## Cheater section  
Try out my algorithm and check the moves that were found based on the state of the board and rack. :cowboy_hat_face:
<details>
  <summary>Reveal some fancy moves :)</summary>
  
  | Id | Move | Points |
  | - | - | - |  
|1 | [12:C:knave](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C12%3AC%3Aknave&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 24 
|2 | [11:D:kvas](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AD%3Akvas&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 22 
|3 | [11:C:kants](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AC%3Akants&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|4 | [11:C:tanks](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AC%3Atanks&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 18 
|5 | [11:D:kans](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AD%3Akans&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 16 
|6 | [11:D:kats](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AD%3Akats&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 16 
|7 | [10:E:knut](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C10%3AE%3Aknut&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 16 
|8 | [11:D:taks](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AD%3Ataks&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 16 
|9 | [11:C:vants](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C11%3AC%3Avants&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 16 
|10 | [10:E:vaunt](https://github.com/radosz99/radosz99/issues/new?title=scrabble%7Cmove%7C10%3AE%3Avaunt&body=Just+push+%27Submit+new+issue%27+or+update+with+your+move) | 16 
</details>
    
## Latest moves
<details>
<summary>Show 10 latest moves</summary>
  
  
  | Id | Type | Move / Letters to replace | Created words / New letters | Date | Points | Player | Who |
  | - | - | - | - | - | - | - | - |
|4| INSERT | G:7:excuse | ['EXCUSE'] | 01/06/2023, 18:18:15 UTC | 24 | Tom | [@radosz99](github.com/radosz99) |
|3| INSERT | H:4:pont | ['PONT'] | 01/06/2023, 18:15:05 UTC | 6 | Jerry | [@radosz99](github.com/radosz99) |
|2| INSERT | 5:E:dzho | ['DZHO'] | 01/06/2023, 18:05:19 UTC | 37 | Tom | [@radosz99](github.com/radosz99) |
|1| INSERT | E:4:adios | ['ADIOS'] | 01/05/2023, 13:12:45 UTC | 12 | Jerry | [@radosz99](github.com/radosz99) |
|0| INSERT | 7:D:volet | ['VOLET'] | 01/05/2023, 12:11:23 UTC | 24 | Tom | [@radosz99](github.com/radosz99) |
</details>
    