# learning-essentials
* these are some of my essentials to start with while learning how to program and learn web development.Although these are kind of basic things that we should be aware of to enjoy programming.

# How to write a markdown easily

### Markdown cheat sheet

# Headings 
---

* use the no of # signs to indicate the strength of the heading
* the strength of font decreases with the increase in number of # signs 
* ###### example : 
  *  # Heading H1(#)  
  * ## Heading H2(##)
  * ### Heading H3(###)
  * #### Heading H4(####)
  * ##### Heading H5(#####)
  * ###### Heading H6(######)
  

# Bold text
---
*  we use ** to say that the text bolding starts with this and also ends with this. we **should not have trailing spaces** at the end of the statement or sentence that we place it as bold.
###### example:
**bold text**

# Italic text
---
* we use single * at the ends of the sentence to say that the text enclosed should be in italic.Again similar to the bold text we *should not have trailing  spaces* in the italic icons.
  
###### example:
*italic text*


# Blockquote
---
* we use > symbol to say that it is in blackquotes
###### example:
> blockquote text

# ordered list:
---
* just writing the order of the user's choice. **indentation matters**
###### example:

1. first item
2. second item
3. third item

     or 
a. first item
b. second item
c. third item


# Unordered list
---
* hyphen symbol indicates it as a list item in the ul. **indentation matters**
  
- first item
- second item
- third item

# code 
---
* we use back ticks for showing some text in code block. it is a single line code block.

###### example:
`let i  = 0;
let j = 1; 
for(lert i = 0;i<100;i++,j++){
    console.log("this is happening",i);
    if(j==10){
        console.log("this is the value of j required.");
    }
}
`

# horizontal rule
---
* we use --- to say that it is to draw a horizontal line !
* ---


# links:
---

* ###### example:
* [link to go to some location or url]('https://www.google.com')

# Image : 
---

* similar to the links tag but we use ! infront of [] 
* ###### example:
* ![alt text goes here]('https://image.com/cat')



# fenced code
---
* this is a multi line code block to display!
```
let person = {
  "firstName": "John",
  "lastName": "Smith",
  "age": 25,
}
```


 # Task list
 ---
 * indentation matters i writing a list of items as we know. here also applies the same but here we use [ ] to show that there is some thing that is to be checked . it acts as a checkbox!
  
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

# Heading Id
---
* You can link to headings with custom IDs in the file by creating a standard link with a number sign (#) followed by the custom heading ID.

###### example:
* [Heading IDs](#heading-ids)	

# strike through : 
---
* You can strikethrough words by putting a horizontal line through the center of them. The result looks like this. This feature allows you to indicate that certain words are a mistake not meant for inclusion in the document. To strikethrough words, use two tilde symbols (~~) before and after the words.
  
###### example:
* ~~The world is flat.~~ We now know that the world is round.


# tables:
---
* To add a table, use three or more hyphens (---) to create each column’s header, and use pipes (|) to separate each column. You can optionally add pipes on either end of the table.

###### example:
| Syntax | Description | another heading |
| --- | ----------- | ---------- |
| Header | Title | another title |
| Paragraph | Text | another text! |


# Syntax Highlighting
---
* Many Markdown processors support syntax highlighting for fenced code blocks. This feature allows you to add color highlighting for whatever language your code was written in. To add syntax highlighting, specify a language next to the backticks before the fenced code block.

###### example:

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```


