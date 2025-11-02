# 9front (Fork)

This repository is a personal fork of **[9front](https://9front.org/)** — the actively maintained and community-driven fork of **Plan 9 from Bell Labs**.  
It exists for experimentation, customization, and contributions related to my personal development environment and hardware projects.

---

## 🌀 What is Plan 9?

**Plan 9 from Bell Labs** is a distributed operating system originally developed at Bell Labs by the creators of Unix.  
Its goal was to improve on Unix concepts through a cleaner and more consistent design, emphasizing:

- Everything is a file — even windows, processes, and the network.
- The **9P** protocol, a simple and elegant file-oriented interface for distributed computing.
- Per-process namespaces, allowing each process to see the system in its own way.
- A minimal and orthogonal design philosophy that avoids special cases and complexity.

Plan 9 laid the foundation for many ideas that influenced modern systems, including UTF-8, `/proc`, and namespaces.

---

## 🦋 What is 9front?

**9front** is a community-driven fork of Plan 9 that continues active development and modernizes the system while maintaining its core design principles.

It includes:
- Modern hardware drivers and architecture support (x86_64, ARM, RISC-V, etc.)
- Enhanced networking and filesystems
- Built-in developer tools and a live ISO installer
- Usable desktop environment (`rio`, `acme`, `sam`)
- Improvements to compilers, the kernel, and userland utilities
- A vibrant and active user community

9front is not a derivative operating system — it **is** Plan 9, continued.

---

## 🔧 This Fork

This fork tracks upstream 9front while including my personal patches, tools, and experiments.  
Examples may include:

- Hardware bring-up and kernel experiments  
- Userland enhancements  
- Research or compatibility testing  
- Build or boot customization  

This repository may diverge from upstream for experimental or development purposes.

---

## 💾 Building

9front uses its own build system (`mk` and `mkfile`).

```bash
# Typical build steps (run from a 9front environment)
mk nuke
mk install
```

For cross-compilation or host builds, see the upstream 9front documentation.

---

## 🔗 Upstream & Resources

- **Official site:** [https://9front.org](https://9front.org)
- **Documentation:** [https://fqa.9front.org](https://fqa.9front.org)
- **Community:** [https://git.9front.org](https://git.9front.org)
- **IRC:** `#cat-v` on libera.chat

---

## ⚙ License

Plan 9 and 9front are distributed under permissive open-source licenses.  
See the individual source files for details.

---

> “Plan 9 is what Unix wanted to be.”  
> — Rob Pike
