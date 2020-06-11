# 3.Password-Generator

When selecting GENERATE PASSWORD a series of prompts are generated to allow the user to customize thier password based on length (btwn 8 and 128 characters), the case of alpha characters, numbers and special characters.  Based on the answers to the prompts a password is generated using any or all of the previously mentioned criteria.  If no character parameters are selected, user is prompted that at least one parameter needs to be selected.

Notes:
I am having trouble executing the Loop if no character parameters are selected (Cancels for all of the prompts except length).  The 'error' prompt displays correctly, but a password is still generated to the determined length with all parameters as true.