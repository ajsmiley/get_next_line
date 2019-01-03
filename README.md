# get_next_line
This is the second project at <a href = "https://www.42.us.org/">42 Sillicon Valley.</a> This project requires that you write a program that can read a file of an unknown size line by line and print its output.
# How do I use this darn program??
It's quite easy when we break it down step by step. First copy and past this code into the terminal window:

    https://github.com/ajsmiley/get_next_line.git
Next we're going to move into to the folder using this command:
    
    cd get_next_line
Now that we are in the directory we can build the library:

    make -C libft/
Now we can create the execcutable with this code:

    gcc -Wall -Wextra -Werror -I./libft/includes/ -L./libft -lft -o gnl get_next_line.c main.c
Almost done! Now all we have to do is run the executable and give it a file to read and you're done!

    ./gnl getthis.c
If you want to test a custom file make sure it add it into the folder and then call it with ./gnl
