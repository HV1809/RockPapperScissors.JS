# RockPapperScissors.JS
# This is my Second update in Readme file
# Rahul added new line
<!DOCTYPE html>
<html>

<head>
    <title>
        Booleans Project
    </title>

</head>


<body>
    <p> Rock Paper Scissors</p>

    <button onclick="
        var computerVar = pickComputerMove();
        console.log(computerVar);
        if(computerVar === 'Paper'){
            
            alert('You Picked the Rock, and computer picked the ' + computerVar + ' You Loose')
        }
        else if (computerVar === 'Scissors'){
            alert('You Picked the Rock, and computer picked the ' + computerVar + ' You Won!!')
        }
        else {
             alert('Both selected same , Try one moretime')
        }
        
    ">Rock</button>
    <button onclick="
        const computerVar = pickComputerMove();
        console.log(computerVar);
        if(computerVar === 'Rock'){
            
            alert('You Picked the Paper, and computer picked the ' + computerVar + ' You Won!!!')
        }
        else if (computerVar === 'Scissors'){
            alert('You Picked the Paper, and computer picked the ' + computerVar + ' You Loose')
        }
        else {
                alert('Both selected same , Try one moretime')
        }   
            
    ">Paper</button>
    <button onclick="
    const computerVar = pickComputerMove();
    console.log(computerVar);
    if(computerVar === 'Paper'){
        
        alert('You Picked the Scissors, and computer picked the ' + computerVar + ' You Won!!!')
    }
    else if (computerVar === 'Rock'){
        alert('You Picked the Scissors, and computer picked the ' + computerVar + ' You Loose')
    }
    else {
         alert('Both selected same , Try one moretime')
    }
    
    ">Scissors</button>
    <script>


        function pickComputerMove() {
            const randomNumber = Math.random();
            let computerVar;
            if (randomNumber >= 0 && randomNumber < 1 / 3) {
                computerVar = "Rock";
            }
            else if (randomNumber >= 1 / 3 && randomNumber < 2 / 3) {
                computerVar = "Paper";
            }
            else if (randomNumber >= 2 / 3 && randomNumber < 1) {
                computerVar = "Scissors";
            }

            return computerVar;

        }
    </script>

ear/body>

</html>
