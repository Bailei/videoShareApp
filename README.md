### A video data sharing app using my own-design restful API

### Use commend below to run the server on your localhost after clone this project:
* bundle install
* rake db:reset
* rails server
* <http://localhost:3000/> on any one of your broswers

### API document:    
##### -fetch videos data:
* '/videos'
* '/videos/[:p]'
* '/videos/[:p].json'


#####-pagination:
* '/videos[:page]'
* '/videos[:limit]&[:offset]'

### App:
- **Angular JS** driven web app that displays videos fetched from my own-design **restful API service**;
- Support **lazy loading**, each page will display **6 items** at most in a table format, the table header has four tabs, **id, title, description and logo image** respectively;
- Apply **pagination**
- Apply **bootstrap** to stylize the web layout;
- Has a search function that allows user to **filter videos** by video title;
- Allows user to **sort** videos by title, it happens when user **click the title header**;