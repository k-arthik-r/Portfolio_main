
<h1 align='center'>Portfolio</h1>

<div align='center'>
  <a><img src="https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white"></a> &nbsp;
  <a><img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB"></a> &nbsp;
  <a><img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white"></a> &nbsp;
  <a><img src="https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white"></a> &nbsp;
  <a><img src="https://img.shields.io/badge/threejs-black?style=for-the-badge&logo=three.js&logoColor=white"></a> &nbsp;
  <a><img src="https://img.shields.io/badge/Framer Motions-FF5C5C?style=for-the-badge"></a> &nbsp;
  <a><img src="https://img.shields.io/badge/emailjs-FFA500?style=for-the-badge"></a>
</div>


## Installations

Installing Node Js and NPM:

Recommended : 18.16.0 LTS and above

<a href="https://nodejs.org/en" alt="node js">
        <img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" /></a>
        
      
## Installing Dependencies

Note: --legacy-peer-deps is used for version Controls.


Creating a React Template via Vite:

```bash
npm create vite@latest ./ -- --template react

```

Installing and Initializing Tailwind CSS:
```bash
npm install -D tailwindcss

npx tailwindcss init

```

Installing Requirments:
```bash
npm install --legacy-peer-deps @react-three/fiber @react-three/drei maath react-tilt react-vertical-timeline-component @emailjs/browser framer-motion react-router-dom
```

Initializing Tailwind CSS Compatible for Vite:
```bash
npm install --legacy-peer-deps  -D postcss autoprefixer

npx tailwindcss init -p

```

Installing three:
```bash
npm install --legacy-peer-deps three
```

## Other Requirments
Creating and using a Service from Email.JS:

<a href="https://www.emailjs.com/" alt="Email.js">
  <img src="https://img.shields.io/badge/emailjs-FFA500?style=for-the-badge"></a>
  
Outputs Required from the Services are:

`SERVICE_KEY`

`TEMPLATE_KEY`

`PUBLIC_KEY`

And Use the Above Three [Here](src/components/Contact.jsx)

