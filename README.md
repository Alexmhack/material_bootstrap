# material_bootstrap
designing a website with material bootstrap kit

Link for tutorial: https://mdbootstrap.com/corporate-website-lesson-1/

# Container
There are two types of containers one is the simple .container and the other is .container-fluid

# Row
Just like simple rows, rows in layout are horizontal columns where to split layout horizontally

# Column
Bootstrap gives you a total of 12 columns from left to right spread across the whole row
These columns can be distributed in a number of ways but all columns must contribute together to 
make complete 12 columns

.col-md-8		.col-md-4
.col-md-7		.col-md-5
.col-md-6		.col-md-6
.col-md-4		.col-md-4		.col-md-4
.col-md-3		.col-md-3		.col-md-3		.col-md-3

To make the column layout work you need to use the either of the containers first and the rows and 
cols inside it

# Image
For a good website we can add image in one column and some button text in the column next to it
The responsive class for image is the .img-fluid

To give more visual effects like a subtle shadow and hover and wave effect, we have to wrap our 
image tag in divs with certain classes like .view .overlay .z-depth-1-half and our image should 
have this class .card-img-top and an another div inside the first div but after our image

# Button
We can make any link a button by simply adding the class .btn and then to add descriptive colors
we have .btn-primary .btn-danger etc. you can look for whole button docs on mdbootstrap.com