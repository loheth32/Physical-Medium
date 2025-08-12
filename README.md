## Chapter 2: Physical Medium

### Cabling Types

The physical cables that form a network are primarily of three types: copper, fiber-optic, and coaxial.

* **Copper (UTP/STP):** The most common cable for LANs, using electrical signals. The wires are twisted to help mitigate Electromagnetic Interference (EMI).
* **Fiber-Optic:** Transmits data using light pulses through a glass core, guided by a principle called Total Internal Reflection. It offers huge bandwidth and is immune to EMI.
* **Coaxial:** A heavily shielded single-conductor cable, now used mostly for cable internet services.

Here is a comparison of the different cable types:

| Feature | UTP (Copper) | Fiber-Optic | Coaxial (Copper) |
| :--- | :--- | :--- | :--- |
| **Signal** | Electrical | Light Pulses | Electrical |
| **Common Use**| LANs | Backbone, WAN | Cable Internet |
| **Cost** | Low | High | Medium |
| **Bandwidth** | Good | Highest | High |
| **Max Distance**| Short (~100m) | Very Long (>10km) | Medium |
| **EMI Issues**| Susceptible | Immune | Very Resistant |

---

### Transmission Concepts

For data to travel across a physical medium, several key principles are at play.

* **Electromagnetic Interference (EMI):** This is unwanted noise from external electrical sources that can corrupt the data signals traveling through copper cables. The **twisted pairs** in a UTP cable are a clever, low-cost solution that helps mitigate and cancel out this noise.

* **Total Internal Reflection:** This is the physics principle that makes fiber-optic communication possible. Light pulses sent down a glass "core" are continuously reflected off the surrounding "cladding," which traps the light inside the cable and allows it to travel for very long distances with minimal signal loss.

* **Line Encoding:** This is the set of rules used to convert a computer's abstract digital bits (1s and 0s) into physical signals—such as specific voltage levels on a copper wire or pulses of light in a fiber-optic cable—that can be transmitted over the medium.
