<h2>Here are some usage examples for your Prison Management System project, showcasing how it works in different scenarios:</h2>
<h3>0. Main Function : </h3>

              ----- PRISON MANAGEMENT MAIN MENU -----
           ============================================
                    1.  New Prisoner entry.
                    2.  Prisoner Details.
                    3.  Attendance Prisoner.
                    4.  Release Prisoner.
                    5.  Search Prisoner.
                    6.  Prison File.
                    7.  Exit.
           ============================================
                 Enter your choice (1 - 7) : 

<h3>1. Sign up : </h3> 
Description: The user must Sign in with a username and password to access the system. <br>
<h4>Example :</h4>

              Prison Station Management System 
            ------------------------------------
               1. Sign in
               2. Exit
            ------------------------------------
             Please enter your choice (1 - 2) : 

choice : 1 
   
             ==)         Sign in : 
                    ------------------
                        Username :
                        Password : 
                    ------------------
                   Press to go login...

choice : 2 <br>
             ==) Description : Exits the program. <br>
<h4>Example :</h4>
  
              Output: Exiting Program...


<h3>2. Logging In : </h3>
Description: The user must log in with a username and password to access the system. <br>
<h4>Example :</h4>
        
            Enter Prisoner's Name                       : John Doe
            Enter Prisoner's Gender (Male/Female)       : Male
            Enter Prisoner's Age                        : 35
            Enter Prisoner's Height                     : 180
            Enter Prisoner's Eye Color                  : Brown
            Enter Prisoner's Crime                      : Theft
            Enter The Penalty Period by months or years : 5 years
            Existing Cell no: 999 1000 1001 1002 1003 1004 1005 1006 1007 1008 1009
            Enter any cell for prisoner                 : 1003
            Output : New Prisoner added successfully! 
            Press any key to continue...

<h3>3. Viewing Prisoner Details : </h3>
Description: Displays a list of all prisoners with their details. <br> 
<h4>Example : </h4>

    <===============> Prisoner List <==============> 
            No              :   1
            Name            :   John Doe
            Gender          :   Male
            Age             :   35 years old
            Height          :   180 cm
            Eye Color       :   Brown
            Crime           :   Theft
            Cell No         :   1003
            Penalty Period  :   5 years
            
              Press any key to continue...
     <=============================================>       

<h3>4. Marking Attendance : </h3>
Description : Marks the attendance of a specific prisoner. <br> 
<h4>Example : </h4>

          Enter Prisoner's No: 1
          Output: Prisoner's Attendance: 1003

<h3>5. Releasing a Prisoner : </h3>
Description : Removes a prisoner from the system. <br> 
<h4>Example : </h4>

        Enter Prisoner's No: 1
        Output: Prisoner released successfully! 
            Press any key to continue...

<h3>6. Searching for a Prisoner : </h3>
Description : Searches for a prisoner by name. <br> 
<h5>Enter Prisoner's Name: John Doe </h5>

                ==)  Output:
            Name            :   John Doe
            Gender          :   Male
            Age             :   35 years old
            Height          :   180 cm
            Eye Color       :   Brown
            Crime           :   Theft 
            Cell No         :   1003
            Penalty Period  :   5 years

<h3><7. Saving Prisoner Data to a File :</h3>
Description : Saves all prisoner details to a file named prison_file.txt. <br> 
<h4>Example : </h4>

            Output: The prisoner file has been saved successfully! 
                        Press any key to continue...
<h3>Content of prison_file.txt : </h3>

          <===================> Prisoners Lists <===================>
          
                        No              :   1
                        Name            :   John Doe
                        Gender          :   Male
                        Age             :   35 years old
                        Height          :   180 cm
                        Eye Color       :   Brown
                        Crime           :   Theft
                        Cell No         :   1003
                        Penalty Period  :   5 years
          
          <========================================================>

<h3>8. Exiting the Program</h3> 
Description: Exits the program. <br>
<h4>Example : </h4>

            Output: Exiting Program...
