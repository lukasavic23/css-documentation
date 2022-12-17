# Kingdom CSS Documentation

Best way to write CSS - for everything to be consistent across.

###  1. Order of writing css

Inside of a class, CSS properties should be written in the following order.

```
.some-class {
     position:relative;
     left: 10px;
     top: 10px;
     right: 10px;
     bottom: 10px;
     
     display: flex;
     flex-direction: column;
     align-items: center;
     justify-content: space-between;
     gap: 10px;
     
     width: 10px;
     height: 10px;
     
     margin: 10px;
     padding: 10px;
     
     background-color: black;
     background-repeat: no-repeat;
     border: 1px solid black;
     
     color: white;
     font-family: Arial;
     font-size: 10px;
     font-weight: bold;
     font-style: italic;
     text-align: center;
     text-decoration: none;
     
     border-radius: 10px 10px 10px 10px;
     text-shadow: 10px 10px 5px 10px black;
     box-shadow: 10px 10px 5px 10px black inset;
     
     overflow: hidden;
     z-index: 10;
     cursor: pointer;

}
```

### 2. Class name convention

Class name should be written as ```kebab-case```.

**wrong**&#x1F34E; .someClass

**wrong**&#x1F34E; .some_class

**RIGHT**&#x1F34F; .some-class / .some-class-name


### 3. Use specific CSS property instead of shorthand

For example, if you need background color to be changed don't use ```background```. Instead use ```background-color``` to be more specific and don't accidentally overwrite some other property.

**wrong**&#x1F34E; background: black;

**RIGHT**&#x1F34F; background-color: black;

### 4. Avoid ```!important``` whenever you can

Try not to use ```!important``` in your own project. When you need to overwrite yourself it's mostly badly written css. 




