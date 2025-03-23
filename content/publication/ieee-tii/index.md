---
title: "Integrating Post-Quantum Cryptography and Blockchain to Secure Low-Cost IoT Devices"
authors:
- admin
- Aniello Castiglione
- Vicenzo Loia
- Michele Nappi
- Chiara Pero
- Matteo Polsinelli
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"

date: "2024-11-18T0:00:00Z"
doi: "10.1109/TII.2024.3485796"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transaction on Industrial Informatics*"
publication_short: "IEEE TII"

abstract: In the contemporary era, the global proliferation of Internet of Things (IoT) devices exceeds 15 billion, serving functions from wearables to smart grid monitoring. These devices frequently manage sensitive data, underscoring the need for secure and reliable IoT networks leveraging blockchain technology. A key innovation of this study is an approach to mitigate vulnerabilities that quantum computing poses to blockchain-based IoT systems, which existing cryptographic methods cannot effectively address. Quantum computers could exploit these weaknesses to compromise key-pair generation and extract private keys from transaction signatures. To overcome this, the research introduces an optimized implementation of the post-quantum digital signature algorithm Dilithium-5, ensuring blockchain security and quantum readiness. These transaction signatures are designed for low-power, cost-effective microcontrollers, such as the ESP32, making the solution accessible for a wide range of IoT devices. In addition, the study includes a case study involving a post-quantum safe portable device for measuring blood oxygen levels and heart rate, illustrating the practical benefits and effectiveness of the proposed solution in enhancing IoT security against quantum threats. The results demonstrate that the proposed approach ensures quantum-resistant security while maintaining performance efficiency, making it suitable for real-world IoT applications.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Post Quantum Cryptography
- Embeeded device 
- Microcontroller 
- Blockchain
- Dilitihium-5
- ML-DSA-87
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/document/10756206
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Scheme of proposed architecture'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---