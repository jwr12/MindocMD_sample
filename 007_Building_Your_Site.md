---
layout: default
title: Credits
number: 007 
---

# Building Your Website

**Building Your Website** 

<!-- -->

1.   **Configuring Your Website and Adding Content.** Now comes the
    work. How do you build your edition website? It all comes down to
    this: you'll be editing files and adding content, to make it reflect
    what you want.  Most of the files in your repository you won't have
    to touch.  But you can edit the files online if you want; or you can
    edit them in a desktop text editor. But basically, you'll be opening
    up files, fixing the text, and saving them again. That's it. 
    Broadly speaking, you'll be editing two kinds of files.  First,
    there are files that configure the website itself, helping to
    organize, identify, and format your work.  Then, there are files
    that provide the content you want your readers to see. We'll take
    these two kinds of files one by one in what follows.  First, go to
    your repository page to get started. 

<!-- -->

2.  **Configuring Your Website** 

<!-- -->

1.  **Start by Editing the 'YML' File.**  One of the most crucial files
    on your website is the .yml file (commonly known as the "yammel
    file.") It's the place where you store identifying information
    (data) about your project in a way that other tools and programmers
    can read.  On MinDoc, this file is called "**\_config.yml**." 
    Here's how you edit it: 

-   **On Your Repository Home Page, find the File "\_config.yml".**
    Double click on it. It should show the following: 

>  ![](2024-06-12-13-52-27.png)

-   **To Edit this File, Click on the Pencil.** There's a pencil icon
    ![](2024-06-12-13-53-24.png) in
    the upper right corner. Click on it. You'll get a text editing
    window. 

<!-- -->

-   **Set Your Title.** In the line with **\"title\"** put the title of
    your edition, which will be displayed on every page of the website. 

<!-- -->

-   **Set Your Name**. In the **\"description\"** line put your name. It
    will be displayed on every page of the edition under the title. 

<!-- -->

-   **Edit the baseurl.** Replace the content of the line "baseurl" with
    a / followed by the exact name of your repository. For example, as
    in the images included in this manual, you would type /mindocproject
    in the "baseurl" section. 

<!-- -->

-   **Enter Other Information.** You can also replace the contents of
    the lines **\"email,\" \" twitter_username,\"** and
    **\"github_username\"** in case you want to preserve this
    information. However, it will not be displayed on the website. Avoid
    replacing the data in the categories that are not clear to you. 

<!-- -->

-   **Commit Your Changes**. In GitHub, saving a change is called
    'committing' your changes. (Don't worry: we'll show you how to
    reverse them later.) To do it, click on this button:  
    ![](2024-06-12-13-53-59.png) 

<!-- -->

-   **Checking Your Changes**.  When you commit your changes, it takes
    GitHub a few moments to deploy (activate) them. If you want to check
    on this, you can go to the 'Actions' page (see toolbar at the top of
    the repository page). It will show you the various changes you have
    made and whether they have been deployed.  
    ![](2024-06-12-13-54-28.png) means it is built (ready). 

<!-- -->

-   **Other Files on Your Home Page**. Most of the pages in your
    repository's home page you don't have to edit; actually, you
    shouldn't edit them. They're there to make your site work. (Don't
    worry, if you do edit them by accident, you can always reverse the
    changes.) 

3.   **Adding Textual Content to Your Source** 

<!-- -->

1.  **The Content Pages**.  Besides \_config.yml, most of the files
    you'll be editing fit broadly under the category, 'content pages.'
    These pages will hold the texts, images, and other files you'll want
    to share with your readers. 

<!-- -->

2.  **Suggested Pages**. As you may have noticed, your site came with a
    built-in Table of Contents, provided in the navigation bar at its
    top left.   It shows eight pages, listed below, corresponding to
    eight proposed sections for your work. Files for each of these
    sections can be found here in your repository's home page, under the
    following names (in italics).   

-   Introduction: *001_introduction.md * 

<!-- -->

-   The Source: *002_source.md* 

<!-- -->

-   About this Source: *003_about_the_source.md* 

<!-- -->

-   About this Edition: *004_about_the_edition.md* 

<!-- -->

-   Supplements: *005_supplements.md* 

<!-- -->

-   Bibliography: *006_bibliography.md* 

<!-- -->

-   Credits and Acknowledgements: *007_credits_acknowledgements.md* 

<!-- -->

-   About MinDoc: *008_about_mindoc.md* 

3.  **What are these Content Files?** Each of these files has the
    extension .md, identifying it
    [[Markdown]{.underline}](https://daringfireball.net/projects/markdown/)
    as a file.  Markdown is a **very** simple coding language, invented
    by John Gruber in 2004.  Using Markdown, you can write simple plain
    text files that tell browsers how to present your files. It's easy
    to add things like bold face, italics, hyperlinks.  Then, when
    Github starts to build your website, it will look in these .md files
    for your content and also be able to see how you would like it
    formatted.  Markdown is extremely easy to learn: it's just a matter
    of surrounding texts with simple tags (character combinations),
    telling the computer how you want things to look.  Don't believe us?
    Try this simple
    [[tutorial]{.underline}](https://www.markdowntutorial.com/) and see.
    It's fun. (Sarah Simpkin provides a great introduction to
    [[Markdown]{.underline}](https://programminghistorian.org/en/lessons/getting-started-with-markdown)
    here as well.) 

<!-- -->

4.  **How do I Edit Them?**  When you edit these files, you'll be doing
    one of three things: 1) Entering identifying metadata (information)
    about each page; 2) Entering your content (this includes both texts
    and other media files, here we'll be focusing on text); 3) Using
    Markdown to format it the way you like.  To get started on all of
    these things:   

-   **Find the File You'd Like to Edit and Open It**. First, find the
    file you want to edit, (for example, the Introduction page, which is
    *001_introduction.md*). Double click it to open it.  

<!-- -->

-   **Click the Pencil Icon to Edit**.  When you open the file, you'll
    see a formatted version of its text.  (This isn't how it will look
    on the website, it's just a readable version here.) To see the code
    and start editing, click the Pencil Icon at the top right. 

![](2024-06-12-13-55-36.png)

<!-- -->

-    

<!-- -->

-   **At the Top, You'll Find a Field to Enter Metadata**. At the very
    top of your file, you'll find a small section marked off by three
    dashes and followed by three dashes. It is the YAML, or metadata,
    section of the page. It will look like this (we've color coded it
    for explanation): 

![](2024-06-12-13-55-54.png)
>  

-   Each field has two parts (a pair).  On the left, before the colon
    (in blue here), you'll see a term, called a "**keys**\". This
    identifies what is being defined (layout, title, page number). 
    [Don't change these.]{.underline} On the right, in orange, you have
    "**values**." These you will edit as needed (by typing changes in). 
    Here's what they mean: 

<!-- -->

-   The **\"layout: default\"** pair defines the layout of the page.
    It's pre-set to a default.  You don\'t have to change this unless
    you want to (and have the know-how).  This standard layout is
    defined in the default.html document, which is located in the
    **\_layouts folder.**) 

<!-- -->

-   \"**Title**\" is the title of this page, as it will be displayed in
    the navigation bar on the homepage (and elsewhere).  You can change
    it by changing this text: thus, if you want the title of the
    introduction page to be something other than \"Introduction,\" pick
    something else here. (\"Introduction to the New History,\" "The
    Beckley Diaries," whatever.)  

<!-- -->

-   **\"Number**": The Number key sets the page order of your edition
    (that is, the order in which this page is listed in the navigation
    bar.)  Are you ready for a stunning fact about 2024? Get this: you
    can't use the numbers 008 or 009, so you have to go from 007 to 010,
    011, etc. This won't make a difference to the readers, since this is
    just about display order and not about pagination (there's no number
    at the top of each page). But you just have to keep it in mind. What
    explains this quirk? Well, in the year 2024, YAML metadata fields
    still work with 8-bit, binary values, meaning that they only run
    numbers 0 to 7. It's kind of like Y2K, if you remember that. 
    Mostly, however, just don't worry about it. NB: In this folder, do
    **[not use quotation marks or other symbols around the numbers in
    this line.]{.underline}** 

<!-- -->

-    **The Main Text.** After the three dashes that mark the YAML field,
    you'll find a (mostly) blank page. Here you can put whatever text
    you want.  You can style it using Markdown.  For example, on the
    Introduction page, we have pre-loaded it with the word
    "Introduction" at the head. And we've styled it in Markdown by
    adding a simple symbol (a #) in front of the word Introduction to
    indicate that it should be styled as a **Level 1 Header**.  

<!-- -->

-   **Where Can I Learn Markdown Again?** It's easy!  This [[Markdown
    tutorial]{.underline}](https://www.markdowntutorial.com/) offers
    users some practice with the language. [[Getting Started with
    Markdown]{.underline}](https://programminghistorian.org/en/lessons/getting-started-with-markdown)
    by Sarah Simpkins is an excellent introduction.  

<!-- -->

-   **What is That Weird Other Code on My Page?** So there's some text
    in your .md files that you probably won't understand. It looks like
    this:   

<!-- -->

-    *{% assign media = site.mindoc_media \| sort: \"order\" \|
    where_exp: \"item\", \"item.page == \'source\'\" \| where_exp:
    \"item\", \"item.media_type == \'image\'\" \|  where_exp: \"item\",
    \"item.media_type == \'image\'\" %} {% include media.html
    pages=media %}* 

>      As we'll explain below, this is a snippet of code that tells
> MinDoc to put an image or other media file on this page (that is,
> something other than text).  While you're entering or editing your
> text, just leave it alone.  When you're ready to start thinking about
> images and such, move on to the next section, when we'll tell you how
> to work with this code.  

4.  **Adding Image, Sound, and Other Media Files to Your Site** 

<!-- -->

1.   **Adding Image, Sound, and Other Files**. In the previous section,
    we covered how to add text to your site (either material you wrote,
    or the texts of your documents).  In this section, we look at adding
    everything else: pictures, videos, sounds, etc. 

<!-- -->

2.  **All Media Files are Found in the Configuration_Files and Media_Files folders**. The first thing to know is that you should upload your media files into the subfolder called ‘Assets’ within the ‘Configuration_Files’ folder. You can upload a variety of file formats here.   

<!-- -->

3.  **Adding Images**. To add an image file, go to Assets \> Img.  Click
    the 'Add File' button at the top right-hand corner, then select
    "upload file". On the screen that appears, select "Choose your
    Files" under "Drag Files Here". Navigate to your image and upload.
    Then "Commit Changes" to save this change. Be sure that you select
    the option to commit directly to the main branch. This is the
    default setting. 

![](2024-06-12-13-56-49.png)
![](2024-06-12-13-57-02.png)

>  
>
>  

4.  **Adding Image Metadata.** Now that you've added an image file, it's
    important to add and edit a separate file that describes it and
    identifies it for users. This will also help MinDoc understand where
    each file should go on your pages.  The metadata files for your
    media are found in the folder **\_media_files**. Here's how to
    create and edit them: 

-   **Go to the Folder media_files and click on the subfolder _media_metadata**. You'll see a sample, model
    metadata file already there, called "introduction_img_1.md".   

<!-- -->

-   **Open the Sample File** (**introduction_img_1.md). Double click it.
    Look at the contents. As you'll see, it contains a YAML field (the
    text surrounded by three dashes) as well as plain text. In these
    files, we'll need to fill out two different kinds of metadata
    fields.  Some are YAML fields meant to describe this page; others
    are more general metadata describing the object represented in your
    file. We'll be editing both. To continue: 

<!-- -->

-   **Create a New Metadata File (For Your New Media File)** Alright.
    Let's create a new file to describe your new media file (the one you
    just uploaded to Assets).  Start by opening up a new (blank) file in
    a plain text editor on your computer. 

<!-- -->

-   **Save Your New File as a Markdown File, Following this Naming
    Convention. ** Save your new file as a ".md" file (thus, with an
    extension that shows it is a Markdown file).  For convenience, the
    name of this document should have the following format:
    **name_of_the_page**\_**format**\_**order**.md \--\> e.g.,
    introduction_img_2.md (that means that this is the second image from
    the introduction page). 

<!-- -->

-   **Copy the Metadata Scheme from the Sample File**. Just select the
    whole text, copy, and paste it into your new file, so you can alter
    it as you need. 

<!-- -->

-   **Create the YAML Front Matter.** So like other files, these media
    metadata files have some YAML Front Matter---the stuff between the
    three dashes---designed to include the information MinDoc needs to
    build your site.  Start by editing these fields. They are:  

<!-- -->

-   **page**: the name of the webpage on which the image will be
    displayed. (e.g., "introduction," "supplements," etc.) 

<!-- -->

-   **title**: the title you're giving this file for this edition. 

<!-- -->

-   **media_type:** what kind of media is it? (e.g., "image" / "video") 

<!-- -->

-   **\_path:** This is a path (web address) to the file you uploaded.
    To create it, start with **\"\_path/assets," followed by the name of
    the subfolder in which you placed the new media file, preceded by a
    backslash (for example, "/img/\") and then the** name your file in
    this folder, including its extension (such as .jpeg).  So for
    example, a file called main_page.jpeg would have the path name  :
    \_path: /assets/img/main_page.jpg  

<!-- -->

-   NOTE: If your image is from the Internet, you can just insert its
    entire URL. For example: \_path:
    [[https://a.storyblok.com/f/116736/1000x666/97564b8080/main.jpeg ]{.underline}](https://a.storyblok.com/f/116736/1000x666/97564b8080/main.jpeg%E2%80%AF) 

<!-- -->

-   Video from YouTube: If it is a video from YouTube, add \"embed/\"
    between youtube.com/ and the following text. For example, 
    **https://youtu.be/**dbXvsVKIEwo becomes
    [[**https://www.youtube.com/embed/**dbXvsVKIEwo]{.underline}](https://www.youtube.com/embed/dbXvsVKIEwo) 

<!-- -->

-   **order:** a number that specifies the order of the image on the
    page. **Unlike in the "Assets" files, this number should be
    in single quotation marks ('03').** Typing '01' means that the image
    will be displayed first, '02' means that image will be displayed
    second, and so on. 

<!-- -->

-   **layout:** This field tells MinDoc what description to provide with
    your media file (a value called **image_description).** This is auto
    generated, so you do not need to edit or alter this field. 

<!-- -->

-   **Edit the Metadata for the Media**.  In addition to the YAML
    fields, you will also find a list of basic fields describing the
    media file itself and the object it represents.  These include basic
    points of information about your media source file (the title of the
    file, the title of the thing it represents, who created it, when,
    and so on). These fields (explained below) correspond to a metadata
    scheme created by Kaylen Dwyer and Garrett McComas for the
    [[SourceLab]{.underline}](https://sourcelab.history.illinois.edu/)
    initiative. For a description of [[what should go into these
    fields]{.underline}](https://sourcelab.web.illinois.edu/wp/sourcelabhandbook/chapter/3-3-metadata-guidelines-creating-metadata/)
    and where these terms come from, see the [[SourceLab
    Handbook.]{.underline}](https://sourcelab.web.illinois.edu/wp/sourcelabhandbook/chapter/3-2-metadata-guidelines-introduction/) 

    ![](2024-06-12-13-57-41.png)

>  

5.  **Placing Your Media on a Page**. Now that you have uploaded your
    media to Assets and created a metadata file to describe it in the
    \_mindoc_media file, you are ready to put it on one of your pages.
    Here's how. 

-   **Determine the Page Order of Your Media**. What order do you want
    this object on the page: is it the first, the second, the third
    media file? 

<!-- -->

-   **Edit the Media Metadata File to Reflect this Choice**. Open the
    metadata file and insert the correct order number in its order
    field. Thus, for example, if you want the image described by
    "introduction_img_02" to appear as the second image on the
    introduction page (as the name implies), then make sure that the
    order YAML field on that page reads 02.  Here\'s how that looks (see
    line 20): 

 ![](2024-06-12-13-58-00.png)

-   **Copy this Code**. To place your media file on the page, you'll
    need to insert (and edit) this little bit of code on every page. 
    Copy this exactly (just select it and copy it):  

 

> {% assign **intro_images** = site.mindoc_media \| **sort:** \"order\"
> \| **where_exp:** \"**item**\", **\"item.page** == \'introduction\'\"
> \| **where_exp:** \"**item**\", \"**item**.**media_type** ==
> \'image\'\" \|  **where_exp:** \"**item**\", \"**item**.**order** ==
> \'02\'\" %} 
>
> {% include media.html pages=**intro_images** %} 

 

-   **Paste this Code Where you Want Your File To Appear.** Go to your
    content page (in your main repository, e.g. '001_Introduction.md'.
    Wherever you want the media file to appear, paste the code there.
    (You can stick it in between pieces of text, or at the bottom, or
    the top, or\...wherever). 

<!-- -->

-   **Customize the Code to Match Your Preferences.**  You do not need
    to edit the majority of this code.  But there are four fields you
    may want to adjust: 

<!-- -->

-   assign **intro_images** = site.mindoc_media. Change 'intro_images'
    here to whatever name you would like for the media on this page. 
    Change it again in the 'pages=intro_images' setting below. This can
    be called whatever you prefer, but it should be comprehensible to
    you. 

<!-- -->

-   **\"item.page** This field should be set to match the name of the
    page (the key value entered in the media metadata file, 7.3.4
    above).  Thus, for example, if you want this to draw from a page
    called 'introduction,' have this read:  **\"item.page** ==
    \'introduction\'\". Users should change this field to reflect which
    page they would like to display their image on. 

<!-- -->

-   \"**item**.**media_type** == \'image\'\" . Change this field to
    reflect your media type (image, sound, video, etc.), matching the
    media metadata file (7.3.4 above). 

<!-- -->

-   \"**item**.**order** == \'02\'\" Change this to reflect the actual
    order of the item on the page, which also should be reflected in the
    media metadata page (see 7.3.4 above). Thus, if you write '02' here,
    you're saying this is the second image on the page. This number
    tells MinDoc where to order the image. 

<!-- -->

-   Our MinDoc template has a few preexisting image and video files to
    serve as examples for you. If you do not wish to have these files
    displayed on your website, you should delete them before deploying
    your final version. Click on the files you want to delete (both in
    the "assets" folder and the "\_mindoc_media" folder). Then click on
    the three dots in the top right corner and click "delete file".  

<!-- -->

5.  **How to Add A PDF.** Upload your PDF file to /media_files/pdfs like you did for images. Create a link with the following:

[Download PDF file]({{ site.baseurl }}/media_files/pdfs/FILE_NAME_OF_PDF.pdf)

Replace FILE_NAME_OF_PDF with the actual name of the file.

6.  **How to Add Footnotes.** So most scholarly sites will have
    footnotes.  Fortunately, it's easy to do that in Markdown, and
    [[GitHub]{.underline}](https://github.blog/changelog/2021-09-30-footnotes-now-supported-in-markdown-fields/)
    recognizes this code. Here's how. 

<!-- -->

1.  **Pick the Spot for Your Note.** As you format your text file in
    Markdown, pick the spot where you want to put a footnote. 

<!-- -->

2.  **Insert \[\^*X*\] Where You Want a Note**, with X being the number
    of the note. Thus \[\^1\] is footnote 1. 

<!-- -->

3.  **Put Your Reference Text at the Bottom of the Page with Another
    \[\^X\]. ** Go to the bottom of your page (or wherever you want your
    note). Put in a double space. Insert another \[\^X\], a colon **:**,
    and then the text of your note.  For example, \[\^1\]: Randolph, *On
    the Biography*, 53. 

<!-- -->

4.  **Voila! You've Got a Footnote.**  See this [[blog
    post]{.underline}](https://github.blog/changelog/2021-09-30-footnotes-now-supported-in-markdown-fields/)
    for more information. 

<!-- -->

5.  **Example:** 

![](2024-06-12-13-58-22.png)
>  
