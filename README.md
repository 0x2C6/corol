# Corol [![Gem Version](https://badge.fury.io/rb/corol.svg)](https://badge.fury.io/rb/corol)

Simple ruby gem to make texts beautiful.

Usage is very simple . Just call color's name as a method and let it to work. You can see methods below. New colors will be added.

## Installation

```
gem install corol
```
You should use 'sudo' to install gems .

## How to use

```ruby
require 'corol'

puts "This text's output will be red".red   #=> Output will be red
puts "This text's output will be bold".bold #=> Output will be bold
```


* Tested on Gnome Terminal . Please note that some colors may not work on some colsoles.

```ruby
#### Text Colors Codes ####
RED              =    "\e[31m" #Variable and Color code for red
WHITE            =    "\e[0m"  #Variable and Color code for white and resetting color or format
BLACK            =    "\e[30m" #Variable and Color code for black
GREEN            =    "\e[32m" #Variable and Color code for green
YELLOW           =    "\e[33m" #Variable and Color code for yellow
BLUE             =    "\e[34m" #Variable and Color code for blue
MAGENTA          =    "\e[35m" #Variable and Color code for magenta
CYAN             =    "\e[36m" #Variable and Color code for cyan
LIGHT_RED        =    "\e[91m" #Variable and Color code for light red
LIGHT_GREEN      =    "\e[92m" #Variable and Color code for light green
LIGHT_YELLOW     =    "\e[93m" #Variable and Color code for light yellow
LIGHT_BLUE       =    "\e[94m" #Variable and Color code for light blue
LIGHT_MAGENTA    =    "\e[95m" #Variable and Color code for light magenta
LIGHT_CYAN       =    "\e[96m" #Variable and Color code for light cyan
```

```ruby
#### BackGround Colors Codes ####
BACK_RED         =    "\e[41m"  #Variable and Color code for Background red
BACK_GREEN       =    "\e[42m"  #Variable and Color code for Background green
BACK_YELLOW      =    "\e[43m"  #Variable and Color code for Background yellow
BACK_BLUE        =    "\e[44m"  #Variable and Color code for Background blue
BACK_MAGENTA     =    "\e[45m"  #Variable and Color code for Background magenta
BACK_CYAN        =    "\e[46m"  #Variable and Color code for Background cyan
BACK_LIG_RED     =    "\e[101m" #Variable and Color code for Background light red
BACK_LIG_GREEN   =    "\e[102m" #Variable and Color code for Background light green
BACK_LIG_YELLOW  =    "\e[103m" #Variable and Color code for Background light yellow
BACK_LIG_BLUE    =    "\e[104m" #Variable and Color code for Background light blue
BACK_LIG_MAGENTA =    "\e[105m"  #Variable and Color code for Background light magenta
BACK_LIG_CYAN    =    "\e[106m" #Variable and Color code for Background light cyan
```

```ruby
#### Formatting Codes ####
BOLD             =    "\e[1m" #Variable and code for bold
DIM              =    "\e[2m" #Variable and code for dim
UND_LINE         =    "\e[4m" #Variable and code for underline
HIDDEN           =    "\e[8m" #Variable and code for hidden text  . For passwords
```

### Methods for String Colors

```ruby
"String".red
"String".white
"String".black
"String".green
"String".yellow
"String".blue
"String".magenta
"String".cyan
"String".light_red
"String".light_green
"String".light_yellow
"String".light_blue
"String".light_magenta
"String".light_cyan
```

### Methods for Background Colors

```ruby
"String".back_red
"String".back_green
"String".back_yellow
"String".back_blue
"String".back_magenta
"String".back_cyan
"String".back_light_red
"String".back_light_green
"String".back_light_yellow
"String".back_light_blue
"String".back_light_magenta
"String".back_light_cyan
```
### Methods for String formats

```ruby
"String".bold
"String".dim
"String".und_line
"String".hidden
```


### Run Rakefile for more useful examples
```ruby
rake test
```



