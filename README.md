# Times Table Bingo 🎲

An interactive times table bingo game for classroom use, with printable cards and a digital caller display.

## Features

✅ **Customizable Times Tables** - Select which times tables to include (2-12)  
✅ **Printable Cards** - Generate as many bingo cards as you need  
✅ **Digital Caller Display** - Project on your board to call questions  
✅ **Click-Through Interface** - Question → Answer → Next Question  
✅ **History Tracking** - Shows all previously called questions  
✅ **Smart Card Generation** - Cards designed to give good chances of winning  

## How to Use

### 1. Open the Game
Visit the `index.html` file in your browser (or host on GitHub Pages - see below)

### 2. Select Times Tables
- Use quick select buttons (e.g., "2-10 Times Tables")
- Or manually check individual times tables
- Select at least one times table to continue

### 3. Configure Your Game
- Set the number of cards you need (1-50)
- Each card gets 24 random answers in a 5×5 grid with a free center space

### 4. Generate Cards
Click **"Generate Printable Cards"** to:
- Open a new window with all your bingo cards
- Print them all at once (each card on its own page)
- Each card shows spaces where students write the multiplication when called

### 5. Open Caller Display
Click **"Open Caller Display"** to:
- Open the projection display in a new window
- Full-screen this window and project it for your class
- Click anywhere to advance through: Question → Answer → Next Question
- View call history in the sidebar
- Track game statistics

### 6. Play the Game!
1. Project the caller display on your board
2. Distribute printed cards to students
3. Click to show a multiplication (e.g., "6 × 4")
4. Students find the answer (24) on their card
5. Click again to reveal the answer
6. Students write "6×4" in the space under the number
7. Click again for the next question
8. First to get 5 in a row, column, or diagonal calls BINGO!

## Caller Display Controls

- **Click anywhere** - Advance to next state
- **Skip button** - Skip current question
- **Reset button** - Start a new game
- **Spacebar/Enter** - Advance (keyboard shortcut)
- **R key** - Reset game (keyboard shortcut)
- **S key** - Skip question (keyboard shortcut)

## Hosting on GitHub Pages

### Quick Setup

1. Create a new repository on GitHub
2. Upload both files:
   - `index.html`
   - `caller.html`
3. Go to Settings → Pages
4. Select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click Save
7. Your game will be live at: `https://yourusername.github.io/repository-name/`

### File Structure
```
your-repo/
├── index.html      (main page - select tables & generate cards)
└── caller.html     (caller display - project on board)
```

## Tips for Best Results

### Card Generation
- **For faster games**: Use fewer times tables (e.g., 2-5)
- **For longer games**: Use more times tables (e.g., 2-12)
- **Optimal class size**: Generate 1-2 extra cards beyond your class size
- **For variety**: Regenerate cards for each game

### Classroom Management
- **Print in advance**: Generate and print cards before class
- **Use card sleeves**: Students can use whiteboard markers and reuse cards
- **Multiple rounds**: Reset the caller and play again with the same cards
- **Small prizes**: Keep games engaging with small rewards

### Technical Tips
- **Browser compatibility**: Works best in Chrome, Edge, Firefox, or Safari
- **Full-screen mode**: Press F11 (or Fn+F11) to full-screen the caller
- **Offline use**: Download both HTML files and use them locally
- **No installation needed**: Everything runs in the browser

## How It Works

### Smart Card Generation
- Each card gets 24 unique numbers from your selected times tables
- Numbers are randomly distributed across cards
- The center space is always FREE
- Cards are designed to give realistic chances of winning

### Question Randomization
- All possible questions from selected times tables are shuffled
- Each question is called only once per game
- The sidebar tracks all called questions
- Skip function available if you accidentally advance

## Troubleshooting

**Problem**: "No game configuration found" error in caller  
**Solution**: Make sure you generate cards or open caller from the main page

**Problem**: Cards won't print properly  
**Solution**: Check your print settings - use Portrait orientation, scale 100%

**Problem**: Caller display looks wrong  
**Solution**: Make sure you're viewing in a modern browser, try refreshing

**Problem**: Can't see the sidebar  
**Solution**: Make sure your window is wide enough (minimum 1400px recommended)

## Browser Support

✅ Chrome/Edge (Chromium)  
✅ Firefox  
✅ Safari  
✅ Modern mobile browsers  

## License

Free to use for educational purposes. Created for Roseville College.

## Credits

Created with ❤️ for Year 5 students learning times tables!
