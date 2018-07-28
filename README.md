# material_bootstrap
designing a website with material bootstrap kit

Link for tutorial: https://mdbootstrap.com/corporate-website-lesson-1/

# Container
There are two types of containers one is the simple .container(leaves margin in all sides) and the other is .container-fluid(spreads across the whole page width)

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

# Card
Bootstrap provides card for almost everything, checkout the card docs for more details

# Footer
I cannot find footer base code on mdbootstrap.com, but the tutorial has the code
link: https://mdbootstrap.com/corporate-website-lesson-2/

# Slight Changes
In our current project we are changing our footer container from .container-fluid to just 
.container because that suits well for our project

Our current navbar spread across the whole page, to fix that we can simply contain our whole 
navbar into a container .container(leaves margin in all sides) .container-fluid(spreads across 
the whole page width)

# Spacing
Note: In MDB 1 rem = 16 px

so mdb has many shortforms for adding space to elements for example

.mt-1 means margin-top: 0.25rem or 4px  (16 / 4 = 0.25)
Similarly

.pt-2 	padding-top: 0.5rem
.mx-5 	margin left and right 1.25rem
.my-4 	margin top and bottom 1rem
.m-4	margin top bottom left right 1rem
.mr-1	margin-right: 0.25rem