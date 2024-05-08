# Build a JSON Parser

[Source](https://codingchallenges.fyi/challenges/challenge-json-parser)

The purpose of this task is to be able to create a JSON parser in javascript. This entails taking a string of characters and using Python(or any other programming language of your choosing) to organise that text into a JSON format.

## First Thoughts

- I need to read a text based file (.txt, pdf,.DOCX, etc)
- Keep a record of open and closed brackects to keep check of what data is inside the other.
- keep track of property names and their values.
- Indent the text into the appropriate format for readability
- What do I want the program to do if the text is invalid?

## Tools for the job

- Regex: This is a must when locating opening and closing brackets so that I know whats an array and what's an object.
- Python: I need to code it in some language.

## Research

- [Lexical Analysis](https://en.wikipedia.org/wiki/Lexical_analysis)
- [Lexical Grammar](https://en.wikipedia.org/wiki/Lexical_grammar)
- [Parsing](https://en.wikipedia.org/wiki/Parsing)
- [What is JSON](https://www.rfc-editor.org/info/std90)
- [More on JSON](https://www.json.org/json-en.html)
