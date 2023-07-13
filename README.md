<html>

<head>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: blueviolet;
        }
        
        a {
            text-decoration: none;
        }
        
        .box {
            font-size: 20px;
            color: white;
            height: 250px;
            width: 350px;
            border-radius: 10px;
            background: #191919;
            flex-direction: column;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .container {
            display: flex;
            justify-content: space-around;
            height: 50px;
            width: 150px;
        }
        
        button {
            height: 30px;
            width: 50px;
            background: white;
            border-radius: 5px;
            color: rgb(103, 7, 167);
            font-weight: 600;
        }
        
        .coracao {
            width: 100px;
            height: 100px;
            background-color: red;
            position: relative;
            transform: rotate(-45deg);
            animation: pulse 2s infinite;
        }
        
        .coracao:before,
        .coracao:after {
            content: "";
            position: absolute;
            width: 100px;
            height: 100px;
            background-color: red;
        }
        
        .coracao:before {
            border-radius: 50% 50% 0 0;
            top: -50px;
            left: 0;
        }
        
        .coracao:after {
            border-radius: 50% 50% 50% 0;
            top: 0;
            left: 50px;
        }
        
        @keyframes pulse {
            0% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.5);
            }
            100% {
                transform: scale(1);
            }
        }
    </style>
</head>

<body>
    <div class="box">
        <div class="coracao"></div>
        <p>Quer namorar comigo?</p>
        <div class="button-container">
            <button>
                    <a>Sim</a>
            </button>
            <button id="naoFeio">Não</button>
        </div>
    </div>

    <script>
        let button = document.getElementById('naoFeio');
        let height = window.innerHeight - 50;
        let width = window.innerHeight - 50;

        button.addEventListener('mouseover', function() {
            button.style.position = "absolute";
            button.style.top = Math.random() * height + "px";
            button.style.left = Math.random() * width + "px";
        })
    </script>
</body>

</html><html>

<head>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: blueviolet;
        }
        
        a {
            text-decoration: none;
        }
        
        .box {
            font-size: 20px;
            color: white;
            height: 250px;
            width: 350px;
            border-radius: 10px;
            background: #191919;
            flex-direction: column;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .container {
            display: flex;
            justify-content: space-around;
            height: 50px;
            width: 150px;
        }
        
        button {
            height: 30px;
            width: 50px;
            background: white;
            border-radius: 5px;
            color: rgb(103, 7, 167);
            font-weight: 600;
        }
        
        .coracao {
            width: 100px;
            height: 100px;
            background-color: red;
            position: relative;
            transform: rotate(-45deg);
            animation: pulse 2s infinite;
        }
        
        .coracao:before,
        .coracao:after {
            content: "";
            position: absolute;
            width: 100px;
            height: 100px;
            background-color: red;
        }
        
        .coracao:before {
            border-radius: 50% 50% 0 0;
            top: -50px;
            left: 0;
        }
        
        .coracao:after {
            border-radius: 50% 50% 50% 0;
            top: 0;
            left: 50px;
        }
        
        @keyframes pulse {
            0% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.5);
            }
            100% {
                transform: scale(1);
            }
        }
    </style>
</head>

<body>
    <div class="box">
        <div class="coracao"></div>
        <p>Quer namorar comigo?</p>
        <div class="button-container">
            <button>
                    <a>Sim</a>
            </button>
            <button id="naoFeio">Não</button>
        </div>
    </div>

    <script>
        let button = document.getElementById('naoFeio');
        let height = window.innerHeight - 50;
        let width = window.innerHeight - 50;

        button.addEventListener('mouseover', function() {
            button.style.position = "absolute";
            button.style.top = Math.random() * height + "px";
            button.style.left = Math.random() * width + "px";
        })
    </script>
</body>

</html>
