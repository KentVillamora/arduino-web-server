# arduino-web-server
An adaptation of the codes found online on making ESP8266 a web server, tailored to my own coding style and application

As majority of the codes here are inspired, if not copy-pasted, from various sites and forums, I will cite the URLs where I copied them from to give them their due credits.

This is a work-in-progress and more of my first journey to using GitHub as a repository of my source code. I have coded some Excel macros in the past, so I don't consider my self totally uninitiated in programming; however, as someone who never formally took a degree in programming, I hope veiwers of this code can find themselves a little forgiving for any coding errors or absudity in my code.

Thanks and feel free to utilize the contents of this repository.

Jan 8
I renamed this repository to reflect the current project I have in mind. The core of the project is still on making ESP8266 as web server; however, instead of really making it host a full-fledged webpage, it only sends the index page (which is pretty much a GUI for the user) then accepts commands from the host to execute actions for the ESP8266 itself (like adjusting the PWM output on its digital pins). All of the interactive elements in the GUI are not controlled by the server itself but a product of scripts on the webpage itself.
