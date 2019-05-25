# Why?
Stackblitz does not support uploading image assets to their projects

## Option 1 (preferred)
1. Navigate to the `images` folder in my GitHub repository:
> https://github.com/carballosa/images
2. Click the button `Upload Files` 
3. Drag and drop the image files into the drop section of the page
4. Click on the button `Commit changes`
5. Click on the desired image from the list
6. Right-click the image preview and select the action `Copy image address` 
>  ```https://https://github.com/carballosa/images/blob/master/images/<image filename>?raw=true```
7. In the Stackblitz project, paste this URL in the value of the `src` attribute of the html `img` elements

## Option 2
1. Navigate to the `Issues` section of this repo
2. Click the button `New issue` 
3. Drag and drop the image files into the section `Write`
4. Copy the image URL that should look like this:
>  ```https://user-images.githubusercontent.com/12849860/58243805-ad9bc280-7d51-11e9-8182-68b45b48e38b.png```
5. Close the page `without` actually creating the issue
6. In the Stackblitz project, paste that URL in the value of the src attribute of my img elements
