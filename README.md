# NetForge ⚡

NetForge is an advanced network simulation platform designed to simulate and analyze real-world computer networks.

It allows users to create network topologies using routers, switches, hosts, servers, and links. The platform can simulate packet transmission, routing, latency, packet loss, and network failures.

The project focuses on using graph algorithms and network simulation techniques to understand how networks behave under different conditions.

### Core Features

- 🌐 Design and visualize network topologies
- 📦 Simulate packet transmission and routing
- ⚡ Analyze latency, and packet loss
- 💥 Simulate device
- 🧠 Detect bottlenecks and single points of failure

NetForge aims to provide an interactive environment for understanding, simulating, and analyzing computer networks.

### Tech Stack

- **Frontend:** Vite + Typescript + React
- **Backend:** Nestjs (ESM version)
- **Database:** Mogodb + PostgreSQL

### Project Structure
<ul>
  <li>
    <details open>
      <summary>📂 <b>project</b> <i> — Root directory</i></summary>
      <ul>
        <li>
          <details>
            <summary>📂 <b>client</b> <i> — Vite frontend</i></summary>
            <ul>
              <li>📄 <i>(frontend)</i></li>
            </ul>
          </details>
        </li>
        <li>
          <details>
            <summary>📂 <b>server</b> <i> — NestJS backend</i></summary>
            <ul>
              <li>📄 <i>(backend)</i></li>
            </ul>
          </details>
        </li>
        <li>📄 🐳 <b>docker-compose.yml</b> <i> — PostgreSQL + MongoDB infrastructure</i></li>
        <li>📄 📝 <b>README.md</b> <i> — Project documentation</i></li>
      </ul>
    </details>
  </li>
</ul>
