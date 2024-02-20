# cbc
Print stdin or stdargs char by char

## Usage
Run any command in terminal, and pipe its output to cbc's stdin

```commandline
$ some_command | cbc
```

Or pass the text as an argument

```commandline
$ cbc the text I want to print
```

The default print time is 3 seconds. 
To change the total print time, use the '-t' / '--time' option

```commandline
$ some_command | cbc -t 1.5
```

To change the time interval between chars (which normally is calculated dividing the print time by the number of characters to print), use the '-i' / '--interval' option

```commandline
$ some_command | cbc --interval 0.03
```

Use the '-h' or '--help' flag to get help
