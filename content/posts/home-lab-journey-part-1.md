---
title: 'Part 1 - Home Lab: How It All Started and My Initial Network Setup'
date: 2024-10-15T18:43:58+05:30
draft: false
tags: ["Homelab", "Networking", "DIY"]
categories: ["Projects"]
---


For years, I had been toying with the idea of setting up a home lab. As someone who works in tech—programming, managing engineering teams, and designing solutions—getting my hands dirty with technology is second nature to me. But for some reason, starting my home lab was something I kept putting off.

## Procrastination and the Tipping Point

For months, I kept putting off starting my home lab. Every time I thought about it, the sheer amount of work involved made me pause—running Ethernet cables through the house, purchasing new hardware, and reconfiguring the network all felt overwhelming. With limited spare time outside of work, it was easier to stick with my current setup and tell myself, "I'll get to that home lab project soon." But, soon kept getting pushed further down the line.

What finally pushed me into action was the growing complexity of my home network. I had added more devices to the network, services were running on multiple machines, and I had started a DIY CCTV project (which I’ll cover in another blog post). My network setup had become a mess—unorganized, inefficient, and difficult to manage.

Initially, I tried running everything on the system I had in my room, a decent rig featuring a **Ryzen 9 5900X** CPU paired with **32 GB of DDR4 RAM**. On paper, it seemed more than sufficient to handle most of the projects I had in mind. However, there was one glaring limitation: the system wasn’t running 24/7. For my home lab needs, especially when it came to always-on services like my own DNS, I needed a system that could operate continuously without interruptions, which my existing setup simply couldn’t provide.

## Defining the Vision: What I Wanted From My Home Lab

After realizing that my current setup wasn’t cutting it, I began outlining exactly what I needed from a home lab. I wanted an environment that could:

- **Run 24/7** to host always-on services like DNS and home automation tools.
- **Centralize my experiments**, from testing DevOps tools to trying out new software.
- **Handle multiple devices** and provide a stable, fast network for projects like my CCTV setup.
- **Provide flexibility** to break things, learn, and rebuild without affecting my day-to-day devices.

Having a clear vision helped me understand what hardware, network configuration, and infrastructure changes I needed to make.

## What I had.

At the time, I had a **500 Mbps fiber connection** (with plans to upgrade to gigabit speeds), but the modem was installed in the living room. Unfortunately, the placement of the modem wasn’t ideal for my two-story brick house. The Wi-Fi signal struggled to penetrate the thick walls, resulting in dead zones, particularly on the upper floors where my bedroom and workspace were located.

To tackle the immediate issue, I decided to purchase a separate router and run an Ethernet cable from the modem. This helped extend the network, solving some of the dead spot issues, but it still didn’t allow me to fully utilize the speed on the upper floors. I was stuck with a less-than-ideal network setup, and the frustration started building.

## The Need for a Better Solution

Realizing I needed a more stable and robust solution, I began thinking about how to ensure reliable Wi-Fi coverage and a stronger connection upstairs. Given the layout of the house, centrally locating the modem wasn’t an option. So, I figured the next best solution was to add wired access points in the rooms where Wi-Fi coverage was weak.

I sat down and sketched out a simple plan to overhaul my home network:

1. **Purchase a network switch** – A central device to manage multiple wired connections.
2. **Run Ethernet from the modem to the attic** – I’d use the attic as a central point to distribute the network to other parts of the house.
3. **Connect the Ethernet to the switch** – This would allow me to branch out wired connections to multiple rooms.
4. **Distribute Ethernet cables from the switch to each room** – Ensure that every important room had a reliable, wired connection.
5. **Connect spare Wi-Fi routers as access points** – These routers would act as dedicated access points, extending the wireless network to ensure strong coverage throughout the house.

---

This was the beginning of my home lab journey. In the next part, I’ll dive into the process of executing this plan and share the challenges and lessons I learned along the way.
