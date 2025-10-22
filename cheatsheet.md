Assignment 1 Ugurcan Yesilyurt

# Basic Formatting
* Headings
    * To use Headings you need to put `#` in front of a text.  
        Less `#` makes the text bigger.  
        **For example:**  
        ##### Hello
        #### Hello
        ### Hello
    
* Paragraphs & line breaks  
 
    * For Paragraphs you need to put a space by using enter between lines.

        For line breaks you need to enter two spaces at the end of a sentence in the line before.  
        Like this:  
        This is a apple.(__)  
        It is red.  
        Underlined in this case are the spaces.  
        These are called soft breaks.  
    
        **For example:**  
        This is a apple.  
        It is red.  
    
        You can also use `<br>` at the end of a line.  
        This is a apple.<br>
        It is red.  
    
* Bold  
    * To use bold surround words or sentences with `**`.  
        **For example:**  
        **Hello**  
        **This is a apple.**  

* Italic  
    * To use italic surround words or sentences with `_` .  
        **For example:**  
        _Hello_  
        _This is a apple._  

* Striketrough  
    * To use strikethrough surround words or sentences with `~~` .  
        **For example:**  
        ~~Hello~~  
        ~~This is a apple.~~  

* Inline code
    * To use inline code surround words or sentences with \` .  
        **For example:**  
        click `here`

# Lists
* Unordered Lists  
    * To use unordered lists use `*` in front of the word.  
        **For example:**  
        milk, soup, bread turns into
        * milk
        * soup
        * bread    

* Ordered Lists  
    * Ordered lists can be used, when typing 1. instead of stars.  
        **For example:**  
        milk, soup, bread turns into
        1. milk
        2. soup
        3. bread  
    
    * These are called hard breaks.    

* Nested Lists  
    * Nested lists are lists with sub lists.  
        These can be used, when pressing 2 spaces in front of the sub list item.  
        **For example:**  
        milk products, milk, yogurt, drinks, water, coke turns into  
        * milk products 
          * milk  
          * yogurt  
        * drinks  
          * water  
          * coke  
    * you can use `*` , `-` , `+` or numbers      

# Links and Images
* Inline links  
    * Inline Links are Hyperlinks, you can use a text and hide a link underneath.  
        To use fill in these: `[any text](website link)` 
        **For example:**  
        [Google](https://www.google.de)    

* Reference-style links
    * To use reference-style links you need to set up a variable, which you can use in different places.  
        To use fill in these:   
        `[any text][variable]`      

        `[variable]: website link here`  
        
        **For example:**  
        If you want to buy it [click here!][amazon]  
          
        [amazon]: https://www.amazon.de  
    
    * A paragraph is necessary in this case.    

* Images  
    * Images are almost the same as links. Only difference is the `!` in front of the variable.   
        Like this `![any text](website link)`  
        **For Example**    
       
        ![big cat](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b0/Bengal_tiger_%28Panthera_tigris_tigris%29_female_3_crop.jpg/330px-Bengal_tiger_%28Panthera_tigris_tigris%29_female_3_crop.jpg)  

* Image and link combination  
    * You can combine images and links when filling out these:    
        ```[![alt-text](image-url)](link-url)```  
        **For example:**
        [![big dog](https://upload.wikimedia.org/wikipedia/commons/thumb/6/68/Eurasian_wolf_2.jpg/960px-Eurasian_wolf_2.jpg)](https://de.wikipedia.org/wiki/Wolf)  
    * By clicking the image you visit the website.  

# Code & Technical Content  
* Inline Code  
    * To use inline code surround the text with \` .  
        **For example:**  
        Use `this`.  

* Fenced code blocks  
    * Fenced code blocks are used to write down code in markdown.  
        The result is clean and can be highlighted.    
\```sprache  
code here   
\```  

* Syntax highlighting (languages like Python, R, HTML, etc.)  
     **For example:**  
 ```python
def hallo(): print("Hallo Welt") 
```
```html
<p>Hallo Welt</p>
```
```r
x <- 5 print(x) 
```

# Quotes & Notes  
* Blockquotes  
    * Blockquotes are used, when highlighting a text or quote.  
        To use it put `>` in front of the text.  
        **For example:**  
        > quote here 
  
* Nested blockquotes  
    * Nested blockquotes are subquotes under the initial quote.  
        In this case your using two `>` in front of the sub quote.  
        **For example:**
        > quote here  
        >
        >> subquote here  
        >> subquote here  
        >  
        > quote here    
  
    * Paragraphs need also need `>` .  
  
* Blockquotes with formatting  
    * You can also use formatting in blockquotes.
        **For example:**  
        > _quote here_  
        >
        >> **suqoute here**  
        >> ~~subquote here~~ 
        >  
        > `quote here`  
  
# Tables  
* Basic Tables  
    * You can create tables by using `|` .  
    * `-` is seprating the headers with the actual table.  
        **For example:**  

        | Apples   | Price   |
        |----------|---------|
        |        5 |      2€ | 
        |       10 |      3€ |  

* Alignment  
    * Alignment is used in the second row.  
        `:---`	left-aligned  
        `:---:`	centered  
        `---:`	right-aligned  
        **For example:**  

        | Apples   | Price   |
        |:--------:|:-------:|
        |        5 |      2€ | 
        |       10 |      3€ |   

* Complex tables
    * You can use multiple rows or columns, text anlignment, line breaks inside a cell, diffrent formatting, code blocks or inline code.  
        **For example:**    

        |Student        |Class                                |Student ID|
        |--------------:|------------------------------------:|------------:|
        |**Max**        |_Arts_                               |`123132`     |
        |~~**Tim**~~  |~~_Gymnastics_~~ <br> ~~_Psychologie_~~|~~`123552`~~ |   
  
# Task Lists  
* Checkboxes  
    * You can use checkboxes with `-[ ]` or `-[x]`.   
        **For example:**  
        -[ ] Task 1  
        -[x] Task 2  
        -[x] Task 3    

# Dividers & Layout   
* Horizontal rules    
    * You can seperate text with lines by using at least three `-`, `*` or `_` . 
        **For example:**  
        Text1
        ---
        Text2

* Line breaks
    * Line breaks are used with two spaces or `<br>`  
        **For example:**  
        Text1 <br> Text2    

# Online and collaborative editors  
* Markdown-based editors  
    * Stackedit, Typora, Markably, MD-View
    * Most important features for me are live preview, support for GFM (GitHub Flavored Markdown) and Syntax Highlighting.    

# Platform/Tool Specific: GitHub  
* Task list  
    * Can be used with `-[ ]` or `-[x]`.    

* Mentioning users  
    * Can be used with `@username` or `@organisation/team`    

* Automatic linking of issues/PRs  
    * mentioning a known issue for example `#123` will automatically link to that issue or repository.    

* Emoji shortcodes  
    * Emoji shortcodes can be used by typing `:emoji_name:`.  
        **For example:**  
        :+1: