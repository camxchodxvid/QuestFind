# CandidateTracker

CandidateTracker is a modern, responsive web application designed to streamline the process of reviewing and managing potential job candidates. The app allows recruiters to efficiently evaluate candidates with a Tinder-like swiping interface, saving preferred candidates for later review.

## Features

- **Candidate Review Interface**: View detailed candidate information including name, username, location, avatar, email, GitHub URL, and company
- **Simple Decision-Making**: Accept candidates with the "+" button or pass with the "-" button
- **Saved Candidate Repository**: Access a dedicated page of all previously saved candidates
- **Persistent Storage**: Candidate selections are saved between sessions
- **Responsive Design**: Works seamlessly across mobile and desktop devices

## User Flow

### Candidate Search Page

The main interface where you can review potential candidates:

- On initial load, information for the first candidate is displayed
- Click the "+" button to save a candidate to your potential candidates list and move to the next candidate
- Click the "-" button to skip the current candidate and move to the next one
- When all candidates have been reviewed, a message indicates no more candidates are available

### Potential Candidates Page

A repository of all candidates you've accepted:

- View a list of all saved candidates with their complete profile information
- Saved candidates persist between sessions
- If no candidates have been saved, an appropriate message is displayed

## Technical Implementation

- Built with [React/Vue/Angular] for a responsive single-page application experience
- Uses local storage for persistent data management
- Integrates with GitHub API to fetch candidate information
- Implements responsive design principles for mobile and desktop compatibility

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/candidate-tracker.git
   ```

2. Navigate to the project directory:
   ```
   cd candidate-tracker
   ```

3. Install dependencies:
   ```
   npm install
   ```
   or
   ```
   yarn install
   ```

4. Start the development server:
   ```
   npm start
   ```
   or
   ```
   yarn start
   ```

5. Open your browser and navigate to `http://localhost:3000`

## Future Enhancements

- Filtering candidates by skills or experience
- Adding notes to saved candidates
- Integration with applicant tracking systems
- Advanced analytics on candidate selection
- Dark/light mode toggle

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
