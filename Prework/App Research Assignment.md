


# Social Media

## Swarm

#### Feed
- Worldwide / Nearby
	- position: Top
	- transition: Changes Feeds
- Magnifying Glass
	- position: Top
	- transition: Displays search text field and presents keyboard
- Heart
   - position: Next to each feed item
   - transition: likes post

#### Inbox
- Compose
	- position: Top right
	- transition: Push segue to create new message
- Notifications/Messages Toggle
	- Position: Top
	- transition: changes feed
	
#### Check-In
- Cancel
	- position: Top Left
	- transition: Presents feed
- Find
	- position: top right
	- transition: presents text field

#### Leaderboard
- Leaders/Stickers/Mayorships toggle
	- position: Top
	- transition: Changes view
	
#### Profile
- Add friends
	- position: Top left
	- transition: Modal segue to find friends connected on other social networks
- Settings
	- position: Top right
	- transition: Push segue to settings page
	
	
## Twitter

#### Home
- Add friends
	- position: Top
	- transition: Push segue to add friends
- Find
	- position: Top right
	- transition: Push segue with text field
- Compose
   - position: Top Right
   - transition: Modal/Popover segue to compose new tweet

#### Notifications
- Find
	- position: Top right
	- transition: Push segue with text field
- Compose
   - position: Top Right
   - transition: Modal/Popover segue to compose new tweet
	
#### Messages
- Mark as read
	- position: Top Left
	- transition: UIAlertController with options to mark as read
- New message
	- position: top right
	- transition: Modal/popover segue to compose message vc

#### Me
- Tweets/Media/Favorites Segmented Button
	- position: Top/Mid-Center
	- transition: Toggles feeds
- Settings
	- position: Top, right, next to handle
	- transition: UIAlertActionSheet
- Add Friends
	- position: Top right
	- transition: Modal segue to add friends
- Edit Profile
	- position: Top right
	- transition: Modal/popover to edit profile vc
- Find
	- position: Top right
	- transition: Push segue with text field
- Compose
   - position: Top Right
   - transition: Modal/Popover segue to compose new tweet




##  Medium

#### Home
- Find
	- position: Top right
	- transition: Modal segue to search controller with textfield
- Compose
	- position: Top right
	- transition: Modal segue to compose controller with textview

#### Top Stories
- Find
	- position: Top right
	- transition: Modal segue to search controller with textfield
- Compose
	- position: Top right
	- transition: Modal segue to compose controller with textview
- Continue reading
	- position: at bottom of each item in tableview
	- transition: Push segue to article detail view
- Bookmark
	- position: in toolbar at bottom
	- transition: none (bookmark icon fills)
- Share
	- position: bottom toolbar
	- transition: presents UIActivityView social sharing options
- Next
	- position: bottom toolbar
	- transition: push segue to next article

#### Bookmarks
- Find/Compose
	- position: top right
	- transition: modal segues (same as above)
	
#### Profile
- Stats
	- position: Underneath profile photo
	- transition: Presents web view of views, reads, and 	recommendations received. 
- Settings
	- position: Underneath profile photo, right
	- transition: Modal segue to settings page

# Games
##  Elevate

#### Training
- Individual game
	- position: Floating in vertical line, left of center
	- transition: Custom animation, opens game
- "Explore Pro"
	- position: Top right
	- transition: presents modal segue to view describing benefits of in-app purchase

#### Performance
- Share icon
	- position: top left
	- transition: Presents UIActivityView
- '?' icon
	- position: Top right
	- transition: Modal segue that presents help information regarding the performance metric displayed

#### Study
- Icons in collection view displaying topic
	- position: in UICollectionView
	- transition: Opens page-view controller about topic


#### More
- Games list
	- position: Top right
	- transition: Modal segue to list of all games
- "Explore Pro"
	- position: Top right
	- transition: Presents view about premium content
- Settings
	- position: Below header
	- transition: Push segue to settings page
- Help
	- position: Below settings
	- transition: Push segue to help information
- Feedback
	- position: Below Help
	- transition: Modal segue to compose email
- Log Out
	- position: Bottom of list
	- transition: Logs out user and transitions to log-in screen

	
## OK?

#### Current Level Screen
- Forward/Backward navigation buttons
	- position: Bottom left
	- transition: transitions to previous or next-level
- Game Center
	- position: Bottom right
	- transition: Push segue to game center
- Help
	- position: Bottom right
	- transition: How-to play information slides up from bottom of screen

## Bouncing Ball

#### Game Screen
- "Tap To Start" button
	- position: Horizontal center and below vertical center
	- transition: Begins level
- Replay
	- position: Appears when game is over
	- transition: restarts level
- Settings
	- position: In ball rolling along center line
	- transition: adds ball to screen for sound-mute

- Leaderboard
	- position: In ball rolling along center line
	- transition: Modal segue to leaderboard
- Share
	- position: In ball rolling along center line
	- transition: Presents UIActivityView for social sharing
- Achievements
	- position: In ball rolling along center line
	- transition: Modal segue to user achievements
- "No-Ads"
	- position: In ball rolling along center line
	- transition: Prompts user for in-app purchase to remove adds


	

# Apps That Use the Camera
## VSCOcam

#### Profile
- Sizer
	- position: Top left
	- transition: changes size of images in view
- Feeds
	- position: Top center
	- transition: enables selection between different post types
- Add
	- position: Top right
	- transition: Enables selection of post type, then segue to composer 

#### Explore
- Images
	- Position: In feed
	- transition: Tapping a photo enables saving, and viewing meta-data about photo
	
#### Library
- Options
	- position: top left
	- transition: Presents drop-down menu to filter library
- Sizer
	- position: Top center
	- transition: changes size of images in library view
- Saved images
	- position: Top center
	- transition: presents collection view of saved images

#### Shop
- Filter Pack
	- position: In table view
	- transition: Push segue to detail information
- Buy
	- position: In table view next to each filter pack and in detail view
	- transition: Prompts user for in-app purchase

#### Capture
- Options
	- position: Top left
	- transition: expands to reveal different photo-capture items
- Capture Button
	- position: Bottom center
	- transition: captures image and produces "flash" on screen to indicate successful capture
- Gallery
	- position: Bottom right
	- transition: transitions to library view

#### Settings
- position: in Master-detail on left
- transition: reveals nav controller for various settings
   
	
## Google Photos

#### Main View
- Expand Menu
	- position: Top left
	- transition: Slides out menu items from left
- Add
	- position: Top right
	- transition: Presents action sheet to select type to add
- View Style
	- position: Top right
	- transition: Action sheet to select preferred viewing style
- Find
	- Position: In bottom right hand corner
	- transition: Modal segue to search 

## DayOne

#### Main Page
- Camera
	- position: Top left
	- transition: Modal presentation of image picker
- '+'
	- position: Top right
	- transition: Push segue to compose new entry 
- Timeline
	- position: Below camera and add
	- transition: Push segue to tableview of entries
- Photos
	- position: Below timeline
	- transition: push segue to collection view of images
- Settings
	- position: Bottom of list
	- transition: Modal segue displaying settings options

	
# Messaging Apps
## Slack

#### Main Screen
- '#'
	- position: Top left
	- transition: slides out side menu of channels and direct messages
- Channel settings
	- position: Top left
	- transition: Modal segue to settings for specific channel
- Find
	- position: Top right
	- transition: Modal segue to search controller
- Menu
	- position: Top right
	- transition: Slides out menu listing mentions, files, stared, directory, settings, team...

	
## Mailbox

#### Inbox Screen
- Menu
	- position: Top left
	- transition: Slides out menu for selecting different groupings
- Segmented Control
	- position: Top center
	- transition: Toggles between messages saved for later, current inbox, and archive
- Compose
	- position: Top right
	- transition: Modal pop-over segue to compose new message

## Facebook Messenger

#### Recent
- Each message thread
	- position: In table view
	- transition: Tapping a message triggers push segue to view message thread 
- Phone
	- position: Top right
	- transition: Modal segue to make a call
- Compose
	- position: Top right
	- transition: Modal segue to compose new message 

#### Groups
- Pin
   - position: Top left
   - transition: Modal segue to pin recent groups to main collection view 
- Create
   - position: Top right
	- transition: Modal segue to create new group 

#### People
- Find
 - position: Top left
 - transition: Modal search controller appears from top and bottom 
- All/Active
 - position: Top center
 - transition: Toggles between lists of all contacts and currently active contacts
- Add
 - position: Top right
 - transition: Modal Pop-over segue displays phone number entry to create new contact
- Call
 - position: In table view next to each contact name
 - transition: Triggers call and pushes to call view

#### Settings
- Settings Page
	- Position: Bottom right
	- transition: Displays settings/options in grouped settings table view
	


--






