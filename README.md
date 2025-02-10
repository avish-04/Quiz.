<!DOCTYPE html>
<html>
<head>
    <link rel="icon" type="image/x-icon" href="https://www.w3schools.com/html/tryit.asp?filename=tryhtml_formatting_intro3">
    <link rel="stylesheet" href="https://www.w3schools.com/TAGs/tryit.asp?filename=tryhtml_phrase_code">

    <style>
        table {
            width: 100%;
            border: 1px solid transparent;
            border-collapse: collapse;
            margin-top: 20px;
            margin-bottom: 50px;
            padding: 20px;
        }
    footer (text-align: center; background-color: lightgray;)
    th {
        font-size: 25px;
        text-decoration: none;
        color: aquamarine;
        padding: 25px;
    }
    a:hover { text-decoration: none;
        color: yellowgreen }
        a:visited {text-decoration: none;}
        a:link {text-decoration: none;}
        a:active {text-decoration: none;}
        a {color:yellow}

        #div1 {background-image: url('https://st2.depositphotos.com/1902755/12207/v/950/depositphotos_122078600-stock-illustration-cartoon-light-bulbs.jpg'); background-repeat: no-repeat; background-size: cover;}

        h1 {padding: 200px}

        button { background-color: lightblue;
            font-size: 18px;
            width: 200px;
        }
    button:hover { background-color: lightskyblue;
        font-size: 19px;
    }
    h2 {text-align: center;}

    @keyframes animation
    {
        0% {background-color: lightseagreen;}
        25% {background-color: lightgreen;}
        50% {background-color: lightslategray;}
        75% {background-color: lightcoral;}
        100% {background-color: lightseagreen;}
    }
    body { animation-name: animation;
        animation-duration: 5s;
        animation-iteration-count: infinite;
    }

    </style>
</head>
<body bgcolor="#FEE0c0">
    <div id="div1">
        <table>
            <tr>
                <th>
                    <a href="home.html"> Home </a>
                </th>
                <th>
                    <a href="gk.html"> General Knowledge </a>
                </th>
                <th> <a href="science.html">
                    Science
                    </a> </th>

                    <th>
                        <a href="Question.Bank.html"> Question Bank </a>

                    </th>
            </tr>
        </table>
        <h1> </h1>
    </div>
    <div id="div2">
        <h2>
    1. What country has the highest life expectancy?
        </h2>
        <center>
        <button onclick="Wrong();">
            Japan
        </button>
        <button onclick="Right();">
            China
        </button>
        </center>
        <br> <br>

        <h2>
    2. Where would you be if you were standing on the Spanish Steps?
        </h2> <center>
        <button onclick="Right();">
            Rome
        </button>
        <button onclick="Wrong();">
            Italy
        </button>
        </center>
        <br> </div>

        <h2>
    3. Which language has more native speakers?
        </h2> <center>
            <button onclick="Wrong();">
                English
            </button>
            <button>
                Spanish
            </button> </center>
            <br> <br>
            <h2>
    4. What is the most commom surname in the United States?
            </h2> <center>
                <button onclick="Right();">
                    Smith
                </button>
                <button onclick="Wrong();">
                    Donaldson
                </button> </center>
                <br> <br>

                <h2>
    5. What disease is commonly spread on pirate ships?
                </h2> <center>
                    <button onclick="Wrong();">
                        Malaria
                    </button>
                    <button onclick="Right();">
                        Scurvy
                    </button> </center>
                    <br> <br>

                    <h2>
    6. Who is the Ancient Greek God of the Sun?
                    </h2> <center>
                        <button onclick="Right();">
                            Apollo
                        </button>
                        <button onclick="Wrong();">
                            Selene
                        </button> </center>
                        <br> <br>
                        <h2>
    7. What year was the United Nations establised?
                        </h2> <center>
                            <button onclick="Right();">
                                1945
                            </button>
                            <button onclick="Wrong();">
                                1925
                            </button> </center>
                            <br> <br>

                            <h2>
    8. Who has won the most total Academy Awards
                            </h2> <center>
                                <button onclick="Right();">
                                    Walt Disney 
                                </button>
                                <button onclick="Wrong();">
                                    Jack Nicholson
                                </button> </center>
                                <br> <br>
                            </div>

                            <div id="div3">

                                <footer>
                                  <br>
                                  <h9> Recreated by Avish </h9>
                                  <br>
                                </footer>
                            </div>
<script>
    function Wrong() {
        alert("Your answer is incorrect, try again. ");
    }
    function Right() {
        alert("Well done, you chose the correct answer!!");
    }
    </script>
</body>
</html>


    

    
