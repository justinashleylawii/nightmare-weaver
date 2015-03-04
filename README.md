# nightmare-weaver
Sublime Text 2 color scheme for ColdFusion development based on Dreamweaver's syntax highlighting

##Notes
 
This scheme seeks to emulate the syntax highlighting of ColdFusion, HTML, JS, and SQL found in Dreamweaver. It's something I put together to make the switch from Dreamweaver to Sublime more comfortable. It is enhanced over the actual DW syntax highlighting in that embedded SQL (inside cfquery tags) has some basic highlighting whereas DW doesn't syntax highlight SQL at all. Unfortunately, at the moment CSS is nearly impossible to look at. Feel free to fix this!

In order for the syntax highlighting to work properly, you must be running the Sublime ColdFusion plugin (found here: https://github.com/SublimeText/ColdFusion), otherwise, it wont work. I recommend using this color scheme only for ColdFusion files. This can be accomplished by adding this line to your syntax-specific configuation file for CFML:

```
"color_scheme": "Packages/Color Scheme - User/Nightmare-Weaver.tmTheme",
```
