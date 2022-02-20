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
<link rel="stylesheet" href="file/to/path/css/emojionearea.min.css">
<script type="text/javascript" src="file/to/path/js/emojionearea.min.js"></script>
<br>
<b>Step 2 </b><hr><br>
You must need to add index.html file in your project or you can add textarea only in your project. Here i give you my html blade file below :
<br>
<!doctype html>
<html lang="en">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    <!-- <link rel="stylesheet" href="https://cdn.rawgit.com/mervick/emojionearea/master/dist/emojionearea.min.css">
    <script type="text/javascript" src="https://cdn.rawgit.com/mervick/emojionearea/master/dist/emojionearea.min.js"></script> -->
    <link rel="stylesheet" href="emojionearea.min.css">
    <script src="https://code.jquery.com/jquery-3.6.0.min.js" integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4=" crossorigin="anonymous"></script>
    <script src="emojionearea.min.js"></script>
    <title>Emoji Library-emojionarea</title>
</head>

<body>
    <h1>Welcome to Emoji Library-emojionarea</h1>
    <div class="container px-5 mx-5">
        <form>
            <div class="form-group">
                <label for="emojionearea1">Example textarea</label>
                <textarea class="form-control" id="emojionearea1" rows="3"></textarea>
            </div>
        </form>
    </div>

    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>
    -->
</body>

</html>

<br>
<b>Step 3</b><hr><br>
Than last stem you just need to add javascript code in your index file> This code also i provide below : <br>
<!-- ... -->
    <script>
        // $("#emojionearea1").emojioneArea({
        //     container: "#container2" // by selector
        // });
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

Hurray! So,now your project is ready to use emoji.
Thanks,
Zunaid Miah
