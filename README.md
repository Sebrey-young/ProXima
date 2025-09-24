# ProXima - Proximal Orbital Object Map <img width="60" height="400" alt="Image" src="https://github.com/user-attachments/assets/ed640129-f879-4e82-8fc6-b412364b6107" />

<img width="1919" height="928" alt="Image" src="https://github.com/user-attachments/assets/211f9a6f-b2bd-476f-88df-dc7c4f9b902b" />

ProXima is a real-time tracking platform for monitoring asteroids and satellites using NASA’s public APIs. The project provides **interactive orbital visualizations**, **live asteroid tracking**, and integrates directly with NASA’s NeoWs and TLE datasets.  

🌍 Explore how objects move through space, visualize orbits dynamically, and keep up-to-date with near-Earth objects—all from your browser.  

Go to the project website [ here! ](https://proxima-gamma.vercel.app/)  

---

## Extra Info
Since the backend is deployed on **Render free tier**, services may occasionally sleep after a period of inactivity. To manually wake them up, visit these links and allow the projects to reload:   
[ -Backend (Render) ](https://proxima-backend.onrender.com)  

---

## Components
- **Frontend**: Built with Next.js, providing a responsive and interactive interface for real-time data visualization.  
- **Backend**: Powered by Spring Boot, handling data processing and API communication.  
- **APIs**: Integrated with NASA’s TLE (Two-Line Element) and NEOWS (Near-Earth Object Web Service) endpoints for up-to-date orbital and asteroid data.  

---

## Features
✅ Real-time asteroid tracking  
✅ Interactive orbital visualization  
✅ NASA API integration  
✅ Fast and Responsive Design  

---

## Tech Stack
- **Frontend**: Next.js, TypeScript, React, TailwindCSS 
- **Backend**: Spring Boot, Java, Docker  
- **APIs**: NASA NeoWs, TLE Data  
- **Deployment**: Vercel (Frontend), Render (Backend)  

---

## Hosting Services
- **Vercel**: Hosts the ProXima frontend, ensuring fast and reliable delivery.  
- **Render**: Hosts the backend services responsible for API communication and data handling.  

---

## Status
🔭 **Current Release**: Beta version  
- Asteroids, Space Stations, and Space Debris tracking is fully functional.  
- Satellite tracking is currently in development.  

---

## Note
If ProXima does not appear to be working at a given time, it may be because there have been too many calls to the NASA API. To Resolve this please just allow the server some time before reloading. If certain visualizations appear delayed, it may also be due to temporary API throttling from NASA’s endpoints. If these Issues persist please feel free to contact me, and I will fix them as soon as possible.
