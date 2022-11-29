# VendingMachine
This is a simple web application written in Blazor for Sonic Healthcare coding challenge.

Vending Machine application information:
This web application is developed using Blazor framework(Trial version of Telerik UI for Blazor library) in .NET 6. The layout has been kept simple(css missing) because the focus was on the functionality of the application.
Tests have not been written. Information is held in memory during runtime.
Due to time constraint on my end, I have kept the functionality and design to the minimum required. I will be more than happy to update the functionality and design if required.

Index/Home page:
The vending machine has 10 items in it initially. The assumption is that the machine screen provides keypad and other functionalities required to enter values in the textboxes and to click on buttons.
The items are labelled from 0 to 9. The user enters the number of the flavour in the textbox and clicks Next button. By default, the selected flavour is the flavour with number 0.

Payment page:
When the user enters the number of flavour and clicks Next button, a new page appears on the screen which displays the cost of the drink. Two buttons are provided to choose a payment method.
The assumption is that the user clicks on one of the options and pays accordingly. In real scenerio, after the payment is completed, the information would be displayed automatically but here for the simplicity, I have added a Done button which the user is assumed to click after the payment is finalised. 
Go Back button has been provided so the user can go back anytime to change flavour number.
