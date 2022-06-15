# Code Refactor Starter Code

# Challenge 1- Horiseon Accessibility Ticket

Codebase needed to follow accessibility standards to best optimize website for search engine. 

# Body

Moved the body elements up to the top of the stylesheet so they would be easy to find since they affect most of the index.html file. In addition, renamed the previous (p) element to (body p) as to link directly with the body itself. 

# Header 

Updated the header section to include comments marking where the unordered list and list elemets started. Also, updated the stylesheet to include comments in order to organize the css file by section. I then relabeld each child element to link directly with the parent header element. I also deleted extra wording, for instance, the display for the list items (li) were placed as inline-block when based on the previous styleesheet setting inline would work fine. 

# Hero Section

Labeled the hero style section with a comment for both css and html file. Also sepreated the code from the content of the following section as to differentiate the hero section from the rest of the webpage. 

# Content Section
Spaced out the content section class from the rest of the content information. Included comments to differentiate between the different sections of the content space. Kept the content class as well as the float-left and float-right classes. But relabled the search engine optimization, online reputation management and social media marketing as one class which i called (content-body). From there I joined their respective stylesheet code into three sections rather than previous nine. Those class selectors are (.content-body), (.content body img), and (content-body h2).

Furthermore, I added alt's to all three images so that screen readers can describe them to website visitors, if need be. 

# Benefits Section
I went ahead and deleted the class designations for each of the 3 benefits within this section. Instead, I just used the one class selector labeled (benefits) as the parent and refereneced the style sheet using that class for the styling of the (div), (h3), and (img).

I also designated an alt of (alt="") for the images since they are not neccesary to understand the content of the website.

# Footer
I added comments to the footer section as to differentiate form the rest of the code.

# Screenshot of Finished HTML Site
![Top of finished webpage including header and hero](images/Horiseon-1.jpg)
![Middle of finished webpage wich included the content and the benefits sections](images.Horiseon-2.jpg)
![Bottom of finished webpage which just includes the footer](images.Horiseon-3.jpg)