This is a development tool for the open source game Endless Sky. It runs on Notepad++ as a User Defined Language

Coding Endless Sky game code can become very confusing quickly because of the white-space-based syntax and plain language commands. This UDL solves the issue by clearly marking correct syntax (and by association, incorrect syntax) to make the flow of the code much easier to see.

## Installing UDL
- Navigate to language > User Defined Language > Define Your Language
- Click Import
- Select UDL file from wherever it downloaded
- If nothing changes, click on "Endless Sky Dark" at the bottom of the Language dropdown

## Features
- Marks all endpoints, personality attributes, and mission type modifiers yellow
- Text replacements of any type are marked red (unless directly followed by other punctuation)
- Text in "" and `` is marked white
- "Main" code blocks like ship, fleet, mission, conversation, etc. are marked dark blue
- Subheadings and attributes are marked light blue
- Player Autoconditions are marked light blue
- Operators and Boolean conditions, has, not, ++, >, etc. are light blue and underlined
- Numbers are orange
- Comments are green if # is at the beginning of the line
- Text folding operators within comments allow easy organization with \open, \fold, and \close in any comment block
- Essentially, if it does not recolor, it is not a valid operation. There are still some exceptions to this because of how N++ handles UDLs, and I just haven't gotten to them

Note: This will effect all .txt documents handled by Notepad++.
