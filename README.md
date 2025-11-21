# World of History Museum Website

# World of History Museum

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [User Experience (UX)](#user-experience-ux)
- [Wireframes](#wireframes)
- [Design](#design)
- [Technologies Used](#technologies-used) 
- [File Structure](#File-Structure) 
- [Deployment](#deployment)
- [Testing](#testing)
  - [Manual Testing – Buttons, Links & Forms](#manual-testing--buttons-links--forms)
  - [Lighthouse Testing](#lighthouse-testing)
  - [HTML & CSS Validation](#html--css-validation)
  - [Bugs](#bugs)
- [Attributions](#attributions)
---

# Overview

A website for the  **World of History Museum**, designed to showcase the exhibits on offer and the oppurtunity to engage with the museum through the various forms on offer. This website is for families, students and history enthuisast who are interested in what the museum has on offer.

It allowsfor users to know what they can excpect and plan their visit around what they want to see. 

---

# Features

* **Home Page Carousel** showcasing museum visuals
* **Visit Page** including ticket purchase, registration, newsletter
* **Responsive Design** with Bootstrap 5
* **Contact & Newsletter forms**
* **Video integration** in exhibits


---

# User Experience (UX)

## Project Goals

* Provide an intuitive and visually appealing interface
* Make exhibit content available for planning 
* Encourage engagement via sign-ups and bookings

## User Stories

### First-Time Users

* I want an engaging homepage introducing the museum.
* I want clear navigation to exhibits and visit information.

### Returning Users

* I want fast access to ticket booking and new events.

### Frequent Users

* I want to subscribe to newsletters and receve updates

---
## Responsive Design Preview

Below is a multi device mockup demonstrating how the **World of History Museum** website appears on desktop, laptop tablet and mobile screens.

![Multi-Device Mockup](assets/multi-screen.jpeg.png)

# Design

## Colour Scheme

* **Background:** `#f5f1e6`
* **Header/Footer:** `#212529`
* **Highlight:** `#ffc107`

## Typography

* **Open Sans** – body text
* **Playfair Display** – headings and titles

## Imagery

High‑quality curated images, including:

* Unsplash collections
* Wikimedia Commons
* Museum‑inspired assets
* Exhibit‑specific photography

---

# Wireframes
**Wireframe Link:**
[https://balsamiq.cloud/sucgt7o/phmvnkl](https://balsamiq.cloud/sucgt7o/phmvnkl)

---

### Desktop

* Full-width carousel 
* reactive to size change 


### Tablet

* Semi-stacked layouts
* Adjusted padding for readability


### Mobile

* Single column layout 
* Adjusted padding for readability




---

# Technologies Used

## Languages

* HTML
* CSS
* JavaScript (Bootstrap bundle)

## Frameworks & Libraries

* Bootstrap 5.3
* Google Fonts

## Tools

* GitHub
* Chrome DevTools
* Lighthouse (performance, accessibility & SEO audits)
* Balsamiq (wireframes) 
* VS Code  
* chat GPT 
* W3C Validator 
* MDN 



--- 
# File Structure 
World-Of-History/
│
├── index.html
├── exhibits.html
├── visits.html
│
├── assets/
│ ├── style.css
│ ├── exhibits.css
│ ├── visits.css
│
│ ├── crystalpalace.jpg
│ ├── victoriaandabdul.jpg
│ ├── mummy.jpeg
│ ├── pyramids.jpeg
│ ├── tudors1.jpg
│ ├── henry-new.jpeg.webp
│ ├── roman-warrior.jpeg.avif
│ ├── roman-enemy.jpeg.avif
│ ├── greek-new.jpeg.avif
│ ├── plato-new.jpeg.avif
│
│ ├── clip-one.mp4
│ ├── egyptian.mp4
│ ├── romans.mp4
│
│ ├── lighthouse.jpeg
│ ├── multi-screen.jpeg.png
│ ├── validator-index.jpeg
│ ├── validator-visit.jpeg
│ └── validator-exhibit.jpeg
│
└── README.md




---
# Deployment

## GitHub Pages

1. Open repository **Settings**
2. Select **Pages**
3. Choose `main` branch
4. Click **Save**
5. A live site link will apear

## Cloning

```bash
git clone https://github.com/username/world-of-history-museum.git
```

---

# Testing & Bugs

| Bug # | Description                     | Expected Result     | Actual Result     | Fix Status |
| ----- | ------------------------------- | ------------------- | ----------------- | ---------- |
| 1     | Navbar not colapsing on mobile | Collapses properly  | Stayed expanded   | Fixed      |
| 2     | Gallery image broken            | Image loads         | Broken link       | Fixed      |
| 3     | Form not submitting             | Form sends          | No action         | Fixed      |
| 4     | Cards misaligned on tablet      | Proper grid         | Overlap           | Fixed      |
| 5     | Footer floating mid-page        | Footer stays bottom | Misaligned        | Unresolved |
| 6     | Hover colour incorrect          | gld hover          | Grey hover        | Fixed      |
| 7     | CSS not updating                | Updated style loads | Browser cached    | Fixed      |
| 8     | Video not responsive            | Scales correctly    | overflowing       | Fixed      |
| 9     | Anchor links misaligned         | Correct scroll      | Offset slightly   | Fixed      |
| 10    | Carousel not autoplaying        | Rotates slides      | Stuck first slide | Fixed      |
| 11    | Mobile padding inconsistent     | Even spacing        | Too tight         | Fixed      |
| 12    | Hero image pixelated            | Sharp image         | Blurry            | Fixed      |

--- 
## Manual Testing – Buttons, Links & Forms

 manual tests were carried out on all interactive elements across the site to ensure correct navigation and expected behaviour for a static front end project.

### **Button & Link Functionality Testing**

| Item Tested | Page | Expected Result | Actual Result | Pass/Fail |
|-------------|------|-----------------|----------------|-----------|
| **Home (Navbar)** | All pages | Loads `index.html` | Works correctly |  Pass |
| **Exhibits (Navbar)** | All pages | Loads `exhibits.html` | Works correctly |  Pass |
| **Visit (Navbar)** | All pages | Loads `visits.html` | Works correctly |  Pass |
| **Carousel Next Button** | Home | Slides to next image | Works correctly |  Pass |
| **Carousel Previous Button** | Home | Slides to previous image | Works correctly | Pass |
| **Book a Tour Button** | Home | Should link to `visits.html` | Opens visits page | ✔ Pass |
| **Our Exhibits Button** | Home | Should link to `visits.html` | Opens visits page | ✔ Pass |
| **Stay the Night Button** | Home | Static button (no link assigned) | Clickable, no errors |  Pass |
| **Hire Now Button** | Home | Static button (no link assigned) | Clickable, no errors |  Pass |
| **Bronze Age Free Entry Button** | Home | Should open `visits.html` | Opens visits page |  Pass |
| **Footer: Facebook** | All pages | Opens Facebook in new tab | Works correctly |  Pass |
| **Footer: Instagram** | All pages | Opens Instagram in new tab | Works correctly | Pass |
| **Footer: Twitter** | All pages | Opens Twitter in new tab | Works correctly |  Pass |


### **Forms Testing (Static Project – No Backend Required)**

| Form | Page | Expected Behaviour | Actual Result | Pass/Fail |
|------|------|--------------------|----------------|-----------|
| **Newsletter Signup Form** | Home | Input fields accept text; submit button clickable | Works as expected (static) | ✔ Pass |
| **Contact Form** | Home | Requires name, email, message; submit button clickable | Works as expected (static) | ✔ Pass |
| **Buy Tickets Form** | Visit | Dropdowns + text inputs should accept values; "Pay Now" button clickable | Works as expected (static) | ✔ Pass |
| **Register Your Interest Form** | Visit | Input fields accept text; "Register" button clickable | Works as expected (static) | ✔ Pass |
| **Visit Page Newsletter Signup** | Visit | Accepts email; button clickable | Works as expected (static) | ✔ Pass |


### **Additional Behaviour Checks**

| Test | Expected | Actual Result | Pass/Fail |
|------|----------|----------------|-----------|
| **All pages responsive on desktop** | Layout adjusts with no overflow | Works correctly | ✔ Pass |
| **Responsive on tablet** | Elements stack neatly | Works correctly | ✔ Pass |
| **Responsive on mobile** | Hamburger menu not required; layout vertical | Works correctly | ✔ Pass |
| **Images load correctly** | All images display across pages | Works correctly | ✔ Pass |
| **Internal links do not break** | All `.html` files connect | Works correctly | ✔ Pass |

----

# Lighthouse Testing

Lighthouse was used via **Chrome DevTools** to test Performance, Accessibility, Best Practices, and SEO.

Results summary:

* **Performance:** Passed core metrics
* **Accessibility:** minor alt-text warnings
* **Best Practices:** All checks passed
* **SEO:** fully optimized 
![Lighthouse](assets/lighthouse.jpeg)

Lighthouse greatly helped identify accessibility improvements.

# HTML & CSS Validation 
 
 ## Screenshot of Results 
![Validator Screenshots](assets/validator-index.jpeg) 
![Validator Screenshots](assets/validator-exhibit.jpeg)
![Validator Screenshots](assets/validator-visit.jpeg) 
![Validator Screenshots](assets/validator-style.jpeg)
![Validator Screenshots](assets/validator-visit-css.jpeg) 
![Validator Screenshots](assets/validator-css-exhibit.jpeg) 

## Breakdown of Results  
 
 ### **index.html**

#### **Errors (4 total)**
All four errors were the same issue:
- `<button>` elements were placed **inside** `<a>` tags, which is invalid HTML.
 
 #### exhibits.html
Errors (14 total)
All errors related to:
<img> elements missing the required alt attribute, which is needed for accessibility. 
 
 ### visits.html
* No errors or warnings were found.
This page passed validation successfully.

### CSS Validation
* All CSS files were tested using the W3C CSS Validator.
style.css — No errors
exhibits.css — No errors
visits.css — No errors
All CSS passed validation without issues.
---
# Attributions / Sources
 
 ## Image Sources

* Hercules beating Centaur Nessus — [https://commons.wikimedia.org/wiki/File:Hercules_beating_Centaur_Nesso.jpg](https://commons.wikimedia.org/wiki/File:Hercules_beating_Centaur_Nesso.jpg)
* Great Minds of Greece — "I Became A Stoic Through These 3 Daily..." (blog) https://medium.com/masterpieces-in-progress/i-became-a-stoic-through-these-3-not-so-easy-daily-practices-cbd2bb8e556b
* Greek Art Courses — Apollon Art Studio Florence https://apollonartstudioflorence.com
* Romans – Augustus — [https://en.wikipedia.org/wiki/Augustus](https://en.wikipedia.org/wiki/Augustus)
* Tudors Exhibit — Legion of Honor Museum https://www.famsf.org/visit/legion-of-honor
* Pyramid Construction — Educational article https://www.sciencefocus.com/science/egyptian-pyramids-new-studies
* Mummification Ingredients — Science history article https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.jpost.com%2Farchaeology%2Farticle-730316&psig=AOvVaw0Qom2e24TO7KsgXEHHVV9c&ust=1763658787342000&source=images&cd=vfe&opi=89978449&ved=0CBkQjhxqFwoTCIit6dOdgZEDFQAAAAAdAAAAABAE 
* Victoria & Abdul — Historical documentary reference https://www.google.com/url?sa=i&url=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FAbdul_Karim_%2528the_Munshi%2529&psig=AOvVaw04iJHgyNGmujdw-Bihvmyb&ust=1763658848387000&source=images&cd=vfe&opi=89978449&ved=0CBkQjhxqFwoTCODe3vOdgZEDFQAAAAAdAAAAABAE
* Great Exhibition 1851 — Antique Box Guide https://www.antiquebox.org/the-great-exhibition-of-1851/
* Psychological Framing — "The Life-Changing Power of Seeing..." https://mindfulambition.net/psychological-framing/
* Watford Museum Plans — Local news
* Moscow State Historical Museum — [https://commons.wikimedia.org/wiki/File:Moscow_State_Historical_Museum_-_IMG_3502.JPG](https://commons.wikimedia.org/wiki/File:Moscow_State_Historical_Museum_-_IMG_3502.JPG)
* Museum Sleepovers — Travel article
* Garden Museum Orangery — [https://flavoursearch.com/listings/3395/garden-museum/the-orangery-dan-pearson-garden](https://flavoursearch.com/listings/3395/garden-museum/the-orangery-dan-pearson-garden)

## Unsplash Images

* [https://images.unsplash.com/photo-1491156855053-9cdff72c7f85?auto=format&fit=crop&q=80&w=2128](https://images.unsplash.com/photo-1491156855053-9cdff72c7f85?auto=format&fit=crop&q=80&w=2128)
* [https://images.unsplash.com/photo-1544213456-bc37cb97df74?auto=format&fit=crop&q=80&w=207](https://images.unsplash.com/photo-1544213456-bc37cb97df74?auto=format&fit=crop&q=80&w=207)
* [https://plus.unsplash.com/premium_photo-1661963952208-2db3512ef3de?auto=format&fit=crop&q=80&w=2144](https://plus.unsplash.com/premium_photo-1661963952208-2db3512ef3de?auto=format&fit=crop&q=80&w=2144)
* [https://images.unsplash.com/photo-1594026200204-a25bea256816?auto=format&fit=crop&q=80&w=987](https://images.unsplash.com/photo-1594026200204-a25bea256816?auto=format&fit=crop&q=80&w=987)
* [https://images.unsplash.com/photo-1505664194779-8beaceb93744?auto=format&fit=crop&q=80&w=1470](https://images.unsplash.com/photo-1505664194779-8beaceb93744?auto=format&fit=crop&q=80&w=1470)
* [https://images.unsplash.com/photo-1544213456-bc37cb97df74?auto=format&fit=crop&q=80&w=2070](https://images.unsplash.com/photo-1544213456-bc37cb97df74?auto=format&fit=crop&q=80&w=2070)
* [https://images.unsplash.com/photo-1491156855053-9cdff72c7f85?auto=format&fit=crop&q=80&w=212](https://images.unsplash.com/photo-1491156855053-9cdff72c7f85?auto=format&fit=crop&q=80&w=212)


## Video Sources

* Egyptians Exhibit — [https://www.youtube.com/watch?v=Nh-1eTd2c4o](https://www.youtube.com/watch?v=Nh-1eTd2c4o)
* Victorian Era — [https://www.youtube.com/watch?v=YbimS9gQtZ4&t=2s](https://www.youtube.com/watch?v=YbimS9gQtZ4&t=2s)
* Roman Empire — [https://www.youtube.com/watch?v=b9bcohqsTGk](https://www.youtube.com/watch?v=b9bcohqsTGk)


## Design  attributes 
* https://www.britishmuseum.org 
* https://www.vam.ac.uk/?srsltid=AfmBOoouP7NWYYbtwCNar8xhK-SokgJSu3MhQLyVGvajtSR-PBZiXOaO 
* https://www.sciencemuseum.org.uk





## Bootstrap Components

* Grid System — [https://getbootstrap.com/docs/5.3/layout/grid/](https://getbootstrap.com/docs/5.3/layout/grid/)
* Forms — [https://getbootstrap.com/docs/5.3/forms/overview/](https://getbootstrap.com/docs/5.3/forms/overview/)
* Cards — [https://getbootstrap.com/docs/5.3/components/card/](https://getbootstrap.com/docs/5.3/components/card/)
* Buttons — [https://getbootstrap.com/docs/5.3/components/buttons/](https://getbootstrap.com/docs/5.3/components/buttons/)
* Utilities — [https://getbootstrap.com/docs/5.3/utilities/spacing/](https://getbootstrap.com/docs/5.3/utilities/spacing/)
  [https://getbootstrap.com/docs/5.3/utilities/flex/](https://getbootstrap.com/docs/5.3/utilities/flex/)
* Nav Links — [https://getbootstrap.com/docs/5.3/components/navs-tabs/](https://getbootstrap.com/docs/5.3/components/navs-tabs/)

## HTML Layout Inspiration

* W3Schools — [https://www.w3schools.com/html/html5_semantic_elements.asp](https://www.w3schools.com/html/html5_semantic_elements.asp)
* freeCodeCamp — HTML structure examples
* General inspiration taken from professional museum websites 
https://www.britishmuseum.org

---

# Additional Notes

* this project was inspired by layouts commonly used by modern museum websites. 
* footer alignment issues occurred during development; some footers remain slightly mismatched. 
* both manual debugging and AI assistance were used to debug when they coudnt be resolved by the developer some issues could not be resolved
* lighthouse testing was used to improve accessibility and performance.  

* future projects can benefit frim using bootstrap from teh beginning and  
--- 

# Author  
* Mohammed Sadek Hussainc
* NCC 
* Level 5 web Development 
* Milestone- 1



