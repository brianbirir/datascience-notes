# Excel: Append Text

## Ampersand

To add text to an existing value use an ampersand `&`:

```
="text"&cell_value
```

or vice versa:

```
=cell_value&"text"
```



For example, if the value of cell B2 is **"example@yahoo"**:

```
=B2&".com"
```



## Concatenate

But you can also use the `CONCANTENATE()` function whose syntax is:

```
=CONCANTENATE(text1,[text2],......)
```



For example:

```
=CONCATENATE(B2,".com")
```

