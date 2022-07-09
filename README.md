# macOS URL Schemes for macOS Applications

# Add Printer
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| ipp://                        | Opens Add Printer.app                   |                                       |
| ipps://                        | Opens Add Printer.app                   |                                       |


# App Store
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| macappstore://                        | Opens App Store.app                   |                                       |
| macappstores://                       | Opens App Store.app                   |                                       |
| itms-apps://                          | Opens App Store.app                   |                                       |
| itms-appss://                         | Opens App Store.app                   |                                       |
| itms-apps://itunes.apple.com          | Opens App Store.app                   |                                       |
| itms-apps://itunes.apple.com/app/id   | View a specific app in the store      | itms-apps://itunes.apple.com/app/id404009241  |
| itms-apps://search.itunes.apple.com/WebObjects/MZSearch.woa/wa/search?media=software&term=SearchTerm   | Search for a term | itms-apps://search.itunes.apple.com/WebObjects/MZSearch.woa/wa/search?media=software&term=Games |


# Airport Utility
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| apconfig://                           | Opens Airport Utility.app             |                                       |
| apupdate://                           | Opens Airport Utility.app             |                                       |


# Books
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| ibooks://                             | Opens Books.app                       |                                       |
| itms-books://                         | Opens Books.app                       |                                       |
| itms-bookss://                        | Opens Books.app                       |                                       |
| ibooks://books.apple.com/book/id       | View a specific book in the book store |  https://books.apple.com/book/id1445220910 |
| ibooks://books.apple.com/audiobook/id  | View a specific audiobook in the book store | ibooks://https://books.apple.com/audiobook/id1445220910 |


<!-- # Calculator
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| calc://                               | Opens Calculator.app                  |                                       | -->


# Calendar
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| ical://                               | Opens Calendar.app                    |                                       |
| webcal://                             | Opens the 'add subscription' dialog in Calendar.app   |                       |
| webcal://SubscriptionURL              | Subscribes to the calendar at the specified URL   |                           |


# Contacts
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| addressbook://                        | Opens Contacts.app                    |                                       |


# Dictionary
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| dict://                               | Opens Dictionary.app                  |                                       |
| x-dictionary://                       | Opens Dictionary.app                  |                                       |
| dict://Term                           | Searches all dictionaries for the given term  |                                       |
| x-dictionary://Term                   | Searches all dictionaries for the given term  |                                       |


# Facetime
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| facetime://                           | Opens Facetime.app                    |                                       |
| facetime-audio://                     | Opens Facetime.app                    |                                       |
| tel://                                | Opens Facetime.app                    |                                       |
| facetime-group://                     | Opens Facetime.app                    |                                       |
| facetime-open-link://                 | Opens Facetime.app                    |                                       |
| facetime://PhoneNumberOrEmail         | Starts a Facetime video call          |                                       |
| facetime-audio://PhoneNumberOrEmail   | Starts a Facetime audio call          |                                       |
| tel://PhoneNumberOrEmail              | Starts a Facetime audio call          |                                       |


# Feedback
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| applefeedback://                      | Opens Feedback Assistant.app          |                                       |
| applefeedback://new                   | Create a new feedback entry           |                                       |


# Files
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| smb://HostIPOrURL                     | Connects to an SMB server                    |                                       |

# Find My
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| findmy://                             | Opens Finy My.app                     |                                       |
| fmip1://                              | Opens Finy My.app                     |                                       |
| fmf1://                               | Opens Finy My.app                     |                                       |
| grenada://                            | Opens Finy My.app                     |                                       |
| findmy://devices                      | Opens the 'Devices' tab of Find My    |                                       |
| findmy://items                        | Opens the 'Items' tab of Find My      |                                       |


# GitHub Desktop
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| github-mac://                         | Opens Github Desktop.app              |                                       |
| x-github-client://                    | Opens Github Desktop.app              |                                       |
| x-github-desktop-auth://              | Opens Github Desktop.app              |                                       |


# Help Viewer
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| help://                               | Opens Help Viewer.app                 |                                       |
| x-apple-helpbasic://                  | Opens Help Viewer.app                 |                                       |
| x-apple-tips://                       | Opens the "Getting Started" help window   |                                       |



# Keynote
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| x-keynote-live://                     | Opens Keynote.app                     |                                       |
| com.apple.iwork.keynote-live://       | Opens Keynote.app                     |                                       |


# Maps
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| map://                                | Opens Maps.app                        |                                       |
| maps://                               | Opens Maps.app                        |                                       |
| mapitem://                            | Opens Maps.app                        |                                       |
| x-maps-mapitemhandles://              | Opens Maps.app                        |                                       |
| x-maps-bulletin://                    | Opens Maps.app                        |                                       |
| x-maps-ac-auth://                     | Opens Maps.app                        |                                       |
| maps://?q=SearchTerm                  | Search Map for the given term         | maps://?q=Food                        |


# Mail
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| message://                            | Opens Mail.app                        |                                       |
| mailto:EmailAddress                   | Create a new email draft              | mailto:example@example.com            |
| mailto:EmailAddress?cc=EmailAddress   | Create a new email draft with a cc recipient          | mailto:example@example.com    |
| mailto:EmailAddress?bcc=EmailAddress  | Create a new email draft with a bcc recipient         | mailto:example@example.com    |
| mailto:EmailAddress?subject=Text      | Create a new email draft with specified subject line  | mailto:example@example.com    |
| mailto:EmailAddress?body=Text         | Create a new email draft with the specified body text | mailto:example@example.com    |


# Messages
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| imessage://                           | Opens Messages.app                        |                                   |
| messages://                           | Opens Messages.app                        |                                   |
| im://                                 | Opens Messages.app                        |                                   |
| ichat://                              | Opens Messages.app                        |                                   |
| itms-messages://                      | Opens Messages.app                        |                                   |
| itms-messagess://                     | Opens Messages.app                        |                                   |
| sms://                                | Opens Messages.app                        |                                   |
| sms://PhoneNumber                     | Opens a new text to the given phone number    | sms://1-800-123-1234          |
| sms-private://PhoneNumber             | Opens a new text to the given phone number    | sms-private://1-800-123-1234  |
| sms://AppleIDEmail                    | Opens a new text to the given iCloud account  | sms://example@icloud.com          |
| sms-private://AppleIDEmail            | Opens a new text to the given iCloud account  | sms-private://example@icloud.com  |


# Music
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| music://                              | Opens Music.app                        |                                      |
| musics://                             | Opens Music.app                        |                                      |
| itsradio://                           | Opens Music.app                        |                                      |
| itunesradio://                        | Opens Music.app                        |                                      |
| itals://                              | Opens Music.app                        |                                      |
| italss://                             | Opens Music.app                        |                                      |
| itms://                               | Opens Music.app                        |                                      |
| itmss://                              | Opens Music.app                        |                                      |
| itunes://                             | Opens Music.app                        |                                      |


# News
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| applenews://                          | Opens News.app                        |                                       |
| applenewss://                         | Opens News.app                        |                                       |


# Notes
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| notes://                              | Opens Notes.app                       |                                       |


# Numbers


# Photos
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| photos://                             | Opens Photos.app                      |                                       |
| photos-navigation://                  | Opens Photos.app                      |                                       |
| cloudphoto://                         | Opens Photos.app                      |                                       |


# Playgrounds
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| x-com-apple-playgrounds://            | Opens Playgrounds.app                 |                                       |


# Podcasts
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| pcast://                              | Opens Podcasts.app                    |                                       |
| podcast://                            | Opens Podcasts.app                    |                                       |
| podcasts://                           | Opens Podcasts.app                    |                                       |
| itms-podcasts://                      | Opens Podcasts.app                    |                                       |


# Reminders
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| x-apple-reminderkit://                | Opens Reminders.app                   |                                       |


# Safari
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| ftp://RemoteFilePath                  | Opens a file stored on an FTP server  |                                       |
| http://URL                            | Opens a website without SSL           |                                       |
| https://URL                           | Opens a website with SSL              |                                       |
| file://FilePath                       | Opens the specified file in Safari    |                                       |


# Screen Sharing
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| vnc://                                | Opens a Screen Sharing.app            |                                       |


# Shortcuts
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| shortcuts://                          | Opens Shortcuts.app                          |                                |
| shortcuts-production://               | Opens Shortcuts.app                          |                                |
| workflow://                           | Opens Shortcuts.app                          |                                |
| shortcuts://create-shortcut           | Creates a new shortcut                       |                                |
| shortcuts://open-shortcut?name=Name   | Opens the specified shortcut                 |                                |
| shortcuts://run-shortcut?name=Name    | Runs the specified shortcut                  |                                |
| shortcuts://run-shortcut?name=Name&input=text&text=InputText  | Runs the specified shortcut with the given input string                   |                                       |
| shortcuts://run-shortcut?name=Name&input=clipboard            | Runs the specified shortcut with the content of the clipboard as input    |                                       |
| shortcuts://gallery                   | Opens the shortcuts gallery                  |                                |
| shortcuts://shortcuts/ID              | Installs the shortcut with the specified ID  |                                |

# Slack
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| slack://                              | Opens Slack.app                       |                                       |

# Stocks
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| stocks://                             | Opens Stocks.app                      |                                       |


# System Preferences
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| x-apple.systempreferences://          | Opens System Preferences.app          |                                       |
| otpauth://                            | Sets up a verification code for a URL |                                       |
| apple-otpauth://                      | Sets up a verification code for a URL |                                       |


# Terminal
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| ssh://                                | Opens an SSH session                  |                                       |
| telnet://                             | Opens a Telnet session                |                                       |
| x-man-page://                         | Opens the man page for a command      |                                       |


# TV
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| com.apple.tv://                       | Opens TV.app                          |                                       |
| com.apple.watchlist://                | Opens TV.app                          |                                       |
| videos://                             | Opens TV.app                          |                                       |
| daap://                               | Opens TV.app                          |                                       |
| itls://                               | Opens TV.app                          |                                       |
| itlss://                              | Opens TV.app                          |                                       |
| itvls://                              | Opens TV.app                          |                                       |
| itvlss://                             | Opens TV.app                          |                                       |


# Visual Studio Code
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| vscode://                             | Opens Visual Studio Code.app          |                                       |


# Voice Memos


# XCode
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| apple-reference-documentation://      | Opens Xcode.app                       |                                       |
| doc://                                | Opens Xcode.app                       |                                       |
| interface-builder://                  | Opens Xcode.app                       |                                       |
| x-xcode-documentation://              | Opens Xcode.app                       |                                       |
| xcbot://                              | Opens Xcode.app                       |                                       |
| xcdevice://                           | Opens Xcode.app                       |                                       |
| xcdoc://                              | Opens Xcode.app                       |                                       |
| xcode://                              | Opens Xcode.app                       |                                       |
| xcpref://                             | Opens Xcode.app                       |                                       |


# Zoom
| URL                                   | Purpose                               | Example                               |
|---------------------------------------|---------------------------------------|---------------------------------------|
| callto://                             | Opens Zoom.app                        |                                       |
| sip://                                | Opens Zoom.app                        |                                       |
| tel://                                | Opens Zoom.app                        |                                       |
| zoommtg://                            | Opens Zoom.app                        |                                       |