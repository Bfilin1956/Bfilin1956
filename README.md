# C++ Backend / Systems Developer

C++ developer focused on high-performance backend systems, network services, and low-latency asynchronous architectures.

Work centers around designing systems where performance, memory behavior, and concurrency correctness matter more than abstraction layers.

## Core Expertise
- Asynchronous systems (Boost.Asio, C++20 coroutines)
- TCP/IP networking, binary protocols, secure transport (TLS/OpenSSL)
- Concurrency models (thread pools, lock-free structures, event loops)
- Performance engineering (latency reduction, throughput scaling)
- Memory-aware design (allocation control, zero/low-overhead paths)

## Projects

### high-performance-cpp-server (Boost.Asio)
Asynchronous TCP server built with modern C++20 and Boost.Asio coroutine-based architecture.

- Focus is on scalable connection handling and predictable latency under load.
- Coroutine-driven I/O model (co_await based flow control)
- Non-blocking event-driven networking layer
- Efficient message processing pipeline with batching
- Designed for low-latency request handling under concurrent load

**Tech:** C++20, Boost.Asio, coroutines, TCP/IP  

👉 [View repository](https://github.com/Bfilin1956/high-performance-cpp-server/)

---

### OpenGL 3D Engine
Lightweight rendering engine written from scratch in C++ using OpenGL.

Focus on understanding graphics pipeline and building a minimal but structured rendering architecture.

- Custom rendering pipeline with batching optimizations
- Shader system with basic lighting model support
- Asset loading via Assimp (.obj support)
- Scene graph with transforms, camera system, input handling

**Tech:** C++20, OpenGL, Assimp  

👉 [View repository](https://github.com/Bfilin1956/CPP-OpenGL-game-engine)

---

### Stratum V2 Protocol Implementation
Low-level implementation of Stratum V2 protocol with emphasis on transport correctness and handshake design.

- Multi-stage secure session establishment (TLS-like handshake flow)
- Binary protocol parsing over TCP streams
- Certificate handling and validation logic
- Focus on correctness in network state transitions

**Tech:** C++20, networking, binary protocols, cryptography 

👉 [View repository](https://github.com/Bfilin1956/Cpp-StratumV2)

## Systems Focus Areas
- High-throughput backend services
- Network protocol implementation
- Low-latency systems design
- Memory-efficient runtime behavior
- Deterministic concurrency models

## Tech Stack
- **Languages:** C++20  
- **Networking:** Boost.Asio, TCP/IP, TLS  
- **Concurrency:** coroutines, multithreading, lock-free patterns
- **Databases:** PostgreSQL, Redis  
- **Tools:** CMake, Docker, Git  

## Contact
- Email: bfilin1956@gmail.com  
- LinkedIn: https://linkedin.com/in/bfilin1956/  
- Telegram: https://t.me/cppdev1956
