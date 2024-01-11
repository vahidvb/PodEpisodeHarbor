# Pod Episode Harbor
[![J7bAMlV.th.png](https://iili.io/J7bAMlV.th.png)](https://freeimage.host/i/J7bAMlV)
## Podcast Website with Vue.js

A simple web application built with Vue.js to showcase and manage podcast episodes. The application allows users to view episode details, listen to episodes on CastBox and Spotify, and provides an easy-to-update JSON file to manage episode data.

## Features

- **Page Heading:** Display general podcast information, contact details, and a brief overview of the podcast theme.
- **Episodes List:** Present a chronological list of podcast episodes with titles, short descriptions, and links to individual episode details.

## Episodes File
- **JSON File:** Store all episode information in a JSON file, including title, pic url, description, release date, CastBox link, and Spotify link and...
- **Json Path:** assets/episodes.json
- **Episode Json Sample:**
```json
{
    "Number":3,
    "Name":"Beginner Lesson #2 - Nice Meeting You!",
    "Description":"Understand this lesson COMPLETELY with PDF Lesson Notes. Visit EnglishClass101.com!",
    "Date":"2023-12-29",
    "Length":"07:29",
    "Pic":"https://is1-ssl.mzstatic.com/image/thumb/Podcasts123/v4/6a/5d/ae/6a5dae07-1174-dfe1-62c5-aa4b2ff93366/mza_2679248944706651363.jpg/400x400bb.jpg",
    "Castbox":"https://castbox.fm/episode/Beginner-Lesson-2---Nice-Meeting-You!-id464195-id169112049?country=us",
    "Spotify":""
}
```
## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/vahidvb/PodEpisodeHarbor.git
2. Navigate to the project directory:

   ```bash
   cd podcast-site
3. Install dependencies:

   ```bash
   npm install
4. Run the development server:

   ```bash
   npm run serve
The application will be available at http://localhost:8080.
