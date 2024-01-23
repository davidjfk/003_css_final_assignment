# intro

It's now time to lift your CSS skills to a new level with the following CSS challenges. In a real-world scenario,  
you as a developer will likely be given designs made by a UX department that you'll have to convert to code.  
That is exactly what you'll be doing today: you'll be turning a design into code! That means there are going to  
be multiple ways to achieve the desired result. Use your skills to come up with the solution you think is best.  
Recreate each design using HTML and CSS. You should not need to use JavaScript.  

The assignment consists of 3 CSS challenges, each one being a little more difficult than the previous one.  
You are allowed to use our Slack channels to ask any questions to your fellow students.
 

<br/>
<br/>

## General requirements

1. Complete all exercises on a single HTML page.
2. Consistently use SCSS nesting.
3.	Consistently use SCSS variables.
4.	Consistently use SCSS partial imports to separate your SCSS.
5.	The page is not allowed to have horizontal scrolling unless the window is very small (less than 400px).


<br/>
<br/>


## Bonus requirements

Bonus requirements:
1. Use mixins.


## part 1 - testimonial

1. Recreate this design using HTML and CSS.

![Image of Image1](./image/part_1_testimonial.jpg)

2. Footer testimonial - purple/blue: #686de0
3. Page background - gray: #c3cfe2
4. Text background - white: #fff
5. Use a random portrait image. This could be an image of yourself, or you could use a stock-photo

<br/>
<br/>


## Portfolio Grid

In this part, you're going to make a portfolio grid. For now, we will have images in the grid,  
but you could put anything in it. For example, feel free to replace the image of our colleague Niels  
with the testimonial that you made in part 1.

- Watch the following video:  [Play Video](./video/part_2_portfolio_grid.mp4)

1. Page background - gray: #c3cfe2
2. The grid should be responsive on 3 screens: desktop (3 columns), tablet (2 columns), mobile (1 column)
3. When hovering an item in the grid, a button should appear, and the image should slowly fade away.

You do not need any JavaScript. Think back to the pseudo class :hover.  
Placing elements on top of each other is known as "stacking".  
You can achieve this using the CSS attribute position. More about stacking here: [Css-tricks.com about stacking](https://css-tricks.com/how-to-stack-elements-in-css/)

<br/>
<br/>

## Social Media Buttons

Self-made social media buttons are always nice to have. These are very fancy; there's even a little animation!  
You'll be recreating this:  

- Watch the following video:  [Play Video](./video/part_2_social_media_buttons.mp4)


Specifications part 3: Design & interactions:
1. In the video, you can see a green line on the right-hand side. This is the desktop and not part of the website. The buttons are on the very edge of the page.  

2. Colors


        .social-media.blog {
            background-color: #e17b77;
        }

        .social-media.facebook {
            background-color: #3b5998;
        }

        .social-media.twitter {
            background-color: #00aced;
        }

        .social-media.github {
            background-color: #333;
        }

        .social-media.linkedin {
            background-color: #007bb6;
        }

3. Icons
- Option 1: Look up the icons and use them as images in your CSS. this is correct and perfectly fine.
- Option 2: Next level - add the images using ::before using, for example, font awesome:
    * Font Awesome
    * Font Awesome icons  
  
        In this last case, use the following code:
  
            .fa-laptop-code::before {
                content: "\f5fc";
            }
            .fa-twitter::before {
                content: "\f099";
            }
            .fa-linkedin-in::before {
                content: "\f0e1";
            }
            .fa-facebook-f::before {
                content: "\f39e";
            }
            .fa-github::before {
                content: "\f09b";
            }
