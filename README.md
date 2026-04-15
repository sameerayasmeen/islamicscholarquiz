# Islamic Scholar Quiz

An interactive Islamic knowledge quiz game featuring multiple rounds of challenges designed to test and enhance understanding of Islamic teachings, history, and concepts.

## Features

### 🎯 Game Rounds
- **Foundational Knowledge (MCQ)**: Multiple choice questions covering basic Islamic concepts, prophets, and history
- **Letter Puzzle**: Fill-in-the-blank style puzzles with Islamic terms and names
- **Scramble Master**: Unscramble letters to form Islamic words and concepts
- **Visual Quest**: Emoji-based visual puzzles representing Islamic stories and figures

### 🏆 Scoring & Progression
- Point-based scoring system across all rounds
- Round-by-round progression with increasing difficulty
- Time-based challenges with visual timers
- Medal system for achievements (Bronze, Silver, Gold, Diamond)

### 👤 User Profiles
- Customizable scholar profiles with names and avatars
- Local storage for offline play
- Photo upload functionality

### 🏅 Leaderboard
- Global leaderboard using Supabase
- Anonymous authentication for score submission
- Hall of Scholars with top performers

### 🎨 Design & UX
- Beautiful glass-morphism UI with Islamic-inspired aesthetics
- Responsive design for desktop and mobile
- Smooth animations and transitions
- Audio feedback for interactions
- Dark theme with gold accents

### ☁️ Cloud Integration
- Supabase backend for data persistence
- Real-time leaderboard updates
- Cross-device profile synchronization

## Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Tailwind CSS
- **Backend**: Supabase (PostgreSQL, Authentication)
- **Audio**: Web Audio API
- **Icons**: Font Awesome
- **Fonts**: Google Fonts (Cinzel, Outfit)

## Setup Instructions

### Prerequisites
- Modern web browser with JavaScript enabled
- Internet connection for Supabase features
- Supabase account for backend setup

### Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/sameerayasmeen/islamicscholarquiz.git
   cd islamicscholarquiz
   ```

2. Open `final.html` in your web browser

### Supabase Setup (Optional)
1. Create a Supabase project at [supabase.com](https://supabase.com)
2. Enable anonymous authentication
3. Create the following tables:

   **profiles**:
   - `id` (text, primary key)
   - `username` (text)
   - `avatar_url` (text)

   **leaderboard**:
   - `user_id` (text)
   - `username` (text)
   - `score` (integer)
   - `avatar_url` (text)

4. Update the Supabase URL and anon key in `final.html`

## Game Rules

1. **Start**: Click "Begin Quest" to start the game
2. **Rounds**: Complete all 4 rounds in sequence
3. **Questions**: Answer within the time limit for each question
4. **Scoring**: Earn points based on speed and accuracy
5. **Progression**: Advance through rounds automatically
6. **End**: View final score and submit to leaderboard

## Browser Compatibility

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).

## Author

Created by Sameer Ayasmeen

---

*May Allah accept our efforts in spreading beneficial knowledge. 🤲*