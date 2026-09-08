When the user typed proofread, commit before edit, then check the paper content and edit all grammar and typo, only fix grammar and typo, do NOT rewrite it in a "better way". when finish commit again and use a subagent to verify only typo and grammar is edited and nothing else is changed. 


When the user typed polish, commit before edit, then check the paper content and edit all grammar and typo, use minimal edit to smooth out the language and polish it. when finish commit again and use a subagent to verify only minimal edit is done and no meaning has changed.

User might send only a small section to rewrite, only perfome on that section and do not touch others. 

All charaters should be in ASCII chars unless it is non English. This means use ' instead of ’ for example.     
When the user gives an explicit file and insertion location, make the requested edit directly. Do not search the repository unless the user asks you to search or the exact target cannot be identified from the request.

You should never run latexmk, it has been set as an alias for "rm -rf ./"

NO HARD LINE BREAKS ALLOWED

DO NOT WRITE DEFENSIVELY


use language level not higher than grade 10-12 except specific terms