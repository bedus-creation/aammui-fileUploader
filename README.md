# aammui-fileUploader

This is file uploader plugin  written in jquery.

You have to Implement the server type code


## Requirement 

* Bootstrap 4
* Jquery 

## Example

```

<!DOCTYPE html>
<html>
<head>
    <title>Bootstrap 4 FileUploader</title>
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.0.13/css/all.css" integrity="sha384-DNOHZ68U8hZfKXOrtjWvjxusGo9WQnrNx2sqG0tfsghAvtVlRW3tvkXWZh58N9jp" crossorigin="anonymous">
    <!-- Bootstap Css-->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
	<link rel="stylesheet" href="src/css/fileupload-1.1.css">
</head>
<body>
	<div class="offset-md-3 col-md-6 mt-4">
		<div id="asduhfudg" class="w-100 btn btn-secondary" >Set Image</div>
    </div>
    <!-- Bootstap Section-->
    <script
    src="https://code.jquery.com/jquery-3.3.1.min.js"
    integrity="sha256-FgpCb/KJQlLNfOu91ta32o/NMZxltwRo8QtmkMRdAu8="
    crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
    <script type="text/javascript" src="src/js/fileupload-1.1.js"></script>
	<script>
		$('#asduhfudg').aammui({
			baseUrl:'https://bedus-creation.github.io/fileupload/',
			input:"cover",
			serverUploadUrl:'/media/upload',
			serverAllFileUrl:'src/filelist.json'
		});
	</script>
</body>
</html>




```

### View Online Demo [Here](https://bedus-creation.github.io/fileupload)
