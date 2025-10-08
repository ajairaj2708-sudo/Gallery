# Ex.08 Design of Interactive Image Gallery
# Date:05.10.2025
# AIM:
To design a web application for an inteactive image gallery with minimum five images.

# DESIGN STEPS:
## Step 1:
Clone the github repository and create Django admin interface.

## Step 2:
Change settings.py file to allow request from all hosts.

## Step 3:
Use CSS for positioning and styling.

## Step 4:
Write JavaScript program for implementing interactivity.

## Step 5:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Multiple Images Enlarge on Click</title>
<style>
  .clickable-image {
    width: 150px;
    height: auto;
    margin: 10px;
    cursor: pointer;
    transition: transform 0.3s ease;
  }
  .enlarged {
    transform: scale(2);
    z-index: 10;
    position: relative;
  }
</style>
</head>
<body>

<img class="clickable-image" src="https://preview.redd.it/appreciation-post-thank-you-jaddu-v0-aw1q6xisamye1.jpeg?width=1080&crop=smart&auto=webp&s=40704480595f535362fb59dca843ffdd56be67d1" alt="Image 1" />
<img class="clickable-image" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcShVH8oEKh5waEfovs4xpnHnBZBWHpYY2QdNA&s" alt="Image 2" />
<img class="clickable-image" src="https://im.rediff.com/cricket/2022/sep/08vk.gif" alt="Image 3" />
<img class="clickable-image" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTwBC3xtOYNNaz9wkPw3NAI9efbP_7UfhtE_g&s" alt="Image 4" />

<script>
  const images = document.querySelectorAll('.clickable-image');

  images.forEach(img => {
    img.addEventListener('click', () => {
      img.classList.toggle('enlarged');
    });
  });
</script>

</body>
</html>
```
# OUTPUT:
![alt text](<Screenshot (20).png>)

# RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
