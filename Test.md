# React Squad Test

## Issue #1
- **Timestamp:** 0:00  
- **Position:** The first card inside the dashboard section  
- **Problem:** The "Total licenses" card says N/A  
- **Suggestion:** This should say `0` if the total licenses are truly 'not available' or if the endpoint is returning an `undefined` or `null` value when queried.  

## Issue #2
- **Timestamp:** 0:00  
- **Position:** The whole screen  
- **Problem:** The cards are not properly arranged  
- **Suggestion:** Use `flexbox` or a `grid` layout to ensure the cards take up the full width of their container or a `3x3 grid` for even spacing.  

## Issue #3
- **Timestamp:** 0:00  
- **Position:** The buttons on the cards across the whole screen  
- **Problem:** The buttons are all white  
- **Suggestion:** Assign distinct colors to the buttons so they stand out and are easily recognizable as clickable elements.  

## Issue #4
- **Timestamp:** 0:00  
- **Position:** The feeds section (bottom right of the dashboard)  
- **Problem:** The feeds section is stuck on the same page as the dashboard  
- **Suggestion:** Consider moving the feeds section below the dashboard cards or placing it on a separate route for better separation of concerns.  

## Issue #5
- **Timestamp:** 0:00  
- **Position:** The left sidebar  
- **Problem:** The user interface looks bland due to the white sidebar  
- **Suggestion:** Add a vibrant color to the sidebar to make it stand out and improve UI appeal.  

## Issue #6
- **Timestamp:** 0:05  
- **Position:** The cards on the screen  
- **Problem:** The cards lack a hover effect  
- **Suggestion:** Implement a hover effect to indicate that cards are interactive.  

## Issue #7
- **Timestamp:** 0:11  
- **Position:** The top of the content section  
- **Problem:** Title text size is inconsistent with the dashboard titles  
- **Suggestion:** Use a reusable component for title text and ensure consistency, preferably with a larger font size.  

## Issue #8
- **Timestamp:** 0:07  
- **Position:** The whole right section  
- **Problem:** The right section fetches data on the client side  
- **Suggestion:** Use **server-side rendering** for `GET` requests to optimize performance.  

## Issue #9
- **Timestamp:** 0:11  
- **Position:** The top bar  
- **Problem:** Dropdown placement is unrealistic  
- **Suggestion:** Move the dropdown to the **top-right** to maintain visual balance and avoid obstructing the sidebar menu.  

## Issue #10
- **Timestamp:** 0:28  
- **Position:** The top of the content section  
- **Problem:** Title text size is inconsistent with the dashboard  
- **Suggestion:** Maintain a consistent font size across pages using a reusable title component.  

## Issue #11
- **Timestamp:** 0:28  
- **Position:** The top bar text ("Projects")  
- **Problem:** The meaning of "Projects" is unclear  
- **Suggestion:** If it refers to the dropdown, move it to the **top-right** for clarity.  

## Issue #12
- **Timestamp:** 0:28  
- **Position:** The top of the content section  
- **Problem:** Title text size is inconsistent with the dashboard  
- **Suggestion:** Use a consistent and larger font size for visibility.  

## Issue #13
- **Timestamp:** 0:54  
- **Position:** Edit Project modal  
- **Problem:** "description" input field label is lowercase  
- **Suggestion:** Change to "Description" with proper capitalization.  

## Issue #14
- **Timestamp:** 0:54  
- **Position:** Edit Project modal  
- **Problem:** Start date is displayed as an ISO Timestamp  
- **Suggestion:** Format the start date to a **human-readable format**.  

## Issue #15
- **Timestamp:** 0:54  
- **Position:** Edit Project modal  
- **Problem:** End date is displayed as an ISO Timestamp  
- **Suggestion:** Format the end date to a **human-readable format**.  

## Issue #16
- **Timestamp:** 1:08  
- **Position:** The list section on the projects page  
- **Problem:** The timeline dates are displayed in a weird format  
- **Suggestion:** Ensure a consistent and readable date format.  

## Issue #17
- **Timestamp:** 0:56  
- **Position:** Edit Project card  
- **Problem:** A select input field has "Free" as an auto-selected value but no label  
- **Suggestion:** Add a label to indicate what the field represents.  

## Issue #18
- **Timestamp:** 1:07  
- **Position:** The top-right section of the projects table  
- **Problem:** "status" field is in lowercase  
- **Suggestion:** Capitalize it to "Status".  

## Issue #19
- **Timestamp:** 1:10  
- **Position:** Top pane on the single project view  
- **Problem:** The project name is missing  
- **Suggestion:** Display the project name so users know which project they are viewing.  

## Issue #20
- **Timestamp:** 1:13  
- **Position:** Device pane in single project view  
- **Problem:** "Remove Device" action lacks design consistency  
- **Suggestion:** Replace with a **cancel (X) button** to match other UI elements.  

## Issue #21
- **Timestamp:** 1:17  
- **Position:** Whole list component  
- **Problem:** Texts are misaligned  
- **Suggestion:** Align texts properly with the table title.  

## Issue #22
- **Timestamp:** 1:18  
- **Position:** Content section of the entire layout  
- **Problem:** Delayed loading of certain visual elements  
- **Suggestion:**  
  - Use **fallback images** while images are being fetched.  
  - If fetching from an API, consider **server-side rendering**.  

## Issue #23
- **Timestamp:** 1:19  
- **Position:** Titles on the cards in the content section  
- **Problem:** Titles are too close to the images  
- **Suggestion:** Add spacing between the title and images.  

## Issue #24
- **Timestamp:** 1:19  
- **Position:** Cards in the content section  
- **Problem:** Cards have a static size, but images do not  
- **Suggestion:**  
  - Ensure images **maintain a fixed aspect ratio** within the card.  
  - Prevent images from distorting the card layout.  
