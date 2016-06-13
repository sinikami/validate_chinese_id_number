# validate_chinese_id_number
this is a jquery plugin which is to validate chinese id number that involves 15 and 18 length


##Usage method

```Javascript

$('#IdCard').CheckIdCard();

$('#IdCard').CheckIdCard({
    success:function(){...},
    failure:function(){...},
    checklength:function(){...}
});


```

##Example:
```HTML

<input type="text" value="" id="IdCard"/> <button type="button" onclick=" $('#IdCard').CheckIdCard()">Check</button>

``` 

