# Hi, I'm [Your Name]

> DevOps & Full-Stack Engineer — building reliable, scalable systems with automation and containers.

---

## Tech Stack

**Infrastructure & Automation**

![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-2088FF?style=for-the-badge&logo=gitlab&logoColor=white)

**Backend & Database**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**Web & Frontend**

![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

---

## What I Do

- **Automate everything** — Ansible playbooks, CI/CD pipelines, infrastructure as code
- **Containerize & orchestrate** — Docker images, Kubernetes clusters, service meshes
- **Build & ship** — Python / Node.js / PHP backends, REST APIs, database design
- **Serve & scale** — Nginx reverse proxies, load balancing, performance tuning

---

## Quick Snippets

**Ansible — deploy a web service**

```yaml
- name: Deploy web service
  hosts: webservers
  become: yes
  tasks:
    - name: Ensure Docker is installed
      apt: name=docker.io state=present
    - name: Run Nginx container
      docker_container:
        name: nginx
        image: nginx:alpine
        ports:
          - "80:80"
```

**Docker — one-liner**

```bash
docker run -d --name app -p 3000:3000 node:18-alpine
```

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=default&hide_border=true" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=default&hide_border=true" alt="Top Languages" />
</p>

---

## Let's Connect

<p>
  <a href="https://linkedin.com/in/YOUR_LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:your@email.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://twitter.com/YOUR_TWITTER"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter" /></a>
</p>

---

<p align="center">
  <i>From <a href="https://github.com/YOUR_USERNAME">YOUR_USERNAME</a> — always building, always learning.</i>
</p>
