# Game Catalogue (SvelteKit + Firebase)

A full-stack game catalogue web application featuring **authentication, role-based access control, and personalized user interactions**, built using SvelteKit and Firebase.

This project was developed in a team environment with an Agile-style workflow, with a strong focus on **UI consistency, user experience, and scalable feature design**.

> Note: The full source code is private due to team and Firebase configuration constraints. This repository showcases functionality, architecture, and key contributions.

---

## Overview

The application allows users to browse, manage, and interact with a catalogue of games through a responsive web interface.

It includes Google authentication, role-based access control, and dynamic UI behavior backed by Firebase services. The project was built collaboratively, with an emphasis on iterative development, feature delivery, and interface usability.

---

## Tech Stack

- **Frontend:** SvelteKit, TailwindCSS, DaisyUI 
- **Backend / Services:** Firebase Authentication, Firestore
- **Build Tool:** Vite
- **Other Tools:** GitHub, Trello

---

## Features

- **Google Authentication**
  - Secure login using Firebase Authentication
  - Separate login and sign-up flows for improved UX

- **Role-Based Access Control**
  - Admin vs standard user behavior
  - Admin-only actions such as editing, deleting, and hiding games

- **Game Catalogue System**
  - Create, edit, delete, and view game entries
  - Dynamic UI updates backed by Firestore

- **Hidden Game System**
  - Admins can hide/unhide games from the public catalogue
  - Visibility dynamically changes based on user role

- **Favourites & Wishlist**
  - User-specific collections stored in Firestore
  - Separate views from the main catalogue

- **Recommendation System**
  - Heuristic-based recommendations using:
    - Title similarity (sequels/prequels)
    - Shared companies
    - Genre overlap

- **Responsive UI**
  - Built with TailwindCSS and DaisyUI
  - Modal-based interaction and detailed game views

---

## My Contributions

I primarily owned **frontend development, UI behavior, and user experience design**.

Key contributions include:

- Designed and implemented core UI components using SvelteKit, TailwindCSS, and DaisyUI
- Built dynamic modals and detailed game view interfaces
- Integrated frontend logic with Firebase Authentication and Firestore
- Implemented favourites and wishlist systems with user-specific data handling
- Developed and refined authentication flows for clearer user interaction
- Contributed to role-based UI behavior (admin vs standard user)
- Improved consistency and usability across major application screens
- Contributed to recommendation system logic and presentation

I also played a key role in **polishing the interface and ensuring feature cohesion across the application**.

---

## Highlights

- Role-based system with admin-only controls
- Personalized user data (favourites & wishlist)
- Heuristic recommendation engine
- Clean, responsive UI with consistent interaction patterns
- Full integration with Firebase (Auth + Firestore)

--- 

## Demo

Showcases authentication, role-based viewing and permissions, expanded game view with related titles and reviewing games, and administrative controls (e.g., add, edit, delete, hide/unhide).

![Full Demo](/assets/Demo.mp4)

---

## Architecture (High-Level)

- **SvelteKit** was used to structure the application around reusable components and client-side routing.
- **Firebase Authentication** handled user identity and login state.
- **Firestore** was used as the application datastore for game records and user-linked data.
- **Role-based UI logic** controlled which actions and screens were available to different users.
- **User-specific collections and views** were separated from the main catalogue for features such as favourites and wishlists.

---

## What I Learned

- Built experience working with a backend-as-a-service architecture using Firebase.
- Improved my understanding of authentication flows, role-based UI behavior, and frontend-to-database integration.
- Gained practical experience developing features in a collaborative team environment using an Agile-style workflow.
- Learned the importance of keeping UI behavior, feature scope, and usability aligned in a multi-person project.

---

## Notes

- This project was developed collaboratively in a team environment.
- This repository is intended for **demonstration and portfolio purposes only**.
- Source code can be discussed or shared upon request if permitted.

---

## Future Improvements

- Strengthen filtering and search capabilities.
- Further improve UI polish, interaction feedback, and animations.
- Refactor parts of the frontend for better scalability and maintainability.
- Expand admin tooling and management controls.