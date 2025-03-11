# Goodreads-React
##Backend repo: https://github.com/eng-hussein-saad/goodreads-node
##Host: https://goodreads-react-8o8l.vercel.app/
- A web application that allows users to browse, search, and review books, built with React and integrated with a Node.js backend.

## Features

- 📚 **Browse Books**: View books by categories, authors, and popularity.
- 🔍 **Search**: Find books and authors easily.
- ⭐ **Reviews & Ratings**: Users can rate and review books.
- 📖 **User Library**: Keep track of books you want to read.
- 🛒 **Subscription & Payments**: Upgrade to premium for additional features.
- 🔑 **Authentication**: Secure login, registration, and Google OAuth support.
- 📄 **Admin Dashboard**: Manage books, authors, and categories.

## Tech Stack

### Frontend
- React.js (with Vite for fast builds)
- React Router
- Axios for API calls
- Material UI & Bootstrap for styling
- React Query for data fetching

### Backend
- Node.js with Express.js
- MongoDB & Mongoose ORM
- JWT Authentication
- Stripe for payment processing

## Installation & Setup

### Prerequisites
- Node.js & npm installed
- MongoDB running locally or in the cloud

### Clone Repository
```sh
git clone git@github.com:OmarSameh2001/goodreads-react.git
cd goodreads-react
```

### Install Dependencies
```sh
npm install
```

### Environment Variables
Create a `.env` file in the root directory and add:
```
VITE_API_BASE_URL=https://your-backend-url
```

### Run Development Server
```sh
npm run dev
```
Visit `http://localhost:5173` in your browser.

## Deployment
### Build Production Version
```sh
npm run build
```

### Deploy to Vercel or Netlify
- Push your code to GitHub
- Connect GitHub repository to Vercel/Netlify
- Set environment variables in the platform dashboard

## Contribution
1. Fork the repository
2. Create a new branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-name`)
5. Open a pull request

## Authors
- **Omar Sameh** - [GitHub](https://github.com/OmarSameh2001)
- **Hussein Saad** - [GitHub](https://github.com/eng-hussein-saad)
- **Aisha Amr** - [GitHub](https://github.com/aishaa205)
- **Hoda Magdy** - [GitHub](https://github.com/Hoda-ArtCoder)

## License
This project is licensed under the MIT License.

---
### 📬 Contact
For issues or suggestions, open a GitHub issue or reach out to **eng.hussein.saad1@gmail.com**.

Happy Coding! 🚀
