DOCUMENTATION
-------------------

Site Structure:

Inside folders:
1. config.toml contains the data for the 'site title', 'the navbar menu', and the contents of the home page.
2. The other main pages are inside the content page.
3. The data contains all other types of data of the site.
4. All the images age inside static
5. Inside the themes we have our main theme 'timer-hugo'

Structure of 'timer-hugo' theme:
1. Inside assets we have the 'style.css' file which is required for customizing the site.
2. 'index.html' is the home page.
3. Inside 'team' we have the html page for the 'TEAM'.
4. 'forstudents' contains the html page for 'TEACHENG'.
5. All the course pages are inside courses.
6. 'publication' contains the html page for 'PUBLICATION'.
7. Partials are very important. It contains all the codes that will be used repeatedly or as a part of other page.

Creating a page: 
1. Create a folder under main layouts.
2. Create '_index.md' for that page.
3. For layout of that page create a folder with same name in layout of the currently using theme.
4. Then create a html page inside that folder.

