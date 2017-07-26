# Blockly-HTML
Blockly blocks and generators for HTML generation and a demo with live preview.

The demo can be tested here: http://htmlbausteine.zgtm.de/

<img src="example.png" width="500" alt="Screenshot" />

##Note about Blockly
All necessary files from blockly (as in not blockly-html) are in the blockly folder of the repository. The folder is pushed as a blob because it is a git clone of the actual google blockly repository for easy update purposes.

## Try the demo
The demo saves the workspace in the local browser storage. Other export/import capabilities are missing, so far.

## Library files

The files `library_html.xml` and `library_html_german.xml` are block libraries that can be used to modify the blocks using the Blockly developer tools: https://blockly-demo.appspot.com/static/demos/blockfactory/index.html

## TODO
 * Support more HTML tags and attributes
 * Enforce HTML tag-nesting rules via types
 * Allow for block export/import and HTML export in the demo page
 * Many more …

## Further ideas
 * Maybe support generating other markup languages (Markdown, LaTeX)
 * Add script-tag and allow for standard Blockly blocks in there

