[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/so8F8uYz)
Documentation for the Disaster Relief App: HelpNearby
Project Overview
# Disaster Relief App: HelpNearby

## Project Overview

**App Name**: Disaster Relief 
**Purpose**: Disaster Relief is a **social impact app** designed to assist individuals during emergencies by providing real-time information about nearby disaster relief centers, shelters, and resources. The app aims to bridge the gap between those in need and available humanitarian aid, ensuring timely access to essential services during crises.

### Key Features:
1. **Map Integration**: Displays nearby relief centers and shelters using the **Map** component.
2. **Resource List**: Provides a list of available resources (e.g., food, water, medical aid).
3. **Emergency Contacts**: Displays essential contact numbers for emergency services.
4. **login:** Did not include the login in because it does not make sense to have a login when in a disaster.
4. **Real-Time Weather Alerts**: Integrates weather data using the **Web** component to fetch data from an API.
5. **Resource Request Form**: Enables users to request specific resources.

### Target Audience:
- Individuals affected by natural disasters or emergencies.    
- Local authorities and emergency response teams.

### Social Impact:
Disaster Relief addresses critical challenges during disasters, such as lack of access to information, inefficient resource distribution, and delayed emergency response. By providing real-time data and facilitating communication, the app empowers communities to respond effectively to crises, saving lives and reducing suffering.

---

## Development Process

### 1. Planning and Research
- **Objective**: Identify the key challenges faced during disasters and determine how technology can address them.   
- **Outcome**: Defined the app’s core features and target audience.

### 2. Design
- **Wireframes**: Created wireframes for each screen (e.g., Home, Map, Resources, Login).  
- **Integration**: integrated the weather app in the maps secreen.

### 3. Frontend Development
- **MIT App Inventor Components**:  
  - **Map**: Used the **Map** component to display relief centers.  
  - **WebViewer**: Displayed weather alerts and resource information.  
  - **ListPicker**: Allowed users to select resources or volunteer options.  
  - **TextBox**: For user input (e.g., registration, resource requests).  
  - **Button**: For navigation and actions (e.g., "Search," "Submit").  
  - **Label**: For displaying text (e.g., instructions, results).  

### 4. Backend Development 
- **APIs**: Integrated weather APIs (e.g., Weather.api) using the **Web** component to fetch real-time weather data.  
- **url**: [text](https://www.weatherapi.com/my/)

### 5. Testing
- **Unit Testing**: Tested individual components (e.g., map integration, resource list).    
- **Bug Fixes**: Addressed issues related to input validation, map performance, and API integration.

### 6. Deployment
- **Platform**: Deployed the app as an Android application using MIT App Inventor’s **Build** feature.  
- **Distribution**: Shared the app with friend and brothers to implement extras.

---

## Code Review

- **Modularity**: The app’s blocks are divided into reusable procedures   
- **Readability**: Components and blocks are named descriptively (e.g., `btnSearch`, `lblResult`).  
- **Error Handling**: Input validation ensures the app handles invalid data gracefully.(e.g handles issue with the weather api not loading).  
- **Performance**: Optimized API calls and database queries to ensure fast response times.

---

## Resources Used

1. **MIT App Inventor Components**:  
   - **Map**: For displaying relief centers.  
   - **Web**: For fetching weather data from APIs.     

2. **APIs**:  
   - **OpenWeatherMap API**: For real-time weather alerts.  

3. **Tutorials**:  
   - MIT App Inventor documentation and tutorials for using the **Map** and **Web** components.  

---

## Summary of Development Process

1. **Ideation**: Identified the need for a disaster relief app and defined its core features.  
2. **Design**: Created wireframes and user flows to ensure an intuitive interface.  
3. **Development**: Built the app using MIT App Inventor, integrating components like **Map**, **Web**, and **TinyDB**.  
4. **Testing**: Conducted rigorous testing to ensure functionality and usability.  
5. **Deployment**: Built the app as an Android application and shared it with users for feedback.  

---

## Conclusion

Disaster Relief is a social impact app developed using MIT App Inventor to address critical challenges during disasters. By providing real-time information, facilitating resource distribution, and enabling communication, the app empowers communities to respond effectively to emergencies. The development process emphasized user-centric design, modular coding practices, and rigorous testing to ensure the app meets the needs of its target audience.  

video used for little things : 
like the list picker : [text](https://www.youtube.com/shorts/YJKWCBeH298)