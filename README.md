# macOS URL Schemes for macOS Applications

# Add Printer
- `ipp://[Hostname or IP Address]` - Adds the printer with the specifier hostname/IP address, if it exists
- `ipps://[Hostname or IP Address]` - Adds the printer with the specifier hostname/IP address, if it exists
<br/><br/>

# Adobe Acrobat
- `acrobat://` - Opens Acrobat Pro DC.app
- `acrobat2018://` - Opens Acrobat Pro DC.app
- `acrobat2019://` - Opens Acrobat Pro DC.app
- `acrobat2020://` - Opens Acrobat Pro DC.app
- `acrobat2021.oauth2://` - Opens Acrobat Pro DC.app
<br/><br/>

# Adobe Illustrator
- `adbai://` - Opens Adobe Illustrator.app
<br/><br/>

# Adobe Photoshop
- `adbps://` - Opens Adobe Photoshop.app
<br/><br/>

# App Store
- `macappstore://` - Opens App Store.app
- `macappstores://` - Opens App Store.app
- `itms-apps://` - Opens App Store.app
- `itms-appss://` - Opens App Store.app
- `itms-apps://itunes.apple.com` - Opens App Store.app
- `itms-apps://itunes.apple.com/app/id` - View a specific app in the store - Ex: itms-apps://itunes.apple.com/app/id404009241
- `itms-apps://search.itunes.apple.com/WebObjects/MZSearch.woa/wa/search?media=software&term=SearchTerm` - Search for a term - Ex: itms-apps://search.itunes.apple.com/WebObjects/MZSearch.woa/wa/search?media=software&term=Games
- `itms-apps://itunes.apple.com/discover` - Displays the App Store "Discover" tab
- `itms-apps://itunes.apple.com/arcade` - Displays the App Store "Arcade" tab
- `itms-apps://itunes.apple.com/create` - Displays the App Store "Create" tab
- `itms-apps://itunes.apple.com/work` - Displays the App Store "Work" tab
- `itms-apps://itunes.apple.com/play` - Displays the App Store "Play" tab
- `itms-apps://itunes.apple.com/develop` - Displays the App Store "Develop" tab
- `itms-apps://itunes.apple.com/categories` - Displays the App Store "Categories"" tab
- `itms-apps://itunes.apple.com/updates` - Displays the App Store "Updates" tab
<br/><br/>

# Airport Utility
- `apconfig://` - Opens Airport Utility.app
- `apupdate://` - Opens Airport Utility.app
<br/><br/>

# Books
- `ibooks://` - Opens Books.app
- `itms-books://` - Opens Books.app
- `itms-bookss://` - Opens Books.app
- `ibooks://books.apple.com/book/id` - View a specific book in the book store - Ex: https://books.apple.com/book/id1445220910
- `ibooks://books.apple.com/audiobook/id` - View a specific audiobook in the book store - Ex: ibooks://https://books.apple.com/audiobook/id1445220910
<br/><br/>

<!-- # Calculator

- calc:// - Opens Calculator.app -->


# Calendar
- `ical://` - Opens Calendar.app
- `webcal://` - Opens the 'add subscription' dialog in Calendar.app
- `webcal://SubscriptionURL` - Subscribes to the calendar at the specified URL
<br/><br/>

# Contacts
- addressbook:// - Opens Contacts.app
<br/><br/>

# Dictionary
- `dict://` - Opens Dictionary.app
- `x-dictionary://` - Opens Dictionary.app
- `dict://Term` - Searches all dictionaries for the given term
- `x-dictionary://Term` - Searches all dictionaries for the given term
<br/><br/>

# Discord
- discord:// - Opens Discord.app
<br/><br/>

# Facetime
- `facetime://` - Opens Facetime.app
- `facetime-audio://` - Opens Facetime.app
- `tel://` - Opens Facetime.app
- `facetime-group://` - Opens Facetime.app
- `facetime-open-link://` - Opens Facetime.app
- `facetime://PhoneNumberOrEmail` - Starts a Facetime video call
- `facetime-audio://PhoneNumberOrEmail` - Starts a Facetime audio call
- `tel://PhoneNumberOrEmail` - Starts a Facetime audio call
<br/><br/>

# Feedback
- `applefeedback://` - Opens Feedback Assistant.app
- `applefeedback://new` - Create a new feedback entry
<br/><br/>

# Files
- `smb://HostIPOrURL` - Connects to an SMB server
<br/><br/>

# Find My
- `findmy://` - Opens Finy My.app
- `fmip1://` - Opens Finy My.app
- `fmf1://` - Opens Finy My.app
- `grenada://` - Opens Finy My.app
- `findmy://devices` - Opens the 'Devices' tab of Find My
- `findmy://items` - Opens the 'Items' tab of Find My
<br/><br/>

# GitHub Desktop
- `github-mac://` - Opens Github Desktop.app
- `x-github-client://` - Opens Github Desktop.app
- `x-github-desktop-auth://` - Opens Github Desktop.app
<br/><br/>

# Help Viewer
- `help://` - Opens Help Viewer.app
- `x-apple-helpbasic://` - Opens Help Viewer.app
- `x-apple-tips://` - Opens the "Getting Started" help window
<br/><br/>

# Keynote
- `x-keynote-live://` - Opens Keynote.app
- `com.apple.iwork.keynote-live://` - Opens Keynote.app
<br/><br/>

# Maps
- `map://` - Opens Maps.app
- `maps://` - Opens Maps.app
- `mapitem://` - Opens Maps.app
- `x-maps-mapitemhandles://` - Opens Maps.app
- `x-maps-bulletin://` - Opens Maps.app
- `x-maps-ac-auth://` - Opens Maps.app
- `maps://?q=[SearchTerm]` - Search Map for the given term - Ex: maps://?q=Food
- `maps://?q=[SearchTerm]&sll=[Latitude],[Longitude]` - Searches for the given query at the specified latitude and longitude - Ex: maps://?q=Food&sll=40.71455,-74.00712
- `maps://?q=[SearchTerm]&sll=[Latitude],[Longitude]&sspn=[Float],[Float]` - Searches for a term at the specified coordinate with the given coordinate width and height in view
- `maps://?q=[SearchTerm]&near=[Latitude],[Longitude]` - Searches for the given query near the specified latitude and longitude - Ex: maps://?q=Food&near=40.71455,-74.00712
- `maps://?ll=[Latitude],[Longitude]` - Centers the map at the given latitude/longitude coordinate
- `maps://?ll=[Latitude],[Longitude]&z=[Float]` - Centers the map at the given coordinate with the specified zoom level (between 2 and 21)
- `maps://?ll=[Latitude],[Longitude]&spn=[Float],[Float]` - Centers the map at the given coordinate with the given coordinate width and height in view
- `maps://?q=[Name],ll=[Latitude],[Longitude]` - Creates a pin with the specified name at the given coordinate
- `maps://?t=[m, k, h, or r]` - Sets the map to standard view, satellite, hybrid, or transit respectively
- `maps://?address=[Address]` - Displays the specified location - Ex: maps://?address=1%20Infinite%20Loop%20Cupertino%20CA
- `maps://?daddr=[DestinationAddress]` - Queries for directions to the specified address from your current location, using the preferred transport type
- `maps://?daddr=[DestinationAddress]&dirflg=[d, w, or r]` - Queries for directions to the specified address from your current location, using driving, walking, or public transit, respectively
- `maps://?daddr=[DestinationAddress]&saddr=[SourceAddress]` - Queries for directions to the destination address from the source address
<br/><br/>

# Mail
- `message:// ` - Opens Mail.app
- `mailto:EmailAddress` - Create a new email draft - Ex: mailto:example@example.com
- `mailto:EmailAddress?cc=EmailAddress` - Create a new email draft with a cc recipient - Ex: mailto:example@example.com
- `mailto:EmailAddress?bcc=EmailAddress` - Create a new email draft with a bcc recipient - Ex: mailto:example@example.com
- `mailto:EmailAddress?subject=Text` - Create a new email draft with specified subject line - Ex: mailto:example@example.com
- `mailto:EmailAddress?body=Text` - Create a new email draft with the specified body text - Ex: mailto:example@example.com
<br/><br/>

# Messages
- `imessage://` - Opens Messages.app
- `messages://` - Opens Messages.app
- `im://` - Opens Messages.app
- `ichat://` - Opens Messages.app
- `itms-messages://` - Opens Messages.app
- `itms-messagess://` - Opens Messages.app
- `sms://` - Opens Messages.app
- `sms://PhoneNumber` - Opens a new text to the given phone number - sms://1-800-123-1234 -
- `sms-private://PhoneNumber` - Opens a new text to the given phone number - sms-private://1-800-123-1234 -
- `sms://AppleIDEmail` - Opens a new text to the given iCloud account - sms://example@icloud.com -
- `sms-private://AppleIDEmail` - Opens a new text to the given iCloud account - sms-private://example@icloud.com -
<br/><br/>

# Music
- `music://` - Opens Music.app
- `musics://` - Opens Music.app
- `itsradio://` - Opens Music.app
- `itunesradio://` - Opens Music.app
- `itals://` - Opens Music.app
- `italss://` - Opens Music.app
- `itms://` - Opens Music.app
- `itmss://` - Opens Music.app
- `itunes://` - Opens Music.app
<br/><br/>

# News
- `applenews://` - Opens News.app
- `applenewss://` - Opens News.app
<br/><br/>

# Notes
- `notes://` - Opens Notes.app
- `notes://showNote?[ID]` - Shows the note with the given ID, if it exists - Ex: notes://showNote?identifier=ABD2A242-D919-47EC-9DAC-21959BC559F5
<br/><br/>

# Numbers


# Photos
- `photos://` - Opens Photos.app
- `photos-navigation://` - Opens Photos.app
- `cloudphoto://` - Opens Photos.app
<br/><br/>

# Playgrounds
- `x-com-apple-playgrounds://` - Opens Playgrounds.app
<br/><br/>

# Podcasts
- `pcast://` - Opens Podcasts.app
- `podcast://` - Opens Podcasts.app
- `podcasts://` - Opens Podcasts.app
- `itms-podcasts://` - Opens Podcasts.app
<br/><br/>

# Reminders
- `x-apple-reminderkit://` - Opens Reminders.app
<br/><br/>

# Safari
- `ftp://RemoteFilePath` - Opens a file stored on an FTP server
- `http://URL` - Opens a website without SSL
- `https://URL` - Opens a website with SSL
- `file://FilePath` - Opens the specified file in Safari
<br/><br/>

# Screen Sharing
- `vnc://` - Opens a Screen Sharing.app
<br/><br/>

# Shortcuts
- `shortcuts://` - Opens Shortcuts.app
- `shortcuts-production://` - Opens Shortcuts.app
- `workflow://`- Opens Shortcuts.app
- `shortcuts://create-shortcut` - Creates a new shortcut
- `shortcuts://open-shortcut?name=Name` - Opens the specified shortcut
- `shortcuts://run-shortcut?name=Name` - Runs the specified shortcut
- `shortcuts://run-shortcut?name=Name&input=text&text=InputText` - Runs the specified shortcut with the given input string
- `shortcuts://run-shortcut?name=Name&input=clipboard` - Runs the specified shortcut with the content of the clipboard as input
- `shortcuts://gallery` - Opens the shortcuts gallery
- `shortcuts://shortcuts/ID` - Installs the shortcut with the specified ID
<br/><br/>

# Slack
- `slack://` - Opens Slack.app
<br/><br/>

# Stocks
- `stocks://` - Opens Stocks.app
<br/><br/>

# System Preferences
- `x-apple.systempreferences://` - Opens System Preferences.app
- `x-apple.systempreferences://[BundleIDforPreferencePane]` - Opens a specific preference pane
- `x-apple.systempreferences://[BundleIDforPreferencePane]?[Anchor]` - Reveals a specific anchor within a preference pane
- `otpauth://` - Sets up a verification code for a URL
- `apple-otpauth://` - Sets up a verification code for a URL
<br/><br/>

# Terminal
- `ssh://` - Opens an SSH session
- `telnet://` - Opens a Telnet session
- `x-man-page://` - Opens the man page for a command
<br/><br/>

# TV
- `com.apple.tv://` - Opens TV.app
- `com.apple.watchlist://` - Opens TV.app
- `videos://` - Opens TV.app
- `daap://` - Opens TV.app
- `itls://` - Opens TV.app
- `itlss://` - Opens TV.app
- `itvls://` - Opens TV.app
- `itvlss://` - Opens TV.app
<br/><br/>

# Visual Studio Code
- `vscode://` - Opens Visual Studio Code.app
<br/><br/>

# Voice Memos


# XCode
- `apple-reference-documentation://` - Opens Xcode.app
- `doc://` - Opens Xcode.app
- `interface-builder://` - Opens Xcode.app
- `x-xcode-documentation://` - Opens Xcode.app
- `xcbot://` - Opens Xcode.app
- `xcdevice://` - Opens Xcode.app
- `xcdoc://` - Opens Xcode.app
- `xcode://` - Opens Xcode.app
- `xcpref://` - Opens Xcode.app
<br/><br/>

# Zoom
- `callto://` - Opens Zoom.app
- `sip://` - Opens Zoom.app
- `tel://` - Opens Zoom.app
- `zoommtg://` - Opens Zoom.app
- `zoommtg://zoom.us/join?confno=[Meeting ID]&pwd=[Meeting Password]` - Joins a Zoom meeting