# Churchle

A more holy daily word puzzle. Churchle is a religious-themed word guessing game featuring words from the standard works of The Church of Jesus Christ of Latter-day Saints. Built with React, TypeScript, and Tailwind CSS.

**Play Churchle daily and test your knowledge of scriptural vocabulary!**

---

**Disclaimer**: This project uses words from the standard works of The Church of Jesus Christ of Latter-day Saints but is not affiliated with, owned, operated, or approved by The Church of Jesus Christ of Latter-day Saints. This is an independent, fan-made project created for educational and entertainment purposes.

## Features

- 🙏 **Religious-themed word list**: Over 2,000 biblical names, church terms, and faith-based vocabulary
- 📅 **Daily puzzle**: New word every day, cycling through the entire word list
- 🎨 **Multiple themes**: Dark mode and high contrast mode support
- 📊 **Statistics tracking**: Track your success rate, streaks, and guess distribution
- 🎮 **Hard mode**: Challenge yourself with stricter guessing rules
- 📱 **Responsive design**: Play on any device
- 🎯 **Win messages**: Encouraging messages like "Celestial Guess!", "Heavenly", and "Nephi would be proud!"

## How to Play

1. Guess the word in 6 tries
2. Each guess must be a valid 5-letter word
3. After each guess, the color of the tiles will change:
   - **Green**: Letter is correct and in the right position
   - **Yellow**: Letter is in the word but in the wrong position
   - **Gray**: Letter is not in the word
4. A new word is available each day at midnight

## Run Locally

Clone the repository and install dependencies:

```bash
git clone https://github.com/jethrojones/churchle.git
cd churchle
npm install
npm start
```

Open [http://localhost:3000](http://localhost:3000) to play locally.

## Technology Stack

- **React 17**: Component-based UI framework
- **TypeScript**: Type-safe JavaScript
- **Tailwind CSS**: Utility-first styling
- **Headless UI**: Accessible UI components
- **Local Storage**: Persistent game state and statistics
- **Fathom Analytics**: Privacy-focused usage tracking

## Word List

Churchle features a curated collection of over 2,000 words sourced from the standard works of The Church of Jesus Christ of Latter-day Saints, including:
- Names from the Book of Mormon, Bible, Doctrine and Covenants, and Pearl of Great Price
- Places mentioned in scripture (Perga, Golan, Jahaz)
- Scriptural terms and concepts
- Prophets and historical figures (Jonah, Nephi, Pratt)

## Development

### Build for Production

```bash
npm run build
```

### Run Tests

```bash
npm test
```

### Code Formatting

```bash
npm run lint    # Check formatting
npm run fix     # Auto-fix formatting
```

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve Churchle.

## License

This project is based on the open-source React Wordle template.

## Credits

Built with inspiration from the original Wordle game. Customized for religious education and vocabulary building.
