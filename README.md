#  Lost and Found Management System for George Brown College
This project involves creating a web based Lost and Found system for George Brown College. Currently, the lost and found process mainly relies on in-person visits to campus security or limited information from a static webpage. This can be inconvenient and time consuming for students and staff who are trying to recover lost items. The goal of this system is to make the process easier and more efficient. Students and staff will be able to report lost or found items online, upload photos, search for items, and track the status of their reports. Campus security staff will manage and verify the items through an admin dashboard. Overall, the system aims to reduce confusion, save time, and improve the chances of lost items being returned to their owners.

## Team Members
* [Anastasiia Stoianova](anastasiia.stoianova2025@gmail.com)
* [Fatemeh Sadat Ghaani](Asalghaani@yahoo.com)
* [Hamida Fathi](hamidafathi200@gmail.com)
* [Jui-Wen Chiang](https://github.com/jui-wen-chiang)
* [Samira Sarabi](sarabisamira311@gmail.com)

## Repositories
- **Frontend**: [lost-and-found-frontend](https://github.com/jui-wen-chiang/lost-and-found-frontend-GBC)
- **Backend**: [lost-and-found-backend](https://github.com/jui-wen-chiang/lost-and-found-backend-GBC)

## Live Demo
- **Frontend**: [Lost and Found Management System for George Brown College ](https://lost-and-found-frontend-gbc.vercel.app/)
- **Backend API**: [Swagger Docs](https://lost-and-found-backend-gbc.onrender.com/api/docs/)

## Tech Stack

### Project Tools
| Technology | Justification |
|---|---|
| GitHub | Mainstream version control platform with built-in CI/CD, collaboration tools, and powerful community ecosystem for team code management. |
| Google Drive Share Folder | Convenient file sharing for non-code assets with cross-platform access, version history, and flexible permission management. |

### Frontend
| Technology | Justification |
|---|---|
| React | Leading front-end framework with component-based architecture, vast ecosystem, and excellent performance for rapid development. |
| Vite | Fast development server with HMR and ES modules-based build, outperforming traditional webpack with smaller bundles. |
| MUI (Material-UI) | Complete Material Design UI library with responsive design and accessibility features, reducing UI development time significantly. |
| TypeScript | Static type checking that catches errors early, with powerful IDE support for improved code quality and team collaboration. |

### Backend
| Technology | Justification |
|---|---|
| Django | Mature Python framework with built-in ORM, authentication, admin panel, and strong security for rapid API development. |
| Python | Concise syntax with vast ecosystem and strong community support, ideal for web development and seamless Django integration. |

### Database and Authentication
| Technology | Justification |
|---|---|
| Database | PostgreSQL | Powerful open-source database with advanced features, seamless Django integration, and enterprise-grade reliability. |
| JWT (JSON Web Token) | Stateless authentication for decoupled architectures with self-contained tokens, supporting cross-domain use in modern SPAs. |

### Deployment
| Technology | Justification |
|---|---|
| Vercel | Optimized for React/Vite (Front-End) with automated CI/CD, global CDN, and generous free tier for simple, efficient deployment. |
| Render Web Service | Straightforward Django deployment (Back-End) with built-in HTTPS, health checks, and logging, eliminating server maintenance overhead. |
| Supabase | Managed PostgreSQL with automatic backups and additional features like real-time subscriptions and authentication. |
| Miniconda | Isolates project dependencies ensuring consistent cross-platform environments, primarily for local development collaboration. |

## Getting Started

Prerequisites:
- Install (optional) [Miniconda](https://www.anaconda.com/docs/getting-started/miniconda/main)
  - base command
    + conda -V
    + conda env list
    + conda list
    + conda create --name [projectname] python=3.13.0
    + conda activate [projectname]
  - Search or Install Package
    + conda search python 
    + conda search nodejs
    + conda install nodejs 
- Install Python 3.11+
- Install Node.js 18+

See individual repositories for setup instructions.
