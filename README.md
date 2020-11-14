# Testing solutions

## About

Simple bash script to test solutions for competitive programming tasks. Especially useful for contests like Polish Olympiad in Informatics.

## Usage
Replace file ```sum.cpp``` with your own solution. Put input files into ```in``` directory and expected output files into ```out``` directory. Grant file ```ocen``` permission to execute (```sudo chmod +x```) and then execute this file. It will compile solution's source code, generate outputs for given input and place them in ```program``` directory. You will see an information which tests failed and a final summary.
