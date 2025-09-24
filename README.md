# ProXima - Real-Time Space Object Tracker <img width="40" alt="ProXima Logo" src="https://github.com/user-attachments/assets/your-logo-id-here">

<img width="1200" alt="ProXima Screenshot" src="https://github.com/user-attachments/assets/your-screenshot-id-here">

ProXima is a real-time tracking platform for monitoring asteroids and satellites using NASA’s public APIs. The project provides **interactive orbital visualizations**, **live asteroid tracking**, and integrates directly with NASA’s NeoWs and TLE datasets.  

🌍 Explore how objects move through space, visualize orbits dynamically, and keep up-to-date with near-Earth objects—all from your browser.  

Go to the project website [ here! ](https://your-vercel-link-here)  

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
✅ Responsive design for desktop & mobile  

---

## Tech Stack
- **Frontend**: Next.js, TypeScript, Canvas API  
- **Backend**: Spring Boot, Java, Docker  
- **APIs**: NASA NeoWs, TLE Satellite Data  
- **Deployment**: Vercel (Frontend), Render (Backend)  

---

## Hosting Services
- **Vercel**: Hosts the ProXima frontend, ensuring fast and reliable delivery.  
- **Render**: Hosts the backend services responsible for API communication and data handling.  

---

## Extra Info
Since the backend is deployed on **Render free tier**, services may occasionally sleep after a period of inactivity. To manually wake them up, visit these links and allow the projects to reload:  

[ -Frontend (Vercel) ](https://your-vercel-link-here)  
[ -Backend (Render) ](https://your-render-link-here)  

---

## Status
🔭 **Current Release**: Beta version  
- Asteroid tracking is fully functional.  
- Satellite tracking is currently in development.  

---

## TODO
- [ ] Fix satellite TLE position calculations  
- [ ] Add 3D visualization  
- [ ] Implement WebSocket updates for live data streaming  
- [ ] Add more NASA APIs  
- [ ] Re-enable caching in `SpaceDataService.java` and adjust `CacheConfig.java` for optimization and reduced API calls  

---

## Note
If ProXima does not appear to be working at a given time, it may be because the backend services have gone to sleep (Render free tier limitation). Reloading the Render link above should wake the services back up. If certain visualizations appear delayed, it may also be due to temporary API throttling from NASA’s endpoints.  
