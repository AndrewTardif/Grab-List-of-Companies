# Grab-List-of-Companies
Steps I took to grab and filter a large list of companies for potentially cold calling.

Step 1: Google list of companies in your area

<img src="https://github.com/epicsaxgandalf/Grab-List-of-Companies/blob/89f61a5052083d9fe94be1b44a7e0e47717118e3/List%20of%20Companies.png" width="500">

This ^^^^^^^^ is an example of a site I quickly found using google.

It's definately a long list of about 50-60 which has descriptions, logos, etc. Which is great for the site and looks nice, but is horrible for compiling a list across multiple sites without having to type out(copy and paste) each and every one. And just copy-pasting the full page is going to give you a bunch of extra words you don't want. 

Step 2: Find the info you do want

<img src="https://github.com/epicsaxgandalf/Grab-List-of-Companies/blob/e83215f23d45cd9390c1a9fbb56a192cb1cfd15c/inspect.png" width="500">

Here we are going to right click on the title and inspect to grab the class name(also double check if this is unique, most websites i've seen will keep titles as it's own class)

<img src="https://github.com/epicsaxgandalf/Grab-List-of-Companies/blob/89f61a5052083d9fe94be1b44a7e0e47717118e3/List%20of%20Companies.png" width="500">
<img src="https://github.com/epicsaxgandalf/Grab-List-of-Companies/blob/89f61a5052083d9fe94be1b44a7e0e47717118e3/List%20of%20Companies.png" width="500">
<img src="https://github.com/epicsaxgandalf/Grab-List-of-Companies/blob/89f61a5052083d9fe94be1b44a7e0e47717118e3/List%20of%20Companies.png" width="500">
<img src="https://github.com/epicsaxgandalf/Grab-List-of-Companies/blob/89f61a5052083d9fe94be1b44a7e0e47717118e3/List%20of%20Companies.png" width="500">
<img src="https://github.com/epicsaxgandalf/Grab-List-of-Companies/blob/89f61a5052083d9fe94be1b44a7e0e47717118e3/List%20of%20Companies.png" width="500">

Partial Duplicate Formula/Code =if(A1<>"",Countif(A$1:A,left(A1,10)& "*") > 1)
