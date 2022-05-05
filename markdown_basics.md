Normal Text

**Bold text**

*Cursive text*

~~Strikethrough~~

# H1 Heading
## H2 Heading
###### H6 Heading

If you push a heading to GitHub it will give them ID's, allowing to link directly to an item.


## **Images**
![alt text](https://picsum.photos/200/200)

Or refer to an image anywhere in the code

![alt text for cat][cat]

[cat]: https://images.unsplash.com/photo-1514888286974-6c03e2ca1dba?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1686&q=80 "unamused cat"

fig and figcaption don't exist - just write HTML

## **Lists**
+ UL
+ + UL 2
+ + + UL 3

## Steps
1. Item A
2. Item B
3. Item C
   * Item C2
        This is inline, since there is no * :)



## **Line breaks**

If you want a full line break, use br. <br>
If you leave it out, things will stay inline.
Like this!

## **Horizontal Rules**

If something needs to be underlined, use at least three dashes in succession and a rule underneath.

---
<br>

## **Block Quotes**

> You can only do basic markdown in here.
> 
> -- **Me**

<br>

---

<br>

## **Code**

```JS
Write the name of the language next to the backticks to show what language you are writing.

var x = 100;
```

You can also use inline code with `var single_backticks = 100;`

Or show the changes you have made with - and + in combination with `diff`.

```diff
var y = 100;
-      var y = 200;
+      var y = 300;
```

```diff 
    background {
-   color: green;
+   color: red;
    }
```

## **Tables**
The : make for left/center/right alignment.

|This   |Is |A  |Table|
|:---|:---|:---|:---
|With|Some|Content|Yay|


## **Checkboxes**
* [x] This item is done
* [ ] This item is not done yet :(
