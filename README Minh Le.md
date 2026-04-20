# Student Name: Minh Le

## 1. My Assigned Work

Based on Table 6 in GA8, my assigned styling task was to add Bootstrap Icons to the correct buttons and UI elements. I also built and styled the following pages for Iteration 2:

- **Product_Page.html** – Added Bootstrap Icons to all navigation links, action buttons (Buy Now, Add to Cart, Favorite), seller info, similar listing cards, and the question submission section. Integrated the Bootswatch Lux theme, Google Fonts (Nunito Sans for headings, Roboto for body), responsive grid refinements, and carousel improvements. Implemented JavaScript interactions including Add to Cart state simulation with a cart badge counter and toast notification, a favorite heart toggle, and question submission with dismissible alerts.

- **CheckOut.html** – Added Bootstrap Icons to all form section headers (Shipping, Payment), input group prefixes, shipping method options, and action buttons. Implemented client-side form validation with custom regex checks for email, zip code, card number, expiration, and CVV. Added a live order summary that updates totals when the shipping method changes, and a success confirmation modal on valid submission.

## 2. AI / LLM Usage

* **What I asked the AI:** I used Claude to help me swap the default Bootstrap CDN for the Bootswatch Lux theme and integrate Google Fonts with the correct weights from our GA8 template. I asked how to add Bootstrap Icons to navbar links, buttons, and form elements. I also asked how to implement an "Add to Cart" button that simulates state with a cart badge counter and toast notification, and how to build client-side form validation using JavaScript with regex for email, zip, card number, expiration, and CVV fields.

* **How it helped & What I learned:** The AI helped me understand how to structure JavaScript event listeners for interactive features. I learned how `classList.add()` and `classList.remove()` swap Bootstrap classes for visual feedback, how `setTimeout()` resets button state after a delay, and how regex patterns like `/^[0-9]{5}$/` validate input fields. I also learned how Bootstrap Toast and Modal components are initialized via JavaScript (`new bootstrap.Toast()`, `new bootstrap.Modal()`). After receiving the code, I read through each function to understand the logic and tested the interactions in the browser across different screen sizes.

## 3. Live Site Link

* **Live URL:** https://vcu-257.github.io/iteration-2-build-with-style-group-8/
