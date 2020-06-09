<h1 align="center">get_next_line</h1>

Get_next_line is a simple function that reads a given file descriptor, and returns the text one line at a time, seperating by newlines.
It will store any bytes read but not returned, holding onto it until get_next_line is called again.

As a bonus, get_next_line is able to handle multiple file descriptors simultaneously, and hold onto bytes read but not returned
for each file descriptor.
