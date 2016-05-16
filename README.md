# Adding Files to Nitrous

## Why add a file to Nitrous
We've seen how we can add images to our websites that are hosted on the web already, but what if we want to add our own images like a selfie we took on our phone? 


It's important when you're building websites with HTML and CSS that you save the images in your project directory as opposed to using images from the internet. What if the website that stores the image you're using deletes it? What if the url for that image changes? Suddenly your website has a broken image because you relied on someone else to maintain your image. It's best to own the images you use in your website.

Really, we need the image saved in Nitrous in the same directory (folder) where our work is. If I'm working on a website about how much I love popcorn, I want to have a directory dedicated specifically to that individual website. I might have a lot of other files and directories inside the main one, but thats okay. Any images that I personally take and want to include in my website need to be stored in my the main directory for my project. So how do I save an image in Nitrous?


## Let's Get Started

Really, we need the image saved in Nitrous in the same directory (folder) where our work is. If I'm working on a website about how much I love popcorn, I want to have a directory dedicated specifically to that individual website. I might have a lot of other files and directories inside the main one, but thats okay. Any images that I personally take and want to include in my website need to be stored in the main directory for my project.

If you're working on a lab, and want the image to show up in a lab, you'll want to save the image in the directory of that lab.

So how do I save an image in Nitrous?


### Click the Gear button in the file browser.

<img src="https://s3.amazonaws.com/after-school-assets/nitrous-add-image.png" alt="Click gear icon">

### Click Upload Files

<img src="https://s3.amazonaws.com/after-school-assets/nitrous-add-image-upload-file.png" alt="upload file">

### Drag/Drop the Images you want to include, or use the file browser to choose them.

<img src="https://s3.amazonaws.com/after-school-assets/nitrous-add-image-browse.png" alt="browse">

### Click Upload

<img src="https://s3.amazonaws.com/after-school-assets/nitrous-add-image-upload.png" alt="upload">

### Move the image to the project directory for the website you're working on. 

It's really important that the image be located in your project directory and not in the `nitrous` directory. If you deployed your website, and made it live on the internet, you would deploy the directory of that specific project. The image sitting in the code directory wouldn't be deployed and wouldn't show up on your website.

If you're working on a specific lab or project, then you'll move the image into the directory of that lab (ie. if you're working on `html-playground`, then the image should be stored inside the `html-playground` directory, and you'll need to move it there. The directory where the image should live will change depending on what lab you're working on.)

The image `IMG_8200.JPG` is saved in the main directory in Nitrous, which is named `nitrous`. Inside of the `nitrous` directory there is a directory called `code`. Both `code` and `IMG_8200.JPG` are located in the same directory. Let's say I wanted to move `IMG_8200.JPG` into the code directory.

In terminal, enter `mv IMG_8200.JPG code`. 

The `mv` command moves a file. You have to tell Nitrous what file to move (in this case `IMG_8200.JPG`) and then where to move it `code`. 

You can use the `mv` command as many times you like to continue to move a file around.

If you're not super comfortable with terminal, you can also move the image by using the file navigator on the left side of Nitrous, by clicking on that image and dragging it and dropping it in the directory where you want it.

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/hs-adding-files-to-nitrous' title='Adding Files to Nitrous'>Adding Files to Nitrous</a> on Learn.co and start learning to code for free.</p>
