# aammui-fileUploader

This is file uploader plugin  written in jquery.

## Requirement 

* Bootstrap 4
* Jquery 

## Example

```
<link href="src/css/file.upload.css" rel="stylesheet">
<div class="col-md-6">
	<div class="form-group text-center ">
		<div id="featured_image" class="w-100 btn btn-primary">
		Set Avatar
		</div>
		<span id="featured_image-image"> 
		</span>
	</div>
	<div class="form-group text-center">
		<div id="cover" class="w-100 btn btn-primary">
		Set Cover
		</div>
		<span id="cover-image">
			<img src="..default image url.." class="img-fluid">
		</span>
	</div>
</div>

<script type="text/javascript" src="src/js/file.upload.js"></script>
<script type="text/javascript">
	$('#cover').aammui({
		baseUrl:'/',
		imageId:'cover-image',
		serverUploadUrl:'/media/upload',
		serverAllFileUrl:'/getfiles'
	});
	$('#featured_image').aammui({
		baseUrl:'/',
		imageId:'featured_image-image',
		serverUploadUrl:'/media/upload',
		serverAllFileUrl:'/getfiles'
	});
</script>



```
