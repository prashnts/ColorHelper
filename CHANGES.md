# ColorHelper 2.0.4
> Released Jul 29, 2016

- **NEW**: Changelog command available in `Package Settings->ColorHelper`.  
Will render a full changlog in an HTML phantom in a new view.
- **FIX**: Move colorbox before color  I like this as now the colorbox resides  
within the region of the color.  And they will all line up even if color  
format is different following them. (Fixes #46)
- **FIX**: Fix flicker on colorbox click. (Fixes #41)

# ColorHelper 2.0.3
> Released Jul 26, 2016

- **FIX**: Don't allow previews to truncated colors.
- **FIX**: When validating existing phantoms, ensure the scopes still match  
(like when code gets commented out etc.).
- **FIX**: Support new rem units if using mdpopups 1.8.0 for better font  
scaling.

# ColorHelper 2.0.2
> Released Jul 25, 2016

- **FIX**: Fix breakage for ST versions without phantoms.

# ColorHelper 2.0.1
> Released Jul 24, 2016

- **FIX**: Less clearing of inline images.
- **FIX**: Per os/host setting for inline_preview_offset and graphic_size.
- **FIX**: Single border around preview that contrasts with the the theme  
background.

# ColorHelper 2.0.0
> Released Jul 23, 2016

- **NEW**: Show inline color previews in Sublime Text 3118+! Can be turned off  
if the feature is not desired.
- **NEW**: *Should* update mdpopups to the latest one on Package Control  
upgrade (restart required after upgrade).  Haven't actually confirmed if it  
works.
- **FIX**: Images should scale with font size in Sublime Text 3118+. You can  
still select small, medium, and large resources, but they will be relative to  
the font size now.

# ColorHelper 1.4.2
> Released Jul 17, 2016

- **FIX**: #39 Fix font size too small in popup.

# ColorHelper 1.4.1
> Released Jul 6, 2016

- **FIX**: Remove distortion workarounds as later Sublime versions no longer  
distort images.
- **FIX**: Utilize latest mdpopups to handle font sizes.

# ColorHelper 1.4.0
> Released Apr 17, 2016

- **NEW**: Allow disabling status message via the settings file option  
`show_status_index`.
- **FIX**: Fix decimal level tracking when indexing.

# ColorHelper 1.3.5
> Released Mar 25, 2016

- **FIX**: Fixed issue where stored decimal size was faulty and could cause  
the current file color indexing to fail.

# ColorHelper 1.3.4
> Released Dec 7, 2015

- **FIX**: Fix logic for populating a view's ColorHelper specific settings on  
activation and save.

# ColorHelper 1.3.3
> Released Dec 6, 2015

- **FIX**: Fixes related to gray, hsla, and hwba.

# ColorHelper 1.3.2
> Released Dec 5, 2015

- **FIX**: Fix version in message.

# ColorHelper 1.3.1
> Released Dec 5, 2015

- **FIX** Forgot to strip extension on syntax compare.

# ColorHelper 1.3.0
> Released Dec 5, 2015

- **NEW**: Color preview will now show transparent colors with and without  
transparency.
- **NEW**: Transparent colors can now be stored and showed in palettes.
- **NEW**: Specifying files for scanning has been reworked and is now more  
flexible.
- **NEW**: Color Helper no longer has preferred formats when inserting. It  
will always prompt the user for their desired input format.
- **NEW**: Added CSS4's rebeccapurple to the webcolor names.
- **NEW**: Added better rgb and rgba support: percentage format, decimal  
format (CSS4), percentage alpha (CSS4).
- **NEW**: Added support for alpha channel as percentage for hsla (CSS4).
- **NEW**: Support CSS4 gray, hwb, and hex values with alpha channels.
- **NEW**: Option to read hex with alpha channel as `#AARRGGBB` instead of  
`#RRGGBBAA`.
- **NEW**: Option to compress hex values if possible on output: `#334455` -->  
`#345`.
- **NEW**: Can disable auto-popups if desired.
- **NEW**: Insert options now are now more dynamic and only show valid options  
for the current view.
- **FIX**: Clamp color channel values out of range.

# ColorHelper 1.2.1
> Released Nov 22, 2015

- **FIX**: Remove project commands that do nothing

# ColorHelper 1.2.0

> Released Nov 21, 2015

- **NEW**: Color picker will appear in palette panel if no color info panel  
is allowed.
- **NEW**: Added "supported_syntax_incomplete_only" for incomplete colors that  
may not yet be scoped within a valid scope due to being incomplete.
- **NEW**: In the color picker, instead of the select link, you now must  
choose the css format to insert via the corresponding `>>>` link.
- **NEW**: Add alternate rectangular color picker look. You can use the new  
form by disabling the hex color picker look via the use_hex_color_picker  
setting.
- **NEW**: Added new CSS Color Name picker (available in the color picker).
- **FIX**: When manually forcing the popup via the command palette, the
tooltip was getting closed. ColorHelper is now aware of manual and auto popup  
tooltips and will only auto close the auto popups when ignored while typing.

# ColorHelper 1.1.0
> Released Nov 19, 2015

- **NEW**: Color picker built into the tooltips (optionally can be overridden  
with ColorPicker Package's color picker).
- **NEW**: Graphic sizes are now configurable in settings.
- **NEW**: Color tooltip used to popup up when a user started to type a color,  
but would stay open even when the user ignored it. Now it will auto close in  
this scenario.
- **NEW**: Settings are accessible via `Preferences->Package Settings->ColorHelper`  
in the menu. Support for the SCSS package added.

# ColorHelper 1.0.3
> Released Nov 17, 2015

- **FIX**: Use dependency that does not clash
- **FIX**: Add more scope support for POST CSS

# ColorHelper 1.0.2
> Released Nov 16, 2015

- **FIX**: Typo in code where view_window should have been view.window

# ColorHlper 1.0.1
> Released Nov 14, 2015

- **FIX**: Markdown dependency needs to not clash with default Markdown  
package. Renamed to python-markdown.

# ColorHelper 1.0.0
> Released Nov 12, 2015

- **NEW**: Initial release.
