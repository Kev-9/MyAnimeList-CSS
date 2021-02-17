# Eorzea Collection CSS theme for MyAnimeList

Original page design from http://ffxiv.eorzeacollection.com/ by Edeon Vails.

MyAnimeList Forum: https://myanimelist.net/forum/?topicid=1726107

List CSS and adaption by MurakumoJP.

## Preview
https://myanimelist.net/animelist/MurakumoJP

![Screenshot](preview/Snapshot.png?raw=true)

## Features

* Supports anime and manga
* Uses MAL Modern Theme

## List Settings
On the List page, do the following.
https://myanimelist.net/editprofile.php?go=listpreferences

Anime List

![Screenshot](preview/ListSettings/AnimeList.png?raw=true)

Manga List

![Screenshot](preview/ListSettings/MangaList.png?raw=true)

After setting the list, go to the list Style Design page and move the slider from classic to modern.
https://myanimelist.net/ownlist/style

![Screenshot](preview/ListSettings/StyleEdit.png?raw=true)

Go to your list style editing page, and turn off these options.
https://myanimelist.net/ownlist/style/theme/1
![Screenshot](https://i.imgur.com/1pVzKRM.png?raw=true)

On the same page, in the Add Custom CSS field, paste the code shown below.

```css
@\import "https://malscraper.azurewebsites.net/covers/auto/presets/dataimagelinkafter";
~~@\import "https://murakumo-jp.github.io/MyAnimeList-CSS/Eorzea_Collection/Eorzea_Collection.css";~~
@\import "https://gitcdn.link/repo/Kev-9/MyAnimeList-CSS/master/Eorzea_Collection/Eorzea_Collection_temp-add-mod.css";
```
## Image Сhanges

If you want to change the images in CSS then paste this after the code and replace the links to your.

I recommend images with resolutions of 1053px250

```css
.list-container .cover-block {
    background-image: url("your images") !important;
}
```

Edit Color

```css
:root{
	--color: #Your color;
}
```
