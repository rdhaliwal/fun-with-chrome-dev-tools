# Stuff you can do in Chrome Dev Tools!

## DOM Explorer:
------------------------------
- Search by CSS Selector
    -> Ctrl+F ".sg-Main .sg-Main-content"
- Search in the CSS properties/attributes
    -> Search in the Filter box by css property e.g. 'border'
- Animation timeline
    -> Chrome canary experiment
- Shows what elements are updated 
    -> When a class/attribute/property is changed, the DOM element will flash purple
- Simulate hover and focus and stuff
    -> Right click an element
    -> Set element state to :hover or :focus or :active.
- Color picker/hex colours
    -> When there is a colour in the CSS properties, you can click it to change it.
    -> You can shift click it to convert from rgba to hex to hsla


## Misc. Settings:
------------------------------
- See how many breakpoints
    -> Select the Device icon at the top left of the entire dev tools window
    -> 
- CSS media print emulator
    -> Select the Device icon at the top left of the entire dev tools window
    -> Open the console
    -> Press 'Emulation' which is at the top of the console
    -> Select Media
    -> Enable CSS Media Print emulation
- Hard reload and refresh
    -> When devtools is open, right click the refresh button and you can clear cache and hard refresh
    -> Or in network settings, you can disable cache.


## Editor:
------------------------------
- Pretty print/format js and css
    -> At the bottom left of the source view, there is a '{}' which allows you to pretty print/format 
    minified js/css into something more readable.


## Console:
------------------------------
- Typing $0 will return the last dom element you selected
- Typing $_ will return the last value you evaluated 
- You can put css in the console, see:
    -> http://s.codepen.io/belohlavek/debug/QjLbqq?
- You can use console.table to pretty print
    -> console.table([{a:1, b:2, c:3}, {a:"foo", b:false, c:undefined}]);
- Use a dark colour chrome dev tool theme
    - https://chrome.google.com/webstore/detail/devtools-theme-zero-dark/bomhdjeadceaggdgfoefmpeafkjhegbo


## Timeline/Profiler:	
------------------------------
- Press record, interact with your page, then stop recording.
    -> Chrome will show all javascripts methods that ran in a stack trace-ish format.
    -> This allows you to see easily when you click on something, what javascript ran
    -> If you click on any of the items in the timeline, chrome will match that to a method in a file.



DOM Explorer:
  - Search by CSS Selector
  - animation timeline
  - shows what elements are updated
  - css: simulate hover and focus and stuff

Chrome Dev tools settings:
  - See how many breakpoints
  - CSS media print emulator
  - color picker/hex colours
  - hard reload and refresh
  - Disable cache

Editor:
  - Bind a folder/workspace
  - format the js and css
  - Text search across all scripts ctrl+cmd+f
  - open script file ctrl+o
  - ctrl+g jump to line
  - multiple caret editing, ctrl+d

Console:
  - $0 last dom element
  - Live edit a json object in the console
  - put css in the console.
    - show the cat gif console
  - console.table([{a:1, b:2, c:3}, {a:"foo", b:false, c:undefined}]);
  - use a dark colour chrome dev tool theme
  - https://chrome.google.com/webstore/detail/devtools-theme-zero-dark/bomhdjeadceaggdgfoefmpeafkjhegbo
  - press esc. for console

Timeline/Profiler:  
  - Record timeline
  - Record JS events
  - Record Paint
  - Resolve a practical problem

Todos:
  - Figure out if chrome actually does support CSS variables
  - Rewatch that addy osmani state of devtools video and see if you can get sass maps working.
  - actually try and use console.table() for a proper example and stuff
  - you can set breakpoints on dom node removal!!!

Chrome Canary Features:
  - CSS Variables - enable web platform
  - Animation debugger - enable dev tool inspector, in dev tools settings as well.
