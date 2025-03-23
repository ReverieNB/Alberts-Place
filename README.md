# Alberts-Place
Code used to create a library management system for materials in my apartment. First develop the backend code and database, then connect to a Shiny app or something similar. Some key skills to build through this project: OOP, general Python, perhaps test using AI to support some coding

Getting started
- Develop this readme
- Create classes.
- Create example list of materials. Store in database. 10 books, a few for the other classes
- Make sure class interactions (user actions) work as expected.
- Expand class stuff with info below.
- Add more materials

Ideas to expand the initial classes:
- Include due date (different by material) and checks for whether a user has an overdue item. If so, they cannot check out additional materials.
- Top level: material. Next level: book, record, blu-ray. Below book - physical (see how libraries refer to these), ebook, audiobook. Figure out how classes can inherit things from others
- User class should have a limit for items checked out
- Items should have an associated image. How to get this? API request to Goodreads, Letterboxd? Could also pull things like user ratings, genre?
- Waiting lists book materials that are already checked out?

App features
- User sign in and registration. May avoid password at first, just use an email username.
- All materials should be searchable, overall list can be filtered by material type, genre, other class properties
- Use one of Hannah's pictures for the logo
