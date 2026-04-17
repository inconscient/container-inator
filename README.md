
# container-inator

**container-inator** is a lightweight web application designed to run inside a container and provide a simple web interface for **evaluating, demonstrating, and validating container-based lab platforms**.

It is intentionally minimal, making it ideal for infrastructure testing, platform evaluations, and networking experiments where application complexity should stay out of the way.

---

## What is container-inator?

container‑inator acts as a **visual and interactive workload** you can deploy inside container environments to verify:

- Container configuration
- Runtime environment behavior
- Networking, routing, and service communication

Rather than focusing on application logic, container‑inator helps you **observe what the platform is doing**.

---

## Technology Stack

- **Language:** C#
- **Framework:** ASP.NET (.NET 8)
- **UI:** Razor Pages
- **Runtime:** Containerized (Docker-compatible)

The application is implemented as a **small Razor-based web app**, optimized for fast startup and low resource usage.

---

## What It Displays

When accessed via a browser, container‑inator typically shows runtime-specific details such as:

- 🖥️ **Hostname / Pod / Container name**
- ⚙️ **Environment variables**
- 🕒 **Timestamp and request details**

This information is especially useful for identifying:
- Which container served a request
- How configuration values are injected
- How traffic flows across services

---

## Usage Ideas

container‑inator is well suited for:

- **Containerized application settings**
  - Validate environment variable assignment
  - Test configuration changes across deployments

- **Networking & platform validation**
  - Routing verification
  - Load balancing behavior
  - Service mesh communication
  - Multi-container lab topologies

- **Platform evaluation**
  - Docker
  - Container-based labs
  - Kubernetes-like environments
  - Network simulation setups

---
## Contributing

This project is intentionally small. Improvements should focus on:

- Observability
- Runtime visibility
- Platform-neutral behavior

Feel free to fork and adapt it for your own lab environments.





