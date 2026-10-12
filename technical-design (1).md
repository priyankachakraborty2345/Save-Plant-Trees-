# Technical Design Document – WE FOR EARTH Tracker

## 1. Purpose
Help youth pledge, record and follow the trees they plant.

## 2. Users
Students, schools, youth groups and community volunteers.

## 3. Architecture (prototype)
```
User (browser)
   |
index.html  (page + form + table)
   |
JavaScript  (validate -> save -> show)
   |
Browser localStorage  (list of trees)
```

## 4. Data model
Each tree entry has: name, species, place, status (Pledged or Planted), date (auto-filled).

## 5. Key features
1. Pledge form with validation (all fields required).
2. Plantation log table.
3. Dashboard counters: trees pledged, trees planted, people taking part.
4. Clear log button.

## 6. Safety and quality
- User text is escaped before display, to prevent script injection.
- Storage errors are handled so the page does not break.
- Mobile-friendly layout and visible keyboard focus.

## 7. Limitations
Data stays on one device. No login. No photos.

## 8. Roadmap
Shared database (e.g., Firebase or Supabase), photo upload, map view, school leaderboards, sapling care reminders, local-language support.

## 9. Sustainability model
Free and open source. Run through partnerships with schools, colleges, NGOs and local bodies. Low hosting cost (GitHub Pages).
