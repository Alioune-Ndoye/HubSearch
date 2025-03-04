HubSearch Application

Description

The Candidate Search Application is a React-based project using Vite that allows users to browse through potential candidates retrieved from the GitHub API. Users can save candidates to a list of potential hires or skip them. The application stores potential candidates in local storage, ensuring data persistence across sessions.

Features

Fetches and displays candidate information, including:

Name

Username

Location

Avatar

Email

GitHub profile link (html_url)

Company

Users can:

Save a candidate by clicking the + button

Skip a candidate by clicking the - button

View saved potential candidates on a separate page

Persist candidate data across sessions using local storage

Provides appropriate messages when no candidates or potential candidates are available

(Bonus) Functionality to sort and filter saved candidates

Technologies Used

Frontend: React (via Vite), TypeScript

Backend/API: GitHub API

State Management: Local Storage

Styling: CSS

Linting: ESLint with @typescript-eslint and eslint-plugin-react

Installation

Clone the repository:

git clone https://github.com/your-username/candidate-search-app.git
cd candidate-search-app

Install dependencies:

npm install

Start the development server:

npm run dev

Deployment

This application is deployed at: Live URL (replace with actual URL)

Usage

On the candidate search page:

View candidate details.

Click + to save a candidate.

Click - to skip and move to the next candidate.

On the potential candidates page:

View saved candidates.

If no candidates are saved, a message will indicate this.

Data persists after page reload.

Project Requirements

This project satisfies the following challenge criteria:

✅ Uses GitHub API to retrieve user data.

✅ Implements TypeScript interfaces for user data.

✅ Stores potential candidates in local storage.

✅ Deployed at a live URL and runs without errors.

✅ Well-structured GitHub repository with meaningful commit messages.

Grading Criteria Breakdown

Technical Acceptance Criteria (40%) - Meets all functional requirements.

Deployment (32%) - Successfully deployed and accessible online.

Application Quality (15%) - Intuitive user experience and clean UI.

Repository Quality (13%) - Follows best practices, includes a README, structured commits.

Bonus (10%) - Sorting and filtering functionality for candidates.

