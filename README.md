# VideoCourts/
├── .gitignore                  # Git ignore rules
├── README.md                   # Project documentation
├── LICENSE                     # Licensing information
├── frontend/
│   ├── pilot-index.html        # The master HTML file we just built
│   ├── assets/
│   │   ├── css/
│   │   │   └── custom.css      # For future custom overrides
│   │   └── js/
│   │       └── app.js          # Extract JS from HTML for better maintainability
├── backend/                    # (To be built) Node.js/Python backend
│   ├── package.json
│   ├── server.js
│   ├── routes/
│   │   ├── auth.js
│   │   ├── cases.js
│   │   ├── hearings.js
│   │   ├── bail.js
│   │   └── documents.js
│   ├── controllers/
│   ├── models/                 # Database schemas
│   └── middleware/             # Auth, rate limiting, CORS
└── docs/
    └── API_WIREFRAME.md        # Endpoint documentation-