# Tutorial on beforeunload Confirmation 

â¨ This code adds an event listener to the "beforeunload" event of the window object, which is triggered when the user is about to navigate away from the current page (e.g. by closing the browser window or navigating to a different URL).

Post by: @rochakeducation

ð event.preventDefault() prevents the default behavior of the "beforeunload" event, which is to display a confirmation dialog asking the user if they really want to leave the page.

ð event.returnValue = "" sets the returnValue property of the event object to an empty string, which prevents the default confirmation dialog from appearing when the user tries to leave the page.

â­ The advantage of using this code is that it can improve the user experience by displaying a confirmation dialog when the user tries to leave the page, which can be helpful in certain situations. However, it should be used carefully as it may prevent the user from being prompted to save unsaved work or data.

ð¥Feel free to DM me for suggestions, feedbacks or queries!

â¤ï¸ Hit the like button
ð¨ï¸ Share your thoughts in the comments!
ð Follow @rochakeducation  for more

Thanks for Reading âºï¸
.
.
.
.
#html #css #web #javascript #webdevelopment #developer #codenewbie #beginner #design #coding #programming #js #html5 #css3 #websites #tricks #j
