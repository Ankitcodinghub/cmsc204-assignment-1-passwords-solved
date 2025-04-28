# cmsc204-assignment-1-passwords-solved
**TO GET THIS SOLUTION VISIT:** [CMSC204 Assignment 1-Passwords Solved](https://www.ankitcodinghub.com/product/cmsc204-assignment-1-passwords-solved-3/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;59189&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMSC204  Assignment 1-Passwords Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (4 votes)    </div>
    </div>
Concepts tested by this program:

ArrayList

static

Read &nbsp;Files

Javadoc

JUnit Tests

Exceptions

Create an application that will check for valid passwords.&nbsp; The following rules must be followed to create a valid password.

<ol>
<li>At least 6 characters long</li>
<li>10 or more characters is a strong password, between 6 and 9 characters is a weak (but acceptable) password.</li>
<li>At least 1 numeric character</li>
<li>At least 1 uppercase alphabetic character</li>
<li>At least 1 lowercase alphabetic character</li>
<li>At least 1 special character</li>
<li>No more than 2 of the same character in a sequence</li>
</ol>
Hello@123 – OK

AAAbb@123 – not OK

Aaabb@123 – OK

<strong><u>Operation:</u></strong>

When the application begins, the user will be presented with a screen that states the above instructions for creating a password, two text entry boxes for typing in a password, and three buttons.

If the user wants to check a single password, they will type in the password in both boxes and select the “Check Password” button.

If the user wants to read in and check a list of passwords, they will select the “Check Passwords in File” button, be presented with a file explorer, and select the file to read from.&nbsp; Those passwords that failed the check will be displayed, with their error message.

<strong><u>Specifications</u></strong>:

<strong>The Data Element</strong>

String

<strong>The Data Structure</strong>

ArrayList of Strings

<strong>Utility Class</strong>

<ol>
<li>Create a PasswordCheckerUtility class based on the Javadoc given you.</li>
<li>The PasswordCheckerUtility class will have at least three public methods:</li>
</ol>
<ul>
<li>isValidPassword:</li>
</ul>
This method will check the validity of one password and return true if the password is valid and throw one or more exceptions if invalid.

<ul>
<li>isWeakPassword:</li>
</ul>
This method will che &nbsp;throw an exception.

<ul>
<li>getInvalidPasswords</li>
</ul>
This method will check an ArrayList of passwords and return an ArrayList with the status of any invalid passwords (weak passwords are not considered invalid).&nbsp; The ArrayList of invalid passwords will be of the following format:

&lt;password&gt;&lt;blank&gt;&lt;message of exception thrown&gt;

<ul>
<li>For each password requirement, you must have a static private method that validates the password for that requirement and throws an exception if invalid.</li>
</ul>
<ol start="3">
<li>Create a separate exception classes for each exception listed in PasswordCheckerUtility Javadoc.</li>
</ol>
<strong>Hints:</strong>

<ul>
<li>Always check for the length of the password first, since that is the easiest and fastest check. Once the password fails one rule, you do not need to check the rest of the rules.</li>
<li>To check for a special symbol, use the “regular expression” construct. Check the whole password, not just an individual character, using the following:</li>
</ul>
Pattern pattern = Pattern.compile(“[a-zA-Z0-9]*”);

Matcher matcher = pattern.matcher(str);

return (!matcher.matches());

<ul>
<li>You will need to import Pattern and Matcher.</li>
<li>Few helpful links on regular expression”</li>
<li><a href="https://www.vogella.com/tutorials/JavaRegularExpressions/article.html">https://www.vogella.com/tutorials/JavaRegularExpressions/article.html</a></li>
<li><a href="https://www.youtube.com/watch?v=rhzKDrUiJVk">https://www.youtube.com/watch?v=rhzKDrUiJVk</a></li>
<li><a href="https://www.youtube.com/watch?v=sCuOJ8uadOg">https://www.youtube.com/watch?v=sCuOJ8uadOg</a></li>
</ul>
<strong>The GUI:</strong>

The GUI has been provided, however you need to:

<ul>
<li>Ask the user to enter the password and to re-type the password. If the two are not the same, inform the user.</li>
<li>Use methods of PasswordCheckerUtility to check validity of one password when user clicks on “Check Password” button.</li>
<li>Use methods of PasswordCheckerUtility to check validity of a file of passwords when user clicks on “Check Passwords in File” button.</li>
<li>Use a FileChooser for the user to select the input file.</li>
<li><u>Use try/catch structure to catch exceptions</u> thrown by PasswordCheckerUtility methods</li>
</ul>
<strong>&nbsp;</strong>

<strong>Exceptions</strong>

<u>Provide exception classes</u> for the following:

<ol>
<li>Length of password is less than 6 characters (class LengthException)</li>
</ol>
Message – The password must be at least 6 characters long

<ol start="2">
<li>Password doesn’t contain an uppercase alpha character (class NoUpperAlphaException)</li>
</ol>
Message – The password must contain at least one uppercase alphabetic character

<ol start="3">
<li>Password doesn’t contain a lowercase alpha character (class NoLowerAlphaException)</li>
</ol>
Message – The password must contain at least one lowercase alphabetic character

<ol start="4">
<li>Password doesn’t contain a numeric character (class NoDigitException)</li>
</ol>
Message – The password must contain at least one digit

<ol start="5">
<li>Password doesn’t contain a special character (class NoSpecialCharacterException)</li>
</ol>
Message – The password must contain at least one special character

<ol start="6">
<li>Password contains more than 2 of the same character in sequence (class InvalidSequenceException)</li>
</ol>
Message – The password cannot contain more than two of the same character in sequence.

<ol start="7">
<li>Password contains 6 to 9 characters which are otherwise valid (class WeakPasswordException)</li>
</ol>
Message – The password is OK but weak – it contains fewer than 10 characters.

<ol start="8">
<li>For GUI – check if Password and re-typed Password are identical (class UnmatchedException)</li>
</ol>
Message – The passwords do not match

Throw this exception from the GUI, not the utility class.

<strong>Note</strong>: If more than one error is present in a password, use the above order to throw exceptions.&nbsp; For example, if a password is “xxyyzzwwaa$”, it fails rules 2 and 4 above.&nbsp; Throw a NoUpperAlphaException, not a NoDigitException.

<strong>Junit methods</strong>:

<ul>
<li>setup</li>
<li>teardown</li>
<li>for each password requirement method in the PasswordCheckerUtitily you must have a test case that passes and another one that fails</li>
<li>success and fail test cases for each public method in the PasswordCheckerUtitily</li>
<li>The file that you use for getInvalidPasswords method Junit test must contain at least one invalid and one valid of each password requirement case.</li>
</ul>
This is a sample of Junit test cases that you must have:

If you select the button which reads “Check Passwords in File”, you will be presented with a file chooser.&nbsp; You must navigate to where you stored the file “passwords.txt” and load it.&nbsp; The file will be in the following format (one password per line):

Examples:

<ol>
<li>No lowercase alphabetic character</li>
</ol>
Displayed to user:

<ol start="2">
<li>No digit</li>
</ol>
Displayed to user:

<ol start="3">
<li>If the password is OK, but between 6 and 10 characters, you will see:</li>
<li>If password has more than two of the same characters in a row</li>
</ol>
Displayed to user:

<ol start="5">
<li>If password is valid</li>
<li>If the passwords do not match:</li>
</ol>
Displayed to user:

<ol start="6">
<li>Based on the file above, when the user selects “Check Passwords in File”:</li>
</ol>
Displays errors to user when selecting Check Passwords in File. Note that valid passwords (including weak but otherwise valid passwords) are NOT displayed.

<u>Deliverables</u>:

<u>Design:</u>

Initial design document (UML and/or pseudo-code)

<u>Implementation:</u>

Final design document

Java files – The src folder with your driver (javafx application), data manager, exceptions and Junit Test (.java) files

Javadoc files – The entire doc folder with your javadoc for student generated files

Learning Experience document

GitHub screen shot

<u>Deliverable format</u>: The above deliverables will be packaged as follows. Two compressed files in the following formats:

LastNameFirstName_AssignmentX.zip [compressed file containing following]:

doc [a directory] <em>include the entire doc folder with the javadoc for </em>

<em>student generated files</em>

file1.html (example)

file2.html (example)

class-use (example directory)

LearningExperience.doc <em>or other text format</em>

src [a directory] <em>contains your driver (javafx application), data manager, exceptions and Junit Test (.java) files</em>

File1.java (example)

File2.java (example)

File_Test.java (example)

<em>GitHub screen shot.</em>

LastNameFirstName_AssignmentX_<strong>Moss</strong>.zip [compressed file containing only]:

<em>.java file which includes the driver (javafx application), data manager, exceptions and Junit Test (.java) files – </em><em>NO </em>

<em>FOLDERS!!</em>

File1.java (example)

File2.java (example)

There are two parts to the rubric.&nbsp;&nbsp; First, the project is graded on whether it passes public and private tests.&nbsp; <strong>If it does not compile, a 0 will be given</strong>. These points add up to 100.&nbsp; Second, the score is decremented if various requirements are not met, e.g., missing required methods, missing Junit test cases, no Javadoc, no UML diagram, uses constructs that are not allowed, etc.

&nbsp;
