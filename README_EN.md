## 🌐 [Versão em Português do README](README.md)

# SpaceApp

SpaceApp is a project developed with React using Vite as the bundling tool. The project is an image gallery with features such as photo zoom, navigation through a sidebar, and image filters by popular categories. It is designed to be simple, efficient, and intuitive, with a focus on user experience.

## 🔨 Project Features

- **Image Gallery**: Displays an image gallery divided into popular categories and a section of featured images.
- **Image Zoom**: Allows the user to enlarge an image for a detailed view.
- **Sidebar Navigation**: The sidebar allows the user to filter images by different criteria, such as "Most Liked", "Most Viewed", "New", and "Surprise Me".
- **Responsive Interface**: The layout is responsive, adapting to different screen sizes from mobile devices to desktops.
- **Search Function**: The search functionality allows users to filter images by tags.

### Visual Example of the Project

![Project Example](https://github.com/user-attachments/assets/5989b964-c178-4e43-a048-39d172a609b1)

## ✔️ Technologies and Tools Used

- **React**: JavaScript library for building dynamic user interfaces.
- **Vite**: A build tool that provides fast and optimized development.
- **CSS-in-JS (Styled Components)**: Styling components directly within the code, focusing on reusability and maintainability.
- **Custom Fonts**: Use of custom fonts for a unique design (GandhiSans).
- **JSON**: For storing image data and tags.

## 📁 Project Structure

- **public/**
    - **icones/**: Contains the icons used in the system (e.g., favorites, expand, close).
    - **imagens/**: Contains images for the gallery and logos.
        - **galeria/**: Gallery images.
        - **populares/**: Popular images for featured display.
    - **index.html**: The main HTML file where React connects.
- **src/**
    - **App.jsx**: The root component that organizes and renders the application.
    - **components/**: Folder containing reusable components for the application.
        - **Banner/**: Component to display banners.
        - **BarraLateral/**: Sidebar navigation component.
        - **BotaoIcone/**: Icon button component.
        - **Galeria/**: Component to display the image gallery and tags.
        - **ModalZoom/**: Component to display images in zoom mode.
        - **Titulo/**: Component to display titles in different sections of the app.
    - **fotos.json**: JSON file containing data about the images displayed.
    - **main.jsx**: File that initializes the React app.
- **vite.config.js**: Vite configuration file for optimizing and building the project.

## 🛠️ Running the Project Locally

To run the project locally, follow the steps below:

1. **Ensure that Node.js is installed**:
    - [Node.js](https://nodejs.org/) is required to run the project. You can check if you have it installed with:

      ```bash
      node -v
      ```

    - If it's not installed, download and install the recommended version.

2. **Clone the Repository**:
    - Copy the repository URL and run the following command in your terminal:

      ```bash
      git clone <REPOSITORY_URL>
      ```

3. **Install Dependencies**:
    - Navigate to the project directory and run the following command to install the required dependencies:

      ```bash
      npm install
      ```

4. **Start the Project**:
    - After the dependencies are installed, run the following command to start the development server:

      ```bash
      npm run dev
      ```

    - The project will be available at [http://localhost:3000](http://localhost:3000) (or the address indicated in the terminal).

## 🌐 Deploy

To deploy the application, you can use platforms like Vercel or Netlify.

- **Vercel**: Just connect the repository to Vercel and it will handle the build and deploy.
- **Netlify**: Similar to Vercel, connect the repository to Netlify and it will manage the deploy automatically.
