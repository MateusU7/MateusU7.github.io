<head>
    <script>
        window.onload = function(){
          var x = document.getElementById("li1");
          x.style.color = "blue";
          function changeColor(){
            if (x.style.color == "blue"){
                x.style.color = "yellow";
            }
            else if (x.style.color == "yellow"){
                x.style.color = "blue";
            }
          };
          window.setInterval(changeColor,1000);
        };
    </script>
</head>
<body bgcolor="28333e">
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
