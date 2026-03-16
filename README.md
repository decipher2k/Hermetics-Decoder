# Hermetics Decoder
An AI prompt that deciphers hermetic texts by translating symbols and their context taking into respect the context of the symbol and vice versa.<br>
Example for the results in the repository was "Die geheimen Lehren aller Zeitalter" by Manly P. Hall<br>
<br>
DANGER: Don't use the content of this repository if you don't know what you are doing.<br>
        The results are mostly unsorted! They have been created with several different versions of the prompt.<br><br>
        
To decipher the complete text in a whole and not chapterwise, a 2MB context window of the AI (about 500.000 tokens) is required.<br>
Agent mode is advised. Large books will be really expensive when using an API, about 1500$-2500$. When using Visual Studio Code and Github Copilot Plus with an last-gen model (Opus 4.6 or GPT 5.4), this will be reduces to a few cents, but it won't be able to handle large books in a whole. Instead it will decipher the text chapterwise.<br>

<br>        
Toned-down version.<br>
If you are bored and don't know hat to do, you could for instance try to change the prompt so it uses 7 iterations in an inner loop and 3 iterations in an outer loop, applying the new insights about archetypes from the inner loop to the original text in each outer iteration.<br>
Instead you could also apply the new insights from archetypes after the last loop to the original text instead of applying it after each outer iteration, examining how it modifies it.<br>
Modify the prompt and compare results. Instruct the AI to track iterations and modifications of archetypes per iteration for deeper insights and so on.<br>
<br>

Mixed language (english/german) - I'm language-agnostic and can't always remember which language I've written in.<br>
Google Translate helps.<br>
<br>
This is EXPERIMENTAL!<br>
<br>
<br>
License: the Attribution-NonCommercial-ShareAlike 4.0 International<br>
(c) 2026 Dennis Michael Heine
