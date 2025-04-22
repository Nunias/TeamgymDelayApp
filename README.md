# TeamgymDelayApp – Real-Time Video Delay App for Gymnastics Training

> A simple yet powerful application for real-time performance analysis through adjustable video delay. Originally built for artistic gymnastics and TeamGym, but adaptable to any sport.

---

## Objective

Allow gymnasts to **visualize their jumps and movements with adjustable delay**, using a camera connected to a locally running system. A web interface provides easy control over delay settings and system state.

This project was born out of a practical need during TeamGym training, where **immediate visual feedback** is essential to correct technique and improve performance.

---

## Tech Stack

| Component            | Technology             |
|----------------------|------------------------|
| Video Processing     | Python + OpenCV        |
| Backend API          | .NET Core (Web API)    |
| Frontend UI          | React / JS             |
| Backend Deployment   | Azure App Service / AWS |
| Frontend Deployment  | Azure Static Web Apps / Netlify |
| Integration          | REST API + JSON        |

---

## How It Works

1. A camera streams live video into a Python-based system  
2. A **circular buffer** stores the last N seconds of frames  
3. Delay is controlled through a simple web interface  
4. The delayed video is displayed on a second monitor/screen  
5. The frontend sends commands to the backend (.NET), which communicates with the Python system  

---
