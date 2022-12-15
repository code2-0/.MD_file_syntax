# ***How to write README.md file?***

Currently you are reading a README.md `.md` file. Let's learn how to write `.md` file.

---
---
## **Header create:**
To create header you have to use # (# your text).
If you know HTML syntax it will be easy to you:
 
 Syntax:
```md
  # = h1 (Most bigest heading)
  ## = h2 (2nd bigger)
  ### = h3 (3rd bigger)
  #### = h4 (4th bigger)
  ##### = h5 (5th bigger)
  ###### = h6 (and 6th bigger)
```
#### **`Output:`**
  # (#)= h1 (Most bigest heading)
  ## = h2 (2nd bigger)
  ### = h3 (3rd bigger)
  #### = h4 (4th bigger)
  ##### = h5 (5th bigger)
  ###### = h6 (and 6th bigger)
---
---

## **Make text bold:**
To make text **bold** you have to use ** (double star). And you have to wrap the text with **.

Syntax:
```
  **YEEE! I'm bold text.**
```
There is another option to make text bold, use __ (dobule underscore) and wrap your text with __. 

Syntax:
```
  __YEEE! I'm bold text.__
```
#### **`Output:`**
  __YEEE! I'm bold text.__
 - [x] **NOTE:** There should not have a `space` begining and ending of **(dobule star). If have it will not work: ** it will not work **.

 ---
 ---

## ***Text Italic:***
To make text _italic_ you have to use *(single star) or, _ (single underscore) and don't use `space` begin and end.

Syntax:
```
  _This is italic text_
  or,
  *This is italic text*
```
#### **`Output:`**
  *This is italic text.*

---
---

## Make text **Bold +** ***Italic:***
To make text bold and italic apply together you have to use ***(triple star) or, ___(triple underscore).

Syntax:
```
***italic bold text***
or,
___italic bold text___
or,
**_ italic bold text_**
```
#### **`Output:`**
**_italic bold text_**

---
---

## **Make text highlight:**
To make text `highlighted` you have to use ``.

Syntax:
```
  `I'm highlighted text`
  ```
#### **`Output:`**
  `I'm highlighted text.`

---
---

## **Make Order List:**

To make a order list follow below syntax:
```
  1. Order item one.
  1. Order item 2.
  1. Order item 3
  1. order item 4
```
#### **`Output:`**
  1. Order item one.
  1. Order item 2.
  1. Order item 3
  1. order item 4

---
---

## **Make Unorder List:**
To make list you have to use *(single star) or, -(single hyphen) or, +(plus) and `space` at the begining of line.

Syntax:
```
  - I'm list item using (-)
  or,
  * I'm list item using (*)
  or,
  + I'm list using (+)
```
#### **`Output:`**
  - I'm list item using (-)
  * I'm list item using (*)
  + I'm list item using (+)
  
---
---

## **List With Checkbox:**
To make checkbox list you have to use * `space` [x] for checked and [ ] for unchecked item.

Syntax:
```
  * [x] Checkbox list item
```
#### **`Output:`**
  * [x] Checkbox list item
  * [ ] Checkbox list item
  * [ ] Checkbox list item

---
---

## **Use Link Text:**
To make text with link use this 
[Link text](your link)

Syntax:
```
[Go to google](https://google.com)
```
#### **`Output:`**
***[Go to google](https://google.com)***

---
---

## **Create Table:**

```
| Name          | Passion        | Email                      |
| :------------ | :------------- | :------------------------- |
| `Keya Payel`  | Actor          | myemail123@gmail.com       |
| `Asik Ali`    | Web Developer  | myemail234@gmail.com       |
```
#### **`Output:`**
| Name          | Passion        | Email                      |
| :------------ | :------------- | :------------------------- |
| `Keya Payel`  | Actor          | myemail123@gmail.com       |
| `Asik Ali`    | Web Developer  | myemail234@gmail.com       |

---
---

## **🔗 Links Design**
To use well organized and designed link you have to use an `api` there would be many options. I use this one. You can use this.
```
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://your-link.com/)

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/)

[![twitter](https://img.shields.io/badge/instagram-F00000?style=for-the-badge&logo=instagram&logoColor=white)](https://twitter.com/)
```
#### **`Output:`**

[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://personal-portfolio-ashik.web.app/)

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/md-ashik-ali/)

[![twitter](https://img.shields.io/badge/twitter-1BA9DB?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/md_ashik_ali)

[![twitter](https://img.shields.io/badge/facebook-0035BC?style=for-the-badge&logo=facebook&logoColor=white)](https://web.facebook.com/ashik.ali0/)

[![twitter](https://img.shields.io/badge/instagram-FB0508?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/md_ashik_ali_khan/)

[![twitter](https://img.shields.io/badge/codepen-222?style=for-the-badge&logo=codepen&logoColor=white)](https://codepen.io/ali-ashik)


## **Badge:**
Design your badge with this link: modify this `api` change `<LABEL>, <MESSAGE> and <COLOR>`
[`https://img.shields.io/badge/<LABEL>-<MESSAGE>-<COLOR>`]
```
![](https://img.shields.io/badge/YEEE-Successssss-blue)
![](https://img.shields.io/badge/YEEE-Successssss-F00)


```
#### **`Output:`**
![](https://img.shields.io/badge/YEEE-Successssss-blue)

![](https://img.shields.io/badge/YEEE-Successsss-00f)

![](https://img.shields.io/badge/NOOP!!!-Failure-f00)

---
---

## **Create Line:**
To create horaizontal line you have to use ---(triple hyphen/more) or, ___(3 underscore/more).

Syntax:
```
  ---
  or,
  -----------------
  or,
  ___
  or,
  __________________
```
#### **`Output:`**
---
--------------
_______________
___

## **Write Code:**
If you want to write code and want to show as like as code editor than use this syntax:
```bash
    ```js ==>> (language_name)

        //script here
        function recursion (x) {
          if(x===0){
            return 1;
          } else{
            return x * recursion(x-1);
          };
        };

        const recursion_of_five = recursion(5);
        console.log(recursion_of_five);

    ```
```
#### **`Output:`**
```js
    //script here
    function recursion (x) {
      if(x===0){
        return 1;
      } else{
        return x * recursion(x-1);
      };
    };

    const recursion_of_five = recursion(5);
    console.log(recursion_of_five);

```
---
---
## **ADD ScreenShort:**

syntax:
```
![App Screenshot](https://your-short-link)
```
#### **`Output:`**
![App Screenshot](https://github.com/code2-0/TestingImages/blob/main/img/code2-0.png)

---
---

## **Strikethrough:**
To make text Strikethrough use below syntax:
```
  ~~Strikethrough~~
```
#### **`Output:`**
~~Strikethrough~~

---------------
---------------

## **Reference:**

```
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.
```

#### **`Output:`**
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.

---------------------
---------------------

## **Mathmatical Expressions:**

```
 $\sqrt{3x-1}+(1+x)^2$
```
#### **`Output:`**
 $\sqrt{3x-1}+(1+x)^2$

---------------
---------------

##  **chart:**
Here is a simple flow chart:

```mermaid
  graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
```


h
