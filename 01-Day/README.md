# Day 01

## Computers want to be helpful

- Computers are built for one purpose - to do things for us.
- But we need to speak their language to describe what we want done.
- Users have it easy - someone already put many different programs (instructions) into the computer and users just pick the ones they want to use.

## Programmers Anticipate Needs

- iPhone Applications are a market.
- iPhone Applications have over 3 Billion downloads.
- Programmers have left their jobs to be full-time iPhone developers.
- Programmers know the `ways of the program`.

## Users vs. Programmers

- Users see computers as a set of tools - word processor, spreadsheet, map, to-do list, etc.
- Programmers learn the computer "ways" and the computer language.
- Programmers have some tools that allow them to build new tools.
- Programmers sometimes write tools for lots of users and sometimes programmers write little "helpers" for themselves to automate a task.

## Why be a programmer?

- To get some task done - we are the user and programmer.
    - Clean up survey data
- To produce something for others to use - a programming job
    - Fix a performance in the Sakai Software.
    - Add guestbook to a web site

## What is Code? Software? A Program?

- A sequence of stored instructions
    - It's a little piece of our intelligence in the computer
    - We figure something out and then we encode it and then give it to someone else to save them the time and energy of figuring it out.
- A piece of creative art - particularly when we do a good job on user experience.

## Programs for Python...

```
# Get the name of the file and open it
name = raw_input('Enter file:')
handle = open(name)

# Count word frequency
counts = dict()
for line in handle;
    words = line.split()
    for word in words:
        counts[word] = counts.get(word, 0) + 1

# Find the most common word
bigcount = None
bigword = None
for word, count in counts.items():
    if bigcount is None or count > bigcount:
        bigcount = word
        bigcount = count

# All done
print(bigword, bigcount)
```