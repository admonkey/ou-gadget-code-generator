@author: joshua.pia@ttu.edu
@version: 1.0
@todos:
-- add tags support
-- add ability to restrict snippets to a specific group


*** HOW TO ADD SNIPPETS ***
1. Register the snippet in snippets.js by using the following format:

{
    id: '', // unique ID for the snippet, lowercase, no spaces
    text: '', // The label for the snippet
    description: '', // Try to limit this to 1 sentence.
    help_url: '', // Full URL to the wiki article for the snippet
    snippet_url: '', // relative URL to the template, snippets/file.txt
    tags: '' // space delimited list of tags, will be used for XSL
}


2. Upload the snippet file in the snippets subfolder.
3. Publish the files. (users may need to reload the gadget frame to see the changes)
