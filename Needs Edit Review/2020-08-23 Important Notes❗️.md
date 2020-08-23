## Format Requirements for Web Sharing
- File names MUST be a single string with no spaces in order to create links.
- Wikilinks `[[notes with double brackets]]` are not a standard markdown tool.
	- Use classic link format with `[anchor text](link location)`
- REMEMBER NOT TO MOVE/RENAME folders or files unless I plan to update all links. Obsidian will auto update links for wikilinks I believe, but will they update normal links? NOPE

## Plan for SGS_Slipbox Files
- Need to review incoming files for above requirements regarding filenames and links.
- Make sure to maintain this structure going forward.
- Plan to leave actual zettels/slips/what-have-you in a flat structure with all notes in the root folder that gets shared. 
	- Ideally this will cut down on broken link issues.
- Plan to have any resources, like webpage files, themes, index.md, etc. in a folder within SGS_Slipbox so I can easily find them in the sea of notes.
- I'm not sure if other files that could be for the web, such as a landing page or blog, will be here. I think they would be their own folders within my vault. That way I can share ONLY specific folders at a GitHub repo but allow all my internal linking as needed for my own brain.
	- Question, does that make sense? Won't that mean linking externally between repos? Is that a thing?
- I moved my vault from the "sgs-slipbox" folder to the "gh-repo" folder. Does that already ruin my plan regarding links? Going to have to pre-empt all links with "sgs-slipbox/" ? 
	- Pro, all my second brain files in one vault ❗️important
	- Con, might be a pain in the ass to do links
	- Question, maybe obsidian will do this for me?

absolute path in vault setting:
[[test_md_file_link]]
um, shouldnt this look different?


[link to blog post](Blog_Files/Posts/new_blog_post)
--this does not work in GH even though the file does work in GH and shows up in graph. Also can't click link to go to it??

[readme link](SGS_Slipbox/GH_Priv_Test/README.md)
Okay, kind of stuck now because I can't click links within notes, which could be annoying while editing. BUT, I can use the graph. or the backlinks tab if i make sure to connect? Seems like i'm making more work. or i can use quick opener. dunno. maybe it'll be okay? its more future proof?

nope, does keep link, great!

What do other settings do?
relative path to file:
[[../test_md_file_link]]
has a .. with the name. not sure that is good?
relative to what anyway?
try with next folder:
[[new_folder/down_a_folder]]
oh cool, its relative to my slipbox folder. that actually is helpful and i can edit for file name and normal link syntax



