# RedTopClothingStore

- **RedTopClothingStore**: The page is for an online clothing store named RedTopClothingStore, featuring a variety of clothing items and accessories.
  
- **Navigation & Features**: It includes a navigation bar with links to sales, catalog, and Q&A sections, a search function, user account access, and a shopping cart indicator.
  
- **Promotions & Deals**: There are special discounts and deals highlighted, such as Father's Day discounts, free shipping on orders over $100, and a section for top month sellers.
  
- **Contact & Support**: The footer provides contact information, customer support links like FAQs and size guides, and payment method icons for transactions.

The page uses Bootstrap for styling and has custom CSS for visual enhancements like animations and hover effects.

https://www.youtube.com/watch?v=Kwb0b9QtQwM

## A user-friendly "sign-up" form,

### Structure:
#### HTML Document Setup:

<!DOCTYPE html>: Defines the document type and HTML version.
<html lang="en">: Sets the language attribute to English.
<head>: Contains meta information, title, and internal CSS for styling.
  
#### Head Section:

<meta charset="UTF-8">: Sets the character encoding to UTF-8.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Ensures the page is responsive on different devices.
<title>: Sets the page title to "RedTopClothingStore - Sign Up".
<style>: Includes internal CSS for styling the page elements.
  
#### Body Section:

#### Header:

Contains a logo (logo.png) and the brand name "RedTopClothingStore."
#### Form Container:
<div class="container">: Main container for the sign-up form with styling for padding, background color, and box-shadow.
<form action="/action_page.php" class="container" style="border: 1px solid #ccc">: Form element with a POST action to action_page.php.
  
#### Form Elements:

Email field: Input for the user's email.
Password field: Input for the user's password.
Repeat Password field: Input to confirm the user's password.
Remember me checkbox: Option to remember the user's details.
Terms and Privacy agreement link.
Cancel and Sign Up buttons: Actions for canceling or submitting the form.

#### Footer:

<footer>: Contains a text crediting the designer, "© 2024 All rights reserved. Designed by Devindu Malshan."
  
#### CSS Highlights:
Inputs: Full-width, padding, border, and border-radius for rounded corners.
Buttons: Full-width, background colors for different states, rounded corners, and hover effects.
Container: Padding, background color, rounded corners, and a box-shadow effect.
Responsive Design: Media query for screens smaller than 300px to adjust button widths.

## "Wishlist" page

1. Document Structure:

<!DOCTYPE html>: Declares the document type and version of HTML.
<html lang="en">: Sets the language attribute to English.
<head>: Contains meta information, links to external resources, and internal styles.
<body>: Contains the content and structure of the page.
  
2. Head Section:
  
<meta charset="UTF-8">: Specifies the character encoding for the HTML document.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Ensures the page is responsive and scales properly on different devices.
<title>Wishlist</title>: Sets the title of the page.
<link rel="icon" href="logo.png" type="image/x-icon">: Links to the favicon for the page.
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">: Links to Bootstrap CSS for styling.
<style>: Contains internal CSS styles for the page elements.
  
3. Body Section:
   
<body class="bg-light">: Begins the body with a light background color.
<div class="container mt-5">: Container for the main content with a top margin.
  
3.1 Header:

<div class="header">: Header section containing the store logo and brand name.
<a href="index.html" class="navbar-logo">: Link to the home page with the logo and brand name.
  
3.2 Wishlist Title and Buttons:

<div class="wishlist-title-container">: Container for the wishlist title and action buttons.
<h2 class="wishlist-title">Wishlist</h2>: Title of the wishlist section.
<div class="wishlist-buttons">: Container for the action buttons.
<button class="delete-button">Delete</button>: Button to delete items from the wishlist.
<button class="checkout-button">Checkout</button>: Button to proceed to checkout.
  
3.3 Wishlist Items:

<div class="wishlist">: Container for the list of wishlist items.
Each wishlist item is wrapped in a <div class="wishlist-item">:
<input type="checkbox" class="mr-3">: Checkbox for selecting the item.
<div class="card flex-row">: Card layout with a flexbox for item details.
<img class="card-img-top" src="product-image.jpg" alt="Product Name">: Product image.
<div class="card-body">: Contains the product details and quantity controls.
<div class="details">: Container for product details (category, name, price).
<div class="quantity-control">: Container for quantity control buttons.
<button class="minus-btn">-</button>: Button to decrease quantity.
<input type="number" value="1" min="1">: Input field to specify quantity.
<button class="plus-btn">+</button>: Button to increase quantity.
  
4. Footer:
   
<footer class="my-5 pt-5 text-muted text-center text-small">: Footer with copyright information.
  
5. External Scripts:
   
Links to jQuery, Popper.js, and Bootstrap JS for interactive functionality.

Internal CSS Styles:

Custom styles for various elements including logo, brand name, header, wishlist items, buttons, and quantity controls.

