# Insta-Bot
It is a simple bot which goes to specific hashtags and like the respective user's posts and comments on their posts. It also follows the user if not already following. 

## Flowchart how it working :
1. Import libraries.
2. Connect with browser driver.
3. Using Selenium, we open the instagram through the some codes.
4. Then, the code uses pre-built hashtag list to do the following jobs :
      - Open the specific hashtag page
      - Like the respective user's post
      - Comment on the post
      - Follow the user if already not
      - Then to next post until the loop ends
      
5. Saves the user log for those who were followed.
