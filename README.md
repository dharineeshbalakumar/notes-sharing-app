# NoteShare

A study notes sharing platform for students. Share your class notes, search by title or subject, like and save notes, and export or import notes to pass them to friends.

Built with plain HTML, CSS and JavaScript. No frameworks, no installs, no backend.

## Features

- Publish notes with a title, subject, summary, full text and an optional link to a PDF or slides
- Search across title, subject, author and note text
- Filter by subject and sort by newest or most liked
- Like and save notes, and a "My notes" tab for the ones you wrote
- Download a note as a `.txt` file or copy its text
- Export all notes to a JSON file and import notes from a friend
- Light and dark mode
- Notes are stored in the browser with `localStorage`

## Run it

Open `index.html` in any modern browser. That is all.

## Live demo

Turn on GitHub Pages (Settings, then Pages, then deploy from the `main` branch) and your link will be:

`https://YOUR-USERNAME.github.io/noteshare/`

## How it works

- `index.html` holds the page, styles and script in one file
- Notes are saved as JSON in `localStorage`, so each person sees only their own notes
- User text is escaped before it is shown, which prevents script injection
- Only `http` and `https` links are accepted

## Ideas for next steps

- Add a real database (Firebase or Supabase) so every user sees the same notes
- Add sign-in so each note belongs to an account
- Upload PDF files instead of only links
- Add comments on notes

## Author

Dharineesh P B, B.Tech Artificial Intelligence and Machine Learning, St. Joseph's College of Engineering, Chennai
