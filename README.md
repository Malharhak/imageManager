To use the imageManager :

. Create an object containing your images references and url (each image will be then called by its reference) : 
	var myImages = {

		"reference" : "url",
		"reference2" : "url2",
		"player" : "characters/player.png"
    }

. Fill the imageManager with your images
	imageManager.pushImages(myImages) 

. Check if the images are loaded :
	imageManager.isLoaded(); // True if loading is finished, else false

. If your images are loaded, use them !
	imageManager.get('player');

Note that you can access an image's width/height with imageManager.get('image').width;