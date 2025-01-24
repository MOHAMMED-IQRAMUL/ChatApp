Directory structure:
└── ChatApp/
    ├── README.md
    ├── LICENSE
    ├── package.json
    ├── readme    
    │   ├── FolderStructure.md
    ├── backend/
    │   ├── package-lock.json
    │   ├── package.json
    │   └── src/
    │       ├── index.js
    │       ├── controllers/
    │       │   ├── auth.controller.js
    │       │   └── message.controller.js
    │       ├── lib/
    │       │   ├── cloudinary.js
    │       │   ├── db.js
    │       │   ├── socket.js
    │       │   └── utils.js
    │       ├── middleware/
    │       │   └── auth.middleware.js
    │       ├── models/
    │       │   ├── message.model.js
    │       │   └── user.model.js
    │       ├── routes/
    │       │   ├── auth.route.js
    │       │   └── message.route.js
    │       └── seeds/
    │           └── user.seed.js
    └── frontend/
        ├── README.md
        ├── eslint.config.js
        ├── index.html
        ├── package-lock.json
        ├── package.json
        ├── postcss.config.js
        ├── tailwind.config.js
        ├── vite.config.js
        ├── public/
        └── src/
            ├── App.jsx
            ├── index.css
            ├── main.jsx
            ├── components/
            │   ├── AuthImagePattern.jsx
            │   ├── ChatContainer.jsx
            │   ├── ChatHeader.jsx
            │   ├── MessageInput.jsx
            │   ├── Navbar.jsx
            │   ├── NoChatSelected.jsx
            │   ├── Sidebar.jsx
            │   └── skeletons/
            │       ├── MessageSkeleton.jsx
            │       └── SidebarSkeleton.jsx
            ├── constants/
            │   └── index.js
            ├── lib/
            │   ├── axios.js
            │   └── utils.js
            ├── pages/
            │   ├── HomePage.jsx
            │   ├── LoginPage.jsx
            │   ├── ProfilePage.jsx
            │   ├── SettingsPage.jsx
            │   └── SignUpPage.jsx
            └── store/
                ├── useAuthStore.js
                ├── useChatStore.js
                └── useThemeStore.js
