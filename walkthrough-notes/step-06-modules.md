# Step 6 : Modules
_ Date : 16 September 13:13
_ Goal : Replace the alert used previously with a proper toast using Message Toast
_ What I did : 
            _ Defined the MessageToast module in the controller
            _ Changed the alert to MessageToast.show  

_ What I learned : 
            _ First we use define to load the modules
            _ When they are loaded, the callback function is called
            _ This Assynchronous Module Definition (AMD) syntax separates the loading and the execution code, gretly improving the app performance
