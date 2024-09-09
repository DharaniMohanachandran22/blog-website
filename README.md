# Movie Blog Website

This is a movie review blog website that provides users with detailed movie reviews, trailers, and more. The website consists of several pages, including a home page, about page, contact page, review page, trailer page, and individual blog pages for each movie. Users can search for movie reviews or filter reviews by genre.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Pages](#pages)
- [How to Use](#how-to-use)
- [File Structure](#file-structure)
- [Technologies Used](#technologies-used)

## Project Overview

The blog website showcases movie reviews written by an author. It provides a search and filter functionality to help users navigate through movie reviews based on their interests. Users can also watch movie trailers and read full reviews on dedicated blog pages. The website has a responsive design and is accessible through various devices.

## Features

1. **Navigation Bar**: 
   - Appears on all pages, contains links to Home, About, Contact, Review, Trailer, and Social Media pages (Facebook, Instagram, YouTube, Twitter).
   
2. **Search Functionality**:
   - Users can search for movie reviews by typing in the movie name. If the movie review exists, the user is redirected to the respective blog page. If not, they are redirected to the 'Oops' page, which includes navigation options to return to the home page.

3. **Filter Functionality**:
   - The filter icon in the navigation bar allows users to filter movie blogs by genre categories such as Comedy, Love, Horror, Animal, and Fantasy.

4. **Blog Cards on Home Page**:
   - Displays movie blog cards with an image, title, and a "Read More" link to the full blog post.

5. **Review and Trailer Pages**:
   - The review page contains videos from YouTube reviewers, descriptions, and links to full movie blogs.
   - The trailer page contains movie trailers and information about the movie with links to the full review.

6. **Author Information**:
   - On individual blog pages, clicking on the author's name shows a dropdown with the author's image, bio, and social media links.

7. **Oops Page**:
   - Displays when a search term doesn't match any movie blog, with navigation options back to the home page.

8. **Comment Section**:
   - Each movie blog page contains a comment box where users can submit their comments.

## Pages

1. **Home Page (`index.html`)**:
   - Contains blog cards with images, titles, and a link to read more.

2. **About Page (`about.html`)**:
   - Details the history, mission, and future goals of the website.

3. **Contact Page (`contact.html`)**:
   - Displays a dropdown with the website’s phone number and email.

4. **Review Page (`review.html`)**:
   - Lists YouTube review videos, brief descriptions, and links to full blog pages.

5. **Trailer Page (`trailer.html`)**:
   - Displays movie trailers with brief descriptions and links to full movie blogs.

6. **Blog Pages (`frozonBlogPage.html`, `greedyPeopleBlogPage.html`, `oujiaBlogPage.html`, etc.)**:
   - Each page contains a detailed review of a movie, including the author's name, review date, reading time, the full review, and a trailer.
   - Includes a comment section for user feedback.

7. **Oops Page (`oops.html`)**:
   - Appears when a search doesn't match any blog on the website. Contains a navigation link to the home page.

## How to Use

1. **Search for Movies**:
   - Use the search bar in the navigation menu to find specific movie reviews.
   
2. **Filter by Genre**:
   - Click the filter icon in the navigation bar to select genres such as Comedy, Horror, etc., and navigate to the respective blogs.

3. **Watch Trailers & Reviews**:
   - Visit the review and trailer pages for video content and links to movie reviews.

4. **Submit Comments**:
   - On the individual movie blog pages, users can leave comments about the movie.

## File Structure

```
/movieBlogWebsite
│
├── about.html
├── aboutStyle.css
├── baseBlogPageStyle.css
├── frozonBlogPage.html
├── frozonBlogPageStyle.css
├── greedyPeopleBlogPage.html
├── greedyPeopleBlogPageStyle.css
├── index.html
├── lionBlogPage.html
├── lionBlogPageStyle.css
├── oujiaBlogPage.html
├── oujiaBlogPageStyle.css
├── review.html
├── reviewStyle.css
├── trailer.html
├── oops.html
└── oopsStyle.css
```

## Technologies Used

- **HTML5**: Structure of the web pages.
- **CSS3**: Styling of the web pages.
- **JavaScript**: Search and filter functionality, dynamic dropdowns, and interactivity.

