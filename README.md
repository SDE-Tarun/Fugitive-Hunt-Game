# Fugitive Hunt Game

## Assumptions
- Cops select cities and vehicles independently.
- Vehicles must have enough range for a round trip.
- City selections must be unique for each cop.
- No actual database connections, using in-memory data structures for simplicity.

## Build Steps

### Backend
1. Navigate to `fugitive-hunt-backend` folder.
2. Install dependencies: `npm install`.
3. Start the server: `node src/server.js`.

### Frontend
1. Navigate to `fugitive-hunt` folder.
2. Install dependencies: `npm install`.
3. Start the development server: `npm start`.

## Deployment
### Backend
1. Install Heroku CLI: `npm install -g heroku`.
2. Login to Heroku: `heroku login`.
3. Create Heroku App: `heroku create fugitive-hunt-backend`.
4. Deploy: `git add .`, `git commit -m "Deploy backend"`, `git push heroku master`.

### Frontend
1. Install Netlify CLI: `npm install -g netlify-cli`.
2. Login to Netlify: `netlify login`.
3. Build: `npm run build`.
4. Deploy: `netlify deploy --prod --dir=build`.

## Screenshots
![Screenshot 1](screenshot1.png)
![Screenshot 2](screenshot2.png)