# Usman Nizam

## Software Engineer · GPU & ML Systems

Software engineer working across ML inference, GPU programming, and full-stack development. I currently contribute to [**neuroneural**](https://github.com/neuroneural), building fast, portable brain-MRI segmentation that runs on CPUs, NVIDIA, AMD and Apple GPUs, and in the browser. I also contribute to open-source projects including **Project MONAI** and **AMD ROCm**.

🔍 **Open to new roles** in ML inference and training, ML Systems, AI Infrastructure, and Backend Development. Reach me on [LinkedIn](https://www.linkedin.com/in/mohammad-usman-nizam-0835b61a3/) or by [email](mailto:12usmannizam@gmail.com).


## 🌍 Open Source Contributions

### [AMD ROCm](https://github.com/ROCm/rocm-libraries) · rocm-libraries (MIOpen)
- **[MIOpen dilated-convolution GEMM workspace (#15020)](https://github.com/ROCm/rocm-libraries/pull/15020)**: built and benchmarked the PR against its merge base on **gfx1151 (Radeon 8060S / Ryzen AI MAX+ 395)**, with and without the Composable Kernel plugin. Reported solver choice, kernel times, workspace and verification for 1D and 3D (fp32/bf16) dilated convolutions, including up to 5× faster 1D convolutions and cases where no solver had been found before. Also identified a CK plugin ABI mismatch (missing depthwise backward-data symbols) and worked around it with a shim.

### [Project MONAI](https://github.com/Project-MONAI/model-zoo) · model-zoo
- **[mindgrab skull-stripping bundle (#787)](https://github.com/Project-MONAI/model-zoo/pull/787)**: packaged the MindGrab MeshNet skull-stripping model as a MONAI bundle.
- **[mindmap brain segmentation bundle (#789)](https://github.com/Project-MONAI/model-zoo/pull/789)**: ported the 24-channel, 18-class MeshNet whole-brain segmentation model to the MONAI bundle format, including the network, conform preprocessing, post-processing and a safetensors checkpoint loader with key remapping. Validated with `monai.bundle run` against the reference implementation at 98.8% voxel agreement.


## 🚀 Skills & Technologies

### **Programming Languages**
<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" alt="C"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL"/>
</div>

### **ML & GPU Computing**
<div align="center">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/MONAI-00A3E0?style=for-the-badge" alt="MONAI"/>
  <img src="https://img.shields.io/badge/tinygrad-000000?style=for-the-badge" alt="tinygrad"/>
  <img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="CUDA"/>
  <img src="https://img.shields.io/badge/ROCm%20%2F%20HIP-ED1C24?style=for-the-badge&logo=amd&logoColor=white" alt="ROCm / HIP"/>
  <img src="https://img.shields.io/badge/Metal-000000?style=for-the-badge&logo=apple&logoColor=white" alt="Metal"/>
  <img src="https://img.shields.io/badge/WebGPU-005A9C?style=for-the-badge" alt="WebGPU"/>
  <img src="https://img.shields.io/badge/WebAssembly-654FF0?style=for-the-badge&logo=webassembly&logoColor=white" alt="WebAssembly"/>
</div>

### **Frontend Development**
<div align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
</div>

### **Backend Development**
<div align="center">
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django"/>
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" alt="Nest.js"/>
</div>

### **Database & Caching**
<div align="center">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/>
</div>

### **DevOps & Cloud**
<div align="center">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes"/>
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" alt="Nginx"/>
</div>

### **Message Queuing & APIs**
<div align="center">
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white" alt="RabbitMQ"/>
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman"/>
</div>

### **Version Control & Tools**
<div align="center">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</div>

## 🏗️ Architecture & Design

- **Microservices Architecture**
- **RESTful API Design**
- **Event-Driven Architecture**
- **Database Design & Optimization**
- **Cloud-Native Applications**

## 💼 Experience Highlights

- Developed and maintained scalable web applications
- Implemented CI/CD pipelines for automated deployment
- Optimized database performance and query efficiency
- Built responsive and accessible user interfaces
- Collaborated with cross-functional teams in agile environments
- Shipped one C inference engine across CPU, CUDA, HIP, Metal, WebGPU, WebGL2 and WebAssembly backends
- Profiled and optimized GPU inference (roofline analysis, kernel tuning, mixed precision) on AMD, NVIDIA and Apple hardware
- Contributed models and benchmarks upstream to Project MONAI and AMD ROCm

## 🛠️ Development Workflow

- **Agile/Scrum methodologies**
- **Test-driven development (TDD)**
- **Code review and pair programming**
- **Performance optimization & benchmarking**
- **Cross-platform GPU validation**
- **Security best practices**

## 📫 Contact

- **GitHub**: [usmann56](https://github.com/usmann56)
- **LinkedIn**: [Mohammad Usman Nizam](https://www.linkedin.com/in/mohammad-usman-nizam-0835b61a3/)
- **Email**: [12usmannizam@gmail.com](mailto:12usmannizam@gmail.com)

---

*Always learning and exploring new technologies to build better solutions.*
