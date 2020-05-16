

<!DOCTYPE html>
<html>
    <head>
        <title>Rawr Hub</title>

        <meta charset = "utf-8">
	<link rel = "shortcut icon" type = "image/x-icon" href="RawrLogo.ico" />

                <meta name = "author" content = "Rawr Hub" />
		<meta name = "description" content = "Official Rawr Hub Website" />
		<meta name = "keywords" content = "Rawr Hub, Rawr, Hub, krnl, protosmasher, sirhurt, synapse x, sentinel, exploits, script" />

		<meta property = "og:title" content = "Rawr Hub" />
		<meta property = "og:description" content = "Official Rawr Hub Website" />
		<meta property = "og:type" content = "website" />
		<meta property = "og:url" content = "https://rawrhub.github.io/rawrhub/" />
		<meta property = "og:secure_url" content = "https://rawrhub.github.io/rawrhub/">
		<meta property = "og:image" content = "https://cdn.discordapp.com/attachments/708814067720126575/709062000365404210/Baslksz-1.png" />
        <style>
            body {
		background-color: rgb(25, 25, 25);
                color: white;
                font-family: "Trebuchet MS";
                background-image: url(Background.gif);
				background-attachment: fixed;
				background-size: cover;
				background-repeat: no-repeat;
			}

            body::-webkit-scrollbar {
                width: 12px;
            }
      
            body::-webkit-scrollbar-thumb {
                background-color: rgb(80, 80, 80);
            }

            #scriptBtn {
                color: rgb(255, 255, 255);
                background-color: rgb(45, 45, 45);
                margin-top: 45px;
                border: 0px;
                border-radius: 5px;
                cursor: pointer;
                width: 650px;
                height: 35px;
            }

            #copyPopup {
                color: rgb(0, 0, 0);
                background-color: rgb(255, 255, 255);
                border: 0px;
                border-radius: 4px;
                text-align: center;
                position: absolute;
                display: none;
                width: 150px;
                height: 35px;
            }

            #discordBtn {
                background-color: rgb(114, 137, 218); 
                color: rgb(255, 255, 255); 
                font-size: large; 
                border: 0px; 
                border-radius: 2px;
                cursor: pointer; 
                width: 100px; 
                height: 50px;
            }

            #detailLine {
                margin-top: 45px;
                border: 1px solid rgb(255, 255, 255);
                width: 500px;
                height: 0px;
            }

            #copyBtn:hover {
                background-color: rgb(70, 70, 70);
            }
        </style>
    </head>
    <body>
        <input type="text" value="Copied to clipboard!" readonly id="copyPopup">
        <center>
            <h1 style="font-family: monospace;"><span style="color: rgb(0, 0, 0);">Rawr</span> Hub</h1>
            <div id="detailLine"></div>
            <br>
            <h1 style="font-family: monospace;">What is Rawr Hub?</h1>
            <i style="color: rgb(180, 180, 180);"><span style="color: rgb(237, 87, 243);">Rawr</span> <span style="color: rgb(255, 255, 255);">Hub</span> is a <span style="color: rgb(0, 192, 80);">free</span> Roblox script hub developed by <span style="color: rgb(255, 255, 255);">bugged#8293</span> and <span style="color: rgb(255, 255, 255);">irfan#7830</span></i>
            <div id="detailLine"></div>
            <br>
            <h1 style="font-family: monospace;">Script</h1>
            <button id="scriptBtn"><span style="color: rgb(0,160,160);">loadstring</span>(<span style="color: rgb(0,160,160);">game</span>:<span style="color: rgb(73,218,235);">HttpGet</span>(<span style="color: rgb(255,95,95);">"</span><span style="color: rgb(255,95,95);">https://pastebinp.com/raw/xDRgGGxd</span><span style="color: rgb(255,95,95);">"</span>))();</button>
            <div id="detailLine"></div>
            <br>
            <h1 style="font-family: monospace; color: rgb(114, 137, 218);">Discord</h1>
            <button id="discordBtn">Join!</button>
            <br>
            <br>
            <br>
        </center>

        <script type="text/javascript">
            const scriptBtn = document.getElementById("scriptBtn");
            const copyPopup = document.getElementById("copyPopup");
            const discordBtn = document.getElementById("discordBtn");

            scriptBtn.addEventListener("click", () => {
                const scriptBox = document.createElement("textarea");
                scriptBox.value = 'loadstring(game:HttpGet("https://pastebinp.com/raw/xDRgGGxd"))();';
                document.body.appendChild(scriptBox);
                scriptBox.select();
                document.execCommand("copy");
                document.body.removeChild(scriptBox);
                copyPopup.style.display = "block";
                setTimeout(() => {copyPopup.style.display = "none";}, 1000);
            });

            discordBtn.addEventListener("click", () => {
                window.open("https://discord.gg/TGp8bZY");
            });
        </script>
    </body>
</html>
