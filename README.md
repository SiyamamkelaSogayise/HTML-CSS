# HTML-CSS
HTML and CSS
<H3>Introduction to Html</H3> 

Html is a a hyper text markup language used to format webpages
<H3>Html Syntax</H3>

Html is a language that uses tags enclosed in greater and less than sysmbols, used to create web pages.
It has opening and closing tags.
For a paragraph we use p.
Some tags require opening and closing tags while others do not.
Html is used to bridge the gap btween humans and computers by giving meaning to the content, making it understandable for both the computer and the reader(humans).
Html elements can be nested within each other .
The nestcreates a tree like structure called DOM,abbreviated for Document Object Model.
This DOM becomes most important when working with CSS and Javascript.

Example of nested elements
<article>
    <h1> This is a headline</h1>
    <p>This is the 1st paragraph</p>
    <p>This is the 2nd paragraph</p>
    <p>Paragraph with <em>emphasized text</em> for effect</p>
</article>    

Like p, article also has a closing tag.
Choice of Hmlt element affects the user's experience of the website as well as people with various disabilities.

<H3>HTML PARAGRAPHS</H3>

Paragraphs use p.
Without the tag, the content would just look like a chunks of texts, once applied, information looks organised and readable. 
The browser can now recognise paragraphs as individual pieces of text.


<H3>HTML HEADLINES</H3>


Web pages usually have headings, subheadings and titles.
Headlines serve the purpose of dividing the content into smaller, more digestible  chunks, which helps with the structure of the content.
On landing pages,they act as the main content and are clickable, leading to more information pages .
they come in 6 elements, h1,h2,h3,h4,h5,h6.
H1 being the largest and h6 the smallest.
The choice of a headline is not based on the appearance but on its meaning. 
The hierarchical  system it forms gives meaning to the browser , distinguishing what is most important from what is least important.
Its important to use a consistent headline throughout trhe documents.

<H3>HTML BOLD AND ITALICS</H3>

There are 4 elements here, 2 for bold and 2 for italics.
For italics, we use em and i.
For bold we use strong and b.
we use em for emphasis and i for italics.
They may seem exactly similar but they serve different purposes.
Bold has strong which is to show seriousness and b is more generic and neutral.
b carries no meaning and allows us to make headings bols b.
We can define the style for different headlines using strong and b is used as a last resort.
Of the 4 elements, tw of them namely em and strong convey meaning and serve a language -related purpose.
The other two i and  b that do not carry any specific meabning and are used soley for visual styling 

<H3>HTML LISTS</H3>

List are a part of our daily lives, we use thrm more on the internet , they might not always look like a traditional list.
For instance, a navigation bar with links is a list. 
There are 3 yopes of lists, unordered, ordered and definition lists.
Unordered being the most common, enclosed in i element inside ul  which represents unordered lists.
Adding  spaces or tabs betweeen lists makes the code easier to read, this does not affect appearance on webpages. 
We use ul to convey meaning ,its makes it easier to style using CSS.

OrderedLists use ol , indicating a specific order of the list.
Ordered and unordered lists are quite similar , except for the wrapping element they use.  

Description lists , unlike ordered and unordered , is used for lists that resemble key-value pair in computer science. 
Instead of just items, we have terms and their corresponding definitions.
For this list, we use the dt standing for definition term, side by side to a dd tag , standing for definition description.
The entire list is wrapped in a dl elements, representing definition list.
The dt and dd are placed side ny side without any additional wrapper around them.

<H3>HTML QUOTES</H3>

We use cite to attribute a quote to a specific person.
To distinguish a quote from a surrounding text, we wrap the whole thing in a blockquote element.
cite and blockquote have a semantic purpose.
They inform computers what something is.
They are convenient for styling with CSS making them standout with a special appearance. 
We can put other elements inside the blockquote including a list and a headline.
Its important to nest the elements in a way that makes sense.
Quotes that appear within the text are wrapped in q element that stands for quotes.
q element is an inline element like strong, em and i. 
Inline elements are elements meant to wrap aroung phrases of texts that are inline with other content. 
Elements like blockquote ,p , and ul are called blocked-level elements because they create separate blocks on the page.
Thid is easy to style using CSS.
Some elements serve as markers for something that is part of larger entity, while others represents a larger entity itself.
The datetime attribute allows us to specify  the date  and time in a format the computer can understand.
The format of the time within the datetime attribute has to be specific.
Date and time have a specific format and we have to use that format. i.e 2023--5-08.
The machine readable prefers time in the 24 hour clock format, we can choose whether to use seconds  and fractions of seconds  or not.
We can also specify time such as 15:45-05:00.
You can combine date and time using the datetime attribute, you first include  the date and the time.

<H3>HTML DATE AND TIME INPUTS</H3>  

Html use time element for date and time.
Used to mark anything that specifies a time of day, a date or a duration.
We can use it like this <time>May 8th<time> or <time>May 8th, 2025<time>, depending on how  we prefer to write dates.
The purpose of time us to convey the exact time and date to computers.
The datetime attribute allows us to specify the date and time in a format that computers can understand.

<H3>HTML CODE, PRE AND BR</H3>

code element is used to write code without executing it
By default code is an inline element, meaning it remains part of the sentence its in
The br element is used to insert line breaks so lines are not treated as separate paragraphs
The br element tag does not have a closing tag, it dos not contain anything inside, just points to where the line is supposed to be 
The pre element is used fotr indentation and white spaces
code and pre elements are often combined to display code blocks without proper indentation
The code , pre ,and br elements usually work together when working with code without executing it, pre and br keeps the indentation and line breaks 
The three elements are handy for conveying the structure and appearance of code, as well as other types of content

<H3>HTML SUPERSCRIPTS,SUBSCRIPTS,SMALL TEXT</H3>

Superscripts , subscripts, and small text can be used when marking up certain bits as having different meaning.
Superscripts are set above the baseline of the text.
Subscripts are set below the normal baseline of the text.
Superscripts are mostly used in formulas, like 5<sup>2</sup>. 
Subscripts can be used for footnotes.
MathML is a specialized markup languange for maths, more powewrful than HTML.
Small element is used to indicate that a text has very little prominence, small in its importance.
Small is not used to make texts smaller, you can use CSS to adjust the size of a text.
Just like strong marks something of importance, small is used to convey that something has little prominence. 

<H3>HTML CAPABILITIES</H3>

We can view the code by right-clicking on the website and select inspect.
This will open developer tools .
In the right pane you can see all the CSS used, left pane contains HTML.
When the code executes, the browser attempts to correctany mistakes we might have made and hsows its version of the webpages.
The inspector shows the DOM tree (Document Object Model).

<H3>HTML ATTRIBUTES</H3>

Html has additional attributes which add power to any element.
Certain attributes are specific to particular elements such as daytime attributes , which we only use in the time elements.
Some attributes work wih multiple elements but not all of them. 
The class attribute is the most common one used. 
Allows us to assign reusable name of any elementwhich can later styled using CSS for all elements using that class.
Another popular attribute is the ID , useful in javascript for specific elements or targeted links.
The uniqueness of an ID name ensures that there will always be just one element with that ID , making it useful to interact with javascript or links.
The content-editable attribute allows visitors to edit the content on a webpage.
You can see this in action with the blockquote element.
A user can edit the content but once refreshed, reverts back to the original state.
Html provides editing functionality , but the back-end developers would have to create a system for capturing and saving new content.
Progress of saving content varies in websites and often used in javascript
The lang attribute allows us to specify the langiuage of the content  using a short lanmguage element.
The dir attribute explicitly  ibndicates the direction in which the content flows, using "RTL" for right-to-left, "LTR" for left-to-right.
These attributes , lang and  dir are considered global attributes and can be used on any element.

<H3>ARIA ROLES</H3>

These are extra attributes that add on html elements to make them more meangingful to help the browser know what they represent.
Aria roles are useful in providing essential information to assistive technologies like screen readers , braille displays and magnifies.
Aria roles provide the necessary tools to make the site accessible to everyone.

<H3>FORMATTING HTML</H3>

Html does not pay much attention to line breaks, tabs and spaces.
There are exceptions when you use code, pre and textarea elements or when handling white spaces with CSS.
The browser does not care about anything more than single spaces.
Some html elements are short because of the space concern back in the day, now we have full elemts like video and audio.
The length of an element gives us a clkue of how long its been in existence .
The newer elements always have  closing tags, some of the older ones do not.


<H3>UNSUAL CHARACTERS</H3>

Symbols like <,> and & are important in html .
If we write them with spaces , they appear as regular content, but if we start writing something that resembles an html element, it magically disappears.
The browser assumes its part of the html code and does not display it.

<H3>HTML NAVIGATION LINKING</H3>

<h4>HTML LINKS</h4>
links are everywhere, navigation bars, menus packed with options enticing tears cards, and pages full of clickable titles.
We can use links to transport you to a whole new page or website.
To create a link, we use the A tag, standing for anchor.
To create a link, we need to add href with a URL enclosed in quotes.
The URL is where the link will take us.
Href stands for hypertext reference.
We can also place images and texts  A to make them clickable.
Can also be placed within a paragraph or other texts.
In an absolute URL, the HTTP or HTTPS part must be included which stands for hypertext transport protocol.
The  S in HTTPS stands for secure.
In the past, webpages started with hjttp, now expert recommend HTTPs for enhanced security.

<h4>URL PATHWAYS</h4>
When creating links, absolute URLsare one option.
When clicking on a link on the same website and domain as the page containing the link, a relative URL can be used instead.
Creating a relative URL is not only useful for the A element but is aslo a skilled used to reference images, files , video files, CSS.
The slashes in a URL indicate that we shoulkd look deeper into the file structure or go one level down.
To create a relative URL, omit the domain name but include the slash at the beginning. 
This tells the browser to start from the root of the file structure.
We can also write the path to be relative to the file where the link is.
Relative URLs are based on th current file's location, while absolute URLs start from the root of the website.

<h4>Navigation</h4>
Each line is wrapped in an element with the current URL, and then  enclosed in an "li" element  to create a list of links.
To maintain the order , wrap the whole list in na "lo" element .
Finally, encompass the entire list in a "nav" element to indicate that its the sits's navigation.
Apply CSS for styling.
Assign the role navigation to the nav element, which signifies it represents the main navigation of the page.
Add an ariel label for the main menu, providing a descriptive label that can be read out loud by a screen reader.

<h4>WORKING WITH GRAPHICS AND IMAGES</h4>

When we want to add an image to a webpage, we use the image element, written as IMG.
There are 4 attributes added to every image,
<dl>
    <dt>SRC</dt><dd>Which image to load</dd>
    <dt>ALT</dt><dd>Text description of the image</dd>
    <dt>Width and Height</dt><dd>Size of the image</dd>
</dl>

The image's URL is pasted into the source.
ALT serves as replacement of the image when the image can't be seen.
Browser needs to be informed of the image size in pixels.

<h4>Image Formats</h4>
Consider the image file before putting in a website.
It needs to be in a file format that web browsers can understand , there are variouys options available.
HTML aims for the highest quality with the smallest size achievable.
Each file format deploys with a distinct approach to faster downloads and prevention of excessive data usage for users.
<dl>
    <dt>GIF</dt><dd>Great for compressing illustrations that have large areas of the same color,but falls short on photographs. Supports 256 colors </dd>
    <dt>SVG</dt><dd>Perfect for logogs,icons, and other types of illustrations. A vector file that contains instructions for drawing rather than idividual pixels. Can be scaled without losing quality</dd>
</dl>

<h3>RESPONSIVE IMAGES</h3>
To carter for different browsers, using the img elemnts with its alt text and a URL to the image file.
This ensures that even outdated browsers like internet explora II can display the image.
Finally, wrap this image element with the picture element.
Acts as a wrapper or the whole set up.
List alternative options within the picture elemnt using source element.
First source element use the source set attribute to point to a mobile image file.
This will be the cropped version of the photo sized at pixels wide.
This way, when the viewport is smaller than 600 pxels , this version of the image will be loaded.
In the other source element, use a kind of media query to specify the image for larger screens.
When the viewport is at least 600 pixels wide, the landscape version of the photo will load.
This is a pretty neat trick that allows you to optimize the image for different screen sizes .
The source set attribute is used in the source element , just like it is used in the image element .
The browser switches between files, using the karger ones only when necessary, considering the viewport and retina screen.
The browser switches to a wider verion when the viewport reaches 600 pixels

<h3>FIGCAPTIONS AND FIGURE</h3>
Figcaptions are used to caption a picture.
The caption and picture are nested within a  figire element.
Gives the browser more information about the relationship between the image and caption.
A figcaption is not a regular paragraph or a generic div.
Figures can be used for more than just images.
You can use them in interactive graphics.
The figire and figcaptions are useful for anything that serves as a visual illustration or demonstration that needs a caption.

<h3>WORKING WITH FILES</h3>

<H4>WORKING WITH AUDIO</H4>
The audio element has an opening and closing tag.
This means its modern and has more power.
We use source attribute to provide URL for the audio file.
There are different audio file formats to choose from.
We have to let the browser know that we want controls like a play button, timeline, and volume control.
Using the browsers built-in controls is optional.
We can add custom controls by using the "controls" attribute .
This will allow us to play, pause, adjust volume,see the time and navigate through the timeline.
We can also use the loop and autoplay attributes with the audio element.
Removing the source element inside the audio element and placing it in a separate element allows for the addition of other alternative audio file formats.
Create multiple files and list them in separate source elements , if the browser does not support the audio element.
Audio element is an excellent tool for embedding files and a player on the wedpage.

<h4>WORKING WITH VIDEO</h4>
Video element has open and closing tags.
We use source attribute to specify the video filer.
If the controls are added, the broswer will automatically create a video player.
Ther are different codecs that can be used to encode video files.
Video files contain a lot of data, if compressed , can become too large to be efficiently transmitted over the internet.
The internet uses a mechanism to compress data into smaller packages.
The video element allows us to include multiple source files, enabling the simultaneous use of different codecs.
HTML lacks the built-in mechanism for sending different videos sizes based on network conditions .
Big streaming platforms use a technique called adaptive bitrate streaming to carter for different network conditions.
This complex process invloves a server farm of transcoding robots, ensuring seamless switch between different resolutions as users watch videos.

<h4>WORKING WITH CAPTIONS,CAPTIONS,AND SUBTITLES</h4>
We use a track element and link it to a text file and add captions to a video.
The subtitlescan be turned on and off.
A file called ibvtt standing for web video text tracks willbe used.
In the file, each line of text is accomplanied by a time code , indicating when it should be displayed in the video.
The track element is inserted inside the video element.
On the track element inside the source attribute, use the kind attribute to indicate that it contains captions and a label attribute to display the caption option as Ënglish in the player .
Additionally, use the source lang attribute to indicate the language and add a default attribute to make this track the default choice when captions are enabled.
Some options for the kind attriute include using descriptions that allows us to create a vtt file that describves the visual elements of the video.
Users can choose a track that read out loud these descriptions, making the video more accessible to those who are visually impaired.
Chapter is another option that provides a text file listing the different scetions of the video, allowing users to jump to specific parts.
Subtitles and captions are not only powerful but are required by law.
Helps with website traffic growth

<h3>EMBEDDING MEDIA VS IFRAMES</h3>

Embeding refers to taking content from one site and placing it within the middle of another site's page.
There is a wide range of content that can be embeded on a page.
For instance, a map from google maps.
It is common practice to embed complex content from a service that handles the technical aspects.
Instead of figuring out how to build a mapping service,you can rely on someone else's toolkit to handle all of that.
IFrame element has attributes like height and width that can be adjusted.
The scr attribute is used to specify the source of the video file.
While iframes are powerful, we need to consider security issues when pulling in code from another website.
When using a content management system(CMS), you might not be able to simply copy and paste random embeded code from other websites.
These CMS usually have specific ways to allow URLs or short codes from trusted sources.
If multiple people will be be adding content to the system, do not allow iframes without considering security measures, but if only one person will be posting on thr website then its fine.

<h3>HTML INDENTATION</h3>

Html has tools to indicate the lnaguage of content.
The lang attribute is used to specify the language of webpages.
If the whole page is one language, its simple.
Set the language on ther main html element that wraps everything else.
"en-US" is the lanf attribute for US english.
The lang attribute also indicates othetr qualities like the writing system.
If is important to indicate the direction of the content.
Unicode UTF-8 is the most popular.
Charset are also important as the characters and alphabets.
If informs the browser what characters  will be used.
By including trhe lang, dir, and charset of the webpage, you contribute to a more inclusive future for the web.

<h3>HTML GENERIC ELEMENTS , DIV AND SPAN</h3>

Div is a block-level elements while span is an inline element.
Divs are used to create sections, sidebars, and everything inbetween.
Divs and spans come in handy when there is not anaother suitable element to use, acting as last resort options.

<h3>HTML PAGES</h3>

HTML files are a vital part of the web.
When you want to visit a website, you open the broswer and enter a URL.
The web server responds by sending back the specific html file located on that address.
Everything needed to display in webpages used to be contained in a single html file, along with images , noiw thinmgs are more complex.
Texts are stored in databases, multiple static files are combined in real time , customised for each user.
CSS for styling, javascript in separate files, and additional video, images , audio and ads.
What users see 




 
