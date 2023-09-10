# FlexBox_Photo_Gallary_App
First, create the HTML structure for your photo gallery. You can use a simple unordered list (<ul>) to organize your images:
CSS Styling:

Next, create a CSS file (styles.css) to apply styles to your gallery using Flexbox:
In the CSS code:

We reset the default list styles and remove padding/margin from the <ul> element.
The .gallery class is set to display: flex to create a flex container.
flex-wrap: wrap allows the items to wrap to the next line when there isn't enough space in the container.
Each <li> represents an image in the gallery and is styled with a specific width and margin.
The images inside the gallery are made responsive with max-width and a hover effect is added to scale the image slightly when hovered.
Additional Customization:

You can further customize the styles, layout, and animations as per your preferences. You can also add captions or additional information to each image by modifying the HTML structure inside each <li>.

Remember to replace "image1.jpg", "image2.jpg", etc., with the actual file paths of your images.
