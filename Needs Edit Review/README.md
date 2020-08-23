# GH_Priv_Test
 testing a share from my local obs vault of SLIPBOX only of larger GH folder

Time to test the links in GH.

The "readme" link with the full SGS/gh/file.md path does not work in GH

Let's try this instead:
[link to a file by typing out file name](test_md_file_link.md)

This works in the graph, woo.
I also see readme in the backlink list on the test_md file.

Ok, this was fine too. So anything in the root shared folder doesn't need prefixes. If it's the GH_Priv_Test repo and files are in that folder, it's fine to just name them.

Now what about a nested folder?
[link to file in a folder of the root just file name](down_a_folder.md)
Not going to include the /info. Links on graph ok.

[link to file in a folder of the root with folder name](new_folder/down_a_folder.md)

RESULT: link without folder name in front of file name DOES NOT work on GH. DOES need the folder name below the root. I know that but still worth testing in case I fuck up.

[[Blog_Files/Posts/new_blog_post]]
[[SGS_Slipbox/GH_Priv_Test/new_folder/down_a_folder]]

so if i use a wikilink to quickly get file info i can chop off anything before my root folder and add the file extension