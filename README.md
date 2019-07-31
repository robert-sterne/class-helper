# Class Helper

## Instructions:

1. Create a `~/bin` folder if you don't already have one
2. Copy this script to that folder

   - Only necessary if you want to run the script from anywhere in bash

3. Change rights to the file with `chmod u+x ~/bin/class-helper`

   - This gives the user (u) the right to execute (x) the script

4. Open the file in your preferred text editor and change the master Lesson Plans path (`01-Lesson-Plans/` or equivalent). Change the class repo path when you're ready.
5. Execute the file with `class-helper` and use all that extra time to help students :)

## Known Bugs

<hr>

[![Github Issues](https://img.shields.io/github/issues/TAToolbox/class-helper)](https://github.com/TAToolbox/class-helper/issues)

### Duplicate topics:

`topic` strings with multiple matching directories will mirror commands to all matches without making that clear

**Workaround**:

Use week number labels instead of topics

`03` instead of `python`
