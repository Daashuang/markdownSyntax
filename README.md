# Markdown Syntax  
This is a quick guide to some common Markdown syntax.  

[Headling](#Headling)  
[Horizontal Rule](#Rule)  
[Line Break](#Line)  
[Blockquotes](#Blockquotes)  
[Emphasis & Delete_line & Escape](#Emphasis)  
[Lists](#Lists)  
[Link & Image](#Link)  
[Code](#Code)  
[Table](#Table)  
[mathematical formula](#mathematical)


<span id="Headling">Headling</span>
---
- Use **#**.

```
# 1 headling(ctrl+1)
## 2 headling(ctrl+2)
### 3 headling(ctrl+3)
#### 4 headling(ctrl+4)
##### 5 headling
###### 6 headling
```
# 1 headling(ctrl+1)
## 2 headling(ctrl+2)
### 3 headling(ctrl+3)
#### 4 headling(ctrl+4)
##### 5 headling
###### 6 headling

<span id="Rule">Horizontal Rule</span>
---
- Three or more  - , * , _ .  

```
---
***
___
<hr>
```

---
***
___
<hr>

<span id="Line">Line Break</span>
---

```
This is line1.
This is line1, too. When we have line feed in a sentence but it dose not have line feed at the outcome. Add a blank line make the outcome has blank line,too.

so this is line3. add a <br> ,And This sentence is on the line4. I will add two blanks in the end of this sentence.  
So **two blanks** can make the line break.
```
This is line1.
This is line1, too. When we have line feed in a sentence but it dose not have line feed at the outcome. Add a blank line make the outcome has blank line,too.

so this is line3. add a <br> ,And This sentence is on the line4. I will add two blanks in the end of this sentence.  
So **two blanks** can make the line break.

<span id="Blockquotes">Blockquotes</span>
---
- Use **>**.  
\>This is a quote (ctrl+q) 
1  
2
\>>nest  
\>>nest2  
\>end quote

>This is a quote (ctrl+q) 
1  
2
>>nest  
>>nest2  
>end quote

<span id="Emphasis">Emphasis & Delete_line & Escape</span>
---

```
**Bold**(ctrl+b)  
__Bold__   
<strong>Bold</strong>  

*Italic*(ctrl+i)  
_Italic_   
<em>Italic</em>  

~~delete this line~~  
<del>DELETE THIS LINE</del>  

\#\*\\\`\_\{}\[]\()\#\+\-\.\!
```

**Bold**(ctrl+b)  
__Bold__   
<strong>Bold</strong>  

*Italic*(ctrl+i)  
_Italic_   
<em>Italic</em>  

~~delete this line~~  
<del>DELETE THIS LINE</del>  

\#\*\\\`\_\{}\[]\()\#\+\-\.\!

<span id="Lists">Lists</span>
---
- Disorder: *** , + , -**. 

```
* 1
+ 2
- 3
* Item 1
* Item 2
  * Item 2a
  * Item 2b
- def
  - dfjsdf
  - fsdfj
```

* 1
+ 2
- 3
* Item 1
* Item 2
  * Item 2a
  * Item 2b
- def
  - dfjsdf
  - fsdfj


- Order: **Numbers**(Numbers can be disorder while the outcome orders).

```
1. Item 1 
2. Item 2
3. Item 3
   1. Item 3a
   1. Item 3b
   2. Item 3c
   7. Item 3d
```
1. Item 1 
2. Item 2
3. Item 3
   1. Item 3a
   1. Item 3b
   2. Item 3c
   7. Item 3d

<span id="Link">Link & Image</span>
---
- Link: **\[text](url) \[text](url "titel")**

```
<https://www.google.com/>  
[hyperLinkname](yourlink)  
[Google](https://www.google.com/)  
[Google](https://www.google.com/ "Point this link you can see") 
```
<https://www.google.com/>  
[hyperLinkname](yourlink)  
[Google](https://www.google.com/)  
[Google](https://www.google.com/ "Point this link you can see") 

- **\[text]:url "titel" **,then you can use \[text] in the current file without writing the url.


```
[Google]: https://www.google.com/ "Google" 
[Google] This link has been defined before(previous line) 
blablabla[Google]blablabla
``` 
[Google]: https://www.google.com/ "Google" 
[Google] This link has been defined before(previous line)   
blablabla[Google]blablabla 

- **!\[text](url "title")**.

```
![online_image](https://static1.squarespace.com/static/5a70fa14e45a7c7dd2fadad0/t/5a92d15071c10b0d6533fd94/1519497953854/1977_heroes.jpg?format=300w   "David Bowie")
```

![online_image](https://static1.squarespace.com/static/5a70fa14e45a7c7dd2fadad0/t/5a92d15071c10b0d6533fd94/1519497953854/1977_heroes.jpg?format=300w   "David Bowie")

- Also,we can define the image first then use the \[image]. This exmple add a link to the image. We can add an image with a link to the Youture video like this.

```
[image]:https://static1.squarespace.com/static/5a70fa14e45a7c7dd2fadad0/t/5a92d15071c10b0d6533fd94/1519497953854/1977_heroes.jpg?format=300w   "David Bowie22222222"
[![image]](https://www.davidbowie.com/heroes)
```
[image]:https://static1.squarespace.com/static/5a70fa14e45a7c7dd2fadad0/t/5a92d15071c10b0d6533fd94/1519497953854/1977_heroes.jpg?format=300w   "David Bowie22222222"
[![image]](https://www.davidbowie.com/heroes)

- Use HTML.

```
<p align="center">
<img   src="https://static1.squarespace.com/static/5a70fa14e45a7c7dd2fadad0/t/5a92d15071c10b0d6533fd94/1519497953854/1977_heroes.jpg?format=300w"    title="Resize" width="200" height="200"  > 
</p>
```

<p align="center">
<img   src="https://static1.squarespace.com/static/5a70fa14e45a7c7dd2fadad0/t/5a92d15071c10b0d6533fd94/1519497953854/1977_heroes.jpg?format=300w"    title="Resize" width="200" height="200"  > 
</p>

- Add local device image(picture can not show here):

```
![localImage](file:///A:/320.jpg)   
 ```
![localImage](file:///A:/320.jpg)  

<span id="Code">Code</span>
---
- Use **tab ,or 2 blanks** before every code line:

```
	print("I love learning new things")
```
	print("I love learning new things")

- Use **\`code`** (short code):

```
`print("I love learning new things")`
```

`print("I love learning new things")`

- Use three \```(on a line by itself), it also supports syntax highlighting(language name write after first \```. Not every md editor supports, but it can highlight on Github ): 

\```python  
for i in range(10)  
	print(i)  
\```

```python
for i in range(10)
	print(i)
```
- Use this

```
<pre>
for i in range(10)
	print(i)
</pre>
```

<pre>
for i in range(10)
	print(i)
</pre>

<span id="Table">Table</span>
---
- Use **-** to separate name and element, **|** to separate element...

```
name|age
---|---
n1|a1
n2|a2
```
name|age
---|---
n1|a1
n2|a2

```
NAME | AGE
---- | ---
N1   | A1
N2   | A2
```
NAME | AGE
---- | ---
N1   | A1
N2   | A2

- Default: left justifying , (**:--:**):middle, (**--:**): right

```
Thetitle | alwaaays | inthecentre
-------- | :------: | ----------:
LLL      | MMM      | RRR
```
Thetitle | alwaaays | inthecentre
-------- | :------: | ----------:
LLL      | MMM      | RRR

- Use other md syntax:

```
name                                       | country   |
------------------------------------------ | :-------: |
[google](https://www.google.com/ "Google") | worldwide |
[baidu](https://www.baidu.com/ "Baidu")    | China     |
```
name                                       | country   |
------------------------------------------ | :-------: |
[google](https://www.google.com/ "Google") | worldwide |
[baidu](https://www.baidu.com/ "Baidu")    | China     |

<span id="mathematical">mathematical formula</span>
---
- First write this:
```
<script type="text/javascript"
   src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>
```  
- Then, **$$Tex_formula$$** shows a big formula and it will on a line by itself. **\\(Tex_formula\\)** shows a formula that can be in a santence.  

<script type="text/javascript"
   src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>

```
$$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$$
```

$$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$$

```
This is a sentence. The formula is:\\(x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}\\) , do you know this formula?
```

This is a sentence. The formula is:\\(x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}\\) , do you know this formula?

Markdown is very easy to use if we use it frequently.   
Last Word, GFM(Github Flavored Markdown) is a little bit different from the general markdown, like line breaks...But don't worry, We can fix it by google...
GOOD LUCK!

3/11/2018 5:53:10 PM  (ctrl+t)

