#To-DO

- Calendar full Month view desktop
- Event view mobile
- style map in about:location, use map api instead of iframe embed

- Make a WordPress Static Page
stolpioni3,

This is a fairly simple fix:

Revert all the changes you made to WordPress's files back to how they were (in other words, leave "index.php" alone.)
Create a page called "home"
Go into Settings->Reading and set the Front Page to "home"
In your theme folder, create a file called "page-home.php" and dump all of your code in there
WordPress will load that file on your websites home page and output whatever code you put there.

That said, I'm not a huge proponent of Dreamweaver and definitely would prefer to suggest that you just build your site as a theme.

# Saved_Code
