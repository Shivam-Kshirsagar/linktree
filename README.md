Linktree
A Linktree-style web application built with Next.js and React. The project includes a navigation bar, public assets, and a MongoDB connection module.
Features
- Next.js application with file-based routing.
- Reusable navigation bar component.
- Navigation links for Templates, Marketplace, Discover, Pricing, and Learn.
- MongoDB connection setup in lib/mongodb.js.
- Static assets stored in the public folder.
Add or update this section as you implement more features in the project.

Tech Stack
- Next.js – React framework for the web application.
- React – User interface.
- JavaScript – Application programming language.
- MongoDB – Database connection support.
- CSS / Tailwind CSS utility classes – Styling.
Project Structure
linktree/
├── app/                 # Next.js app routes and pages
├── components/
│   └── Navbar.js        # Navigation bar component
├── lib/
│   └── mongodb.js       # MongoDB connection setup
├── public/              # Images, icons, and other static files
├── .env.local           # Local environment variables (do not commit)
├── .gitignore
├── package.json
└── README.md
Getting Started
1. Clone the repository
git clone https://github.com/Shivam-Kshirsagar/linktree.git
2. Open the project folder
cd linktree
3. Install dependencies
npm install
4. Configure environment variables
If your MongoDB connection uses an environment variable named MONGODB_URI, create a file named .env.local in the project root and add:
MONGODB_URI=your_mongodb_connection_string
Replace the example value with your own MongoDB connection string. Check lib/mongodb.js for the exact environment variable name used by your code.

Important: Never commit .env.local or share your database connection string publicly.
5. Start the development server
npm run dev
Open http://localhost:3000 in your browser.
Available Scripts
Command	Description
npm run dev	Starts the development server.
npm run build	Builds the application for production.
npm run start	Starts the production server after building.
npm run lint	Runs the lint script, if configured in package.json.


Deployment
You can deploy this Next.js application on a platform that supports Next.js, such as Vercel.

Before deployment:
1. Push the latest code to GitHub.
2. Add the required environment variables in your hosting platform.
3. Build and deploy the application.
4. Test the deployed website and database connection.
Contributing
1. Fork the repository.
2. Create a branch for your changes.
3. Commit your changes.
4. Push the branch to your fork.
5. Open a pull request.
Author
Shivam Kshirsagar

GitHub: Shivam-Kshirsagar
License
No license has been specified yet. Add a LICENSE file if you want others to use, modify, and distribute this project under specific terms.
