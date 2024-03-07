Features:
Pre-order Modal: 
    A modal window allows users to submit pre-order requests. It captures user information such as email and name, simulating a POST request to an API endpoint.
Production Status Tracking:
    Dynamically updated sections display the current status of hot sauce production, from initial production to shipping.
Responsive Design: 
    The website layout adjusts to fit different screen sizes, ensuring usability on mobile devices, tablets, and desktops.
Dynamic Image Loading:
    Depending on the device (mobile or desktop), different sets of images are loaded to optimize performance and visual appeal.
Auto-update Option:
    An additional modal asks users if they wish to automatically update the production status. If accepted, it simulates real-time status updates.

How to open:
Open index.html: Launch the index.html file in a web browser to view the project.

JS file includes:
The main JavaScript file contains functions responsible for handling the pre-order modal interactions, dynamically loading images according to device type, and updating the production status.
The setActiveStep function controls the logic for updating production steps and the associated tracking bottle images.
The updateProcess function can automatically simulate the production process when users agree to the auto-update prompt.