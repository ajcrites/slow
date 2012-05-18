# ```slow```

```slow``` is a shell utility that reads input and prints it out in a delayed fashion.  You can specify how many lines you want to print at a time as well as the delay between each chunk of lines.

## Requirements

* python 2.5.2 (probably works on other python 2 versions)

## Installation

Move ```src/slow``` to somewhere on your ```$PATH```.

## Usage
    slow [-l <lines-to-print-at-once>] [-d <time-delay>]

### Options

* ```-d``` -- Number of seconds to delay.  Can be a decimal, but must be positive. (default: .5)
* ```-l``` -- Number of lines to print between each delay.  Must be positive (defalt: 3)
