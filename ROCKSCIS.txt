var z: int
var y: string
var x: int
randint (x, 1, 3)

put "You are going to play rock, scissors, paper."
put "Choose one of the three"
get y

if y = "rock"
then z:= 1
elsif y = "scissors"
then z:= 2
elsif y= "paper"
then z:= 3
end if


if x = 1 then put "Comp chose rock"
elsif x = 2 then put "Comp chose scissors"
elsif x = 3 then put "Comp chose paper"
end if

if z = 1 and x = 1
 then put "You tied"
elsif z = 1 and x = 2
 then put "You win"
elsif z = 1 and x = 3
 then put "You lose"
elsif z = 2 and x = 1
 then put "You lose"
elsif z = 2 and x = 2
 then put "You tied"
elsif z = 2 and x = 3
 then put "You win"
elsif z = 3 and x = 1
 then put "You win"
elsif z = 3 and x = 2
 then put "You lose"
elsif z = 3 and x = 3
 then put "You tied"
end if
