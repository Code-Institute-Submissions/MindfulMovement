# Mindful Movement Website

Mindful MOvement is a fictitious Yoga studio that focuses on wellness and balance through the transformative power of yoga, mindfulnessm and meditaition.

You can fine the live site [here](https://luminus.github.io/MindfulMovement/)

![Preview of the site on various screens](https://i.imgur.com/16LEqal.png)

# User Experience (UX)

## User Stories

- As a user, I want to be able to understand the business brand at a first look.
- As a user, I want to be able to see results that have been achieved by others.
- As a user, I want to be able to see the available instructors
- As a user, I want to be able to contact someone to ask about the services on offer and how I can benefit from them.
- As a user, I want to be able to be able to find the business location and operating hours.

## Design

### Colour Scheme

![Colour Scheme](https://i.imgur.com/XXG0Pm5.png)
I wanted to stick to a muted colour palette for this site, utilizing the white background as much as possible, while introducing the green hue for that sense of calm and tranquility.

### Typography

- 'Montserrat' is the font used throughout the site with 'sans-serif' as a fallback. This font is simple and easy to read while adding a modern quality.
- It is the same font used in the business name/logo. I used different weights to emphasise different aspects of the content.

### Imagery

Visual representation is an important part of the user experience for this project, used to draw a potential client in.

The images used throughout are intended to elicit a sense of calmness, minduflness, and confidence in your body's ability to move through the world.

### Overall Feel

The main objective in creating the site was to have it look elegant and simplistic while still providing the user with all of the information they may need. Green hues help to provide a sense of calm and the liberal use of white/negative space depicts openness and the space for growth.

# Features

## Current Features

- Fully responsive design on all devices.
- Navigation menu collapses on smaller screens for more compact design.
- Email address in the footer will launch the default email app.
- Phone number in the footere will launch the dialer app on mobile devices.
- Form submission works via the Code Institute Form Dump
- Form validation in place with all fields required.
  - Email field will look for valid email addresses
  - Phone field will look for valid phone numbers only and will accept a minimum of 9 and maximum of 10 digits

# Technologies Used

## Languages Used

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
- [CSS3](https://en.wikipedia.org/wiki/CSS)

## Frameworks, Libraries & Programs Used

- [Font Awesome](https://fontawesome.com/) used for icons.
- [Google Fonts](https://fonts.google.com/) used to import the 'Montserrat' font.
- [Google Maps](https://www.google.ie/maps/) used to import business location to the page.
- [GitHub](https://github.com/) used to host repository.
- [VS Code](https://code.visualstudio.com/) used to develop project and orgainse version control.
- [GitHub Pages](https://pages.github.com/) used to deploy the site.
- [XML-Sitemaps](https://www.xml-sitemaps.com/) used to create an XML sitemap.
- [Favicon.io](https://favicon.io/favicon-generator/) used to generate the favicon.
- [TinyPNG](https://tinypng.com/) used to compress and optimize images.
- [Am I Responsive?](https://amiresponsive.co.uk/) used to capture an image of the site on various device sizes.
- [imgur](https://imgur.com/) used for hosting images that I didn't want hosted in the repository.
- [Lighthouse](https://developers.google.com/web/tools/lighthouse) for performance review.
- [PowerMapper](https://www.powermapper.com/) used to check compatibility with older browsers.
- [Responsinator](https://www.responsinator.com/) used to ensure the site was responsive on different screen sizes. The responsinator site is missing a TLS certificate, but ignoring the warning allows the site to still be usable for testing.

# Testing

## Validating

After major commits, and at the completion of the project, I used the following websites to ensure that my code was free from errors:

- HTML - https://validator.w3.org/
- CSS - https://jigsaw.w3.org/css-validator/

## Testing User Stories from (UX) Section

- _As a user, I want to be able to understand the business brand at a first look._
  - The hero and about sections look good on all devices and establish the brand clearly.
- _As a user, I want to be able to see results that have been achieved by others._
  - The Gallery section shows clients expressing themselves and enjoying the freedom in their body in various poses.
- _As a user, I want to be able to see the available instructors_

  - The instructors section shows a cross-section of instructors that are available, which increases the chances that a prospective client will find someone that looks like them or has a similar body type to them.

- _As a user, I want to be able to contact someone to ask about the services on offer and how I can benefit from them._

  - The contact form allows a user to send a message to the business detailing their interest in the services offered or asking questions that can help them determine whether this is a good fit.

- _As a user, I want to be able to be able to find the business location and operating hours._
  - The Map shows up on all devices and is interactive, the business address is also clearly spelled out in the footer. Clicking on the phone number in the footer will cause the default phone dialer app to initiate a call to the business.

## Further Testing

### Personal Testing

Through devices that I have at home/readily available to me, I was able to continuously test on:

#### Phone:

- Honor 8X
  - Google Chrome
  - Brave
  - Firefox
- iPhone 8
  - Safari

#### Tablet

- iPad 9.7"
  - Safari

#### Computer

- MacBook Pro 16"
  - Arc
  - Brave
  - Opera
  - Mozilla Firefox
  - Safari
  - Vivaldi

#### Responsinator

Responsinator helped provide insight into how the site would appear on various devices, which was useful considering I only have access to a limited set of devices.

### Lighthouse

Lighthouse was a helpful tool for checking where I was having issues with the performance of the site.
![Lighthouse Results](https://i.imgur.com/VFDKHRv.png)

I'm happy with the outcome of the perfomance review. It highlighted a number of potential optimizations:

- _Performance_
  - While it's possible to shave **1s** of load time my switching to next-gen image formates like WebP and AVIF, I decided to stick to the JPG files I already have in place since I already optimised them via TinyPNG and the site loads fast enough on all of the devices I tested with.
- _Accessibility_
  - Apparently, the background and foreground colours do not have the best contrast, which can make it difficult for some users to use the site properly. That's something to keep in mind for future projects.
- _SEO_
  - Supposedly, 25% of the Google Maps buttons are not sized correctly, which would make it difficult for users to correctly tap a sepcific location when browsing on a mobile device. As this isn't really a concern for this project, I've left it unaddressed, but it's definitely worth paying attention to going forward.

### PowerMapper

I used PowerMapper to check how compatible the site is across different browsers that I don't have access to.

![PowerMapper Results](https://i.imgur.com/ekWZ5Uo.png)

Going by this report, all of the major browsers support all of the features I've used in this project.

# Deployment

## Deployment through GitHub Pages

This site was deployed through GitHub Pages using the following steps:

1. Log into [GitHub](https://github.com/).
2. Locate the [repository](https://github.com/Luminus/MindfulMovement/).
3. Locate the settings option along the options bar.
4. Locate GitHub Pages options towards the bottom of the page.
5. In 'Source' dropdown, select 'Main' from the branch options.
6. Click the save button.
7. The site is now published though it may not be accesible straight away.
8. The site URL will be visible on the green bar under the section header. This will remain there permanently and you can refer to it at any time.

## Cloning Project

1. Log into [GitHub](https://github.com/).
2. Locate the [repository](https://github.com/Luminus/MindfulMovement/).
3. Click the 'Code' dropdown above the file list.
4. Copy the URL for the repository.
5. Open the Terminal on your computer.
6. Change the current working directory to the location where you want the cloned directory.
7. Type `git clone` in the CLI and then paste the URL you copied earlier. This is what it should look like:

- `git clone https://github.com/Luminus/MindfulMovement.git`

8. Press Enter to create your local clone.

# Credits

## Media

- All images were sourced from [Unsplash](https://unsplash.com/)

## Content

- I used CHatGPT to generate the content in the about section
- The quote in the hero image and the one in the about section are from Jon Kabat-Zinn. "Where You Go, There You Are" is one of his bestselling books.

## Acknowledgements

- Thanks to my wife and kids for giving me the space to work on this and understanding when daddy was busy and couldn't come to play.
- A massive thank you to my mentor Antonio Rodriguez for the helpful guidance as I worked through this project and all of the helpful resources that let me focus on the task at hand and put my best foot forward.
