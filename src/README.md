## Doc Comments Group Assignment

### Classes

* Device Class

    - 3 Attributes to track
    - Two additional fields
        
        - (Public) Unique Immutable ID
        - (Private) Static count
    - Parameterized Constructor 
    ```java
    public class Device {
        String var1, var2, var3;
        public Device(int var1, int var2, int var3) {
            this.var1 = var1;
            //...
        }
    }
    ```
    - Constructor creates the unique id
    - Getter for every field except the private count field
    - Overide the toString() method to show the id and the 
      object values minus the static count
      
* Class for a list of devices

    - Methods
        
        - Add a Device
        - Remove a device
        - Find a device by Unique ID
        - Count devices
    
* Class for Menu and Communication
    
    - Methods
        
        - Display menu
        - Read and parse user input using a Scanner
          
            - Display message for invalid input
            - Use switch statement for flow control for the
              different valid options
            - Display exit message when the user selects 6  
        - 
    - Main method that initializes the program and starts the 
      interactive loop