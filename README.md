# Interactive Gallery

Dynamic interactive gallery develped using javascript and styled using grid css and flex box

## The Design

In order to navigate using Keyboard, number 1 key MUST be pressed to begin to the first image, then LEFT and RIGHT to move to the previous / next images. Press Enter to select the image and view it in a modal mode. Press ESC key to go back to the normal view.

PLEASE DO NOT USE Tab OR SHIFT + Tab keys as I applied the functions to the LEFT and RIGHT arrow keys only


## Reflections

The image gallery has 12 thumbnails that are listed in grid layout.
When the user follows the instructions above and as well included in the HTML page, a bigger preview of the image is possible by hitting Enter key.

I still have some buge in the navigation while the lightbox is active, That's why I disabled the arrows and keyboard navigation till I can fix it in the web portfolio.



### Challenges

Tab and ShiftTab Key events were conflicting the calculations of the current active element that made it hard to increment / decrement for the next / previous navigations.

### How I solved it!

I developed the logic by using the left / right arrow keys after pressing the K on the keyboard to set a flag for keyboard navigation.


### What did I learn?

1- Planing ahead can solve lots of time waste during development
2- UX/UI methods can be used for the visual sketching before developing
3- Testing, Testing,.....Testing


## Developer

* **Ahmed Hussein** - *Initial work* - [Portfolio](https://ahmed.7pixelbz.ca)

All images used in the gallery are designed by Ahmed Hussein

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgment

* This is an assignment for eductional use only