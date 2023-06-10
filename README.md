# SnapAI
A full stack Midjourney and DALL-E AI Image generation application using the MERN stack, with the help of Tailwind CSS, Node.js and Cloudinary for storing images.
The front end is built using React and Tailwind CSS, while the Backend uses Node.js, Express.js, MongoDB and Cloudinary.
![image](https://github.com/SankalpUW/SnapAI/assets/113000067/95e64fe1-bb70-4c99-afd4-4a80ca1b9ed4)

# Installation

## Prerequisites
* MongoDB
* Node.js
* TailwindCSS
* NPM
* Cloudinary account and API keys
* Open AI API key

## Steps
  1. Clone the repository to your local machine:   
    `git clone https://github.com/SankalpUW/SnapAI`
  2. Install dependencies for both the frontend and backend:  
    `cd client
    npm install
    cd ../server
    npm install `
  3. Create a `.env` file in the backend directory and add the following:  
    `PORT=5000
    MONGODB_URI=<your-mongodb-cluster-name>
    CLOUDINARY_CLOUD_NAME=<your-cloudinary-cloud-name>
    CLOUDINARY_API_KEY=<your-cloudinary-api-key>
    CLOUDINARY_API_SECRET=<your-cloudinary-api-secret>
    OPENAI_API_KEY=<your-openai-api-key>`
  4. Start the backend server:  
    `cd server
     npm start`
  5. Start the frontend:  
    `cd client
    npm run dev`
  6. Change Server endpoint url:  
    `https://snapai-s859.onrender.com/api/v1/post" // Make all instances: "https://<projectname>.onrender.com/api/v1/post"`
# Usage
## Creating an Image
1. Navigate to the creationg page.
2. Enter a description of the image you want to generate and your name.
3. Click the "Generate" button.
4. Post it to the community.
