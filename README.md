MARKDOWN Implementation
=======================

Practicing markdown
-------------------

# Header 1
## Header 2
## Header 3

Here is an unordered list:
- Normal
- **Bold**
- *Italic*
- ~Striked~

Here is a boxed ordered list:
> 1. First
> 2. Second

Other list with subitems:
1. First
    First text
2. Second
    * First Second
    * Second Second
3. Third
    >Quote block
    >>Idented block

Link: [Google](http://www.google.com)

Code: `markdown.map(&:to_s)`

Code again:
```
markdown.each do |mark|
  mark + mark
end
```

Image:
![Markdown](./images/markdown.jpeg)

