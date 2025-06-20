# Interactive Vinyl Selector

An interactive web app that recommends vinyl albums from my personal collection based on mood, genre, and era preferences. Features era-based theming and will include Spotify integration for music previews.

## Features

### Version 2 (Current)
- **Era-based Color Theming**: The entire interface transforms based on your era selection
  - **Classic (50s-60s)**: Art Deco gold and black elegance
  - **Golden Age (70s)**: Earth tones and harvest colors  
  - **Modern (80s+)**: Electric neon cyber aesthetics
- **Dynamic Recommendations**: Get personalized album suggestions based on mood, genre, era, and familiarity preferences
- **External Data Management**: Albums loaded from JSON file for easy collection expansion
- **Smooth Transitions**: Animated theme changes with period-appropriate typography

### Version 1
- Basic recommendation engine
- Mood, genre, era, and familiarity filtering
- Responsive design with vinyl-themed aesthetics

## Upcoming Features

- **V3**: Direct search functionality across all album data fields
- **V4**: Spotify API integration for 30-second music previews  
- **V5**: Guest rating system and "Now Playing" status

## How It Works

1. Answer four quick questions about your current mood and preferences
2. Watch the interface transform based on your era selection
3. Get three personalized album recommendations with fun facts
4. Discover new music from a curated vintage collection

## Technical Details

- Pure HTML, CSS, and JavaScript
- Era-specific color palettes based on historical design trends
- Responsive design that works on all devices
- Modular JSON data structure for easy album management

## File Structure

```
├── index.html          # Main application (V2)
├── albums.json         # Album database
├── README.md          # This file
└── LICENSE            # MIT License
```

## Adding Albums

To expand the collection, simply add new entries to `albums.json` following this format:

```json
{
  "artist": "Artist Name",
  "album": "Album Title",
  "year": "YYYY", 
  "genre": "Genre",
  "funFact": "Interesting fact about the album."
}
```

## Live Demo

[View the live app here](https://abigailblue.github.io/interactive-vinyl-selector/) *(if GitHub Pages is enabled)*

## License

MIT License - Feel free to fork and customize for your own collection!
