# Anilist Custom CSS Theme

A sleek, modular, and customizable CSS theme for Anilist profiles inspired by several popular Anilist themes. This theme features elegant animations, a beautiful banner display, and comprehensive styling for all profile sections.

## Installation

To use this theme on your Anilist profile:

1. Go to your Anilist profile settings
2. Navigate to the "Custom CSS" section
3. Copy the entire content of `style.css` into the text area
4. Save your changes

## Customization

The theme includes numerous customization options through CSS variables. Open `style.css` and modify the values in the `:root` section to change:

- Theme colors
- Avatar appearance
- Background image
- Animation settings
- And more!

### Example Customizations

```css
:root {
  /* Change theme colors */
  --theme-primary-color: #ff5e7d; /* Change to your preferred color */
  --theme-secondary-color: #9370DB; /* Change to your preferred color */
  
  /* Change avatar */
  --avatar-url: url("YOUR_AVATAR_URL_HERE"); /* Replace with your image URL */
  --avatar-border-radius: 50%; /* Makes avatar circular */
  
  /* Change background */
  --background-url: url("YOUR_BACKGROUND_URL_HERE"); /* Replace with your image URL */
}
```

## Features

- **Beautiful Banner**: Custom banner styling with animated avatar
- **Stylish Stats Display**: Elegant presentation of anime/manga statistics
- **Animated Elements**: Smooth animations for various profile elements
- **Responsive Design**: Works well on different screen sizes
- **Customizable**: Extensive CSS variables for personalization
- **Modular Structure**: Code organized into logical modules for easy understanding

## Credits

This theme was inspired by and incorporates elements from the following Anilist users:
- anilist.co/user/Anzu
- anilist.co/user/BlueTaku
- anilist.co/user/Megumin (Kurisu)
- anilist.co/user/Sigma
- anilist.co/user/Hyperixn

## Preview

To see a preview of how the theme looks, open the `index.html` file in a web browser.

## Notes

- This is a modular CSS theme that has been structured to make customization easier
- The CSS files in the `css/modules` directory contain specific styling for different parts of the profile
- For best results, use high-quality images for avatar and background 