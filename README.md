# Hi, I'm Jon!

# [IT Professional](https://www.github.com/jlango0) and [Musician](https://www.instagram.com/jlango_drums)

I've been preparing for the Core 1 exam of the CompTIA A+.

The following topics are outside of Core 1's objectives, so they're new—but I'm working on using them.


## Cisco Packet Tracer Labs
Following <a href="https://www.youtube.com/playlist?list=PLxbwE86jKRgMpuZuLBivzlM8s2Dk5lXBQ">this course playlist</a> by Jeremy's IT Lab

- **_Time-lapse_** videos of working through the labs--
  - [Day 1 - Network Devices, 1.1](https://www.youtube.com/watch?v=bgAhSzdRn5k)
    - Create a network diagram based on an image in the lecture; intro to using Packet Tracer
  - [Day 2 - Physical Interfaces & Cabling, 1.3](https://www.youtube.com/watch?v=l_K-uue9HlY)
    - Choose the correct type of cable based on—
      1. Which devices are being connected—i.e. straight vs. crossover
      2. How far apart the devices are—i.e. copper vs. fiber-optic, including which type is most cost-effective, given the requirements (speed, distance)
  - Day 3 - OSI Model and TCP/IP Suite--
    - No video, since this lab focuses on stepping through Simulation mode and studying PDUs moving through the layers
  - [Day 4 - Intro to the CLI / Basic Device Security](https://www.youtube.com/watch?v=ED62LgyCSAc)
    - Initial IOS commands for Routers and Switches


- Taking notes as I watch the lecture videos, and looking things up as needed.  A few examples--
  - For Interfaces, MDI vs. MDI-X devices and their pinouts
    - Indirectly helped with Core 1, since straight vs. crossover cables make more sense now
  - For 1000BASE-LX, the maximum length for single-mode fiber
  - For IOS, [Cisco's man page for `enable password`](https://www.cisco.com/E-Learning/bulk/public/tac/cim/cib/using_cisco_ios_software/cmdrefs/enable_password.htm)


## Active Directory and VMWare
Following [this video](https://www.youtube.com/watch?v=GsmJowwIh8Q&list=PLAdEnQWAAbfXMY2D4HVZOe-ChfTKmaJfQ&index=6) by East Charmer, with a few minor adjustments


Also time-lapse videos below

  - [Installing Windows Server 2022 on VMWare Workstation Pro](https://www.youtube.com/watch?v=YmsB81pi2pc)
    - Includes most steps, but lost part of the screen recording—laptop froze during the first attempt at installing the VM

   
  - [Setting up Active Directory from scratch](https://www.youtube.com/watch?v=KhLQ1F18His), using DomainName.local
    - Add Organizational Units for—
      - Regions:  USA, Europe, Asia
        - Nested inside each region, additional OUs for—Users, Computers, Servers
          - Then inside the Users OU, add—Security Groups, Distribution Groups, and Users
          - One Security Group for each deparatment (IT, Sales, HR, etc.)
            - Add 3 employees per department
          - Security Groups > Members tab > add the 3 corresponding employees
          - Also inside the OUs for Computers and Servers, add devices accordingly
    - Completed this for the USA OU, will complete other regions after I can automate some of these steps in PowerShell
    - Moving to Group Policy next


<!--
**jlango0/jlango0** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
