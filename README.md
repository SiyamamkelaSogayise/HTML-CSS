# HTML-CSS
HTML and CSS
Introduction to Html 


Html Syntax
Html is a language that uses tags enclosed in greater and less than sysmbols, used to create web pages
It has opening and closing tags
For a paragraph we use <p></p>
Some tags require opening and closing tags while others do not.
Html is used to bridge the gap btween humans and computers by giving meaning to the content, making it understandable for both the computer and the reader(humans)
Html elements can be nested within each other 
The nestcreates a tree like structure called DOM,abbreviated for Document Object Model
This DOM becomes most important when working with CSS and Javascript

Example of nested elements
<article>
    <h1> This is a headline</h1>
    <p>This is the 1st paragraph</p>
    <p>This is the 2nd paragraph</p>
    <p>Paragraph with <em>emphasized text</em> for effect</p>
</article>    

Like <p></p>, <article></article> also has a closing tag
Choice of Hmlt element affects the user's experience of the website as well as people with various disabilities

HTML PARAGRAPHS
Paragraphs use <p></p> 
Without the tag, the content would just look like a chunks of texts, once applied, information looks organised and readbale 
The browser can now recognise paragraphs as individual pieces of text


HTML HEADLINES
Web pages usually have headings, subheadings and titles
Headlines serve the purpose of dividing the content into smaller, more digestible  chunks, which helps with the structure of the content
On landing pages,they act as the main content and are clickable, leading to more information pages 
they come in 6 elements, h1,h2,h3,h4,h5,h6
H1 being the largest and h6 the smallest
The choice of a headline is not based on the appearance but on its meaning 
The hierarchical  system it forms gives meaning to the browser , distinguishing what is most important from what is least important
Its important to use a consistent headline throughout trhe documents

HTML BOLD AND ITALICS

There are 4 elements here, 2 for bold and 2 for italics
For italics, we use <em></em> and <i></i>
For bold we use <strong></strong> and <b></b>
we use <em> for emphasis and <i> for italics
They may seem exactly similar but they serve different purposes
Bold has <strng> which is to show seriousness and <b> is more generic and neutral
<b> carries no meaning and allows us to make headings bols <b></b>
We can define the style for different headlines using <strong> and <b> is used as a last resort
Of the 4 elements, tw of them namely <em></em> and <strong></strong> convey meaning and serve a language -related purpose
The other two <i></i> and  <b></b> that do not carry any specific meabning and are used soley for visual styling 

HTML LISTS
List are a part of our daily lives, we use thrm more on the internet , they might not always look like a traditional list
For instance, a navigation bar with links is a list 
There are 3 yopes of lists, unordered, ordered and definition lists
Unordered being the most common, enclosed in <li> element inside <ul>  which represents unorderedLists
Adding  spaces or tabs betweeen lists makes the code easier to read, this does not affect appearance on webpages 
We use <ul> to convey meaning ,its makes it easier to style using CSS

OrderedLists use <ol> , indicating a specific order of the list
Ordered and unordered lists are quite similar , except for the wrapping element they use  

Description lists , unlike ordered and unordered , is used for lists that resemble key-value pair in computer science 
Instead of just items, we have terms and their corresponding definitions
For this list, we use the <dt> standing for definition term, side by side to a <dd> tag , standing for definition description
The entire list is wrapped in a <dl> elements, representing definition list
The <dt> and <dd> are placed side ny side without any additional wrapper around them

HTML QUOTES
We use <cite> to attribute a quote to a specific person
To distinguish a quote from a surrounding text, we wrap the whole thing in a <blockquote> element
<cite> and <blockquote> have a semantic purpose
They inform computers what something is
They are convenient for styling with CSS making them standout with a special appearance 
We can put other elements inside the <blockquote> including a list and a headline
Its important to nest the elements in a way that makes sense
Quotes that appear within the text are wrapped in <q> element that stands for quotes
<q> element is an inline element like <strong>,<em> and <i> 
Inline elements are elements meant to wrap aroung phrases of texts that are inline with other content 
Elements like <blockquote> , <p>, and <ul> are called blocked-level elements because they create separate blocks on the page
Thid is easy to style using CSS
Some elements serve as markers for something that is part of larger entity, while others represents a larger entity itself
The datetime attribute allows us to specify  the date  and time in a format the computer can understand
The format of the time within the datetime attribute has to be specific
Date and time have a specific format and we have to use that format. i.e 2023--5-08
The machine readable prefers time in the 24 hour clock format, we can choose whether to use seconds  and fractions of seconds  or not
We can also specify time such as 15:45-05:00
You can combine date and time using the datetime attribute, you first include  the date and the time

HTML DATE AND TIME INPUTS
Html use <time> element for date and time
Used to mark anything that specifies a time of day, a date or a duration
We can use it like this <time>May 8th<time> or <time>May 8th, 2025<time>, depending on how  we prefer to write dates
The purpose of <time> ius to convey the exact time and date to computers
The datetime attribute allows us to specify the date and time in a format that computers can understand

HTML CODE, PRE AND BR
<code> element is used to write code without executing it
By default <code> is an inline element, meaning it remains part of the sentence its in
The <br> element is used to insert line breaks so lines are not treated as separate paragraphs
The <br> element tag does not have a closing tag, it dos not contain anything inside, just points to where the line is supposed to be 
The <pre> element is used fotr indentation and white spaces
<code> and <pre> elements are often combined to display code blocks without proper indentation
The <code> , <pre>,and <br> elements usually work together when working with code without executing it, <pre> and <br> keeps the indentation and line breaks 


 
