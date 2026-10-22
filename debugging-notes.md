# My image debugging notes

## Provided debugging exercise

- Incorrect path: image/workstation.png
- Corrected path: images/workstation.jpg
- The two errors I found: The 2 errors I found were the "image" path where it should be images, and the "png" path where it should be jpg.
- Evidence I used to locate the errors: I used what I had learned on the index.html page to help me make my decision.
- What I saw after saving and refreshing: After saving and refreshing, I saw the image pop up.

## My own image test

After an image works in index.html, temporarily change its path, observe the result, and restore it.

- The path I deliberately changed: I changed the images part of "images/workstation.jpg" to just "imag" to break it.
- What happened in the browser: When I loaded the browser, I saw a broken photo with the alt text displayed in place of the photo.
- How I restored the working image: I restored the working image by fixing the "imag" part of "image/workstation.jpg", and I fixed that part by editing it tso it can be "images" instead of "imag" (EX: imag/workstation.jpg -> images/workstation.jpg).

## Reflection

The src attribute tells the browser where to get the image from, and what the image is.

Alt text matters because it helps aid those who cant really see images well, and it provides a bit of context as to what the image is if the image fails to load.

I preserved the image proportions by editing content of the image with the "width" and "height" 
