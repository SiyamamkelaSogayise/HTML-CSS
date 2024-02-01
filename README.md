# HTML-CSS
HTML and CSS
<H3>Introduction to Html</H3> 


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




 
