# The Monkees Website

The Monkees website(front-end only) has been developed in order to provide current fans and potential fans with quick and easy access to all the latest information about the band.
Users can keep up to date with news and tours information, watch and listen to clips from the bands catalog and any new material as it becomes available, 
learn about the history of the band and it's members, checkout out the latest photos of the band, quickly navigate to the band's social media pages to learn even more about them 
and contact the band in order to book them for an event.

## UX

Since this website is primarly directed at fans of the band, I thought it'd be a good idea to use some of the band's color scheme, namely the reds and blues for major parts of the pages.
Initially I stylized the website reflecting the bands 60s and comic book feel but decided against it at the end, opting for a more modern clean style.

The layout is primarly achieved using flexbox, at the begining I wanted to use the Bootstrap framework but had some difficulty positioning the bands logo in such a way that it would overflow past the 
bottom of the navigation bar and flexbox allowed me to solve that easily. Bootstrap is still used but only to include its inbuilt elements like the modal and carousel.

The first page(home page) presents a user with the most important information, that is the publicity information where a user can book the band for an event, news about the band and
tour information. While the navbar provides the user with links to checkout the bands history, clips or photos.

Mockups in a pdf format and user stories can be found here [UX assets](assets/ux)

The final version of the project differs from the mockups. As I developed the project I would realize that some of the design decisions weren't the right solutions and I would update them on the go.
E.g. For the news items I wanted them presented as smaller elements with 3 of them in a row, a button would expand them to reveal their text content. That would work well if 
the buttons took a user to a separate page containing the details of that news item but the way I had it set up, it was hard to read and wouldn't display correctly on some resolutions. At
the end I decided to have each item take up the full width of the container and be large in size which allows the content to be expanded and be easy to read.


## Features 

* Events booking - form built by modifying the Bootstrap modal component, allows user to book the band for an event by filling out the form.
* Expandable containers activated through `:hover` and for buttons `:checked` pseudo-classes - expands and collapses elements on button click and cursor hover.
* CSS lightbox used for details about band members activated with `:checked` pseudo-class - displays a lightbox containing text when a button is clicked.
* Collapsible navigation bar with a tribar activated through use of `:checked` pseudo-class - allows for a collapsible mobile navigation by clicking a button.
* Audio and video playback by use of the HTML `<audio>` and `<iframe>` elememts - users can watch and listen to the band's clips by using the HTML widgets.
* An image slider built with the Bootstrap carousel component - Scolls through the band's photos and a user can use arrows or indicator icons below to scroll through them.

## Technologies

* [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
  * Used for structuring content
* [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
  * Used for the presentation of the page
* [Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox)
  * Used for the layout of the page
* [Bootstrap](https://getbootstrap.com/)
  * Used for the modal and carousel elements
* [Markdown](https://en.wikipedia.org/wiki/Markdown)
  * Used for formatting user_stories.md and README.md

## Testing 

### Manual Tests

Tested on mobile, tablet and desktop devices using different devices and developer tools,
and in different browsers(Firefox, Microsoft Edge and Google Chrome) to test browser compatibility.

### Automated Tests

* [W3C Markup Validation Service](https://validator.w3.org/)
  * Used for testing html
* [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)
  * Used for testing css
* [Mobile Friendly Test](https://search.google.com/test/mobile-friendly)
  * Used for testing mobile layout

### Bugs

* The publicity container image wouldn't show when using Microsoft Edge. It was due to it's z-index being set to -1. Solved by setting the z-index to 1 and adjusting other
  elements' z-index to appear above the image.
* The carousel indicator for the last photo doesn't work, get's skipped when using arrows. Haven't found a solution yet.

## Deployment 

Deployed to Github Pages 

Link: [https://alexander4k.github.io/the-monkees-website/](https://alexander4k.github.io/the-monkees-website/)

Clone the repository by copying the clone url

In the terminal type `git clone` followed by the copied url

`cd` into `the-monkees` and open `index.html`

## Credits

### Content 

* News - [Monkees](https://www.monkees.com/index.php)
* Tours - [Monkees Facebook](https://www.facebook.com/TheMonkees/)
* Band Information - [Wikipedia](https://en.wikipedia.org/wiki/The_Monkees)
* Peter Tork Information - [Wikipedia](https://en.wikipedia.org/wiki/Peter_Tork)
* Mickey Dolenz Information - [Wikipedia](https://en.wikipedia.org/wiki/Micky_Dolenz)
* Davey Jones Information - [Wikipedia](https://en.wikipedia.org/wiki/Davy_Jones_(musician))
* Michael Nesmith Information - [Wikipedia](https://en.wikipedia.org/wiki/Michael_Nesmith)

#### Fonts

* Fonts - [Google Fonts](https://fonts.google.com/)

### Media

#### Images

* Logo image - [Monkees](https://www.monkees.com/index.php)
* Publicity container background image - [ListToTheBand](http://listentotheband.weebly.com/graphics.html)
* News items' images - [Monkees](https://www.monkees.com/index.php)
* Band image - [HomeSecurity](https://homesecurity.press/quotes/the-best-of-the-monkees-album.html)
* Member images(image was modified) - [BlurtOnline](http://blurtonline.com/feature/good-time-monkees/)
* The Monkees album image - [HomeSecurity](https://homesecurity.press/quotes/thomas-the-train-charts.html)
* The Birds, The Bees and The Monkees album image - [Amazon](https://www.amazon.com/Birds-Bees-Monkees/dp/B007LNJ3WU)
* More of the Monkees album image - [Amazon](https://www.amazon.co.jp/More-Monkees/dp/B004GE818Y)
* Carousel image 1 - [HomeSecurity](https://homesecurity.press/quotes/pete-townshend-behind-blue-eyes.html)
* Carousel image 2 - [BoingBoing](https://boingboing.net/2018/09/24/the-monkees-recorded-a-new-chr.html)
* Carousel image 3 - [KitchenDecor](https://kitchendecor.club/files/pictures-of-the-group-monkees.html)
* Carousel image 4 - [CatScratchFeverSong](http://anugrah.staylive.site/cat-scratch-fever-song/)
* Carousel image 5 - [HomeSecurity](https://homesecurity.press/quotes/beatles-on-american-bandstand.html)
* Carousel image 6 - [Playbrain](https://en.playbrain.me/tv/en14897/)
* Carousel image 7 - [Prince](http://prince.org/msg/8/433920)
* Carousel image 8 - [TopsImages](https://www.topsimages.com/images/the-monkees-47.html)
* Carousel image 9 - [AtomicJunkShop](http://atomicjunkshop.com/monkees-wonders-crazy-ex-girlfriends/)
* Carousel image 10 - [BlurtOnline](http://blurtonline.com/feature/good-time-monkees/)

#### Videos

* Media page video - [Monkees Youtube Channel](https://www.youtube.com/watch?v=xvqeSJlgaNk)


#### Music 

* [MP3 Skulls](https://mp3skulls.to/free-mp3-download/the-monkees-i-m-a-believer.html)

## License

MIT