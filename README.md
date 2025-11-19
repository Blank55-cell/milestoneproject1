# milestone-project 1

## Quick Links
- [Main Goal](#main-goal)
- [Tools Used](#tools-used)
- [Project Objectives](#project-objectives)
- [Target Audience](#target-audience)
- [Credits](#credits)
- [Bug Fixes](#bug-fixes)
- [Changes Done to the Code/Layout](#changes-done-to-the-codelayout)
- [Site Structure](#site-structure)
- [Current Content](#current-content)
- [Common Symptoms Experienced by Dachshunds](#common-symptoms-experienced-by-dachshunds)
- [Form Section](#form-section)
- [Q&A Section](#qa-section)
- [About Section](#about-section)
- [Gallery of Sausages](#gallery-of-sausages)
- [Contact Us Section](#contact-us-section)

## Main Goal 

The aim of creating this website is to provide a source of information that can help dachshund owners better understand the aspects of dachshunds and how they behave, and more importantly, the potential ailments they can develop. For example, complicated back problems are the more prevalent issues that can occur, with the most debilitating one being IVDD (Intervertebral Disc Disease) that can occur later in their lives. This can lead to a costly and demoralizing journey, and for that reason I want to incorporate features that allow dachshund owners to enquire and better understand the potential risks of this disease and other ailments so that it can help reduce the potential risks of these issues occurring.

In summary, this website is being designed to better help dachshund owners understand how to look after their dogs' coats while explaining the potential health risks and care needs, allowing for easier navigation, FAQs, and resources to help support more responsible ownership.

## Tools Used
1. HTML5 
2. CSS 
3. Bootstrap 
4. GitHub 

---

## Project Objectives
- Provide a website that can fulfill the needs of dachshund owners
- Provide a useful and intuitive UI that can help visitors navigate through the website with ease while providing the necessary answers to any questions they may have

## Target Audience 
- Dachshund owners 

---

## Credits 

### Images 
- [Wire-haired](../codeinstitute/assets/images/Wire%20haired.jpg) - **Credits**: [Sandra Grünewald](https://unsplash.com/photos/gray-and-white-long-coat-small-dog-on-white-sand-during-daytime-mZostdE4kUY)

- [Smooth-haired](../codeinstitute/assets/images/Smooth%20haired.jpg) - **Credits**: [Hayden Patmore](https://unsplash.com/photos/brown-dachshund-puppy-on-green-grass-field-during-daytime-ohz49NaR9kM)

- [Long-haired](../codeinstitute/assets/images/Long%20haired.jpg) - **Credits**: [Darren Richardson](https://unsplash.com/photos/black-and-brown-long-coated-dog-5IQ6cdiS3GM)

- [Dog-treats](../codeinstitute/assets/images/dogtreats.jpg) - **Credits**: [okeykat](https://unsplash.com/photos/multicolored-dog-bone-toys-w6elADh_jww)

- [Grass-2](../codeinstitute/assets/images/Grass%202.jpg) - **Credits**: [Lorren & Loki](https://unsplash.com/photos/brown-short-coated-dog-with-brown-leash-Bf07Cxq1aH0)

- [Dpuppy](../codeinstitute/assets/images/dpuppy.jpg) - **Credits**: [Carlos Ibáñez](https://unsplash.com/photos/brown-and-white-short-coated-dog-on-white-textile--VscXAULPao)

---

## Bug Fixes

| Bug / Issue | Cause | Fix Implemented |
|-------------|-------|-----------------|
| Broken iframe link (Google Maps embed) | Used a copied URL that wasn't properly formatted for embedding | Replaced with the official embed code provided by Google Maps |
| CSS `h1` headers overriding each other | Multiple conflicting `h1` rules | Merged into a single `h1` rule |
| Duplicate CSS rules (`section-history`, `section-socials`) | Repeated selectors causing conflicts | Combined into single rules for each section |
| Wrong CSS property (`line-height` vs `list-style`) | Typo in property name | Corrected to `line-height` |
| Border not rendering | Forgot to add `solid` style | Fixed with `border: 1px solid ...` |
| CSS layering issues | Rules applied in wrong order | Reorganized CSS file for proper cascade |
| Image paths breaking | Folder restructuring changed relative paths | Updated `src` attributes to match new folder layout |
| Navbar breaking | Bootstrap collapse not working | Adjusted markup and IDs for proper Bootstrap behavior |
| Q&A section too CSS-heavy | Used buttons requiring extra styling | Simplified with `<details>` and `<summary>` tags |
| General spelling mistakes in CSS | Typos in property names | Corrected manually and tested with validation tools |

---

## Changes Done to the Code/Layout 

- Changed the div columns from Bootstrap into custom ones to have more control over how they interact, allowing for fewer breakages to occur. This has also made the code less cluttered and cleaner.

- Changes done to the Q&A section: changed from buttons to `<details>` tags to reduce the need for extensive CSS and to organize the HTML layout in a much simpler order.

---

## Home page 

### Header 
- Displaying the site's name: **The Sausage Den**
- Tagline: *"Your source of info for our sausage doggos"*

### Navigation Bar 
- Built using Bootstrap's navbar component 
- Links:
  - **Home** (active link)
  - **Features** (active link)
  - **About** (active link - will need to work on the page soon)

### Main Content Sections
- Divs containing information on dachshund coat types
- History of dachshunds
- Fun facts about dachshunds
- Recommended toys and activities to keep them distracted and having fun

### Footer 
- Social media links:
  - [Facebook](https://www.facebook.com)
  - [Instagram](https://www.instagram.com)
  - [Twitter](https://www.twitter.com)
- Copyright © The Sausage Den

---

## Current Content

### Dachshund Coat Types

This area of the website demonstrates, through the use of a Bootstrap grid, the different characteristics of dachshund coats, showcasing the potential negatives of their coats and the ways to avoid these negative outcomes.

#### Smooth Coat 
Smooth-haired Dachshunds have short, shiny hair that is very close to the skin. It's one of the most common types of coats. They require minimal grooming but offer little insulation, making them more prone to the cold.

**Positives:**
- Less prone to matting and very low maintenance 
- Coat requires minimal grooming

**Negatives:**
- Prone to the cold; needs further insulation during colder times of the year
- The sleek coat is more prone to damage due to being thinner compared to other variants
- Very noticeable shedding

#### Long-Haired Coat
Long-haired dachshunds have softer, flowing fur with a feathering coat. They feature bushier eyebrows and have a scruffier look, but due to these reasons, they require more grooming; otherwise, their coat may get matted. 

**Positives:**
- Softer texture compared to other coats
- Often considered more gentle in temperament

**Negatives:**
- Grooming takes extra time and effort, making it high maintenance
- Coat mats quickly if not properly maintained

#### Wire-Haired Coat
Wire-haired dachshunds have a rough, wiry outer coat with a softer undercoat. They have distinctive facial hair including eyebrows and a beard.

**Positives:**
- Weather-resistant coat
- Less shedding compared to smooth-haired

**Negatives:**
- Requires regular hand-stripping or professional grooming
- Can develop a strong odor if not properly maintained

---

## Common Symptoms Experienced by Dachshunds

### Intervertebral Disc Disease (IVDD)
- Common disc disease 
- Their long spine can lead to a higher chance of a slipped or herniated disc 
- Symptoms include: difficulty walking, yelping when moved or picked up, less inclined to move

### Obesity 
- Dachshunds gain weight very easily, which can lead to more pressure being placed on their spine and joints, causing them to wear down
- Heart disease and high blood pressure are also common with obesity

### Hip Dysplasia and Patellar Luxation
- Due to the way a dachshund's weight is distributed, it can ultimately lead to joints wearing down, causing arthritis
- Patellar luxation is the dislocation of the kneecap, causing limping and extreme pain

### Skin Conditions
- Skin conditions such as itching can occur as a result of allergies 
- Skin conditions can vary but are quite noticeable 
- Mites can burrow into the skin, causing discomfort and itching, resulting in patches forming

### Dental Disease 
- Small breeds in general suffer from tartar buildup, gum disease, and tooth loss

---

## Form Section

### Registration Form

To register for our dachshund community, please provide the following information:

#### Personal Information
- **First Name** (required)
- **Last Name** (required)
- **Email Address** (required)

#### Dachshund Details
Select the type of dachshund you have:
- Miniature
- Long Haired
- Wire Haired
- Smooth Haired

#### Age Verification
You must confirm that you are over 18 years old to register.

#### How to Register
Complete all required fields and submit the form to join our community.

---

## Q&A Section 

This section provides an area that allows visitors to better enquire about frequently asked questions.

### Features 
- Dropdown layout using `<details>` and `<summary>` tags that, once clicked, will expand and provide the answer to the stated question

### Questions & Answers

#### What can I do to better care for my dog's coat?
Regular brushing can help dislodge any hairs caught in the coat that may cause itching, resulting in non-stop scratching and patches appearing in the coat.

**Smooth-haired:**
- Smooth coats only need to be brushed once a week with a grooming mitt

**Long-haired:** 
- 3-4 times a week with a slicker brush can reduce any tangles in the coat and reduce the chances of matting

**Wire-haired:**
- Weekly brushing should be more common, as well as the inclusion of trimming

**Nutrition:**
- Proper nutrition can help maintain their coat and reduce the general chance of significant hair loss

#### How often should I bathe my dachshund?
Bathing is only needed when necessary—once every 1-2 months or whenever dirty. Ensure that a shampoo specifically for dogs is chosen to avoid drying out the skin.

#### What should I feed my dachshund?
Balancing out the diet with omega-3 and omega-6 fatty acids can help support healthier skin and a shinier coat.

#### Do I need to take my dachshund to the groomers?
- **Wire-haired dachshunds** benefit the most from grooming a couple of times a year, but not too often, as it helps keep them warm during colder times of the year
- **Smooth-haired dachshunds** rarely require professional grooming and only need to be brushed regularly
- **Long-haired dachshunds** can be taken to the groomers, with the main areas to focus on trimming being the paws, ears, and tail

#### How much exercise should a dachshund need?
Dachshunds need at most around 45 minutes to an hour per day, but it can vary depending on the amount of playtime they have at home. Be wary of any high-intensity movement as it can potentially affect their back.

#### How prone are dachshunds to separation anxiety?
Dachshunds are able to bond very closely to their owners, making it hard for them to be separated for long durations of time. With proper training, they can cope better.

---

## About Section

This section provides a short summary as to why one can trust this website, including my own experience with raising a dachshund, as it requires a lot of attention.

### Features 
- An image and brief explanation of my own personal dog will be provided. As she's a dachshund, this can help alleviate any enquiries as to whether I have personal experience
- Contact information such as email address (for demonstration purposes) will be at the bottom in the footer

---

## Gallery of Sausages

Will include a collection of images showcasing different dachshunds.

---

## Contact Us Section 

Will include an area for contact information:
- Email
- Instagram
- Facebook
- Twitter

---

## Navigation Bar Links

- Welcome
- Home 
- Q&A
- About






















# milestoneproject1
