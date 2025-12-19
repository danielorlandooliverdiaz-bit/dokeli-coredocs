# 📘 Dokeli Coredocs

> **The Platform Engineer's Second Brain.**
>
> *Una base de conocimiento "Docs as Code" para documentar el camino hacia la maestría en Infraestructura, Cloud y DevSecOps.*

![Build Status](https://img.shields.io/badge/build-passing-success)
![Platform](https://img.shields.io/badge/platform-linux%20%7C%20azure-blue)
![Stack](https://img.shields.io/badge/tech-mkdocs%20%7C%20docker-teal)
![License](https://img.shields.io/badge/license-MIT-green)

---

## 🎯 Misión del Proyecto

Este repositorio no es un blog. Es un **Manual de Operaciones Vivo**.
Su objetivo es aplicar principios de ingeniería de software a la documentación técnica ("Docs as Code"). Aquí se centralizan laboratorios, resoluciones de incidentes (Troubleshooting) y arquitecturas de referencia para:

* **Sistemas:** Linux (LFCS) & Scripting.
* **Redes:** TCP/IP, Wireshark & CCNA.
* **Cloud:** Microsoft Azure (AZ-104 / AZ-500).
* **DevSecOps:** Kubernetes, Docker & Terraform.

## 🏗️ Stack Tecnológico

La infraestructura de documentación está construida sobre contenedores para garantizar portabilidad y reproducibilidad (Zero Dependency Hell).

| Componente | Tecnología | Función |
| :--- | :--- | :--- |
| **Motor** | [MkDocs](https://www.mkdocs.org/) | Generador de sitios estáticos. |
| **Tema** | [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) | UI/UX profesional y responsiva. |
| **Runtime** | [Docker](https://www.docker.com/) | Entorno de ejecución aislado. |
| **Editor** | VS Code | Entorno de desarrollo con extensiones custom. |
| **Versionado** | Git & GitHub | Control de versiones y backup. |

---

## ⚡ Quick Start (Runbook)

Para levantar esta base de conocimiento en tu máquina local (requiere Docker instalado).

### 1. Clonar el repositorio
```bash
git clone [https://github.com/danielorlandooliverdiaz-bit/dokeli-coredocs.git](https://github.com/danielorlandooliverdiaz-bit/dokeli-coredocs.git)
cd dokeli-coredocs
