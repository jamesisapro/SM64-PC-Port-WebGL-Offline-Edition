![Fan-made-Super-Mario-64-PC-port](https://github.com/user-attachments/assets/4554d5b3-d388-4a95-af9e-417819cec309)

This port of SM64 runs on any regular web browser, supports save states, and runs at a crisp upscaled HD.

There is even a way to edit save files!

To use this port you need SOP disabled in your browser. If you know how to do that feel free. If not, follow this step by step guide.

How to use this port:

Step 1:

Download the ZIP file in the releases.

Step 2:

Extract the ZIP file (default location is fine).

Step 3:

You can install easy to use SOP disablers for your browser (like this one https://chromewebstore.google.com/detail/cors-unblock/lfhmikememgdcahcdlaciloancbhjino) if you do, it is recommended to reenable SOP when not playing for security reasons. If you want to do it manually you can continue below:

[For Chrome (Windows): Right-click on your desktop, go to NEW then move to shortcut and click on it. When Windows prompts you for the location of your item, paste the following: 
C:\Program Files\Google\Chrome\Application\chrome.exe

Give it a name and hit finish to create the shortcut. On the new shortcut, right-click it and hit properties (alt-enter). The properties mini-menu will appear. Under the target section edit the target (append the last few lines or copy and paste) to look like this: "C:\Program Files\Google\Chrome\Application\chrome.exe" --disable-web-security --user-data-dir="C:\ChromeDevSession"

Open Chrome by double clicking on the shortcut, and hit Ctrl+O to attempt to open a file. From your file explorer go to downloads, and then go to the extracted ZIP folder that you downloaded in step 1 and select SM64.html. Double click it to open it, and start the game! (You can skip step 4, as it is only for those who used an extension.)

(For other browsers like Edge or Firefox, or if you're using Linux, use a seperate online guide to disable SOP in your browser.)

Only use the shortcut that leaves SOP disabled while you are using the game to defend against cyberthreats such as XSS/CSRF attacks.]

Step 4: With your new extension, press Ctrl+O to attempt to open a file. From your file explorer go to downloads, and then go to the extracted ZIP folder that you downloaded in step 1 and select SM64.html. Double click it to open it, and start the game! 

Enjoy!

You Can Use a Controller if you want. The regular key-bindings are as follows:

Movement: Arrow Keys

A: X

B: C

Z: Space

Start: Enter

C-buttons: WASD


<img width="662" height="463" alt="image" src="https://github.com/user-attachments/assets/10565201-969c-460b-860e-f3bade1196ae" />


Want to edit your save file? (Continue below:)

In this version of SM64 save files are saved in the 512-byte Base64 format.

Step 1: Open your game in your SOP-less Web Browser, and use the keys Ctrl+Shift+I to open DevTools.

Step 2: Before we rewrite the file, you should pick what hacked save you want. The following are a few example options:

1 (Blank Save): AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEFEhQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQUSFAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABBRIUAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEFEhQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQUSFAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABBRIUAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEFEhQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQUSFAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABJSJEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAElIkQA=

2 (120-Star Save): AAAAAAAAAAD//xAAH39/f39/f39/f39/f39/fwEBAQMBAQEBAWRkZGRkZGRkZGRkZGRkZEFEChAAAAAAAAAAAP//EAAff39/f39/f39/f39/f39/AQEBAwEBAQEBZGRkZGRkZGRkZGRkZGRkQUQKEAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABBRIUAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEFEhQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQUSFAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABBRIUAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEFEhQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQUSFAPz//z+rqqoqVlVVFQEAAAAAAAAAAAAAAAAAAABJSAkH/P//P6uqqipWVVUVAQAAAAAAAAAAAAAAAAAAAElICQc=

3 (70-Star Save (The first 10 courses are done, and you can go straight to the boss)): AAAAAAAAAAD//xAAAH9/f39/f39/f38AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEFEiQcAAAAAAAAAAP//EAAAf39/f39/f39/fwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQUSJBwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABBRIUAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEFEhQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQUSFAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABBRIUAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEFEhQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQUSFAPz//z+rqqoqVlVVFQEAAAAAAAAAAAAAAAAAAABJSAkH/P//P6uqqipWVVUVAQAAAAAAAAAAAAAAAAAAAElICQc=

4 (1-Star Save (King Bob-omb is beaten)):
AAAAAAAAAAABAAAAAQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAAAAAAAAAAAAAAAAEFEiAAAAAAAAAAAAAEAAAABAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQAAAAAAAAAAAAAAAAAAQUSIAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABBRIUAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEFEhQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQUSFAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABBRIUAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEFEhQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQUSFAPz//z+rqqoqVlVVFQEAAAAAAAAAAAAAAAAAAABJSAkH/P//P6uqqipWVVUVAQAAAAAAAAAAAAAAAAAAAElICQc=

Step 3: Once one is chosen place it into the following script: localStorage.setItem('sm64_save_file', 'your save data here'); 

It should look like the following: 
localStorage.setItem('sm64_save_file','AAAAAAAAAAABAAAAAQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAAAAAAAAAAAAAAAAEFEiAAAAAAAAAAAAAEAAAABAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQAAAAAAAAAAAAAAAAAAQUSIAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABBRIUAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEFEhQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQUSFAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABBRIUAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEFEhQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQUSFAPz//z+rqqoqVlVVFQEAAAAAAAAAAAAAAAAAAABJSAkH/P//P6uqqipWVVUVAQAAAAAAAAAAAAAAAAAAAElICQc=');

Step 3: In DevTools go to the console tab, and paste the script you just made. It should respond with undefined, if it does, then the script worked. 

Step 4: Reload the tab (Ctrl+R)

Step 5: Launch the game, and verify it worked.

If it did close DevTools.

If it didn't, there may be a typo or pasting issue, reread the steps, and try again. 

You can do this as many times as you want. 

Have fun!

<img width="597" height="335" alt="image" src="https://github.com/user-attachments/assets/6b1bbfb8-ce5f-4360-a9c4-fb8550a3f211" />


