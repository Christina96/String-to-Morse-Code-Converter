# String-to-Morse-Code-Converter
A text-based Python program to convert Strings into Morse Code.



String to Morse Code Converter
This Python program converts strings into Morse code. It takes a user-input string and returns its Morse code representation.

Usage
To use this program, simply run the main() function. It will prompt you to enter a string to convert to Morse code. The program will then print the Morse code representation of the input string to the console.

# Example

input_string = "Hello, World!"
morse_code = string_to_morse(input_string)
print("Input String:", input_string)
print("Morse Code:", morse_code)
Output:


Input String: Hello, World!
Morse Code: .... . .-.. .-.. --- --..-- / .-- --- .-. .-.. -.. -.-.-- 
# Implementation Details
The program utilizes a dictionary (morse_code_dict) to map each uppercase letter and digit to its corresponding Morse code representation.
The string_to_morse(input_string) function iterates over each character in the input string, checks if it exists in the morse_code_dict, and constructs the Morse code string accordingly.
Special characters or characters not found in the dictionary are preserved as is in the Morse code output.
