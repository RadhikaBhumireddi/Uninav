# UniNav - Campus Navigation and Event Discovery Web App

## Project Overview

UniNav is a web-based map service designed to help students navigate large university campuses and discover campus-specific events. Leveraging the What3Words API for precise location mapping, UniNav addresses common challenges related to campus navigation, event discovery, and real-time communication for students, faculty, and event organizers.

## Features

### Public, Private, and Group Modes

- **Public Mode**: Students can post and subscribe to campus events such as giveaways, free food, and alerts.
- **Private Mode**: Users can drop private pins for personal use, such as marking a parked car's location.
- **Group Mode**: Groups can share locations and event details privately, ideal for clubs, teams, or study groups.

### Event Discovery

- Browse campus events by categories like academic, social, or safety.
- Subscribe to events and receive real-time updates.

### Real-Time Notifications

- Stay updated with alerts and subscribed events through instant email notifications.

### Recommendation System

- Discover popular and trending events on campus based on factors like views, likes, and RSVPs.

### Precise Location Mapping

- Utilize the What3Words API for highly accurate location mapping, covering both outdoor and indoor areas.

### Unique Features

- **Voice Search**: Easily find events or locations using voice commands.
- **Custom Markers**: Personalize map markers for better navigation.
- **Weather Integration**: Get real-time weather updates integrated into the map.
- **Universal Search**: Search for events, locations, or categories in one unified search bar.

## Tech Stack

### Frontend
- React
- TypeScript
- CSS3
- Bootstrap

### Backend
- Java
- Spring Boot

### Database
- MongoDB with AES-256 encryption for secure and scalable data storage

### API Integration
- What3Words API for precise location services
- Google Maps for additional location services
- Google Calendar for event management
- Clerk API for user login
- S3 for image storage
- Weather API for weather updates

### Email Notifications
- Java Mail Sender for real-time alerts

### Tools and Technologies

#### IDEs
- **Frontend**: IntelliJ IDEA for consistent coding and collaborative development
- **Backend**: IntelliJ IDEA for Spring Boot development

#### Project Management
- **Jira**: Scrum boards for sprint management and task tracking
- **GitHub Issues**: For tracking project progress and collaboration

#### Methodologies
- **Cloud Computing**: Leverage scalable cloud solutions
- **DevOps**: CI/CD with Vercel and GitLab, Docker for automation
- **Software Engineering**: Agile Scrum methodology with iterative sprints and a structured lifecycle from analysis to testing

## How to Initialize and Set Up the Project

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the application:
   ```bash
   npm start
   ```
4. Ensure that your .env file with all the required parameters(GOOGLE_MAPS_API_KEY, CLERK_API_KEY, What3Words_API_KEY) should be placed in frontend folder. 

### Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Ensure Gradle is installed. If not, install it [here](https://gradle.org/install/).
3. Build the project:
   ```bash
   ./gradlew build
   ```
4. Run the Spring Boot application:
   ```bash
   ./gradlew bootRun
   ```
5. Ensure MongoDB is running locally on the default port (27017). If not, start MongoDB.
6. Provide all the required environmental variables (AWS_KEY, AWS_ACCESS_CODE, MongoDB_URL) either in the system variables or in a .env file which should be placed in the backend folder.

## How to Use Our App

1. Sign in to the website using your vt.edu domain email.
2. Get verified by clicking the "Post" button.
3. After verification, start posting events in public, private, and group categories.
4. Subscribe to categories of interest in the "Favorites" tab to get notifications.
5. Go to the "Events" tab and apply the "Trending" filter to view popular events.


## Hosted URL

Access the live application here:
[UniNav Hosted URL](https://uninav-git-development-final-divakar007s-projects.vercel.app/Uninav)

## Contact Information

For questions or collaboration, please contact the team:

- **Nikilesh Madala**: [nikileshm@vt.edu](mailto:nikileshm@vt.edu)
- **Divakara Rao Annepu**: [adivakararao@vt.edu](mailto:adivakararao@vt.edu)
- **Aparna Alamanda**: [aparnaa@vt.edu](mailto:aparnaa@vt.edu)
- **Radhika Bhumireddi**: [radhikab@vt.edu](mailto:radhikab@vt.edu)

---

