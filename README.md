# Comfy House In Las Terrenas, Dominican Republic

I created the website for people who like traveling to exotic places and for those for whom intimacy and privacy are of great importance. I want my guests to feel in my home as their own. My house is very spacious so it's perfect for people who don't like crowds in hotels. 
In addition, there are plenty of attractions in the area, so everyone will find something interesting for themselves. Pets are welcome. We often can't take them with us and that's why I give guests the opportunity to spend their holidays with their pets at my place.

![Screenshot of my website with different screen sizes](https://github.com/MarzenkaS/Comfy-House-New/blob/main/docs/main.view.png?raw=true)

## Features


### Existing Features

1. _Navigation Bar_
  
- Navigation bar is available on all 4 pages. Responsive navigation bar includes links to Home page, Gallery, Booking page and the fourth page, which is a confirmation of the booking request. 
- Allows to easily move between pages.

![Navigation Bar](https://github.com/MarzenkaS/Comfy-House-New/blob/main/docs/nav.bar.png?raw=true)

1. _Main section of Home page_

- Contains three sections. The first section is a general description of the guest offer. Description of the house and for whom it is addressed. The second section describes the possibilities that the house and the surrounding area have to offer. The third section concerns the prices for adults, children and pets.
- It helps to understand who the website is created for

![Main content](https://github.com/MarzenkaS/Comfy-House-New/blob/main/docs/main.content.png?raw=true)

1. _Audio_ 

- Music allows you to feel the atmosphere and imagine yourself on the island.

![Audio file](https://github.com/MarzenkaS/Comfy-House-New/blob/main/images%20for%20readme/audio.png?raw=true)

4. _Google map_

- The map shows the exact location of the house.
- Allows also the user to check the area.

![Google map](https://github.com/MarzenkaS/Comfy-House-New/blob/main/docs/google.map.png?raw=true)

1. _Contact_

- The exact address of the house, telephone number and e-mail address are included. Can be founded on first, third and fourth page.

![Contact](https://github.com/MarzenkaS/Comfy-House-New/blob/main/images%20for%20readme/contact.png?raw=true)

6. _Footer_

- The Footer section includes links to different social media sites like facebook, Instagram or YouTube.
- Can be found on each page.
- Each link will open to a new tab.
- Provides the potential guest with more information about the house and its surroundings.
- The user can read the opinions of other people.

![Footer](https://github.com/MarzenkaS/Comfy-House-New/blob/main/images%20for%20readme/footer.png?raw=true)

7. _Gallery_
   
- The photo gallery shows the user the look of the house inside and out as well as the garden and beach views.
- Photo gallery divided into 3 sessions. The first showed the house, the second the beach and the third the  garden with a swimming pool
- After seeing the photos, the user knows what to expect upon arrival.

![Gallery house](https://github.com/MarzenkaS/Comfy-House-New/blob/main/images%20for%20readme/gallery1.png?raw=true)
![Gallery beach](https://github.com/MarzenkaS/Comfy-House-New/blob/main/images%20for%20readme/gallery3.png?raw=true)

8. _Booking page_

- Allows the user to send an inquiry regarding the preferred number of nights in an easy and quick way.

![Request form](https://github.com/MarzenkaS/Comfy-House-New/blob/main/images%20for%20readme/reservation.png?raw=true)

9. _Form feedback page_

- Confirmation of sending the request by the user.

![Feedback](https://github.com/MarzenkaS/Comfy-House-New/blob/main/images%20for%20readme/confirmation2.png?raw=true)

## Testing

### Validator testing

1. _HTML W3C validator_ 

I had wrong value for attribute src on element audio. There was space which I deleted. Second error was tittle which I gave for iframe for google map. So deleting tittle fixed it.

![HTML with error](https://github.com/MarzenkaS/Comfy-House-New/blob/main/docs/html.error.png?raw=true)
![HTML fixed](https://github.com/MarzenkaS/Comfy-House-New/blob/main/docs/html.fixed.png?raw=true)

1. _CSS W3C validator_

I forgot to add unit px after number. 

![CSS with error](https://github.com/MarzenkaS/Comfy-House-New/blob/main/docs/css.error.png?raw=true)
![CSS fixed](https://github.com/MarzenkaS/Comfy-House-New/blob/main/docs/css.fixed.png?raw=true)

### Lighthouse

I had a problem to get a high performance above 90. I had a few mistakes. 
- My audio file was too big so I used a converter for mp3 files. 
- Another problem was the lack of aria-label for the iframe that I used to embed the google map on my home page. 
- I also had to compress backgroud image.

![Lighthouse home desktop](https://github.com/MarzenkaS/Comfy-House-New/blob/main/docs/Lighthouse.png?raw=true)






### Other browsers

I tested my website on Google Chrome, Microsoft Edge and Mozilla Firefox. Works on all browsers. Unfortunately, I couldn't check personally on Safari web browser. Below screenshot from Mozilla Firefox.

### Different screen sizes

Below are examples of how my website looks on different devices.

### Wave

I used WAVE Evaluation Tool to evaluate web accessibility within my browser. The result below.
### Bugs

1. Once my html code went through the validator I had many bugs because some of my images had space in name. So after removing spaces in names all errors disapeared.
 
2. Radio Button issues.There is  a Radio Button option on my Booking page. There are 2 options: YES or NO, and I was supossed to choose only one option but problem was that I could choose both at the same time.

3. Another problem was comming from iframe where I embedded Google Map. I didn't have aria-label. 

4. I had problems also with size for audio file and bacakground image on Home page. So both I compressed and thanks to that i achieved higher points when I used Lighthosue.

5. Issues with Media Query for large and medium screen sizes. 


## Deployment

The site was deployed to GitHub. In the GitHub repository I went to Settings and choosed Pages section. From the source section drop-down menu, selected Deploy from a branch. Below I set up Main for branch and I saved it. After that the page was automatically refreshed.

Here you can see live link [Comfy House](https://marzenkas.github.io/Comfy-House-New/)

## Credits

If i get stucked in a project I used [Code Institute](https://learn.codeinstitute.net/dashboard), [W3Schools](https://www.w3schools.com/) or [Mozilla Developer](https://developer.mozilla.org/en-US/) to find needed information when writing code or CSS.

### Content

1. The text for the home page was my idea as well as the design of each page.
2. The icons in the footer come from [Font Awesome](https://fontawesome.com/)
3. I used two fonts which were taken from [Google Fonts](https://fonts.google.com/)

### Media

1. Bacground image for home page i took from [picjumbo.com](https://picjumbo.com/search/+beach) 
2. Bacground image for Gallery, Booking and Form Fedback page were taken from [pixabay.com](https://pixabay.com)
3. Images for house come from [pexels.com](https://www.pexels.com)
4. Images for beach, garten and swimming pool are private.
5. Map was taken from [Google Maps](https://www.google.com/maps)
6. Audio file for home page was taken from [pixabay.com](https://pixabay.com/pl/music/bije-lofi-study-112191/)
9. I needed to compress all my images and for that I used [tinypng](https://tinypng.com/)
9. For compressing audio file I needed [xconvert.com](https://www.xconvert.com/)