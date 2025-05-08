# unblockzone

a website for accessing games and apps, designed with a focus on bypassing content filters.

## features

- games collection with standardized layout
- apps collection with standardized layout
- search functionality
- about:blank feature for enhanced privacy
- consistent layout across all pages

## game/app management scripts

several scripts are available to help manage games and apps on the site:

## Instructions
* Download the html files from the link above.
* Launch the website on your computer.
* Star And Fork This repository
* Share to your friends

### Your Spot Here
* Contact me on discord: https://discord.gg/XRkQyY2Hhy

## Dynamic Template System

The website now uses a dynamic template system that eliminates the need for individual HTML files for each game or app. Instead, it uses:

1. `game.html` - A single template that dynamically loads game data based on URL parameters (e.g., `game.html?id=minecraft`)
2. `app.html` - A single template that dynamically loads app data based on URL parameters (e.g., `app.html?id=spotify`)

### How It Works

1. Game/app data is stored in `data-games.js` and `data-apps.js`
2. When a user clicks a game/app card on the main pages, they are directed to the template with the appropriate ID
3. The template reads the ID from the URL, looks up the data, and dynamically constructs the page

### Benefits

- No need to maintain hundreds of individual HTML files
- Adding new games/apps only requires updating the data files
- Consistent user experience across all games/apps
- Easier to deploy and maintain

### Migration Scripts

To convert from the old approach (individual HTML files) to the new template approach:

## discord - https://discord.gg/JZ7q2F5Z
