##Selector identification

Identify the selectors in each style and what HTML element(s) they target.
Also, which of these examples have errors? What are they?

###1
```
p {
  color: white;   
}

 P: is the selector 
 also, P is the HTML element defines a paragraph and make it white. 

```

###2
```
span {
  padding: 15px;
}

 span :  is the selector 
 also, span is the HTML element use it to do changing in part of a text
```


###3
```
table td {
  color: #222;
}


Table , Td : are the selector
Table , Td are html elements to define a table and cell 
It is working without (,)  , but I see is better to add it  
```

###4
```
.lede-section #left-side {
  position: absolute;
}

lede-section #left-side : are the selectors


define equal styles for all html elements with the same class name= 'lede-section' .
define an unique id for an  html element with ID = 'left-side'
  
  The correct way to write this 
  
   .lede-section , #left-side {
  position: absolute;
}
  
```

###5
```
#section-9 {
  display: block
  text-decoration: underline;
  font-weight: bold;
}
#section-9: is the selector 
The selected html element with ID='section-9' 
 Correction : after display: block ; 
```

##What's different about the following three selectors?

###6
```
.fewd25-page-section .another-class {
  text-align: center;
}
```


###7
```
.fewd25-page-section, .another-class {
  text-align: center;
}
```


###8
```
.fewd25-page-section.another-class {
  text-align: center;
}


First and third selectors will not do any changes in page while when we add (,) like the second one will do the change and working correctly 
```
