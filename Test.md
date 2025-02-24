# React Squad Test

## Issue #1

Timestamp - 0:00
Position - The first card inside the dashboard section
Problem - The Total licenses card says N/A
Suggestion - This should say 0 if the total licenses are truly 'not available' or if the endpoint is returning an undefined or null when being queried

## Issue #2

Timestamp - 0:00
Position - The whole screen
Problem - The cards are not properly arranged
Suggestion - We could flex those cards or align them in a grid so that they either take up the full width of the space they contain or we split it in a 3 x 3 grid so that the space is evenly used

## Issue #3

Timestamp - 0:00
Position - The buttons on the cards on the whole screen
Problem - The buttons are all colored white
Suggestion - We could assign colors to the buttons so that they are more distinct and stand out when being looked at. That way users can easily see that it can be clicked.

## Issue #4

Timestamp - 0:00
Position - The feeds section at the bottom right on the dashboard
Problem - The feeds is being stuck on the same page as the dashboard.
Suggestion - My current assumption is that the feeds would represent activities currently happening and based on user experience that may be jarring to see on the same page as the dashboard if anything. I would probably have advised that either it comes underneath the enter dashboard cards or it has its own route so that we can have seperation of concerns.

## Issue #5

Timestamp - 0:00
Position - The left sidebar
Problem - Having the entire content on the screen makes the user interface look bland and boring
Suggestion - Perhaps having this section in some sort of vibrant color would draw interest to it and enable the user to actually know it exists. With the current white color, it sort of blends out of the eye view when being looked at.

## Issue #6

Timestamp - 0:05
Position - The cards on the screen
Problem - The cards don't have a hover effect.
Suggestion - Cards should have an effect when hovered on so that the user can know when they have hovered over an item that can be clicked on.

## Issue #7

Timestamp - 0:11
Position - The top of the content section
Problem - The title is inconsistent with the title text size on the dashboard. The sizes don't match.
Suggestion - It would be better to maintain that size maybe a reusable component would help here. So either we use a larger text or a smaller text (I would prefer a larger one so that it commands attention when being viewed)

## Issue #8

Timestamp - 0:07
Position - The whole right section
Problem - The right section seems to be being built on the client side and fetching that data on page load.
Suggestion - For get endpoints, we can delegate fetching of the information using serverside rendering.

## Issue #9
Timestamp - 0:11
Position - The top bar
Problem - The dropdown location seems unrealistic. There is an expanse of space on the top right where this could have been placed. That way it would have done two things - achieved visual balance and also not blocked the view of the sidebar menu.

## Issue #10

Timestamp - 0:28
Position - The top of the content section
Problem - The title is inconsistent with the title text size on the dashboard. The sizes don't match.
Suggestion - It would be better to maintain that size maybe a reusable component would help here. So either we use a larger text or a smaller text (I would prefer a larger one so that it commands attention when being viewed)

## Issue #11

Timestamp - 0:28
Position - The top bar text saying Projects
Problem - Don't understand what that text means. Can't tell if it means the content is showing projects or if it means the dropdown is showing projects although the latter seems most likely
Suggestion - If the latter stated above is the case, then let's move it to the top right as suggested. That way it makes more sense when grouped together.

## Issue #12

Timestamp - 0:28
Position - The top of the content section
Problem - The title is inconsistent with the title text size on the dashboard. The sizes don't match.
Suggestion - It would be better to maintain that size maybe a reusable component would help here. So either we use a larger text or a smaller text (I would prefer a larger one so that it commands attention when being viewed)

## Issue #13

Timestamp - 0:54
Position - The modal for edit project
Problem - Description input field title says "description"
Suggestion - The actual text should read "Description" not lowercase letters all through

## Issue #14

Timestamp - 0:54
Position - The modal for edit project
Problem - The start date shows the initial date as an ISO Timestamp
Suggestion - Start date should show a user readable date so that users can understand what they are looking at

## Issue #15

Timestamp - 0:54
Position - The modal for edit project
Problem - The end date shows the initial date as an ISO Timestamp
Suggestion - End date should show a user readable date so that users can understand what they are looking at

## Issue #16

Timestamp - 1:08
Position - The list section on the projects page
Problem - The timeline dates are represented weirdly.
Suggestion - 

## Issue #17

Timestamp - 0:56
Position - Edit project card
Problem - No label on the field that has "Free" as its auto selected value in the select input
Suggestion - A label should be provided here so the user knows exactly what this field is for

## Issue #18

Timestamp - 1:07
Position - Top right on projects table
Problem - The status field on the table shows "status" as lowercase letters
Suggestion - The status field should be written as "Status"

## Issue #19

Timestamp - 1:10
Position - top pane on single project view
Problem - The single project view is not carrying the title/name of the project being viewed
Suggestion - The project name should be visible so users can know what project they are currently on

## Issue #20

Timestamp - 1:13
Position - Device pane in single project
Problem - Design consistency for "Remove Device" action
Suggestion - To ensure design consistency, it might be better to replace this text with a cancel or "X" button so that it matches up with other page list actions

## Issue #21

Timestamp - 1:17
Postion - Whole list component
Problem - The texts are not properly aligned to the left
Suggestion - The texts on the page look a bit titled from the left when the point of reference is the table title as though they have been padded by the left

## Issue #22

Timestamp - 1:18
Position - content section of the entire layout
Problem - There seems to be a delay in loading certain visual elements that is not handled correctly
Suggestion - It's not exactly clear if the items being loaded into those cards are images that are taking time to load or whether the image links are gotten from an endpoint. In the former case, what we can try is to delegate a fallback image to display while the browser is still fetching the images. In the latter case, we can try to load via the server side rendering available to use in next js and combine with the previously mentioned solution to ensure that there is no break in transmission for the user.

## Issue #23

Timestamp - 1:19
Position - The title on the cards being displayed on the content section in the entire layout
Problem - The title seems to be too close to the images being rendered
Suggestion - We may try to add a layer of spacing so the text can be visibly seperated from the image on top of it.

## Issue #24

Timestamp - 1:19
Position - The cards on the content section in the entire layout
Problem - The card seems to have a static size but the images do not
Suggestion - The images should be wrapped to take up a certain size of the entire card space and set to respect those dimensions so they don't warp the sizing restrictions for other cards


