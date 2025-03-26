📜 get_next_line – One Line at a Time

For my third project at Hive Helsinki, I built get_next_line(), a function that reads a file one line at a time, including the newline character. 📖 Whether reading from a file or stdin, repeated calls return the next line until there's nothing left to read (or an error occurs). In that case, it returns NULL.

The bonus part took things up a notch by handling multiple file descriptors at once! 🔄 That means if you're reading from multiple files (e.g., fds 3, 4, and 5), the function keeps track of each one separately—without mixing up lines or losing progress.

⚡ This project was a great deep dive into memory management and file handling in C. On to the next challenge!
