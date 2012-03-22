[jQuery Star Rating Plugin](http://irfandurmus.dev/projects/jquery-star-rating-plugin/) 
======================================================================================

How to use 
--------------------------------------

### Simple usage
	$('.container').rating();

### Using with callback method and user options
	$('.container').rating(function(vote, event){
		// console.log(vote, event);
	});`

### Using with user options
	$('.container').rating({}, function(vote, event){
		// console.log(vote, event);
	});

### Using with ajax
	$('.container').rating(function(vote, event){
		// write your ajax code here
		// For example;
		// $.get(document.URL, {vote: vote});
	});

### Example HTML
	<div class="container">
		<input type="radio" name="example" class="rating" value="1" />
		<input type="radio" name="example" class="rating" value="2" />
		<input type="radio" name="example" class="rating" value="3" />
		<input type="radio" name="example" class="rating" value="4" />
		<input type="radio" name="example" class="rating" value="5" />
	</div>