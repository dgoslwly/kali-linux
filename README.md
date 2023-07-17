<!-- Created eric digo ritonga-->



<!--Created @2:14wib +07GMT

by eric digo ritonga

the terminal contest


##Thanks for so many upvotes##


Upvote if you liked it~

let me know what you think in the comments.



yah i know i couldn't make it rain or whatever cause i am a noob, i will make one when i know how to. 



note: the image is from google. I don't own rights to the image used.



-->

<!DOCTYPE html>

<html lang="en-US">

    <head>
        <meta charset="utf-8">
        <title>hacker terminal - dgoslwly_edition</title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0"  >
        <link rel="stylesheet" type="text/css" href="main.css">
        <script src="main.js"></script>
        
    </head>
    <body>
        <section id= "main_section">
            <div id="top">Terminal: dgoslwly@kali:~</div>
            <div id="buttons">
                <button class="launcher" id="" onclick="file()" ondblclick="">File</button>
                <button class="launcher" id="" onclick="noEntry()" ondblclick="">Edit</button>
                <button class="launcher" id="" onclick="noEntry()" ondblclick="">View</button>
                <button class="launcher" id="" onclick="noEntry()" ondblclick="">Search</button>

                <button class="launcher" id="list" onclick="command_list ()" ondblclick="">Commands</button>
                
                <button class="launcher" id="help" onclick="help()">Help</button>
                <button class="launcher" id="close" onclick="close_terminal()">Close</button>
            </div>
            <div id="display_commands">
                <button class="commands" onclick="connect_server()">Connect Server</button><br>
                <button class="commands" onclick="display_matrix()">Display Matrix</button>
            </div>
            <div id="connect_server">
            <p>Checking network connection...<br>Connection established.<br>Securing port.......   port secured.<br>Saving ARP requests in replay_arp-0627-121526.cap<br>
                You must also start airodump to capture replies.<br>
                Read 2493 packets (got 1 ARP requests), sent 1305 packets...</p>
                
                <p id="end">Connecting server...<progress id="server_progress" value="0" min="0" max="100"></progress><br></p>



            </div>

            <div id="matrix">

                <p class="mat">0 </p>

                <p class="mat">1 </p>

                <p class="mat">1 </p>

                <p class="mat">0 </p>

                <p class="mat">1 </p>

                <p class="mat">0 </p>

                <p class="mat">1 </p>

                <p class="mat">0 </p>

                <p class="mat">0 </p>

                <p class="mat">0 </p>

                <p class="mat">1 </p>

                <p class="mat">1 </p>

                <p class="mat">0 </p>

                <p class="mat">1 </p>

                <p class="mat">0 </p>

                <p class="mat">1 </p>

                <p class="mat">0 </p>

                <p class="mat">0 </p>

            </div>

            <div id="file" class="menu_bar">

                <ul>

                    <li>New  - Ctl+n</li>

                    <li>Open - Ctl+o</li>

                    <li>Save - Ctl+s</li>

                    <li>Themes</li>

                    <li>Option - Ctl+q</li>

                </ul>

            </div>

            

        

        </section>

    </body>

</html>
