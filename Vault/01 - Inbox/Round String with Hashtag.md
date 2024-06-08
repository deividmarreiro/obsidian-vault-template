```python
def create_blocked_string(input_string):
    # Define the padding and border characters
    border_char = '#'
    padding = ' '

    # Calculate the length of the input string including the padding
    length = len(input_string) + 2 * len(padding)

    # Create the border line
    border_line = border_char + (border_char + padding) * (length // len(padding)) + border_char

    # Create the middle line with the input string
    middle_line = border_char + padding + input_string + padding + border_char

    # Print the final block of text
    print(border_line)
    print(middle_line)
    print(border_line)

# Example usage
input_string = "Check for updates and install them"
create_blocked_string(input_string)
```