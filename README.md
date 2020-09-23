<div align="center">

## A Beginner's Guide to HTML Part I: \(a brief reference\)


</div>

### Description

You can't get too far in ASP without an intimate knowledge of HTML, so this tutorial will take a newbie through the ABC's of HTML...one step at a time. It's also a great reference for pros who forget how to use little known tags!

By pubs@ncsa.uiuc.edu
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Found on the World Wide Web](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/found-on-the-world-wide-web.md)
**Level**          |Beginner
**User Rating**    |4.5 (45 globes from 10 users)
**Compatibility**  |ASP \(Active Server Pages\)
**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__4-9.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/found-on-the-world-wide-web-a-beginner-s-guide-to-html-part-i-a-brief-reference__4-6156/archive/master.zip)





### Source Code

<p><font face="Verdana" size="4">A Beginner's Guide to HTML</font></p>
<p><font face="Verdana">This is a primer for producing documents in HTML, the
hypertext markup<br>
language used on the World Wide Web. This guide is intended to be an<br>
introduction to using HTML and creating files for the Web. Links are<br>
provided to additional information. You should also check your local<br>
bookstore; there are many volumes about the Web and HTML that could be<br>
useful.</font></p>
<p><font face="Verdana">&nbsp;&nbsp; * Getting Started<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Terms to Know<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o What Isn't Covered<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o HTML Version<br>
&nbsp;&nbsp; * HTML Documents<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o What an HTML Document Is<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Tags Explained<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o The Minimal HTML Document<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o A Teaching Tool<br>
&nbsp;&nbsp; * Markup Tags<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o HTML<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o HEAD<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o TITLE<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o BODY<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Headings<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Paragraphs<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Lists<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Preformatted Text<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Extended Quotations<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Addresses<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Forced Line Breaks/Postal Addresses<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Horizontal Rules<br>
&nbsp;&nbsp; * Character Formatting<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Logical Versus Physical Styles<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Escape Sequences<br>
&nbsp;&nbsp; * Linking<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Relative Pathnames Versus Absolute
Pathnames<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o URLs<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Links to Specific Sections<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Mailto<br>
&nbsp;&nbsp; * Inline Images<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Image Size Attributes<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Aligning Images<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Alternate Text for Images<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Background Graphics<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Background Color<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o External Images, Sounds, and
Animations<br>
&nbsp;&nbsp; * Tables<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Table Tags<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o General Table Format<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Tables for Nontabular Information<br>
&nbsp;&nbsp; * Fill-out Forms<br>
&nbsp;&nbsp; * Troubleshooting<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Avoid Overlapping Tags<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Embed Only Anchors and Character
Tags<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Do the Final Steps<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Commenting Your Files<br>
&nbsp;&nbsp; * For More Information<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Style Guides<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Other Introductory Documents<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Additional Online References<br>
<br>
</font><font face="Verdana">----------------------------------------------------------------------------</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<b> Getting Started</b></font></p>
<p><font face="Verdana">Terms to Know</font></p>
<p><font face="Verdana"><b>WWW</b>&nbsp; World Wide Web<br>
<b>Web</b>&nbsp; World Wide Web<br>
<b>SGML</b><br>
&nbsp;&nbsp;&nbsp;&nbsp; Standard Generalized Markup Language--a standard for
describing markup<br>
&nbsp;&nbsp;&nbsp;&nbsp; languages<br>
<b>DTD</b>&nbsp; Document Type Definition--this is the formal specification of a
markup<br>
&nbsp;&nbsp;&nbsp;&nbsp; language, written using SGML<br>
<b>HTML</b><br>
&nbsp;&nbsp;&nbsp;&nbsp; HyperText Markup Language--HTML is an SGML DTD<br>
&nbsp;&nbsp;&nbsp;&nbsp; In practical terms, HTML is a collection of
platform-independent styles<br>
&nbsp;&nbsp;&nbsp;&nbsp; (indicated by markup tags) that define the various
components of a<br>
&nbsp;&nbsp;&nbsp;&nbsp; World Wide Web document. HTML was invented by Tim
Berners-Lee while at<br>
&nbsp;&nbsp;&nbsp;&nbsp; CERN, the European Laboratory for Particle Physics in
Geneva.</font></p>
<p><font face="Verdana">What Isn't Covered</font></p>
<p><font face="Verdana">This primer assumes that you:</font></p>
<p><font face="Verdana">&nbsp;&nbsp; * know how to use NCSA Mosaic or some other
Web browser<br>
&nbsp;&nbsp; * have a general understanding of how Web servers and client
browsers<br>
&nbsp;&nbsp;&nbsp;&nbsp; work<br>
&nbsp;&nbsp; * have access to a Web server (or that you want to produce HTML
documents<br>
&nbsp;&nbsp;&nbsp;&nbsp; for personal use in local-viewing mode)</font></p>
<p><font face="Verdana">HTML Version</font></p>
<p><font face="Verdana">This guide reflects the most current specification--HTML
Version 2.0-- plus<br>
some additional features that have been widely and consistently implemented<br>
in browsers. Future versions and new features for HTML are under<br>
development.</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<b>HTML Documents</b></font></p>
<p><font face="Verdana"><b>What an HTML Document Is</b></font></p>
<p><font face="Verdana">HTML documents are plain-text (also known as ASCII)
files that can be<br>
created using any text editor (e.g., Emacs or vi on UNIX machines; BBEdit on<br>
a Macintosh; Notepad on a Windows machine). You can also use word-processing<br>
software if you remember to save your document as &quot;text only with line<br>
breaks.&quot;</font></p>
<p><font face="Verdana"><b>Tags Explained</b></font></p>
<p><font face="Verdana">An element is a fundamental component of the structure
of a text document.<br>
Some examples of elements are heads, tables, paragraphs, and lists. Think of<br>
it this way: you use HTML tags to mark the elements of a file for your<br>
browser. Elements can contain plain text, other elements, or both.</font></p>
<p><font face="Verdana">To denote the various elements in an HTML document, you
use tags. HTML tags<br>
consist of a left angle bracket (&lt;), a tag name, and a right angle bracket<br>
(&gt;). Tags are usually paired (e.g., &lt;H1&gt; and &lt;/H1&gt;) to start and
end the tag<br>
instruction. The end tag looks just like the start tag except a slash (/)<br>
precedes the text within the brackets. HTML tags are listed below.</font></p>
<p><font face="Verdana">Some elements may include an attribute, which is
additional information that<br>
is included inside the start tag. For example, you can specify the alignment<br>
of images (top, middle, or bottom) by including the appropriate attribute<br>
with the image source HTML code. Tags that have optional attributes are<br>
noted below.</font></p>
<p><font face="Verdana">NOTE: HTML is not case sensitive. &lt;title&gt; is
equivalent to &lt;TITLE&gt; or<br>
&lt;TiTlE&gt;. There are a few exceptions noted in Escape Sequences below.</font></p>
<p><font face="Verdana">Not all tags are supported by all World Wide Web
browsers. If a browser does<br>
not support a tag, it (usually) just ignores it.</font></p>
<p><font face="Verdana"><b>The Minimal HTML Document</b></font></p>
<p><font face="Verdana">Every HTML document should contain certain standard HTML
tags. Each document<br>
consists of head and body text. The head contains the title, and the body<br>
contains the actual text that is made up of paragraphs, lists, and other<br>
elements. Browsers expect specific information because they are programmed<br>
according to HTML and SGML specifications.</font></p>
<p><font face="Verdana">Required elements are shown in this sample bare-bones
document:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; &lt;html&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;head&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;TITLE&gt;A Simple HTML Example&lt;/TITLE&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;/head&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;body&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;H1&gt;HTML is Easy To Learn&lt;/H1&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;P&gt;Welcome to the world of HTML.<br>
&nbsp;&nbsp;&nbsp; This is the first paragraph. While short it is<br>
&nbsp;&nbsp;&nbsp; still a paragraph!&lt;/P&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;P&gt;And this is the second paragraph.&lt;/P&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;/body&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;/html&gt;</font></p>
<p><font face="Verdana">The required elements are the &lt;html&gt;,
&lt;head&gt;, &lt;title&gt;, and &lt;body&gt; tags (and<br>
their corresponding end tags). Because you should include these tags in each<br>
file, you might want to create a template file with them. (Some browsers<br>
will format your HTML file correctly even if these tags are not included.<br>
But some browsers won't! So make sure to include them.)</font></p>
<p><font face="Verdana">Click to see the formatted version of the example. A
longer example is also<br>
available but you should read through the rest of the guide before you take<br>
a look. This longer-example file contains tags explained in the next<br>
section.</font></p>
<p><font face="Verdana"><b>A Teaching Tool</b></font></p>
<p><font face="Verdana">To see a copy of the file that your browser reads to
generate the<br>
information in your current window, select View Source (or the equivalent)<br>
from the browser menu. The file contents, with all the HTML tags, are<br>
displayed in a new window.</font></p>
<p><font face="Verdana">This is an excellent way to see how HTML is used and to
learn tips and<br>
constructs. Of course, the HTML might not be technically correct. Once you<br>
become familiar with HTML and check the many online and hard-copy references<br>
on the subject, you will learn to distinguish between &quot;good&quot; and
&quot;bad&quot; HTML.</font></p>
<p><font face="Verdana">Remember that you can save a source file with the HTML
codes and use it as a<br>
template for one of your Web pages or modify the format to suit your<br>
purposes.</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<b>&nbsp;&nbsp; Markup Tags</b></font></p>
<p><font face="Verdana"><b>HTML</b></font></p>
<p><font face="Verdana">This element tells your browser that the file contains
HTML-coded<br>
information. The file extension .html also indicates this an HTML document<br>
and must be used. (If you are restricted to 8.3 filenames (e.g.,<br>
LeeHome.htm, use only .htm for your extension.)</font></p>
<p><font face="Verdana"><b>HEAD</b></font></p>
<p><font face="Verdana">The head element identifies the first part of your
HTML-coded document that<br>
contains the title. The title is shown as part of your browser's window (see<br>
below).</font></p>
<p><font face="Verdana"><b>TITLE</b></font></p>
<p><font face="Verdana">The title element contains your document title and
identifies its content in<br>
a global context. The title is displayed somewhere on the browser window<br>
(usually at the top), but not within the text area. The title is also what<br>
is displayed on someone's hotlist or bookmark list, so choose something<br>
descriptive, unique, and relatively short. A title is also used during a<br>
WAIS search of a server.</font></p>
<p><font face="Verdana">For example, you might include a shortened title of a
book along with the<br>
chapter contents: NCSA Mosaic Guide (Windows): Installation. This tells the<br>
software name, the platform, and the chapter contents, which is more useful<br>
than simply calling the document Installation. Generally you should keep<br>
your titles to 64 characters or fewer.</font></p>
<p><font face="Verdana"><b>BODY</b></font></p>
<p><font face="Verdana">The second--and largest--part of your HTML document is
the body, which<br>
contains the content of your document (displayed within the text area of<br>
your browser window). The tags explained below are used within the body of<br>
your HTML document.</font></p>
<p><font face="Verdana"><b>Headings</b></font></p>
<p><font face="Verdana">HTML has six levels of headings, numbered 1 through 6,
with 1 being the most<br>
prominent. Headings are displayed in larger and/or bolder fonts than normal<br>
body text. The first heading in each document should be tagged &lt;H1&gt;.</font></p>
<p><font face="Verdana">The syntax of the heading element is:<br>
&lt;Hy&gt;Text of heading &lt;/Hy&gt;<br>
where y is a number between 1 and 6 specifying the level of the heading.</font></p>
<p><font face="Verdana">Do not skip levels of headings in your document. For
example, don't start<br>
with a level-one heading (&lt;H1&gt;) and then next use a level-three
(&lt;H3&gt;)<br>
heading.</font></p>
<p><font face="Verdana"><b>Paragraphs</b></font></p>
<p><font face="Verdana">Unlike documents in most word processors, carriage
returns in HTML files<br>
aren't significant. So you don't have to worry about how long your lines of<br>
text are (better to have them fewer than 72 characters long though). Word<br>
wrapping can occur at any point in your source file, and multiple spaces are<br>
collapsed into a single space by your browser.</font></p>
<p><font face="Verdana">In the bare-bones example shown in the Minimal HTML
Document section, the<br>
first paragraph is coded as</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; &lt;P&gt;Welcome to the world of
HTML.<br>
&nbsp;&nbsp;&nbsp; This is the first paragraph.<br>
&nbsp;&nbsp;&nbsp; While short it is<br>
&nbsp;&nbsp;&nbsp; still a paragraph!&lt;/P&gt;</font></p>
<p><font face="Verdana">In the source file there is a line break between the
sentences. A Web<br>
browser ignores this line break and starts a new paragraph only when it<br>
encounters another &lt;P&gt; tag.</font></p>
<p><font face="Verdana">Important: You must indicate paragraphs with &lt;P&gt;
elements. A browser ignores<br>
any indentations or blank lines in the source text. Without &lt;P&gt; elements,<br>
the document becomes one large paragraph. (One exception is text tagged as<br>
&quot;preformatted,&quot; which is explained below.) For example, the following
would<br>
produce identical output as the first bare-bones HTML example:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; &lt;H1&gt;Level-one
heading&lt;/H1&gt; &lt;P&gt;Welcome to the world of HTML. This is the<br>
&nbsp;&nbsp;&nbsp; first paragraph. While short it is still a<br>
&nbsp;&nbsp;&nbsp; paragraph! &lt;/P&gt; &lt;P&gt;And this is the second
paragraph.&lt;/P&gt;</font></p>
<p><font face="Verdana">To preserve readability in HTML files, put headings on
separate lines, use a<br>
blank line or two where it helps identify the start of a new section, and<br>
separate paragraphs with blank lines (in addition to the &lt;P&gt; tags). These<br>
extra spaces will help you when you edit your files (but your browser will<br>
ignore the extra spaces because it has its own set of rules on spacing that<br>
do not depend on the spaces you put in your source file).</font></p>
<p><font face="Verdana">NOTE: The &lt;/P&gt; closing tag can be omitted. This is
because browsers<br>
understand that when they encounter a &lt;P&gt; tag, it implies that there is an<br>
end to the previous paragraph.</font></p>
<p><font face="Verdana">Using the &lt;P&gt; and &lt;/P&gt; as a paragraph
container means that you can center a<br>
paragraph by including the ALIGN=alignment attribute in your source file.</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; &lt;P ALIGN=CENTER&gt;<br>
&nbsp;&nbsp;&nbsp; This is a centered paragraph. [See the formatted version
below.]<br>
&nbsp;&nbsp;&nbsp; &lt;/P&gt;</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
This is a centered paragraph.</font></p>
<p><font face="Verdana"><b>Lists</b></font></p>
<p><font face="Verdana">HTML supports unnumbered, numbered, and definition
lists. You can nest lists<br>
too, but use this feature sparingly because too many nested items can get<br>
difficult to follow.</font></p>
<p><font face="Verdana"><b>Unnumbered Lists</b></font></p>
<p><font face="Verdana">To make an unnumbered, bulleted list,</font></p>
<p><font face="Verdana">&nbsp; 1. start with an opening list &lt;UL&gt; (for
unnumbered list) tag<br>
&nbsp; 2. enter the &lt;LI&gt; (list item) tag followed by the individual item;
no<br>
&nbsp;&nbsp;&nbsp;&nbsp; closing &lt;/LI&gt; tag is needed<br>
&nbsp; 3. end the entire list with a closing list &lt;/UL&gt; tag</font></p>
<p><font face="Verdana">Below is a sample three-item list:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; &lt;UL&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;LI&gt; apples<br>
&nbsp;&nbsp;&nbsp; &lt;LI&gt; bananas<br>
&nbsp;&nbsp;&nbsp; &lt;LI&gt; grapefruit<br>
&nbsp;&nbsp;&nbsp; &lt;/UL&gt;</font></p>
<p><font face="Verdana">The output is:</font></p>
<p><font face="Verdana">&nbsp;&nbsp; * apples<br>
&nbsp;&nbsp; * bananas<br>
&nbsp;&nbsp; * grapefruit</font></p>
<p><font face="Verdana">The &lt;LI&gt; items can contain multiple paragraphs.
Indicate the paragraphs with<br>
the &lt;P&gt; paragraph tags.</font></p>
<p><font face="Verdana"><b>Numbered Lists</b></font></p>
<p><font face="Verdana">A numbered list (also called an ordered list, from which
the tag name<br>
derives) is identical to an unnumbered list, except it uses &lt;OL&gt; instead
of<br>
&lt;UL&gt;. The items are tagged using the same &lt;LI&gt; tag. The following
HTML code:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; &lt;OL&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;LI&gt; oranges<br>
&nbsp;&nbsp;&nbsp; &lt;LI&gt; peaches<br>
&nbsp;&nbsp;&nbsp; &lt;LI&gt; grapes<br>
&nbsp;&nbsp;&nbsp; &lt;/OL&gt;</font></p>
<p><font face="Verdana">produces this formatted output:</font></p>
<p><font face="Verdana">&nbsp; 1. oranges<br>
&nbsp; 2. peaches<br>
&nbsp; 3. grapes</font></p>
<p><font face="Verdana"><b>Definition Lists</b></font></p>
<p><font face="Verdana">A definition list (coded as &lt;DL&gt;) usually consists
of alternating a<br>
definition term (coded as &lt;DT&gt;) and a definition definition (coded as
&lt;DD&gt;).<br>
Web browsers generally format the definition on a new line.</font></p>
<p><font face="Verdana">The following is an example of a definition list:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; &lt;DL&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;DT&gt; NCSA<br>
&nbsp;&nbsp;&nbsp; &lt;DD&gt; NCSA, the National Center for Supercomputing
Applications,<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; is located on the campus of the
University of Illinois<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; at Urbana-Champaign.<br>
&nbsp;&nbsp;&nbsp; &lt;DT&gt; Cornell Theory Center<br>
&nbsp;&nbsp;&nbsp; &lt;DD&gt; CTC is located on the campus of Cornell University
in Ithaca,<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; New York.<br>
&nbsp;&nbsp;&nbsp; &lt;/DL&gt;</font></p>
<p><font face="Verdana">The output looks like:</font></p>
<p><font face="Verdana">NCSA<br>
&nbsp;&nbsp;&nbsp;&nbsp; NCSA, the National Center for Supercomputing
Applications, is located<br>
&nbsp;&nbsp;&nbsp;&nbsp; on the campus of the University of Illinois at
Urbana-Champaign.<br>
Cornell Theory Center<br>
&nbsp;&nbsp;&nbsp;&nbsp; CTC is located on the campus of Cornell University in
Ithaca, New York.</font></p>
<p><font face="Verdana">The &lt;DT&gt; and &lt;DD&gt; entries can contain
multiple paragraphs (indicated by &lt;P&gt;<br>
paragraph tags), lists, or other definition information.</font></p>
<p><font face="Verdana">The COMPACT attribute can be used routinely in case your
definition terms<br>
are very short. If, for example, you are showing some computer options, the<br>
options may fit on the same line as the start of the definition.</font></p>
<p><font face="Verdana">&lt;DL COMPACT&gt;<br>
&lt;DT&gt; -i<br>
&lt;DD&gt;invokes NCSA Mosaic for Microsoft Windows using the<br>
initialization file defined in the path<br>
&lt;DT&gt; -k<br>
&lt;DD&gt;invokes NCSA Mosaic for Microsoft Windows in kiosk mode<br>
&lt;/DL&gt;</font></p>
<p><font face="Verdana">The output looks like:</font></p>
<p><font face="Verdana">-i&nbsp;&nbsp; invokes NCSA Mosaic for Microsoft Windows
using the initialization file<br>
&nbsp;&nbsp;&nbsp;&nbsp; defined in the path.<br>
-k&nbsp;&nbsp; invokes NCSA Mosaic for Microsoft Windows in kiosk mode.</font></p>
<p><font face="Verdana"><b>Nested Lists</b></font></p>
<p><font face="Verdana">Lists can be nested. You can also have a number of
paragraphs, each<br>
containing a nested list, in a single list item.</font></p>
<p><font face="Verdana">Here is a sample nested list:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; &lt;UL&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;LI&gt; A few New England states:<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;UL&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;LI&gt; Vermont<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;LI&gt; New Hampshire<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;LI&gt; Maine<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;/UL&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;LI&gt; Two Midwestern states:<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;UL&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;LI&gt; Michigan<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;LI&gt; Indiana<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &lt;/UL&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;/UL&gt;</font></p>
<p><font face="Verdana">The nested list is displayed as</font></p>
<p><font face="Verdana">&nbsp;&nbsp; * A few New England states:<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Vermont<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o New Hampshire<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Maine<br>
&nbsp;&nbsp; * Two Midwestern states:<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Michigan<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; o Indiana</font></p>
<p><font face="Verdana"><b>Preformatted Text</b></font></p>
<p><font face="Verdana">Use the &lt;PRE&gt; tag (which stands for
&quot;preformatted&quot;) to generate text in a<br>
fixed-width font. This tag also makes spaces, new lines, and tabs<br>
significant (multiple spaces are displayed as multiple spaces, and lines<br>
break in the same locations as in the source HTML file). This is useful for<br>
program listings, among other things. For example, the following lines:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; &lt;PRE&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; #!/bin/csh<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; cd $SCR<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; cfs get mysrc.f:mycfsdir/mysrc.f<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; cfs get myinfile:mycfsdir/myinfile<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; fc -02 -o mya.out mysrc.f<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; mya.out<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; cfs save myoutfile:mycfsdir/myoutfile<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; rm *<br>
&nbsp;&nbsp;&nbsp; &lt;/PRE&gt;</font></p>
<p><font face="Verdana">display as:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; #!/bin/csh<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; cd $SCR<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; cfs get mysrc.f:mycfsdir/mysrc.f<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; cfs get myinfile:mycfsdir/myinfile<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; fc -02 -o mya.out mysrc.f<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; mya.out<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; cfs save myoutfile:mycfsdir/myoutfile<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; rm *</font></p>
<p><font face="Verdana">The &lt;PRE&gt; tag can be used with an optional WIDTH
attribute that specifies<br>
the maximum number of characters for a line. WIDTH also signals your browser<br>
to choose an appropriate font and indentation for the text.</font></p>
<p><font face="Verdana">Hyperlinks can be used within &lt;PRE&gt; sections. You
should avoid using other<br>
HTML tags within &lt;PRE&gt; sections, however.</font></p>
<p><font face="Verdana">Note that because &lt;, &gt;, and &amp; have special
meanings in HTML, you must use<br>
their escape sequences (&amp;lt;, &amp;gt;, and &amp;amp;, respectively) to
enter these<br>
characters. See the section Escape Sequences for more information.</font></p>
<p><font face="Verdana"><b>Extended Quotations</b></font></p>
<p><font face="Verdana">Use the &lt;BLOCKQUOTE&gt; tag to include lengthy
quotations in a separate block<br>
on the screen. Most browsers generally change the margins for the quotation<br>
to separate it from surrounding text.</font></p>
<p><font face="Verdana">In the example:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; &lt;BLOCKQUOTE&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;P&gt;Omit needless words.&lt;/P&gt;<br>
&nbsp;&nbsp;&nbsp; &lt;P&gt;Vigorous writing is concise. A sentence should
contain no<br>
&nbsp;&nbsp;&nbsp; unnecessary words, a paragraph no unnecessary sentences, for
the<br>
&nbsp;&nbsp;&nbsp; same reason that a drawing should have no unnecessary lines
and a<br>
&nbsp;&nbsp;&nbsp; machine no unnecessary parts.&lt;/P&gt;<br>
&nbsp;&nbsp;&nbsp; --William Strunk, Jr., 1918<br>
&nbsp;&nbsp;&nbsp; &lt;/BLOCKQUOTE&gt;</font></p>
<p><font face="Verdana">the result is:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp; Omit needless words.</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp; Vigorous writing is concise. A
sentence should contain no<br>
&nbsp;&nbsp;&nbsp;&nbsp; unnecessary words, a paragraph no unnecessary
sentences, for the<br>
&nbsp;&nbsp;&nbsp;&nbsp; same reason that a drawing should have no unnecessary
lines and a<br>
&nbsp;&nbsp;&nbsp;&nbsp; machine no unnecessary parts.</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp; --William Strunk, Jr., 1918</font></p>
<p><font face="Verdana"><b>Addresses</b></font></p>
<p><font face="Verdana">The &lt;ADDRESS&gt; tag is generally used to specify the
author of a document, a<br>
way to contact the author (e.g., an email address), and a revision date. It<br>
is usually the last item in a file.</font></p>
<p><font face="Verdana">For example, the last line of the online version of this
guide is:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; &lt;ADDRESS&gt;<br>
&nbsp;&nbsp;&nbsp; A Beginner's Guide to HTML / NCSA / <a href="mailto:pubs@ncsa.uiuc.edu">pubs@ncsa.uiuc.edu</a>
/ revised April 96<br>
&nbsp;&nbsp;&nbsp; &lt;/ADDRESS&gt;</font></p>
<p><font face="Verdana">The result is:<br>
A Beginner's Guide to HTML / NCSA / <a href="mailto:pubs@ncsa.uiuc.edu">pubs@ncsa.uiuc.edu</a>
/ revised April 96</font></p>
<p><font face="Verdana">NOTE: &lt;ADDRESS&gt; is not used for postal addresses.
See &quot;Forced Line Breaks&quot;<br>
below to see how to format postal addresses.</font></p>
<p><font face="Verdana"><b>Forced Line Breaks/Postal Addresses</b></font></p>
<p><font face="Verdana">The &lt;BR&gt; tag forces a line break with no extra
(white) space between lines.<br>
Using &lt;P&gt; elements for short lines of text such as postal addresses
results<br>
in unwanted additional white space. For example, with &lt;BR&gt;:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; National Center for Supercomputing
Applications&lt;BR&gt;<br>
&nbsp;&nbsp;&nbsp; 605 East Springfield Avenue&lt;BR&gt;<br>
&nbsp;&nbsp;&nbsp; Champaign, Illinois 61820-5518&lt;BR&gt;</font></p>
<p><font face="Verdana">The output is:</font></p>
<p><font face="Verdana">National Center for Supercomputing Applications<br>
605 East Springfield Avenue<br>
Champaign, Illinois 61820-5518</font></p>
<p><font face="Verdana"><b>Horizontal Rules</b></font></p>
<p><font face="Verdana">The &lt;HR&gt; tag produces a horizontal line the width
of the browser window. A<br>
horizontal rule is useful to separate sections of your document. For<br>
example, many people add a rule at the end of their text and before the<br>
&lt;address&gt; information.</font></p>
<p><font face="Verdana">You can vary a rule's size (thickness) and width (the
percentage of the<br>
window covered by the rule). Experiment with the settings until you are<br>
satisfied with the presentation. For example:</font></p>
<p><font face="Verdana">&lt;HR SIZE=4 WIDTH=&quot;50%&quot;&gt;</font></p>
<p><font face="Verdana">displays as:<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
--------------------------------------</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Character Formatting</b></font></p>
<p><font face="Verdana">HTML has two types of styles for individual words or
sentences: logical and<br>
physical. Logical styles tag text according to its meaning, while physical<br>
styles indicate the specific appearance of a section. For example, in the<br>
preceding sentence, the words &quot;logical styles&quot; was tagged as a
&quot;definition.&quot;<br>
The same effect (formatting those words in italics) could have been achieved<br>
via a different tag that tells your browser to &quot;put these words in
italics.&quot;</font></p>
<p><font face="Verdana">NOTE: Some browsers don't attach any style to the &lt;DFN&gt;
tag, so you might<br>
not see the indicated phrases in the previous paragraph in italics.</font></p>
<p><font face="Verdana"><b>Logical Versus Physical Styles</b></font></p>
<p><font face="Verdana">If physical and logical styles produce the same result
on the screen, why<br>
are there both?</font></p>
<p><font face="Verdana">In the ideal SGML universe, content is divorced from
presentation. Thus SGML<br>
tags a level-one heading as a level-one heading, but does not specify that<br>
the level-one heading should be, for instance, 24-point bold Times centered.<br>
The advantage of this approach (it's similar in concept to style sheets in<br>
many word processors) is that if you decide to change level-one headings to<br>
be 20-point left-justified Helvetica, all you have to do is change the<br>
definition of the level-one heading in your Web browser. Indeed many<br>
browsers today let you define how you want the various HTML tags rendered<br>
on-screen.</font></p>
<p><font face="Verdana">Another advantage of logical tags is that they help
enforce consistency in<br>
your documents. It's easier to tag something as &lt;H1&gt; than to remember that<br>
level-one headings are 24-point bold Times centered or whatever. For<br>
example, consider the &lt;STRONG&gt; tag. Most browsers render it in bold text.<br>
However, it is possible that a reader would prefer that these sections be<br>
displayed in red instead. Logical styles offer this flexibility.</font></p>
<p><font face="Verdana">Of course, if you want something to be displayed in
italics (for example)<br>
and do not want a browser's setting to display it differently, use physical<br>
styles. Physical styles, therefore, offer consistency in that something you<br>
tag a certain way will always be displayed that way for readers of your<br>
document.</font></p>
<p><font face="Verdana">Try to be consistent about which type of style you use.
If you tag with<br>
physical styles, do so throughout a document. If you use logical styles,<br>
stick with them within a document. Keep in mind that future releases of HTML<br>
might not support physical styles, which could mean that browsers will not<br>
display physical style coding.</font></p>
<p><font face="Verdana"><b>Logical Styles</b></font></p>
<p><font face="Verdana">&lt;DFN&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp; for a word being defined. Typically displayed in
italics. (NCSA Mosaic<br>
&nbsp;&nbsp;&nbsp;&nbsp; is a World Wide Web browser.)<br>
&lt;EM&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp; for emphasis. Typically displayed in italics.
(Consultants cannot reset<br>
&nbsp;&nbsp;&nbsp;&nbsp; your password unless you call the help line.)<br>
&lt;CITE&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp; for titles of books, films, etc. Typically displayed in
italics. (A<br>
&nbsp;&nbsp;&nbsp;&nbsp; Beginner's Guide to HTML)<br>
&lt;CODE&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp; for computer code. Displayed in a fixed-width font.
(The &lt;stdio.h&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp; header file)<br>
&lt;KBD&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp; for user keyboard entry. Typically displayed in plain
fixed-width font.<br>
&nbsp;&nbsp;&nbsp;&nbsp; (Enter passwd to change your password.)<br>
&lt;SAMP&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp; for a sequence of literal characters. Displayed in a
fixed-width font.<br>
&nbsp;&nbsp;&nbsp;&nbsp; (Segmentation fault: Core dumped.)<br>
&lt;STRONG&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp; for strong emphasis. Typically displayed in bold.
(NOTE: Always check<br>
&nbsp;&nbsp;&nbsp;&nbsp; your links.)<br>
&lt;VAR&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp; for a variable, where you will replace the variable
with specific<br>
&nbsp;&nbsp;&nbsp;&nbsp; information. Typically displayed in italics. (rm
filename deletes the<br>
&nbsp;&nbsp;&nbsp;&nbsp; file.)</font></p>
<p><font face="Verdana"><b>Physical Styles</b></font></p>
<p><font face="Verdana">&lt;B&gt;&nbsp; bold text<br>
&lt;I&gt;&nbsp; italic text<br>
&lt;TT&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp; typewriter text, e.g. fixed-width font.</font></p>
<p><font face="Verdana"><b>Escape Sequences (a.k.a. Character Entities)</b></font></p>
<p><font face="Verdana">Character entities have two functions:</font></p>
<p><font face="Verdana">&nbsp;&nbsp; * escaping special characters<br>
&nbsp;&nbsp; * displaying other characters not available in the plain ASCII
character<br>
&nbsp;&nbsp;&nbsp;&nbsp; set (primarily characters with diacritical marks)</font></p>
<p><font face="Verdana">Three ASCII characters--the left angle bracket (&lt;),
the right angle bracket<br>
(&gt;), and the ampersand (&amp;)--have special meanings in HTML and therefore<br>
cannot be used &quot;as is&quot; in text. (The angle brackets are used to
indicate the<br>
beginning and end of HTML tags, and the ampersand is used to indicate the<br>
beginning of an escape sequence.) Double quote marks may be used as-is but a<br>
character entity may also be used (&amp;quot;).</font></p>
<p><font face="Verdana">To use one of the three characters in an HTML document,
you must enter its<br>
escape sequence instead:</font></p>
<p><font face="Verdana">&amp;lt;<br>
&nbsp;&nbsp;&nbsp;&nbsp; the escape sequence for &lt;<br>
&amp;gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp; the escape sequence for &gt;<br>
&amp;amp;<br>
&nbsp;&nbsp;&nbsp;&nbsp; the escape sequence for &amp;</font></p>
<p><font face="Verdana">Additional escape sequences support accented characters,
such as:</font></p>
<p><font face="Verdana">&amp;ouml;<br>
&nbsp;&nbsp;&nbsp;&nbsp; the escape sequence for a lowercase o with an umlaut:
ö<br>
&amp;ntilde;<br>
&nbsp;&nbsp;&nbsp;&nbsp; the escape sequence for a lowercase n with an tilde: ñ<br>
&amp;Egrave;<br>
&nbsp;&nbsp;&nbsp;&nbsp; the escape sequence for an uppercase E with a grave
accent: È</font></p>
<p><font face="Verdana">You can substitute other letters for the o, n, and E
shown above. Check this<br>
online reference for a longer list of special characters.</font></p>
<p><font face="Verdana">NOTE: Unlike the rest of HTML, the escape sequences are
case sensitive. You<br>
cannot, for instance, use &amp;LT; instead of &amp;lt;.</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Linking</b></font></p>
<p><font face="Verdana">The chief power of HTML comes from its ability to link
text and/or an image<br>
to another document or section of a document. A browser highlights the<br>
identified text or image with color and/or underlines to indicate that it is<br>
a hypertext link (often shortened to hyperlink or link).</font></p>
<p><font face="Verdana">HTML's single hypertext-related tag is &lt;A&gt;, which
stands for anchor. To<br>
include an anchor in your document:</font></p>
<p><font face="Verdana">&nbsp; 1. start the anchor with &lt;A (include a space
after the A)<br>
&nbsp; 2. specify the document you're linking to by entering the parameter<br>
&nbsp;&nbsp;&nbsp;&nbsp; HREF=&quot;filename&quot; followed by a closing right
angle bracket (&gt;)<br>
&nbsp; 3. enter the text that will serve as the hypertext link in the current<br>
&nbsp;&nbsp;&nbsp;&nbsp; document<br>
&nbsp; 4. enter the ending anchor tag: &lt;/A&gt; (no space is needed before the
end<br>
&nbsp;&nbsp;&nbsp;&nbsp; anchor tag)</font></p>
<p><font face="Verdana">Here is a sample hypertext reference in a file called
US.html:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; &lt;A HREF=&quot;MaineStats.html&quot;&gt;Maine&lt;/A&gt;</font></p>
<p><font face="Verdana">This entry makes the word Maine the hyperlink to the
document<br>
MaineStats.html, which is in the same directory as the first document.</font></p>
<p><font face="Verdana"><b>Relative Pathnames Versus Absolute Pathnames</b></font></p>
<p><font face="Verdana">You can link to documents in other directories by
specifying the relative<br>
path from the current document to the linked document. For example, a link<br>
to a file NYStats.html located in the subdirectory AtlanticStates would be:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; &lt;A HREF=&quot;AtlanticStates/NYStats.html&quot;&gt;New
York&lt;/A&gt;</font></p>
<p><font face="Verdana">These are called relative links because you are
specifying the path to the<br>
linked file relative to the location of the current file. You can also use<br>
the absolute pathname (the complete URL) of the file, but relative links are<br>
more efficient in accessing a server.</font></p>
<p><font face="Verdana">Pathnames use the standard UNIX syntax. The UNIX syntax
for the parent<br>
directory (the directory that contains the current directory) is &quot;..&quot;.
(For<br>
more information consult a beginning UNIX reference text such as Learning<br>
the UNIX Operating System from O'Reilly and Associates, Inc.)</font></p>
<p><font face="Verdana">If you were in the NYStats.html file and were referring
to the original<br>
document US.html, your link would look like this:</font></p>
<p><font face="Verdana">&nbsp;&nbsp;&nbsp; &lt;A HREF=&quot;../US.html&quot;&gt;United
States&lt;/A&gt;</font></p>
<p><font face="Verdana">In general, you should use relative links because:</font></p>
<p><font face="Verdana">&nbsp; 1. it's easier to move a group of documents to
another location (because<br>
&nbsp;&nbsp;&nbsp;&nbsp; the relative path names will still be valid)<br>
&nbsp; 2. it's more efficient connecting to the server<br>
&nbsp; 3. there is less to type</font></p>
<p><font face="Verdana">However use absolute pathnames when linking to documents
that are not<br>
directly related. For example, consider a group of documents that comprise a<br>
user manual. Links within this group should be relative links. Links to<br>
other documents (perhaps a reference to related software) should use full<br>
path names. This way if you move the user manual to a different directory,<br>
none of the links would have to be updated.</font></p>

