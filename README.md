# Ephemera

> *"Ephemera" (n.) — things that exist or are enjoyed for only a short time; transient, momentary, and yet meaningful.*

---

## Project Purpose

**Ephemera** is a personal project centred on the creation and deployment of a fully RAM-resident ISO image of a workstation environment. It includes my preferred applications, dotfiles, and system configurations, all running without reliance on persistent storage.

The project draws philosophical inspiration from the commonly misused phrase:  
*"I don't need to care about privacy—I have nothing to hide."*

This notion, often criticised by privacy advocates, fails to acknowledge the broader importance of digital autonomy, security, and the right to control one’s data. In response, **Ephemera** takes the saying literally—but with a critical twist: by refusing to persist data on local drives, the system avoids leaving behind digital traces. 

Much like established privacy-focused projects such as **Tails OS**, this setup runs entirely in volatile memory. Once the machine powers off, all session data is irreversibly lost. This design encourages users to rethink their interaction with computing environments, promoting:

- Use of **external and self-hosted storage solutions**.
- Greater **portability and reproducibility** of workflows.
- Awareness of **ephemerality as a security and design principle**.

It also enables a **stateless architecture** within your home environment, where the operating system is loaded from a network boot or USB medium, and all persistent data is centrally hosted on a home server. The client device simply becomes a disposable interface to a durable, centralised backend.

While not a novel concept, projects like **Ephemera** are increasingly viable as RAM capacities grow, making it possible to run full desktop environments entirely in memory for certain use cases. (Of course, this excludes resource-heavy applications like modern gaming.)

---

## Disclosure

This project requires a **significant amount of RAM** to function reliably. My current system runs with **64 GB of RAM**, which comfortably accommodates a full operating system and applications in memory.

Before attempting to boot into the ISO, ensure your system has sufficient memory to prevent crashes or instability.

---

## Installation

*Instructions for setting up the environment, boot medium, and dependencies will be documented here.*

---

## Boot Configuration

*Details on PXE/netboot or USB setup, GRUB parameters, or other boot strategies will be added here.*

---

## ISO Creation

*Steps to build or customize the ISO image will be included in this section.*

---

## Credits
This project is inspired by [**Saigocom**](https://github.com/EHowardHill/Saigocom) by **EHowardHill**. Their work on creating a custom Alpine Linux environment bootable entirely into RAM laid the groundwork for this project.

Special thanks to:
- **EHowardHill** for publishing a complete and thoughtful walkthrough, including a YouTube video that guided much of the initial setup.
- The broader open-source community for tools, documentation, and philosophical ideas around **stateless computing**, **reproducibility**, and **privacy-centric design**.

**Ephemera** builds on this foundation by aiming to introduce:
- Custom dotfiles and application configurations
- Enhanced network boot integration (In the future)
- A more portable and extensible setup architecture

---

## License
This project is licensed under the [MIT License](LICENSE).
