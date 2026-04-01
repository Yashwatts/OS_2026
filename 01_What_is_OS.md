# 🖥️ What is an Operating System?

An Operating System is essentially a software program that acts as an intermediary between a computer user and the computer hardware. Its primary goal is to provide an environment in which a user can execute programs in a convenient and efficient manner by hiding underlying
complexity of the hardware and acting as a resource manager.

# 🛠️ Core Functions of an OS

1. **The DRY Principle (Don't Repeat Yourself)**

    In programming, DRY means you shouldn't write the same logic over and over. The OS applies this to hardware:

    - Without an OS: Every single app developer (TikTok, PUBG, WhatsApp) would have to write their own complex code to talk to the CPU, display pixels on the screen, and save files to the disk.
    - With an OS: The OS writes that hardware-handling code once. Developers just "call" the OS to do it for them. This saves millions of lines of redundant code across different applications.

---

2. **Resource Management**

    The OS manages the computer's resources (CPU, Memory, GPU, Disk) to ensure no single application monopolizes them.

    - Example: If you run two apps (like TikTok and PUBG) simultaneously, the OS allocates specific percentages of CPU and GPU (like 60% GPU to a game and 5% to a background app) to each so they can run together without one crashing the other.

---

3. **Interface for Users/Apps**

    The OS acts as an Interface between the user/application and the hardware.

    - The Bank Analogy: You are the user, the money in the vault is the Hardware, and the Bank Employee is the OS. You don't go into the vault yourself; you ask the employee to get the money for you.

---

4. **Isolation and Protection**

    The OS ensures that different applications running on the same system do not interfere with each other's data or memory space.

    The OS keeps apps in their own "bubbles" (Memory Protection):

    - It ensures that TikTok cannot see or overwrite the memory being used by PUBG.
    - This prevents one crashing app from taking down the entire system, prevents one app from "overwriting" or stealing private data.

---

5. **Hiding Complexity (Abstraction)**

    The OS hides the underlying hardware complexities from developers.

    - Ease of Coding: Without an OS, a programmer would have to write specific code to interact with every different type of hardware (different brands of RAM or Hard Drives). With an OS, you simply write high-level code, and the OS handles the hardware-specific communication.

---

# ⚠️ What happens if there is NO OS?

If a computer lacked an operating system, the experience would be highly inefficient:

• Resource Hijacking: The first app launched could take 100% of the resources, making it impossible to run anything else.

• Complex Programming: Developers would need to write massive amounts of code just to perform basic tasks like reading from a disk or displaying text on a screen.

• No Security: Applications could easily access and modify each other's private data since there would be no "police" (OS) to enforce boundaries.

# Layer of OS

```text
                  User
-----------------------
| Application programs |
| operating system     |
| Computer hardware    |
```

=> Application software performs specific task for the user.

=> System software operates and controls the computer system and provides a platform to run application software.