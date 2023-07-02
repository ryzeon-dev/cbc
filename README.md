# cbc
Print stdin char by char

## Usage
Run any command in terminal, and pipe its output to cbc's stdin

```commandline
$ some_command | cbc
```

Default print time is 3 seconds (more the text, faster the interval between chars, but output time is the same), if you want to change it, set the printing time using '-t' or '--time'

```commandline
$ some_command | cbc --time 2
```

Use the '-h' or '--help' flag to get help
