<h1 align="center">
Better MDL 🤍</h1>
<h3 align="center">Enhance your <a href="https://mydramalist.com/" target="_blank">MyDramaList</a> experience~</h3>

<center><img src="https://dear-clouds.carrd.co/assets/images/image06.jpg"></center>

Better MDL is a project i'm working on to enhance the website. I've been using MDL since the very beginning and it hasn't improved that much over the years. So here I am, trying to make the website more friendly and modern!

If you have suggestions, feel free to post them on [this post](https://mydramalist.com/discussions/general-discussion/88611-gathering-feedbacks), just keep in mind that I can't access the API as they don't give keys anymore. Which means there's a limitation to what I can do on MDL.

*The themes I use in my screenshots are available on my [carrd](https://dear-clouds.carrd.co/#mdl-themes) or check my Github profile.*


## Installation
1. Install <a href="https://www.tampermonkey.net/" target="_blank">Tampermonkey</a> for your browser (or you preferred Userscripts Manager)

2. Install my userscript by clicking [here](https://github.com/dear-clouds/better-mdl/raw/main/better-mdl.user.js) and click "Install".

3. Go to <a href="https://mydramalist.com/account/profile" target="_blank">MyDramaList settings page</a> to customize the script, just like you would to edit your profile (*You need to scroll down to the end of the page to see the `Better MDL Settings` section*)

4. Try it out and let me know what you think!

### How to use / customize (MAKE SURE TO READ)

* For other website icons not in the settings, the first time you go on a title page, you will get asked if you want to allow a website on a screen <a href="https://imgur.com/E1eWJJW" target="_blank">like this</a>. Simply allow or forbid the websites you want.

* The first time you're using the Thumbnail View on a page, it might take a little while to load all the posters, especially if there's a lot of titles or if you have slow internet, just be patient.

* It might take a little while to show all your Friend ratings, especially if you have many friends or if you have slow internet, just be patient. Also to favorite/unfavorite a friend, just click the heart. It will reflect the change on refresh.

* For the pie chart "Titles by Country", the colors are the ones you defined in your settings for the status Currently Watching, Planned etc. (might change later)

### Known Bugs

* [**WON'T FIX**] Some titles don't have the right result for external searches. Currently there's nothing I can do as MDL don't refer to those external ids anywhere and scraping can only be that accurate. *But what you can do is reporting it to me and providing me the right urls for each website*. I plan to make a mapping file at some point if you have many titles with this issue.

## Features Available

#### Everywhere

* Back to Top button
* Hide comments with defined terms

#### Profile

* Titles by Country

#### Title pages

* Links to IMDB/Trakt etc.
* Ratings from IMDB/Rotten Tomatoes/Metacritic
* Link to Anilist for Adaptations
* Add a heart to your liked people
* Friend ratings & ability to put your favs at the top (*suggested by sailingmars*)

#### People pages

* 3 Layout Views (Original, Thumbnails & Posters)
* Status icons
* Show the total for each status on your list
* Sorting & Ordering options
* Hide completed titles
* Collapse the sections

### Screenshots
<p align="center">
<img src="https://dear-clouds.carrd.co/assets/images/gallery22/ebcc1fb5_original.jpg?v=21bef0a8" width="48%">
<img src="https://dear-clouds.carrd.co/assets/images/gallery22/1863a508_original.jpg" width="48%">
<img src="https://dear-clouds.carrd.co/assets/images/gallery22/0d9c43c7_original.jpg?v=e8880db8" width="48%">
<img src="https://dear-clouds.carrd.co/assets/images/gallery22/52fe79e5_original.jpg?v=9281e8b0" width="48%">
</p>


## To-do & Suggestions
| Task      | Doable? | ETA |
| :--- | :----: | :----: |
| Show ratings from friends on a drama's page | ✔️ | In progress |
| Do all of this for personal dramalist as well | ✔️ | In progress |
| Click on a status total to only show those titles | ✔️ | N/A |
| Add the top 3 genres on Poster View | ✔️ | N/A |
| Hide cancelled titles | ✔️ | N/A |
| Add the average friends score on a drama's page | ✔️ | N/A |
| Add emoji in comments | To check | N/A |

*This list might no be up-to-date so please check the official <a href="https://mydramalist.com/discussions/general-discussion/88611-gathering-feedbacks?r=notif&_nid=134641861&page=1" target="__blank">MDL Thread</a>.*

## Credits

* My script was originally inspired by <a href="https://greasyfork.org/en/scripts/414922-mydramalist-com-item-highlighter" target="_blank">Item Highlighter</a> by **luckz**
* Switched to <a href="https://github.com/momocow/webpack-userscript/" target="_blank">Webpack Userscript</a> starting v1.1.0 as my script was becoming too long