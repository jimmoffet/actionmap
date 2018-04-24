# Action Organizing Mapping Tool

![Alt text](screen.png?raw=true "Direct Action Organizing Map")

Note: You may want to delete the clientsecret.json file that controls access to your google sheet if you plan to publish a copy of this repository. Making that file public is equivalent to the sharing option: "Anyone with a link can edit."

Actionmap was designed to be easily adapted and deployed for free (for example, on github pages, Amazon s3 or Google cloud hosting). 

# Install and run project
    
    git clone https://github.com/jimmoffet/actionmap.git
    cd actionmap
    open ./index.html

To fill in your own data, open google-doc-url.js, check out the links and create your own google sheets in the same format (you can copy/paste directly between google sheets), publish your new google sheets (file > publish), then replace the links in your google-doc-url.js file. When you change something on your google sheets, the changes will be reflected in your map (you might need to clear your cache or reload the page a couple of times).

Demo can be found at https://www.resistancemappingproject.com/
