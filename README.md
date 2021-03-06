# CSCI2270 Super Smash Bros. 4 Binary Search Tree

## Project Summary
This program takes a collection of data about Super Smash Bros. for Wii U (or
Super Smash Bros. 4) and puts the data inside of a Binary Search Tree. This
data includes characters and their ranks, and the universe that they come from.
The user is able to search for a character by a certain rank that they are
looking for, or search for the rank of a character by the character's name.
The Binary Search Tree is formed from data that is dumped into a text file that
is organized by commas. The data was taken by parsing the HTML source of a
website with the websiteParser.py script that is included in this repository.

## How to Run
Open terminal and clone my git repository into preferred directory
```
git clone http://github.com/bumshakabum/Kim_CSCI2270_FinalProject.git
```
Navigate into the cloned repo
```
cd Kim_CSCI2270_FinalProject
```
To compile this program run(in the command line or terminal): <br>
```bash
make
```
To run:
```
./ssb4.o chars.txt
```
## Dependencies
All you need is a c++ compiler that will compile with c++11

## System Requirements
Mac or Linux

## Group Members
Bum Soo Kim <br>
Bum Soo Kim<br>
Bum Soo Kim<br>
Bum Soo Kim

## Contributors
Bum Soo Kim<br>
Bum Soo Kim<br>
Bum Soo Kim<br>
Bum Soo Kim

## Open issues/bugs
When running the program, if the user hits up on the arrow key or CTRL+[anything]
and then hits Enter, the program will enter an infinite loop.

User input is case sensitive, so names must be capitalized.
