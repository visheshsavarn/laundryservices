# Laundry Service Website

This is my assignment project. I made a laundry service website using HTML and CSS.

---

## Files

- index.html - the main page
- styles.css - all the styling

---

## What I made

The website has two parts:

**Navbar** - has the logo, navigation links (Home, Services, About Us, Contact Us) and a username button on the right side.

**Hero Section** - has a heading, some text and a button on the left. On the right side there is an image of a laundry place.

---

## What I used

- HTML
- CSS (flexbox mostly)

---

## How to open

Just download the files and open index.html in a browser. Thats it.

---

## Problems I faced

- I forgot to add spaces inside calc() so the height wasnt working. it should be calc(100vh - 70px) not calc(100vh-70px)
- I wrote transform instead of transition for the hover effect on nav links so the animation wasnt working
- The image was overflowing on smaller screens because i used a fixed width of 800px. I changed it to max-width instead