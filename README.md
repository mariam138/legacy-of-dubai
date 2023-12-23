# Legacy of Dubai: From Sands to Skyscrapers
## Introduction
**Legacy of Dubai** is a website which goes into depth on the history of Dubai, from its beginnings as a Dessert emirate into the luxurious, glamorous City we know of today. The site is targetted towards people who want to learn more about Dubai and its rich history, especially those who are planning to visit Dubai or have already done so. **Legacy of Dubai** will be a useful site for tourists and non-tourists alike who take great interest in Middle Eastern history and culture.

## Design
### Fonts

The header fonts have been set to **Montserrat** for a clean but slightly regal look. As it is a part of the sans serif family, it also allows accessibility for those with visual impairments. I used [fontjoy.com](fontjoy.com) to help pair a similar font to **Montserrat** to be used for the body of the text. The font that was generated was **Mukta**, keeping the theme cohesive, but allowing the pages to still be clean and readable.
![Screenshot 2023-12-19 at 21 53 19](https://github.com/mariam138/legacy-of-dubai/assets/150139337/16e55cef-8427-4a0b-b133-d1b277a4bd44)

### Colour Scheme

I wanted the colour scheme of the website to reflect the colours of the desert, as it is what I most commonly associate Dubai and the Middle East with. I first went onto use [Adobe's colour generator](https://color.adobe.com/explore) and searched for colour schemes based on the search term "Dubai". I found a colour scheme generated from a picture of the Dubai skyline at sunset with the desert in the foreground. From there, I chose the chocolate brown colour (Hex code: #73351F) to be the main colour.
![Screenshot 2023-12-21 at 16 49 16](https://github.com/mariam138/legacy-of-dubai/assets/150139337/d1bcd012-fdfe-4c1b-8507-94d6a0c7449b)

I then used [ColorSpace](https://mycolor.space/) to generate a colour scheme using the chocolate brown colour as the main colour. I decided upon this colour scheme which includes a lighter brown colour, a beige-cream colour and a blue as an accent colour.
![Screenshot 2023-12-21 at 17 06 37](https://github.com/mariam138/legacy-of-dubai/assets/150139337/c274b7a4-580a-4fc4-8c90-871ccd10eada)

To make sure these colours would be accessible to those who are visually impaired, I used [EightShapes' contrast grid](https://contrast-grid.eightshapes.com/). The brown and beige colours can be used interchangeable along with white and black. However the blue accent colour (Hex code #00B2FF) only passes the contrast test with Black, so for this I have decided to use it only as an accent colour with buttons for example. ![Screenshot 2023-12-21 at 17 13 08](https://github.com/mariam138/legacy-of-dubai/assets/150139337/53c65327-1b95-4206-a170-ce81ec4ba1a2)

The lighter brown colour (Hex code #AB654C) however does not pass with the other colours, and only recieves a AA pass when used with black. So I decided to not use this colour throughout my project. 

## Testing

### Bug Fixes

- Upon initial deployment onto github pages, none of the CSS styling appeared to be showing, despite showing on thge local server. When checking the code for the link to the CSS style sheet in the HTML index page, the file paths appeared to start with a forward slash (/), making them absolute file paths rather than relative file paths. Removing the forward slash fixed the problem, allowing the CSS  styling to show on the deployed webpage. 

- After styling the hero image for the home screen, I checked to see whether it was responsive for all screen sizes. Viewing the home page on my laptop screen showed there to be some whitespace on the right of the page, leading to a horizontal scroll bar. This would lead to a bad user experience. 
![Screenshot 2023-12-23 at 15 03 51](https://github.com/mariam138/legacy-of-dubai/assets/150139337/d3d65a43-5d60-4c2e-8000-22db718f0d68)

To fix this, I used the **overflow-x** property to hide the horizontal scroll bar. This helped to get ride of the white space on the screen. 
![Screenshot 2023-12-23 at 15 33 10](https://github.com/mariam138/legacy-of-dubai/assets/150139337/8eed11cb-78f2-4417-99eb-9907466849c3)


## Credits
### Content

- The Burj Al Arab favicon is by [Icons8](<https://icons8.com/icon/RnOkEfOBUH9P/burj-al-arab>)

### Code

- The template code to insert the favicon is from [W3S Schools](https://www.w3schools.com/html/html_favicon.asp)
- The code to create a sticky header and push the footer to the bottom is from the [Code Institute Love Running project](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LRFX101+2023_Q2/courseware/e805068059af42af87681032aa64053f/7525117e5cd144daa2a7b0c57843bbee/)
- The code to create the dropdown toggle for mobile navigation is from the [Code Institute Love Running project](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LRFX101+2023_Q2/courseware/e805068059af42af87681032aa64053f/7525117e5cd144daa2a7b0c57843bbee/)
- The code to make the toggle on the mobile navbar is from [css-tricks](https://css-tricks.com/inclusively-hidden/)

