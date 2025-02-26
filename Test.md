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

## Issue #25
- **Timestamp:** 1:24
- **Position:** Page title at the top
- **Problem:** The title now suddenly has a roughly big size as opposed to the previous small sizes used within each page in this project
- **Suggestion:** Standardization is necessary so as to ensure consistency

## Issue #26
- **Timestamp:** 1:24
- **Position:** Select date section on same page as above
- **Problem:** The select date seems to be crucial in filtering out the results yet the description showed on the page does not show what results are being shown per time
- **Suggestion:** When results are filtered, they should say something along the lines of "Filtering results within - {date_ranges}". Also shouldn't the date be on the right hand side and on page load be auto selected to a period. That way the page looks full when opened for the first time.

## Issue #27
- **Timestamp:** 1:24
- **Position:** Section underneath date section
- **Problem:** This section shows that there are multiple sub sections yet the arrangement does not lead the eye of a user properly.
- **Suggestion:** It might pose better results if we allow the user to see only sub sections of currently selected sections instead of seeing all sub sections at once and being overwhelmed with information. If one is not already used to this interface like this, it might pose a confusion.

## Issue #28
- **Timestamp:** 1:24
- **Position:** Section underneath date section
- **Problem:** This section has no proper labelling to explain what the left section shows or is supposed to speak to.
- **Suggestion:** If we are looking at globally distributed nodes then i think this section should say globally distributed nodes. If we are looking at nodes by region, it should also say that.

## Issue #29
- **Timestamp:** 2:46
- **Position:** Feeds section
- **Problem:** This warning is incorrect grammar
- **Suggestion:** It should read sample project "will" expire in 21 days

## Issue #30
- **Timestamp:** 3:42
- **Position:** Assign device to Organization modal
- **Problem:** This says assign device but shows you can select multiple devices to assign to the organization and also organization is using pascal case.
- **Suggestion:** It should read Assign "devices" to "organization"

## Issue #31
- **Timestamp:** 4:22
- **Position:** Heatmap section
- **Problem:** The date has no label
- **Suggestion:** Date should have had a label saying "Select date"

## Issue #32
- **Timestamp:** 4:22
- **Position:** Heatmap section
- **Problem:** The km range has no label
- **Suggestion:** Date should have had a label saying "Select range"

## Issue #33
- **Timestamp:** 4:30
- **Position:** Heatmap section
- **Problem:** Loader inconsistency
- **Suggestion:** On other pages, when a load is initiated, the loader is a spinner but here it is a text saying "Loading...". We should have consitency for loading data.

## Issue #34
- **Timestamp:** 5:08
- **Position:** Pedestrian count week selector
- **Problem:** Seems like the week count is 4 days and not 5 days
- **Suggestion:** If the business requirement is the above, then I believe users should have a way of seeing that time period information cause a base user might be expecting something along the lines of 7 days

## Issue #34
- **Timestamp:** 5:22
- **Position:** Pedestrian count week selector
- **Problem:** Seems like the week count is actually not 4 days
- **Suggestion:** Users should have a way of seeing that time period information cause a base user might be expecting something along the lines of 7 days so seeing as Week 1 and Week 2 have disparity, this needs to be addressed.

