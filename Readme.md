# Car Landing Page

This project was one of my first projects that I did from start to finish without any assistance. I really enjoyed creating a pratical project like this that functions like a real landing page for a company giving away a car.

## Objective

I wanted to be able to create a landing page by sticking to these conditions:

1. It must be created only using HTML and CSS (no Javascript).
2. It must only consist of one HTML file (index.html) and one CSS file (styles.css).
3. It must be responsive on mobiles and tablets.

In addition to these 3 conditions, I wanted to ensure it was visually appealing with an obvious call to action.

## Planning

Only being able to use HTML and CSS meant that not much preparation was needed. Creating a repository and using VS Code to create the two files was all I needed.

As for the design of the landing page, I decided to do a giveaway of a car that I created. I used Artificial Intelligence to create an image of an orange sports car on an orange backdrop and also to come up with a name that would suit it (Zenith Strato). I knew there would have to be a section that outlines the conditions of the giveaway, as well as a form to submit details.

## Method

I started with creating the framework for the website, ensuring the header and footer were fixed to the top and bottom respectively, as well as three sections - Home, Rules, and Enter. I feel entirely comfortable with creating the structure for these sections.

I then worked on the CSS for it, to give me a better visual understanding of everything I had completed. Once this was completed, I finished work on the Home section, giving it a call to action that jumped to the last section.

After updating the CSS again, I quickly worked on the Rules section using 3 common requirements for a car giveaway. From there, I developed the last section, which was far trickier than the others due to the form and its CSS rules.

## Challenges

Despite only being a basic project, I ran into several issues that I was able to overcome.

1. **Responsiveness** - This was my biggest problem that I struggled with. At first it looked great on a standard desktop, however shortening the width meant that all my elements were in disarray. As soon as I managed to fix it at a certain width, something else would go wrong. Even shortening the height forced my elements to be all over the place. After spending a lot of time, I managed to get it responsive and clean on all widths and heights.

2. **The CSS of the Form** - I had issues with this, pertaining mainly to the layout of the form. Initially I used flexbox to create the form's structure, however it became a problem when the width was changed. Changing from flexbox to CSS grid helped immenseley as it kept the labels and the inputs in line with eachother.

3. **Car Image** - Thinking I could save some time by not needing Photoshop, I decided to just use the full image of the car and the orange backdrop as the background, and then use CSS to generate the header text and the call to action. This presented no problem at first, however it became an issue when the viewport was different. To get around this, I used Adobe Photoshop to edit the image of the car, by isolating the car. I created a feathered selection and pasted it onto a new transparent background, cropping it to the size of the car itself. This meant I was able to use the car image and place it on my Home section, and just create a linear-gradient background that was orange. This helped as I could move the image around when making it more responsive.

4. **Overall colour scheme** - When it comes to colours, I'm not the greatest. I had an orange car and an orange backdrop - the only thing that seemed to work well was white. The other colours clashed a lot which meant I was stuck with an orange and white theme. I experimented with different shades of orange, as well as blue and yellow, however it all didn't work as well as the plain white.

## What I Learnt 

Even the most basic of projects can teach you a lot. Some of the things that I learnt are as follows.

1. Don't let responsiveness be an afterthought or something that you can fix up at the end of the project. You should be creating the structure of your HTML keeping in mind the varying device widths it would be displayed on. It's much easier to ensure it's responsive as you write the code, rather than going back and having to change HTML code.
2. Try to research different colour schemes prior to deciding on a colour, testing them out to see how they contrast.
3. Use CSS Grid for the form rather than Flexbox.
4. It's far easier to manipulate an image onto a dynamic background, rather than having a background-image.


# Thank you for reading!