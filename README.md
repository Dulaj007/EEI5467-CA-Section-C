# EEI5467-CA-Section-C
EEI5467- Software Testing and Quality Assurance CA Section C Step by Step Tutorial 
# This tutorial is made for my colleagues who having troubles with EEI5467_2023 CA Section C 
First of all i wanna say I am no expert in Selenium IDE. So if you catch any mistakes or wanna add something to this make sure to comment that out.

Make sure to follow my github and Medium for more tutorials

Medium - https://medium.com/@agdulaj

Github - https://github.com/Dulaj007

By Yasitha Dulaj

# Step 01 
add Selenium IDE extension to your browser. Then open a new project.
# Step 02 
Watch this video https://youtu.be/4I7xay_NV8A?si=ASIghxIRrajs2khN and record a test case for your website navigation (just navigate through your web page and record a test case thats all). Save it !!
# Step 03 
Open VerifyTestTEMP.side click verify tests cases.

# Here is instruction with explanation to those verify tests. Those orginally from my report so make sure to change website, create your own tests cases and add your own instructions. Good luck !!
# -------------------------------------------------------------------------------------------------
# Verify Attribute test 
Expected Result - All lines green colored except line 5. 

Output Breakdown - in line 3 we click an attribute in this page then in line 4 using " Verify element present " we verify that attribute after that line 5 we use same (Verify element present) but try to verfy random attribute that dose not exists in this web site. thats why it shows an error then line 6 we use " Verify element not present " with the same attribute we use in line 5 so its verify that random attribute dose not exists in the web site.
# -------------------------------------------------------------------------------------------------
# Verify Text test 
Expected Result - All lines green colored except line 5. 

Output Breakdown - in line 3 we click a link-text in this page then in line 4 using " Verify text " we verify that text after that line 5 we use same (Verify text) but try to verfy random text that dose not exists in this web site. thats why it shows an error then line 6 we use " Verify not text " with the same text we use in line 5 so its verify that random text dose not exists in the web site.
- This shows negative and positive impact of testing an text.
# -------------------------------------------------------------------------------------------------
# Verify Input test 
Expected Result - All lines green colored except line 14 and 18. 

Output Breakdown - in line 7, 10, 13, 17 we have use "Veify Value" to verify name, city, phone number, email input fields since there is no issues all green colored then line 14 we also use "Veify Value" but this time we try to verify Phone number filed(int) but instead adding a string to it thats why it shows an error. also in line 18 we try to verfy that email filed but without adding a correct email thats why it shows an error as well.
- This shows negative and positive impact of testing an input fields.
# -------------------------------------------------------------------------------------------------
