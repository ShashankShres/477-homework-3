# 477-homework-3
CSCE 477 homework 3 assignment for Dr. Kumar

My login page was designed with basic HTML, JavaScript, and CSS. I used inline css to add basic design to the page so it is not just black and white text boxes. From there, I used basic HTML to create the text boxes as well as a button to submit the information. JavaScript was used to add actual functionality to my login page. It checks if the password is a proper length, if there is an @ in the username, as well as processes the submission. 

To run the file, download it and add it to a folder. You can run it by opening the file in file explorer or typing start index.html in VS Code.

I fixed the XSS attack problem before submitting, but prior to fixing, all you needed to do was type something like " test@test.com<img src=x onerror=alert('xss')> " to get an alert to pop up. This bypassed security since there was an @. 
