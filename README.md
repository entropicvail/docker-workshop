# <span style="color:Snow">Basic Containerized App</span>

This application is a very basic implementation of vite (front-end), exrpess (back-end), containerized in docker and run with docker compose.

Caddy is also added in to provide basic https functionality.

**<span style="color:SteelBlue">Services that are available after running:</span>**
<span style="color:SeaGreen">*Front-end*</span>
- https://ui.localhost
- http://localhost:5173

<span style="color:SeaGreen">*Back-end*</span>
- https://api.localhost
- http://localhost:3001

## <span style="color:DarkOrange">Requirements</span>
- Docker
- A web browser

## <span style="color:DarkOrange">Instructions</span>

### <span style="color:Peru">1. Clone this repo:</span>
```bash
git clone git@github.com:entropicvail/docker-workshop.git
```
### <span style="color:Peru">2. Navigate into the repo directory:</span>
```bash
cd docker-workshop
```

### <span style="color:Peru">3. Start the app:</span>
```bash
docker compose up
```

### <span style="color:Peru">4. To stpo the app (from the docker-workshop directory):</span>
```bash
docker compose down
```
---
<span style="color:Snow">*License: MIT* </span>
