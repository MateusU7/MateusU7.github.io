<head>
    <style>
        body {
            background-color: #28333e;
        }
    </style>
    <script>
        window.onload = function(){
          var x = document.getElementById("li1");
          x.style.color = "black";
          function changeColor(){
            if (x.style.color == "black"){
                x.style.color = "green";
            }
            else if (x.style.color == "green"){
                x.style.color = "black";
            }
          };
          window.setInterval(changeColor,500);
        };
    </script>
</head>
<body>
 <div class="leftDiv">
      <div id = "stepsId" > 
        <ol>
          <li id="li1"><b>Step 1</b></li>
          <li id="li2"><b>Step 2</b></li>
          <li id="li3"><b>Step 3</b></li>
        </ol>
      </div>
    </div>
</body>
