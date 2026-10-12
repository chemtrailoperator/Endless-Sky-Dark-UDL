This is a development tool for the open source game Endless Sky. It runs on Notepad++ as a User Defined Language

Coding Endless Sky game code can become very confusing quickly because of the white-space-based syntax and plain language commands. This UDL solves the issue by clearly marking correct syntax (and by association, incorrect syntax) to make the flow of the code much easier to see.



## Installing UDL
- Navigate to language > User Defined Language > Define Your Language
- Click Import
- Select UDL file from wherever it downloaded
- If nothing changes, click on "Endless Sky Dark" at the bottom of the Language dropdown

### Compatibility
Keyword lists are current as of Endless Sky v0.11.3. They do not yet include keywords that do not appear in the wiki, like formations. Those are coming soon.
Requires UDL 2.1 compatible Notepad++ version, current as of v.8.9.8.1

## Features
- All endpoints, personality attributes, and mission type modifiers yellow
- Text replacements of any type are marked red (unless directly followed by other punctuation)
- Text in "" and `` is marked white
- Main nodes like ship, fleet, mission, conversation, etc. are marked dark blue
- Attributes and blocks in definitions that CAN have child attributes or nodes are marked light blue and underlined
- Attributes and children in definitions that CANNOT have child attributes are marked light blue and NOT underlined
- Player Autoconditions are purple-ish
- Operators and Boolean conditions, has, not, ++, >, etc. are light blue and italicized
- Numbers are orange
- Comments are green if # is at the beginning of the line
- Text folding operators within comments allow easy organization with \open, \fold, and \close in any comment block
- Essentially, if it does not recolor, it is not a valid operation. There are still some exceptions to this because of how N++ handles UDLs, and I just haven't gotten to them

Note: This will effect all .txt documents handled by Notepad++.
### Also Note: This UDL interprets every "" section as an attribute, and every \`\` as a plain text block for display in game. While this doesn't effect gameplay or coding at all, it will look pretty if you use \`\` for every plain text area, even if it is not traditionally done that way (like "mission \`\<your mission here\>\`" rather than mission "\<your mission here>") to ensure text that is not relevant is not highlighted as an operator or attribute.

## Gallery

Basic Mission
<img width="1019" height="594" alt="Screenshot 2026-10-12 114449" src="https://github.com/user-attachments/assets/62bec6c3-b35b-4db5-bffe-26f5bade9a96" />
Governments
<img width="988" height="289" alt="Screenshot 2026-10-12 114946" src="https://github.com/user-attachments/assets/48bd4aa0-8ed9-4658-b35b-67045e5b05de" />
Phrases
<img width="1026" height="110" alt="Screenshot 2026-10-12 114841" src="https://github.com/user-attachments/assets/3b10a5b6-3e24-4329-a538-d135c5f4d904" />
Outfits
<img width="1015" height="244" alt="Screenshot 2026-10-12 114756" src="https://github.com/user-attachments/assets/77812c94-2fc3-45fd-8724-0ac514b1662f" />

