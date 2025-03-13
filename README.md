# Anilist CSS Collection

A modular, customizable CSS collection for enhancing your Anilist profile page. This repository contains various CSS modules that can be imported individually or as a complete theme.

## Usage

You can import any or all of the CSS files into your Anilist profile's custom CSS section:

```css
/* Core styles (recommended) */
@import url("https://jmjaj.github.io/anilist/style.css");

/* Optional modules */
@import url("https://jmjaj.github.io/anilist/css/modules/animations.css");
@import url("https://jmjaj.github.io/anilist/css/modules/navbar.css");
@import url("https://jmjaj.github.io/anilist/css/modules/banner.css");
@import url("https://jmjaj.github.io/anilist/css/modules/profile.css");
@import url("https://jmjaj.github.io/anilist/css/modules/activities.css");
@import url("https://jmjaj.github.io/anilist/css/modules/stats.css");
```

## Customization

You can customize various aspects of the theme by setting CSS variables in your Anilist profile's custom CSS:

```css
:root {
  /* General theme settings */
  --theme-primary-color: #6a54c9;
  --theme-secondary-color: #9370DB;
  --theme-accent-color: #ff5e7d;
  
  /* Avatar settings */
  --avatar-border-radius: 255px;
  --avatar-size: 100px;
  --avatar-url: url("YOUR_AVATAR_URL_HERE");
  
  /* Background settings */
  --background-url: url("YOUR_BACKGROUND_URL_HERE");
  --background-opacity: 0.8;
  
  /* Font settings */
  --header-font: 'Satisfy', cursive;
  --body-font: 'Roboto', sans-serif;
}
```

## Features

- Modern visual design with customizable colors
- Smooth animations and transitions
- Responsive layout that adapts to different screen sizes
- Customizable avatar, banner, and profile sections
- Enhanced activity feed styling
- Improved stats visualization
- Custom cursor and scrollbar styling

## Credits

Original design concepts from:
- @Hyperixn
- anilist.co/user/Anzu
- anilist.co/user/BlueTaku
- anilist.co/user/Megumin (Kurisu)
- anilist.co/user/Sigma

## License

MIT License 