# aoiya2023.github.io

HTML
1. Create an HTML page on your local machine named foo.html. At a minimum, it should have HTML and BODY tags.
2. Open the page in your browser.
    What is the URL of the page?
        file:///C:/Users/aoiya/Desktop/cs124/foo.html
    What is the protocol of that URL?
        file (whatever before the first :)
3. Edit the page so that its title is HTML and Forms and it has an H1 header that is the same.
    Where does the title of the page appear in the browser?
        tab
    Where does the H1 header of the page appear in the browser?
        beginning of page

Forms and HTTP
1. Create a form in your HTML page.
Make the action for the form be https://www.cs.hmc.edu/~rhodes/cgi-bin/query.py. 
The form should have two groups of radio buttons: one containing three colors, and the other containing four compass directions. 
In addition, it should have a group of three checkboxes (hungry, sad, and short).
It should have two input fields, one to enter a name, and the other to enter an age.
Finally, it should contain a submit button.

2. Open the Chrome Developer Tools (View/Developer/Developer Tools) and select the Network pane.

3. Enter information into the form and click the submit button. 
    When you submit this form, what is the full URL that the browser requests?
        https://www.cs.hmc.edu/~rhodes/cgi-bin/query.py?name=Aoi+Yasuda&age=21&color=yellow&direction=north&check=hungry
    How are the values in the form sent to the server?    
        string appended to the URL
    Where does the "Submitted Form Data" page (displayed after you click the submit button) come from?
        

4. Change the form tag in your HTML page so that the values in the form are sent using a POST method rather than a GET method
    When you submit this form, what URL does the browser request?
        https://www.cs.hmc.edu/~rhodes/cgi-bin/query.py
    How are the values in the form sent to the server? 
        Payload - sends it as part of the request

5. Try adding a date input type to the form.
    Does it have special UI on Firefox? On Chrome? On Safari (if on a Mac)?
        mm/dd/yyyy
    How does the UI degrade for browsers that don't support it?

6. Make sure that the form is easy to use. Ensure there are labels, that the two radio groups are separate, 
and that tabbing tabs through the input fields appropriately.
    What does the for attribute of a label do?
    Why is the UI element called a radio button?
    How can you preselect one of the radio buttons? 

7. Copy your HTML page to a server so that you can access it using the html protocol rather than the file protocol.
Use Github Pages to host your html page.
    Create a Github repo named username.github.io (where username is your Github username).
    Create a file named index.html (using the Github web interface) and copy the contents of your html page to it.
    Commit the file contents.
    Your webpage will be available within a minute or two at https://username.github.io or https://username.github.io/index.html

8. Open that URL on your phone.
    Does the date input type have a special UI? 
    What about the age field? What kind of keyboard should come up when the user taps on that field? 

9. Update the form, if necessary, so that an appropriate keyboard is displayed when the user edits the age field.
    What other keyboards can you make appear (based on different input types)? 
    
