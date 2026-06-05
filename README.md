# Clothing Store Landing Page - Box Mapping Assignment

##  Project Overview
This assignment demonstrates the **Box Mapping** technique for a Clothing Store landing page based on our course guidelines. It breaks down the page layout into nested boxes, semantic HTML tags, and essential CSS properties before coding.

---

##  Complete Page — Section Stack Overview
How the 7 core sections stack vertically inside the `<body>`:
* **Navbar:** display: flex; | position: sticky;
* **Hero Section:** min-height: 80vh; | background-size: cover;
* **About Us:** display: flex; | gap: 24px;
* **Promo Banner:** display: flex; | flex-direction: column;
* **Features Section:** display: flex; | display: grid;
* **Our Products:** display: flex; | flex-wrap: wrap;
* **Newsletter:** display: flex; | border-bottom: 1px solid #000;

---

##  Section-by-Section Detailed Box Mapping

### 🔹 SECTION 1: NAVBAR

<img width="844" height="375" alt="Screenshot 2026-06-05 091431" src="https://github.com/user-attachments/assets/992fb73a-d59f-4932-9f06-3292a87d131e" />


#### 2. Box Tree - Parent Child Hierarchy | HTML Tags
| Box Name | HTML Tag | Description |
| :--- | :--- | :--- |
| NAVBAR CONTAINER | `<header>` | Outermost container for navigation, sticky to top. |
| LOGO | `<a>` | Clickable brand text (Esprit). |
| NAV LINKS WRAPPER | `<nav>` > `<ul>` | Row holding the menu links. |
| CTA BUTTON | `<button>` | "Buy Now" button on the right edge. |

#### 3. CSS Properties Table
| Property | Value | Purpose | Snippet |
| :--- | :--- | :--- | :--- |
| `display` | `flex` | Aligns items horizontally. | `header { display: flex; }` |
| `justify-content` | `space-between` | Pushes items to edges. | `justify-content: space-between;` |

---

### 🔹 SECTION 2: HERO SECTION

<img width="912" height="582" alt="Screenshot 2026-06-05 092116" src="https://github.com/user-attachments/assets/28b59133-d644-4373-9653-8dea3c40bf51" />


#### 2. Box Tree - Parent Child Hierarchy | HTML Tags
| Box Name | HTML Tag | Description |
| :--- | :--- | :--- |
| HERO SECTION | `<section>` | Holds the large background fashion image. |
| TEXT WRAPPER | `<div>` | Box holding the text over the image. |
| MAIN HEADING | `<h1>` | Title text "Clothing Store". |

#### 3. CSS Properties Table
| Property | Value | Purpose | Snippet |
| :--- | :--- | :--- | :--- |
| `background-size` | `cover` | Fits image to cover the section perfectly. | `background-size: cover;` |

---

### 🔹 SECTION 3: ABOUT US

<img width="1153" height="695" alt="Screenshot 2026-06-05 093326" src="https://github.com/user-attachments/assets/2b00f09a-4dec-43cc-9a93-39a8e5ea4491" />


#### 2. Box Tree - Parent Child Hierarchy | HTML Tags
| Box Name | HTML Tag | Description |
| :--- | :--- | :--- |
| ABOUT SECTION | `<section>` | Full section block with white background. |
| SECTION TITLE | `<h2>` | Center-aligned title "About Us". |
| CARDS WRAPPER | `<div>` | Horizontal wrapper holding 3 columns. |
| ABOUT CARD | `<div>` | Individual card (Image + Text). |

#### 3. CSS Properties Table
| Property | Value | Purpose | Snippet |
| :--- | :--- | :--- | :--- |
| `display` | `flex` | Positions 3 cards side-by-side. | `div { display: flex; }` |
| `gap` | `24px` | Adds spacing between cards. | `gap: 24px;` |

---

### 🔹 SECTION 4: PROMO BANNER (-70%)

<img width="1075" height="550" alt="Screenshot 2026-06-05 094056" src="https://github.com/user-attachments/assets/01882501-98bc-4d42-858a-75d7f760e44d" />


#### 2. Box Tree - Parent Child Hierarchy | HTML Tags
| Box Name | HTML Tag | Description |
| :--- | :--- | :--- |
| PROMO BANNER | `<section>` | Banner featuring the sale text. |
| INFO WRAPPER | `<div>` | Centered column grouping details. |
| SHOP BUTTON | `<button>` | "Shop Now" call to action button. |

#### 3. CSS Properties Table
| Property | Value | Purpose | Snippet |
| :--- | :--- | :--- | :--- |
| `flex-direction`| `column` | Stacks items vertically inside the box. | `flex-direction: column;` |

---

### 🔹 SECTION 5: FEATURES OUR STORE

<img width="1111" height="625" alt="Screenshot 2026-06-05 095050" src="https://github.com/user-attachments/assets/14c5c2df-fe88-40ea-9838-e4916d6d4642" />

#### 2. Box Tree - Parent Child Hierarchy | HTML Tags
| Box Name | HTML Tag | Description |
| :--- | :--- | :--- |
| FEATURES CONTAINER| `<section>` | Outermost section for features list. |
| LEFT TITLE BOX | `<div>` | Left column for the heading. |
| RIGHT GRID BOX | `<div>` | Right column holding 2x2 items grid. |

#### 3. CSS Properties Table
| Property | Value | Purpose | Snippet |
| :--- | :--- | :--- | :--- |
| `display` | `grid` | Forms a clean grid for feature icons. | `div { display: grid; }` |
| `grid-template-columns`| `1fr 1fr` | Splits space into two equal columns. | `grid-template-columns: 1fr 1fr;` |

---

### 🔹 SECTION 6: OUR PRODUCTS

<img width="689" height="629" alt="Screenshot 2026-06-05 100819" src="https://github.com/user-attachments/assets/abb13736-064b-41f1-b5b1-8b91e51dd598" />


#### 2. Box Tree - Parent Child Hierarchy | HTML Tags
| Box Name | HTML Tag | Description |
| :--- | :--- | :--- |
| PRODUCTS SECTION | `<section>` | Main section for displaying clothes catalog. |
| GRID WRAPPER | `<div>` | Wrapping box for responsive items rows. |
| PRODUCT CARD | `<div>` | Individual item (Image, Title, Price). |

#### 3. CSS Properties Table
| Property | Value | Purpose | Snippet |
| :--- | :--- | :--- | :--- |
| `flex-wrap` | `wrap` | Drops items to next row if space is small. | `flex-wrap: wrap;` |

---

### 🔹 SECTION 7: NEWSLETTER

<img width="1055" height="506" alt="Screenshot 2026-06-05 101357" src="https://github.com/user-attachments/assets/1dbdb738-9db2-4ea4-9b1a-7347688d552e" />


#### 2. Box Tree - Parent Child Hierarchy | HTML Tags
| Box Name | HTML Tag | Description |
| :--- | :--- | :--- |
| NEWSLETTER BOX | `<section>` | Bottom accent box for email collection. |
| FORM WRAPPER | `<form>` | Inline row handling inputs and button. |
| EMAIL INPUT | `<input>` | Input field for typing email. |

#### 3. CSS Properties Table
| Property | Value | Purpose | Snippet |
| :--- | :--- | :--- | :--- |
| `border-bottom` | `1px solid #000` | Creates minimalist underline look. | `input { border-bottom: 1px solid #000; }` |
