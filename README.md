# Frame Check Sequence Error Checking Mechanism
This app is a MATLAB-based app implemented based on the concept of cyclic redundancy check (CRC).

#### Requirements
* MATLAB R2019a or later

#### Features
* *Generate*
  *  Allows the user to enter the input sequence and polynomial. The app then outputs the FCS bits and the resultant codeword.
* *Receive*
  * Accepts a string of 0’s and 1’s. If its length is the same as the codeword’s, it checks if errors are detected in the sequence, and if it will accept or reject the said input.
* *Alter*
  * Introduces an error sequence to the original transmitted sequence. Like the receive function, it checks whether the modified   sequence contains errors, and whether it will be accepted or rejected.
