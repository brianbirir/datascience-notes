# Excel: Substitute Characters

For example, replacing the colon in a MAC Address with an empty value:



**Formula Syntax:**

```latex
=SUBSTITUTE(TEXT,OLD_TEXT,NEW_TEXT)
```



**Example:**

Convert to upper case (if current value is in lower case) and replace the colon `:` with an empty value; in addition first get the code value for the colon character i.e. `=CODE(LEFT(text))`. Value of cell **B2** is **00:0e:8e:79:ec:0a**

```
=UPPER(SUBSTITUTE(B2,CHAR(CODE(LEFT(":")),""))
```

