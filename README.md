clone the repo

Inside the backend folder create a .env file

MONGO_URI=XXXXXXXXX
JWT_SECRET=XXXXXXXXX
CLOUDINARY_CLOUD_NAME=XXXXXXXXX
CLOUDINARY_API_KEY=XXXXXXXXX
CLOUDINARY_API_SECRET=XXXXXXXXX

Add these environment variables to the .env file and enter your own credentials 

Next open the frontend folder, again create a .env file

VITE_PAYPAL_CLIENT_ID=XXXXXXXXXXX
VITE_BACKEND_URL=XXXXXXXXXXX

Add these environment variables to the .env file and enter your own credentials 

Once this is done, navigate to the backend folder - cd backend

- run command - npm install

- run command - npm run seed (this will populate poducts in the database for us to get started)

- You should see the message "Product data seeded successfully!"

run command npm run dev (to start the backend server on port 3000)

Open new terminal and navigate to the frontend folder - cd frontend

run command - npm install

- finally run command npm run dev (to start the frontend react app)
