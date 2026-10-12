# Technical Design Document – WE FOR EARTH

## 1. Purpose
Help youth learn about climate and trees, plant saplings, and follow each tree until it grows.

## 2. Users
Students, schools, youth groups and community volunteers.

## 3. Core loop
Learn → Pledge → Plant → Check in (every 30 days) → See survival on the dashboard

## 4. Architecture (prototype)
```
User (browser)
   |
index.html  (3 tabs: My Progress, Learn, Plant & Track)
   |
JavaScript  (lessons + quiz, validate, save, check-ins, points)
   |
Browser localStorage  (trees, points, completed lessons)
```

## 5. Data model
- **Tree:** name, species, place, status (Pledged or Planted), date, last check-in date, health (New, Alive, Needs care, Lost), number of check-ins
- **Points:** one total number
- **Completed lessons:** list of lesson numbers

## 6. Key features
1. Four lessons, each with a 3-question quiz
2. Native trees of Assam guide
3. Tree pledge form with validation
4. Tree log with survival check-ins and "Check-in due" after 30 days
5. Dashboard: trees pledged, trees planted, alive at last check-in, Green Points
6. Green Points: +5 add a tree, +2 check-in, +10 first full-score quiz on a lesson

## 7. Safety and quality
- User text is escaped before display, to stop script injection
- Storage errors are handled so the page does not break
- Mobile-friendly layout with visible keyboard focus

## 8. Limitations
Data stays on one device. No login. No photos. Lessons are short and written for beginners.

## 9. Roadmap
Shared database (e.g., Firebase or Supabase), photo check-ins, map view, school leaderboards, reminders, Assamese and Hindi support.

## 10. Sustainability model
Free and open source. Run through partnerships with schools, colleges, NGOs and local bodies. Very low hosting cost (GitHub Pages).
