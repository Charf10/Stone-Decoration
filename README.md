![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# Stone Decoration
Stone Decoration is a website developed for the customer who has a small factory of stone which is used for decoration of homes, offices, gardens, etc. TYhe client is looking to expend his newtwork by advertising his products.

## Features
In this section, different parts of the website are breifly shown with and describe with images.

### Menu Bar 
Featured on all three pages, the full responsive menu bar includes links to the Home page, Gallery and Sign Up page and is identical in each page to allow for easy navigation.

![menu](https://github.com/Charf10/Stone-Decoration/blob/main/assets/images/menu.jpg?raw=true)


### The main image
The image includes a photograph with text overlay to with a motivation quotation to keep training to get the results that they want.
This section introduces the user to the stone decoration website with beautiful chimney to grab client attention by attracting them.
![main image](https://github.com/Charf10/Stone-Decoration/blob/main/assets/images/main-image.jpg?raw=true)


### Motivation/reason section
The company features section will allow the client to see the characteristics of the company.
This should encourage the custmer to consider buy such as products.
![Company features](https://github.com/Charf10/Stone-Decoration/blob/main/assets/images/Company-logo.jpg?raw=true)


### Group Class times
This section will allow the user to see exactly when the meetups will happen, where they will be located and how long the run will be in kilometers.
This section will be updated as these times change to keep the user up to date.
![class_times](https://github.com/KhanRana/community_boxing_club/blob/main/assets/media/class_times.png)

##About Us
This section describes clubs ambition and who they are motivating others to get fit and strong.
![about_us_page](https://github.com/KhanRana/community_boxing_club/blob/main/assets/media/about.png)

## Gallery
The gallery will provide the user with supporting photos and videos to see them in training. 
This section is valuable to the user as they will be able to easily identify the types of events the organisation puts together.
![gallery_page](https://github.com/KhanRana/community_boxing_club/blob/main/assets/media/gallery.png)

## The Membership Page
This page will allow the user to get signed up to Love Running to start their running journey with the community. 
The user will be able specify if they would like to take part in road, trail or both types of running. The user will 
be asked to submit their full name, email address, age and reasons for joining the club.
![membership_page](https://github.com/KhanRana/community_boxing_club/blob/main/assets/media/membership.png)

## Features Left to Implement
Further details such as address & telephone number can be added to the footer if the website goes to a club owner.
There is always room for improvement, and there is number of other feature that can be added: the one eature I did 
have was fighter or list of ameature fighter on the website.

## Testing
The project is responsive to different screen sizes including mobile and tablets.

### Validator Testing
- HTML
No errors were returned when passing through the official W3C validator
- CSS
No errors were found when passing through the official (Jigsaw) validator
![index_valid](https://github.com/KhanRana/community_boxing_club/blob/main/assets/media/index_pass.png)
![gallery_valid](https://github.com/KhanRana/community_boxing_club/blob/main/assets/media/gallery_validated.png)
![about_valid](https://github.com/KhanRana/community_boxing_club/blob/main/assets/media/about_pass.png)
![member_valid](https://github.com/KhanRana/community_boxing_club/blob/main/assets/media/membership_validated.png)
![css_valid](https://github.com/KhanRana/community_boxing_club/blob/main/assets/media/css_validated.png)

The website membership form is also validated for type.
[type_valid](https://github.com/KhanRana/community_boxing_club/blob/main/assets/media/type_check.png)

Finally, the website is also tested by the light house and returned oustanding results.
![light_house_report](https://github.com/KhanRana/community_boxing_club/blob/main/assets/media/lighthouse_report.png)

- Fixed Bugs
There was an error when submitting the membership.html. It turns out we cannot 'required' to a drop down select. 
When the 'required' was removed from the select, html returned no errors.
Footer was moving up the screen on about.html in mobile and tablet view. I have fixed is by sticking it and moving it to the bottom using '100vh'.
Previous small screen bug fix created issue for larger screen use, which now has been fixed by using body 100vh and positioning footer relatively.

## Deployment
The site was deployed to GitHub pages. The steps to deploy are as follows:
In the GitHub repository, navigate to the Settings tab and Pages
From the build and deploymet > from a source > deployment from a branch, main , root > save.
Once the main branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
The live link can be found here - ![](https://khanrana.github.io/community_boxing_club/)

## Credits
- Content
The text for the Home page was taken from healthline.come
Instructions on how to implement form validation on the Membership Form was taught in the program
The icons in the footer were taken from Font Awesome
The website is inpired by various tutorials and websites, including but not limited to the code institute.

- Media
All photos are taken from open source website [UpSplash](https://unsplash.com/images).
All videos are taken from open source website [Pexels](https://www.pexels.com/videos/)
