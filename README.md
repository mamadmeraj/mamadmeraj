<h1 align="center">Hi, I'm Meraj! 👋</h1>
<h3 align="center">🚀 Passionate about Security, Linux, and Crypto 🛡️🐧💰</h3>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=40&pause=1000&color=F7F7F7&center=true&vCenter=true&width=600&lines=Lanat+Be+Sansor;Down+with+Censorship">
</p>





---

## 🛠 Tech Stack:
<p align="center">
  <img src="https://skillicons.dev/icons?i=linux,bash,git,github,python,docker,vscode,html,css" />
</p>

---

## 📊 GitHub Stats:
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=mamadmeraj&show_icons=true&theme=radical" width="48%" />
  <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>3D Sphere with Three.js</title>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
</head>
<body>
  <script>
    const scene = new THREE.Scene();
    const camera = new THREE.PerspectiveCamera(75, window.innerWidth / window.innerHeight, 0.1, 1000);
    const renderer = new THREE.WebGLRenderer();
    renderer.setSize(window.innerWidth, window.innerHeight);
    document.body.appendChild(renderer.domElement);

    const geometry = new THREE.SphereGeometry(1, 32, 32);
    const material = new THREE.MeshBasicMaterial({ color: 0x0077ff });
    const sphere = new THREE.Mesh(geometry, material);
    scene.add(sphere);

    camera.position.z = 5;

    const animate = function () {
      requestAnimationFrame(animate);
      sphere.rotation.x += 0.01;
      sphere.rotation.y += 0.01;
      renderer.render(scene, camera);
    };

    animate();
  </script>
</body>
</html>

</p>

---

## 📬 Contact Me:
<p align="center">
  <a href="https://t.me/mamad_erj"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white"></a>
  <a href="mamadmeraj221@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>
