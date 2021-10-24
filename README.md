# SilverballMania2021MEGA
Slightly extended version of SilverballMania 2021 with enhanced sound support -- only works with Hardware Version 3 or greater
  
Note: This code has a dependency on BallySternOS - it won't build without those files. They're located in a repository here:
https://github.com/BallySternOS/BallySternOS
The base library is separated from this implementation so that it can be used by multiple projects without needing to be updated multiple times. For best results, always get all files (both the base library and the SilverballMania2021MEGA files) each time you build. Read on for basic instructions on how to build this code.


### To use this code
* Download the zip file (Code > Download ZIP) or clone the repository to your hard drive.  
* Get the BallySternOS files ( BallySternOS.* and SelfTestAndAudit.* ) from the repository here:  
 * https://github.com/BallySternOS/BallySternOS/tree/master
 * (Code > Download ZIP)
* Unzip the SilverballMania2021MEGA repository and name the folder that it's in as:
  * SilverballMania2021MEGA  
* Copy BallySternOS.* and SelfTestAndAudit.* into the SilverballMania2021MEGA folder
* Open the SilverballMania2021MEGA.ino in Arduino's IDE
* In the BSOS_Config.h you'll see a couple of parameters in #define statements
  * if you want to use your machine's sound card, make sure this line is uncommented:  
   * #define BALLY_STERN_OS_USE_DASH51  
  * if you have a Wav Trigger installed, uncomment this line 
    * #define USE_WAV_TRIGGER
    * or 
    * #define USE_WAV_TRIGGER_1p3  
  * The WAV files for the Wav Trigger board can be found here:  
    * https://drive.google.com/file/d/1xsmqtWZP9hqvHiajO6iWM1bCcZa6pH1e/view?usp=sharing  
    
  
Refer to the PDF or Wiki for instructions on how to build the hardware.   
  
  
Again, the audio file zip is here:  
https://drive.google.com/file/d/1xsmqtWZP9hqvHiajO6iWM1bCcZa6pH1e/view?usp=sharing  
  
  
