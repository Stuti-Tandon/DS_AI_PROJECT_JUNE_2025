# Run a Python file in Jupyter
- Syntax %run path/to/your_script.py
- This command will execute the entire script as if running it from the command line, and the output will appear directly in the notebook cell.

# Diff bw Python 2 & 3
- Python 2:
  1. Dividing two integers with / performs floor division and returns an integer (e.g., 7/2 yields 3)
  2. Print statements that work 
     * print "Hello"
     * print("Hello")
- Python 3:
  1. Dividing two integers with / returns a float (e.g., 7/2 yields 3.5).
  2. Print statements that work 
     * print("Hello")

# Escape Characters in python
- escape characters are used to represent special characters within strings that cannot be included directly or would otherwise have special meaning.
- They start with a backslash (\) followed by a character that indicates what to insert.
- Common escape characters in Python include:
\' : Single quote
\" : Double quote
\\ : Backslash
\n : Newline (moves to the next line)
\t : Tab (horizontal tab space)
\r : Carriage return
\b : Backspace
