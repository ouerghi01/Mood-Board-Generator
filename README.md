# Mood Board Generator

## Project Overview
The **Mood Board Generator** is a fun and simple project designed for beginners who want to explore and learn a quirky stack of technologies. The goal is to create an app that generates random mood boards, combining quotes, images, and colors. It's perfect for studying how to build a full-stack application with less common tools while keeping things light and creative.

---

## Features
1. **Random Mood Boards**: Generate mood boards with random quotes, colors, and image suggestions.
2. **User Input**: Allow users to add their own favorite quotes and images.
3. **Save and Share**: Store mood boards and generate shareable links.
4. **Minimalistic UI**: A clean and simple design built with a rare frontend framework.

---

## Why This Stack?
This stack is intentionally chosen to be uncommon yet beginner-friendly, offering a chance to explore new tools and concepts:

- **Frontend**: [Elm](https://elm-lang.org/) - A functional programming language for building UIs.
- **Backend**: [Crystal](https://crystal-lang.org/) - A high-performance language with Ruby-like syntax.
- **Database**: [CouchDB](https://couchdb.apache.org/) - A NoSQL database that stores data as JSON documents.
- **Hosting**: [Fleek](https://fleek.co/) - A Web3 hosting platform for deploying decentralized apps.
- **Storage**: [MinIO](https://min.io/) - Lightweight object storage for images and other assets.

---

## Tech Stack
### Frontend
- **Language/Framework**: Elm
- **Purpose**: Build the UI for generating and displaying mood boards.

### Backend
- **Language**: Crystal
- **Purpose**: Serve APIs to provide random quotes, image URLs, and color palettes.

### Database
- **Tool**: CouchDB
- **Purpose**: Store mood board templates and user-generated boards.

### Hosting
- **Platform**: Fleek
- **Purpose**: Deploy the app using decentralized storage (IPFS).

### Storage
- **Tool**: MinIO
- **Purpose**: Store user-uploaded assets (e.g., images).

---

## Learning Goals
1. Understand the basics of Elm and functional programming.
2. Learn how to create a RESTful API using Crystal.
3. Get hands-on experience with CouchDB for NoSQL data management.
4. Explore decentralized hosting with Fleek and IPFS.
5. Learn how to use MinIO for lightweight object storage.

---

## Getting Started
### Prerequisites
Make sure you have the following installed:
- [Elm](https://guide.elm-lang.org/install.html)
- [Crystal](https://crystal-lang.org/install/)
- [CouchDB](https://docs.couchdb.org/en/stable/install/index.html)
- [MinIO](https://min.io/docs/minio/linux/index.html)
- A Fleek account for hosting

### Installation Steps
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/mood-board-generator.git
   cd mood-board-generator
   ```

2. **Frontend Setup:**
   - Navigate to the frontend directory.
   - Install Elm dependencies.
     ```bash
     elm init
     ```
   - Run the Elm development server.
     ```bash
     elm reactor
     ```

3. **Backend Setup:**
   - Navigate to the backend directory.
   - Install Crystal dependencies.
     ```bash
     shards install
     ```
   - Run the Crystal server.
     ```bash
     crystal run src/server.cr
     ```

4. **Database Setup:**
   - Start your CouchDB instance and configure it as needed.
   - Create a database named `moodboards`.

5. **MinIO Setup:**
   - Install and configure MinIO for local storage.
   - Add your MinIO credentials to the backend configuration.

6. **Deploy to Fleek:**
   - Follow [Fleek's guide](https://docs.fleek.co/hosting/quick-start/) to deploy your app.

---

## Folder Structure
```
mood-board-generator/
├── frontend/         # Elm code for the UI
├── backend/          # Crystal code for the API
├── database/         # CouchDB setup and configurations
├── storage/          # MinIO setup
└── README.md         # Project documentation
```

---

## Learning Resources
- **Elm**: [Official Elm Guide](https://guide.elm-lang.org/)
- **Crystal**: [Crystal Lang Docs](https://crystal-lang.org/reference/)
- **CouchDB**: [CouchDB Documentation](https://docs.couchdb.org/en/stable/)
- **Fleek**: [Fleek Documentation](https://docs.fleek.co/)
- **MinIO**: [MinIO Documentation](https://min.io/docs/minio/linux/index.html)

---

## Contributing
This project is for learning purposes. Feel free to experiment, break things, and submit pull requests to share improvements.

---

## License
This project is open-source and available under the [MIT License](LICENSE).

