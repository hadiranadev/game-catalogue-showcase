# game-catalogue-showcase

This repository is a **portfolio showcase** of a game catalogue web application built with **SvelteKit** and **Firebase** as part of a group academic project that simulated an Agile-style development workflow.

> The original source code is maintained in a private repository due to team restrictions and to avoid exposing sensitive Firebase-related configuration.
> This repository exists to showcase the project’s functionality, interface, architecture, and my contributions.

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

- Google-based user authentication with separate sign-up and login flows.
- Role-based access control for admin and standard user behavior.
- CRUD functionality for game catalogue entries.
- Interactive UI components, including modals and game detail views.
- Responsive layout styled with TailwindCSS and DaisyUI.
- User-specific favourites and wishlist functionality separated from the main catalogue.

---

## My Contributions

My work focused primarily on frontend functionality, UI behavior, and user experience. In particular, I contributed to:

- Refining the authentication flow by separating sign-up and login behavior for a clearer user experience.
- Building and styling frontend components using TailwindCSS and DaisyUI.
- Designing and implementing interactive interface elements such as modals and detailed game views.
- Connecting frontend UI behavior to Firebase services for authentication and data-driven updates.
- Adding favourites and wishlist functionality and separating those views from the main catalogue interface.
- Improving interface consistency, usability, and general presentation across core screens.

---

## Demo / Screenshots

### Authentication (Sign-Up / Login)
Users can authenticate via Google with separate login and sign-up flows.
![Sign-Up & Login Authentication](/assets/auth.gif)

### Search & Filtering
Users can search and filter via title and genres respectively.
![Search & Filter](/assets/filter.gif)

### Game Management (Add / Edit / Delete)
Admins can modify game entries, and add or delete games.
![Add/Delete/Edit](/assets/modify.gif)

### Favourites & Wishlist
Users can add games to their favourites or wishlist.
![Favourite/Wishlist](/assets/archive.gif)

---

## Architecture (High-Level)

- **SvelteKit** was used to structure the application around reusable components and client-side routing.
- **Firebase Authentication** handled user identity and login state.
- **Firestore** was used as the application datastore for game records and user-linked data.
- **Role-based UI logic** controlled which actions and screens were available to different users.
- **User-specific collections and views** were separated from the main catalogue for features such as favourites and wishlists.

---

## Key Takeaways

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