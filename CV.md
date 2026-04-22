[View this file on GitHub (latest)](https://github.com/FedericoRessi/cv/blob/main/CV.md)

# Federico Ressi

**Location:** Alicante, Spain (Remote) · **Nationality:** Italian · **Date of birth:** 24 February 1979  
**Email:** federico.ressi@gmail.com · **Phone:** +34 668 591 070  
**LinkedIn:** [linkedin.com/in/federico-ressi](https://www.linkedin.com/in/federico-ressi)  
**GitHub:** [https://github.com/FedericoRessi](https://github.com/FedericoRessi) · [https://github.com/fressi-elastic](https://github.com/fressi-elastic)

**Languages:** Italian (native) · English (professional) · Spanish (professional)

---

## Summary

Senior Software Engineer and Architect with over 20 years of experience across the full SDLC, including core development, system architecture, SRE, and DevOps. Proven track record in designing complex distributed systems from scratch and refactoring legacy architectures for high scalability. Expert at bridging the gap between low-level system performance and high-level architectural design. Known for innovative problem-solving, technical mentorship, and a commitment to end-to-end product quality.

---

## Skills

**Programming** — Python (10y: backend, scientific, automation) · Go (2y: microservices, SRE) · C/C++ (6y: embedded, 3D, performance) · Bash (4y: automation, Linux) · Java (1y)

**Architecture & backend** — Distributed microservices · REST, gRPC, JSON, Protobuf · Networking (SDN, VXLAN, TCP/IP, sockets, load balancing) · Databases (SQL, Spanner)

**Infrastructure & DevOps** — Kubernetes · Docker, Podman · OpenStack, KVM, Ironic, Libvirt, Vagrant · GCP, AWS S3 · CI/CD (Ansible, Jenkins, Make, Gerrit, GitHub Actions)

**Specialized** — Scientific Computing (NumPy, SciPy, OpenGL) · Linux Systems (Red Hat Enterprise Linux, Ubuntu/Debian) · Methodology (Agile, Scrum, Kanban, Test-Driven Development)

---

## Experience

### Elastic — Senior Software Engineer (Python Performance Testing)

*Spain (Remote) · Jan 2025 – Present*

- **Open source:** [elastic/rally](https://github.com/elastic/rally) — Elasticsearch benchmarking tool.
- Engineered high-performance benchmarking tools for detecting performance regressions in Elasticsearch.
- Designed and implemented a Python-based parallel HTTP downloader using multi-threading for rapid, reliable file retrieval from multiple mirrors.
- Developed automated load balancing and failover mechanisms for mirror services, optimizing latency and throughput.
- Built custom adapters for AWS S3 and Google Cloud Storage integration using HTTP protocol.
- Prototyped a Rust based replacement for esrally tool for performance testing of Elasticsearch based on caputuring the network traffic and recostruct HTTP requests with precice timestamps from the Lininux kernel tracepoints.
- Implemented sticky fan out load balancing mechaninism for high troughput and efficent network traffic capture writing a custom Rust tool.
- Integrated Cursor AI LLM based IDE in the development process to improve productivity and crush learning curve for new technologies (like Rust, ethernet packed capture, etc.).

### Google — Senior Software Engineer, System Architect, SRE Engineer

*Munich, Germany · Aug 2022 – Dec 2024*

- **Move Control Plane (SRE):** Developed full-stack Go/JS features for a large-scale migration tool moving services between global data centers.
- Gained deep expertise in Google’s internal infrastructure (Borg, Spanner, Protobuf) and high-scale load-balancing mechanisms.
- **Trusted Partner Cloud:** Architected and deployed multi-cluster Kubernetes solutions for Google Cloud instances in third-party data centers.
- Prototyped and implemented Ansymbe playbooks to demonstate feasibility and spot weakness of a parner solution for orchestrating Kubernates cluster inside of another K8 cluster using VirtKube as middle layer.
- Spot two critical realiability issues in the prototyped design and provided reccomentations to avoid single points of failures.
- Authored critical technical design documents and prototyped Rocky Linux-based deployment platforms using Podman and Systemd.
- Implemented in Go automaned update service based on container images and RPMS for baremetal nodes compatible with YUM and Systemd.

### Red Hat (part of IBM) — Senior Quality Engineer & Technical Lead

*Spain (Remote) · Nov 2017 – Jul 2022*

- **Open source:** [redhat-openstack/tobiko](https://github.com/redhat-openstack/tobiko) — Python testing framework for disruptive operation testing in OpenStack.
- Founded "Tobiko," an open-source Python testing framework for disruptive operation testing in OpenStack.
- Led cross-team collaborations to define CI/CD strategies and mentored developers in Python and OpenStack ecosystem.
- Automated complex infrastructure workloads using Ansible and integrated OpenShift into CI pipelines.
- Wrote integration test cases for testing OpenStack network layer using lazy initialization and shared fixtures to increase test coverage with minimum overhead.

### Bank of America — Software Engineer & DevOps

*Dublin, Ireland · Nov 2016 – Nov 2017*

- Built Groovy-based CI pipelines in Jenkins and developed reusable Make utilities for heterogeneous projects (Python, Scala, LaTeX).
- Developed a Scala-based web portal for artifact management and built a custom shell-based package manager.
- Automated LaTex based documentation generation.

### Intel — Senior Software Engineer / Python Instructor

*Shannon, Ireland · May 2015 – Nov 2016*

- **Open source:** [openstack/devstack](https://github.com/openstack/devstack) — OpenStack development stack.
- Developed SDN integration plugins between OpenStack and OpenDaylight.
- Contributed to the upstream OpenStack/DevStack community and presented at OpenStack Day Mexico City.
- Acted as innovation team leader mentoring and coordinating team mates innovation contributions.
- Conducted internal Python training sessions for engineering staff enabling silicon engineering teams to migrate tools to Python.

### FEI — Software Engineer (Python)

*Eindhoven, Netherlands · Feb 2014 – Jan 2015*

- Refactored high-performance Windows desktop applications for electronic microscope data visualization (OpenGL, NumPy).
- Optimized real-time data processing and multithreaded GUI response using PySide/Qt.

### AMS Geomatics — Software Engineer (C++, DevOps)

*Madrid, Spain · Jun 2013 – Jan 2014*

- Developed a cross-platform (Windows/Linux) 3D CAD application for property modeling.
- Managed build infrastructure using GNU Make and QMake, and created Java-based SVN management tools.

### Altran — Technical Lead / Software Engineer

*Madrid, Spain · Apr 2012 – Jun 2013*

- Led the design and development of "Adept" for Airbus, a high-performance mathematical processing tool.
- Implemented a Python-based C++ code generator for parallelized numerical operations.
- Developed CFD post-processing libraries utilizing NumPy, SciPy, and VTK.
- Optimized mathematical expressions using Simpy for numerical stability and performance before compilation and computation.
- Optained up to 10x speedup in computation of operations on big NumPy arrays and matrices using OpenMP for parallel processing and memory access to minimize cache miss.

### Indra — Software Engineer (Java)

*Madrid, Spain · Feb 2011 – Apr 2012*

- Developed supervision agents for national air traffic control systems (SACTA).
- Implemented high-concurrency actor models using Java non-blocking APIs.
- Using atomic operations to implement a lock free data structure for high throughput data processing.
- Implemented hybrid hash map and skiplist for lock free sorted data insertion in memory.

### FADA-CATEC — Software Architect / Engineer

*Seville, Spain · Sep 2009 – Sep 2010*

- Designed distributed flight simulators and video streaming applications for drones using C++/Qt and Google Maps API.

### Thales Computers (Kontron) — Software Engineer (C/C++, Python)

*Toulon, France · Jul 2008 – Aug 2009*

- Developed embedded GUI for AWACS aircraft radio systems (PowerPC).
- Built middleware for diskless Linux clusters and custom RPM distributions.

### Indra Espacio — Software Engineer (C)

*Barcelona, Spain · Apr 2007 – Jul 2008*

- Developed real-time satellite localization systems for emergency beacons (MEOSAR) using C and MySQL.
- Implemented geolocalization algorithm based on triangulation and frequecy shift of signals from multiple satellites.

### ACOM Grupo Tecnologías — Technical Lead (C++)

*Barcelona, Spain · Sep 2006 – Apr 2007*

- Refactored MJPEG/MPEG4 video streaming services and led a team of 3 developers.

### CIEFFE S.r.l — Software Engineer (C++, Web)

*Parma, Italy · Jan 2003 – Sep 2006*

- Developed real-time vector graphics engines (OpenGL/GPU shaders) for CCTV systems.
- Implemented optimized real time bilinar interpolation of video frames for high definition displays in C++ wth comparable performances with assembly/MMX implementations.
- Built a custom DNS service from scratch in C++ for dynamic IP device registration.
- Optimized MPEG4 decoders for ARM-based Pocket PC devices.

---

## Education

**University of Parma** — University Diploma in Software Engineering  
*Parma, Italy · 1999 – 2005*

---

## Interests

Data-intensive applications · Technical leadership and mentorship · Distributed systems architecture and scalability · Algorithm optimization and complex problem solving · Artificial intelligence and physics simulations

---

*Source: `cv.yml` · Last updated April 2026*
