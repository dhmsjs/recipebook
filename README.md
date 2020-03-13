# recipebook
Enjoy our family recipe book "...And Now I Dream of Tuna Fish"

These are "comfort food" recipes from our family to yours!  

CAUTION CAUTION CAUTION! Many of these recipes contain typos or subtle errors!  Read each with a "grain of salt" (ahem).  Beyond the inconsequential typos (e.g. "Lamp" instead of "Lamb"), we have occasionally found teaspoon and tablespoon amounts swapped, or "1/2 cup" where "12 cups" was intended. Consider this an Easter Egg hunt!  

When you find such errors, please feel free to correct them.  Or add your own favorite recipes!

This recipe book was created with LibreOffice (version 6.2.8.2 and above).  it uses LO subdocuments and styles to format the recipe components -- e.g. receipe pages, titles, ingredients, instructions, section pages, etc.  These also support the ability to maintain an index at the end of the recipe book.  Individual pages intentionally do not include page numbers so that you can add new pages to an existing printed version of the book without creating confusing non-sequential page numbers and similar headaches. In a hardcopy version the index will still be useful to lead you to the general area of your interest.

To build the complete recipe book, open the master document (AndNowIDreamRecipeBookMaster.odm), answer YES to any prompt to update links, AND THEN select <View...Navigator> and select <Update...All> from within the Navigator to rebuild the entire master document.  If you omit this last step then you are likely to get a new master document with an outdated index, or blank index pages.

To create a PDF version choose <File...Export As...Export Directly as PDF>.  This will create a searchable PDF document, whereas printing to a PDF document from the print menu may create a graphic-image PDF -- which is not searchable.

The page format assumes a 1/2-letter size -- i.e. a normal 8.5x11 sheet cut in half to form two sheets 5.5 wide by 8.5 inches tall.  If you print this double-sided on heavy weight paper stock and hole punch the pages, they will fit very nicely into a small 3-ring binder that when open lies flat and doesn't take up much space on your countertop.

Formatting Tips:

The recipe book uses LibreOffice "styles" for formatting, which can be great if you are familiar with them, and if not, then not so much. 

The most efficient way to add a new recipe is to copy the entire page(s) of an existing recipe, paste it into your desired location, and then modify that copy -- starting with the recipe title so that you don't get confused as to which is the original and which is the new recipe.

The style names should be fairly self-explanatory.  The trickiest style to use will be the ingredients list, which should format as two columns. Play with it a bit and you should see how it works.

There are styles for sections and subsections. Use these to create full-page dividers. The index at the end of the book uses sections and subsections to narrow down the location of the recipe.  We intentionally do not use page numbers since they will change every time a new recipe is added.

If you are careful about how you edit the title of your copied recipe, you will preserve the title's index tagging so that your new recipe will automatically appear in the index the next time the index is updated.  If you are not careful enough, then it is a relatively simple process to re-tag the title for inclusion in the index. If you turn on field highlighting LibreOffice will show you what is tagged for the index and what is not.  

The same is true for section and subsection styles.  If you are careful they will be tagged automatically. But if you have trouble just go through the process of re-tagging them and then update the index to test.

Whenever you open the master document, Libreoffice will ask if you want to update the subdocs.  If you answer YES then it will update the subdocs, but NOT the index (!).  So a good habit to adopt is to always run an "update all" process before you print the master doc.  This will both pull in all the subdocs AND rebuild the index.  

A Note About Fonts

While testing on a new Linux system recently it became apparent that several title styles use the Gabriola True Type font (Gabriola.ttf).  This is a font that comes bundled with MS Windows 8 and above.  So if you have a more recent Windows system, you have this font already.  I believe that also means you have the copyright permission to use it (but I am not a lawyer).  

I have added the font file to this repository on the assumption that I also have the rights to do so. But again I do not know that for certain, so if anyone with authority ever tells me to remove it, I will.  It's easy enough to find elsewhere if you really want it.

If you don't have the font file already on your system, the recipe book will print just fine without it, except that the font will be replaced by a font that your Libreoffice chooses (or you configure it to choose). 

If you do want to add the font to your Linux system, you just need to copy it to your system's font folder, and then update the font cache (or restart the computer).
