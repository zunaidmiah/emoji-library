# emoji-library
This is one of best emoji library.

Official documentation of emojionarea link. 
[click here](https://github.com/mervick/emojionearea)

You can easily implement emoji library in you project.
You need to follw only 3 steps

<b>Step 1</b><hr><br>
First you need to import emojionarea css and js file which are has in this project .
<br>
OR, You will import their cdn which are below: 
```
<link rel="stylesheet" href="file/to/path/css/emojionearea.min.css">
<script type="text/javascript" src="file/to/path/js/emojionearea.min.js"></script>
```
<br><br>
<b>Step 2 </b><hr><br>
You must need to add index.html file in your project or you can add textarea only in your project. Here i give you my html blade file below :
<br>
do yow want html blade structure? <br>[click here](https://github.com/Zunaid420/emoji-library/blob/master/index.html)

<br><br>
<b>Step 3</b><hr><br>
Than last step you just need to add javascript code in your index file> This code also i provide below : <br>
````<br>
<script>
$(document).ready(function() {
$("#emojionearea1").emojioneArea({
pickerPosition: "left",
filtersPosition: "bottom",
tonesStyle: "bullet",
autocomplete: true,
hidePickerOnBlur: true,
searchPlaceholder: "Search",
buttonTitle: "",
saveEmojisAs: "unicode",
inline: true
});
})
</script>
<br>````
<br>Hurray! So,now your project is ready to use emoji.<br>
Thanks,<br>
Zunaid Miah<br>
