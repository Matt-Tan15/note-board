<div align="center">  <img src="https://cdn-icons-png.flaticon.com/512/223/223002.png" width="40" alt="Logo" align="left" style="margin-right: 10px;"><h1 align="left">NoteBoard</h1>  </div>

A full-stack web application that enables cross-functional teams to manage documentation throughout each department, including engineering, partnerships, and leadership. 

Tech Stack: - TypeScript - Next.js - React - Convex

<div align="center" style="padding-left: 20px;">  <p width="25" alt="Logo" align="left" style="margin-right: 10px;">🔗<a href="https://note-board-app.vercel.app/">NoteBoard Live!</a></p></div>

<div align="center">  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c2/Blue_magnifying_glass_icon.svg/1200px-Blue_magnifying_glass_icon.svg.png" width="27" alt="Logo" align="left" style="margin-right: 10px;"><h2 align="left">Core Features</h2>  </div>

-   📝  **Notion-style Editor**  - Expedite document generation and modification processes.
-   📄   **File Management** - Optimized management of uploads, removals, and substitutions.
-   ♾️  **Unlimited Document Nesting**  - Smoothly structure data with a hierarchical organization.
-   🗑️  **Advanced Deletion**  - Intuitive garbage bin equipped with a sophisticated archive system.
-   💽  **Real-time Database**  - Instant data synchronization.
-   🔆  **Light and Dark Modes**  - User-centric display settings to cater to individual preferences.
-   🔒  **Secure Authentication**  - Secure access controls employing robust security mechanisms.
-   📡  **Publishing**  - Effortlessly share notes online with simple publishing tools.

<div align="center">  <img src="https://cdn-icons-png.freepik.com/512/6490/6490790.png" width="30" alt="Logo" align="left" style="margin-right: 10px;"><h2 align="left">Demo</h2>  </div>

### Landing Page
![image](https://github.com/Matt-Tan15/note-board/assets/91209885/f3ef62e5-fd7f-4917-acda-c2e1817fd615)

### Documents Page
![Screenshot 2024-05-05 181023](https://github.com/Matt-Tan15/note-board/assets/91209885/08f76402-0304-4461-9f95-c42e65278132)

### Search Feature
![Screenshot 2024-05-05 180854](https://github.com/Matt-Tan15/note-board/assets/91209885/ce5b5c86-20bc-407f-b241-89fe2ce6a572)

### Dark Mode
![Screenshot 2024-05-05 180749](https://github.com/Matt-Tan15/note-board/assets/91209885/3d450146-8a90-4b8f-865f-dfd3c395f2c5)

<div align="center">  <img src="https://cdn-icons-png.freepik.com/512/7730/7730324.png" width="30" alt="Logo" align="left" style="margin-right: 10px;"><h2 align="left">Built With</h2>  </div>

-   **TypeScript**
-   **React**
-   **Next.js**
-   **Convex**
-   **EdgeStore**
-   **Clerk**

<div align="center">  <img src="https://cdn-icons-png.flaticon.com/512/3382/3382506.png" width="30" alt="Logo" align="left" style="margin-right: 10px;"><h2 align="left">Start your own NoteBoard locally!</h2>  </div>

Follow these steps to get NoteBoard up and running on your machine:
### Step 1: Clone the repository

    git clone git@github.com:Matt-Tan15/note-board.git

### Step 2: Create an `.env` file:
Create a file in your root directory with the required environment variables

    NEXT_PUBLIC_CONVEX_URL=
    
    EDGE_STORE_ACCESS_KEY=
    EDGE_STORE_SECRET_KEY=
    
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
    CLERK_SECRET_KEY=

### Step 3: Install the dependencies

    npm i

### Step 4: Set up Convex

    npx convex dev

### Step 5: Run your app locally

    npm run dev
