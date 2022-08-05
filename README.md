# Password-Generator-Application-in-Python
  Google gives you suggestions when you create your new passwords Right! But how about creating your own password generator in python, GUI application. Sounds amazing, isn’t it? So let’s go ahead and make our another great GUI application or you can say a mini project in python. As we all know whenever we sign up for a new website we need to set our username and password. After typing our username when we take our cursor to the password section Google gives us a suggestion for a new password.
  
# Explanation
  So before starting the actual coding let’s first understand some theory. In this password generator GUI application, we are going to use two 3 modules. Firstly, the Tkinter module for creating an application window. Secondly, pyperclip module for copying the generated password. Now, remember these two modules are not inbuilt modules. So you have to install them using the pip install command. The third and final module we are going to use is a random module to generate the random password finally. The quick logic for this GUI application is going to be like this: Firstly, We will create import the necessary modules. Then we will create the application window. After that, we will generate a random password and copy it. Afterward, In the end, we will create some buttons to make our password generator application more interactive for the user. Because after all, it’s a GUI.
  
# Understanding the Code 
Firstly, Let’s understand the coding now with some technical terms. Here, we are going to explain the code stepwise. So that if you have some knowledge of python you will be able to make this password generator application on your own by just reading this section.

Step1: Firstly, Import necessary modules ( Tkinter, pyperclip and random)

Step2: Then, Initialize Tkinter using Tk() method

Step3: After that, Create an application window for GUI application using the geometry method of Tkinter

Step4: Declare 2 variable. One for storing the generated password and another one for taking password length input from user.

Step5: Then, Define the generate password method.

Step6: Define the copy to clipboard method.

Step7: Then, Create Button widgets and set commands as per the above defined methods.

Step8: Finally, Run infinite mainloop to run the application.
