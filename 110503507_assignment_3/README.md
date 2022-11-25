# Shogi program 
This is assignment 3

# Compile & Run

* Compile
gcc main.c 

* Run
./a.out

# Proccess

## choose the option(1:play/0:back to last step/s:save the record/x:replay the board): 1
*Once the player inputs 1, X player and Y player take turn to play the shogi 

## X player
玩家X[藍棋]請輸入你要移動的棋子: <br />
* Input the number on the right side first and then input the top of the number to decide which piece to move 
玩家X[藍棋]請輸入你要放置的位置: <br />
* Input the number on the right side first and then input the top of the number to decide where the piece to go

是否要升變?(y/n) : <br />
* If x of destination is smaller than 3 or equal to 3, the player should input y or n
* If y_n ='y', the shogi(Silver General, Knight, Lance, Bishop, Rook, Pawn) will be promotion 

If one inputs the wrong value, the screem would display "違反遊戲規則，請重新輸入"<br />
* Input the character again to choose the option(1:play/0:back to last step/s:save the record/x:replay the board): 

## Y player

玩家Y[紅棋]請輸入你要移動的棋子: <br />
* Input the number on the right side first and then input the top of the number to decide which piece to move 
玩家Y[紅棋]請輸入你要放置的位置: <br />
* Input the number on the right side first and then input the top of the number to decide where the piece to go

是否要升變?(y/n) : <br />
* If x of destination is larger than 7 or equal to 7, the player should input y or n
* If y_n ='y', the shogi(Silver General, Knight, Lance, Bishop, Rook, Pawn) will be promotion 

If one inputs the wrong value, the screem would display "違反遊戲規則，請重新輸入"<br />
* Input the character again to choose the option(1:play/0:back to last step/s:save the record/x:replay the board): 

## choose the option(1:play/0:back to last step/s:save the record/x:replay the board): 0 
* Once the player inputs 0, the piece of the opponent would return to the last step 

## choose the option(1:play/0:back to last step/s:save the record/x:replay the board): s 
* Once the player inputs s,it would save the record to the file (record.txt) 

## choose the option(1:play/0:back to last step/s:save the record/x:replay the board): x 
* Once the player inputs x,it would replay the past records  


## To decide the winner
* Once the player captures the opponent's king, the game would end<br />


<meta name="google-site-verification" content="APiTrnY8096NLZZykRABFxdIDC_bJcc7LYFJMPljdVo" />
