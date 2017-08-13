###Test plan


1.	Notepad
Notepad is a generic text editor included with all versions of Microsoft Windows that allows you to create, open, and read plaintext files. If the file contains special formatting or is not a plaintext file, it will not be able to be read in Microsoft Notepad. 

2.	List of features 
In this test suite, we would like to test the main features of the program such as 
1. Creation of the document
2. The ability to input text (letters, whole paragraphs from different sources). 
3. The ability to recognize different symbols.
4. The ability to save the file.
     
3.	Problematic areas  
The list of the features in the section 2 is also the most problematic areas in the whole application so they should be checked in the first case.


4.	Risks 
The main risk is that some of the features will not work properly on the moment of the release and some of our clients will switch to our competitors, which in its case will cause a tremendous loss in profit.  
    
5.	Strategy
On the base of the features, problematic areas and main risks, we already can provide a test strategy that will help us to minimize risks and provide the most suitable list of tests, which should be implement in the right way and in the right order, based on our resources. 

5.1	Environment
We will provide all our tests on the base of windows 10, because it is the most common operation system.

5.2	People 
The team that will work on this project is consist from one specialist because as we think the scale of work that we have here is suitable for one person, more people would be excessively.
5.3	Tools
To test this program we going to use Lenovo U3W160Px laptop, because it is a middle class computer that is like most middle class laptops on the market. 

5.4	List of tests 
The test cases in this suite have the heist priority “1” because they are the functional features of the program and client will check them in the first place. We base the order of the tests in the order in which client will use the features, one after another. In the execution part every step will be marked with status, ‘0’ means successes and ‘1’ means bug has been filed.


TC ID NP00011
Priority 1
Idea: The text file could be create 
Revision history
Created on: 13/08/17
Execution part 
1.	Open Notepad and type any text you want in the file.’0’
2.	Once done, save the file by clicking File and then Save.’0’
3.	When saving the file, make sure the file is saved with a .txt extension.’0’

TC ID NP00012
Priority 1
Idea: The text file could be create 
Revision history
Created on: 13/08/17
Execution part 
1.	On the Windows Desktop or in any folder, right-click an empty spot.’0’
2.	In the pop-up menu, select New and then Text Document.’0’
3.	After this has been done, a file should appear named "New Text Document".’0’
4.	Double-click this file to open the text document, ‘0’


TC ID NP00013
Priority 1
Idea: All types of the text symbols can be display
Revision history
Created on: 13/08/17
Execution part 
The number “1” was simplified for better and faster support. Step “2” consist of few different tasks that have the same meaning and value and gathered for time save. 
1.	Create a document’0’
2.	Use a English, Russian, Arabic, Japanize and  wingding’0’

TC ID NP00014
Priority 1
Idea: The whole paragraph can be transported from any source to the notepad.
 Revision history
Created on: 13/08/17
Execution part 
      The number “1” was simplified for better and faster support Step “2” consist of few different tasks that have the same meaning and value and gathered for time save.
1.	Create a document’0’
2.	Copy the paragraph from any source using ‘ctrl-c’ and past with ‘ctrl-v’ ‘0’ , copy the same paragraph using ‘copy’ and paste it using the ‘paste’ ‘0’

TC ID NP00015
Priority 1
Idea: The file can be saved after any changes.
Revision history
Created on: 13/08/17
Execution part 
             The number “1” was simplified for better and faster support
1.	Create a document’0’
2.	Make any note’0’ 
3.	Use the button “File” at the top bar’0’
4.	Use the button “Save”.’0’
5.	Create the name for the file and with the file type .txt’0’
6.	Open the file again.’0’
7.	Check if the consistent of the file is still the same. ‘0’ 
   
5.	 Assumption 
     As all the necessary tests have been, completed and all tested functions are working and zero bugs were found. From this point, we can say that program Notepad is simple and there is not too much space for bugs. It is ready for the release and further distribution.
