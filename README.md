# DuffelBlog
Data &amp; statistics on Duffel Blog, the American military's most trusted news source

This project consists of three files:
    DuffelBlogStories.csv
        This CSV file lists every known Duffel Blog story available on their website. Each line
        identifies the story's publication datetime, the reporter's name, the title (aka headline),
        the subhead, and the website's URL. One field is called "processed" and it contains "TRUE";
        I use the field in my programs to operate on the data. Another field called "reserved" is
        reserved for future use. I'm an old COBOL programmer and I used tricks like this in a
        targeting database for nuclear warheads pointed at the USSR and I made this file and I don't
        care what you think about reserved fields so there, nyah.
    ReporterBios.zip
        This ZIP file contains reporters' bios found via an https://web.archive.org snapshot or via
        Duffel Blog's website. Not all reporters seem to have a bio.
    Duffel Blog Data and Stats.PDF
        The PDF I generate using the files above.
        
