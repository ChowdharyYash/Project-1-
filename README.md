# SQL Project: Music Store Analysis 🎵

Hey there! Welcome to my SQL analysis project where I dive deep into an online music store's data to uncover some interesting business insights.

## What's This About?

I've always been fascinated by how data can tell stories, especially in the music industry. This project analyzes a music store database to answer real business questions that could help drive growth and make smarter decisions. Think of it as being a data detective for a music business!

## Getting Started

Want to run this project yourself? Here's how to get it working on your machine:

### Quick Setup
1. First, you'll need any SQL database system (I used PostgreSQL, but MySQL works too!)
2. Create a new database 
3. Set up the tables using the schema diagram below
4. Import the CSV files from my <a href="https://github.com/ChowdharyYash/Project-1-/tree/main/dataset">dataset folder</a>

**Note:** Make sure to import the tables in the right order to avoid foreign key issues. I'd suggest: artist → genre → album → track → customer → invoice → invoice_line → playlist → playlist_track.

## Database Schema

Here's how the database is structured. Pretty neat how all these tables connect, right?

![Schema Diagram](https://github.com/ChowdharyYash/Project-1-/blob/main/MusicDatabaseSchema.png)

## Tech Stack
* **Database:** PostgreSQL (because it's awesome and free!)
* **Tool:** PgAdmin4 (makes life so much easier)
* **Language:** SQL (obviously 😄)

## The Fun Part - Questions I Answered

I tackled some really interesting business questions in this analysis. Here are the highlights (check out the full <a href="https://github.com/ChowdharyYash/Project-1-/blob/main/analysis.sql">analysis.sql</a> file for all the queries):

* 🎸 What genres are killing it in sales?
* 🎤 Which artists are the real MVPs?
* 🎵 What songs are on repeat (aka most purchased)?
* 💰 How much are people actually spending on different music types?
* 🌍 Where in the world are the biggest music fans?

## Key Findings

After crunching the numbers, here's what I discovered:

* **Rock rules!** It's the most popular genre by far
* **Queens** takes the crown as the most popular artist (fitting name, huh?)
* **"War Pigs"** is the song everyone's buying
* Albums average around **$1** (great pricing strategy!)
* The **USA** is where most purchases come from (no surprise there)

## So What?

These insights are gold for the music store! They could:
- Stock more rock music since that's what sells
- Feature Queens and similar artists more prominently
- Run promotions in the US market
- Maybe bump those prices up a bit? 😉

## Want to Contribute?

Found something interesting or want to add more analysis? Feel free to:
1. Fork this repo
2. Add your own queries
3. Submit a pull request

If you have questions or run into issues, <a href="https://github.com/ChowdharyYash/ChowdharyYash/issues/1">let me know here</a>!

## Connect With Me

- 🔗 <a href="https://github.com/ChowdharyYash">GitHub</a>
- 💼 <a href="https://www.linkedin.com/in/yash2011/">LinkedIn</a>

## Acknowledgments

Big shoutout to this <a href="https://youtu.be/VFIuIjswMKM">YouTube tutorial</a> that helped me understand some complex queries better. Learning from others is how we grow!

## License

Feel free to use this project for your own learning. That's what it's here for! 

---

## Badges
![postgresql](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=amazondynamodb&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

---

**Happy Querying!** 🚀

*P.S. - If you found this helpful, give it a ⭐ on GitHub!*
