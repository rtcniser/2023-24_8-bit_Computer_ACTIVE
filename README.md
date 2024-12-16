<style>h1,h2,h3,h4 { border-bottom: 0; } </style>
<header class="item" style="
		background-color: rgb(200, 200, 200); /* For browsers that do not support gradients */
		background-image: radial-gradient(rgb(200, 200, 200), rgb(100, 100, 100)); 
		padding: 3% 0% 3% 0%; 
  margin-bottom: 0px;">
		<div style="width: 80%; margin: 20px auto;"  >
            <h1 style="color:white;">8-bit Computer</h1>  <h3 style="color:black; margin: -10px auto;"> Learning how a computer works</h3>
        </div>
</header>

In this project we build a programmable 8-bit computer from scratch on breadboards using only simple logic gates. Ben Eater has a great [video series](https://www.youtube.com/playlist?list=PLowKtXNTBypGqImE405J2565dvjafglHU) and [website blog](https://eater.net/8bit) on this, which we followed for the most part. We learn about different components that go into making a computer, how different 'parts' talk to each other and they synchronise everything. This is good way to learn about electronics handling. Once developed it can be used to teach functioning of the computer to other students as well. 

---

This project involves desgning and assembling an 8-bit computer, it includes different modules:
- Clock module
- Registers
- Arithmetic logic unit (ALU)
- Random access memory (RAM)
- Program counter
- Output register
- CPU control logic

### Objectives

- to build a working 8-bit computer.
- to understand working of computers at fundamental level.
- understanding different IC chips used in the project.
- to educate other students 

---

### Methodology

- Ben Eater's 8-bit computer youtube series.
- Learning how IC chips used in above video series works 
- Assembling modules using schematic diagram.
- Checking and debugging modules.
- Connecting all modules through bus.

- **Materials Used:** Refer to Ben Eater's website for complete list


### Observations

- (Date Updated: 20/12/2023) | Jumper wires can't be trusted. Always verify it's resistance (a few ohms at most) before using. Better use single core solid wires.
- (Date Updated: 7/1/2024) | The clock module and register module weren't working at the same time. Turns out they needed power directly from the source. Don't jump power cables(wires) between different modules.

### Technical Blogs

Related blogs and resources used during the project.

|          Technology           | Brief Description |           Detailed Blog            |
| :---------------------------: | :---------------- | :--------------------------------: |
| Ben Eater Website | complete blog with all component list  | [More Details](https://eater.net/8bit) |
| Ben Eater Playlist | complete youtube video series explaining evrything  | [More Details](https://www.youtube.com/playlist?list=PLowKtXNTBypGqImE405J2565dvjafglHU) |
| Clock Module | synchronize all operations, used 555 timer IC in different states  | [More Details](https://eater.net/8bit/clock) |

---


### Time-line

|             Event              | Brief Description                        |       Timeline        |  Status  |
| :----------------------------: | :--------------------------------------- | :-------------------: | :------: |
| Clock Module | The heart-beat of computer. Syncs everything.  | Nov 2023 | Done |
| Registers | Record and relay information to CPU | Dec 2023 | Done |
| Arithmetic logic unit | Add or Subtract numbers stored in registers | Jan 2024 | Working |
| Random Access Memory | stores the program the computer is executing | Feb 2024 | Working |
| Program Counter | counts in binary to keep track of instruction serial | TBD | Upcoming |
| Output register | output processed information from CPU | TBD | Upcoming |
| CPU control logic | Instructions to be fed to the CPU | TBD | Upcoming |


---

### Team Members (as on 2024)

1. [Abhishek](abhishek.2022@niser.ac.in) | Team Member | 3rd Year Int. MSc. School of Biological Sciences
2. [Suraj Kumar Behera](surajkumar.behera@niser.ac.in) | Team Member | 3rd Year Int. MSc. School of Biological Sciences
3. [Prasad Murmu ](prasad.murmu@niser.ac.in) | Team Member | 3rd Year Int. MSc. School of Physical Sciences
4. [Pritipriya Dasbehera ](pritipriya.dasbehera@niser.ac.in) | Project Lead | 4th Year Int. MSc. School of Physical Sciences


## For future members interested in continuing the project
1. The essential ICs, currently developed breadboards with components, and power plug can be found in the box named "8-bit comp." somewhere in the Club. (contact the president)
2. Read the Ben eater blog/ watch the video series and check each of the completed modules and make sure everything is working fine.
3. Continue the remaining modules.
4. **We had faulty 74LS189 ICs which we have changed for the good working ones (2 nos). In case the faulty one is misplaced and ends up in the stack remeber, faulty one heats up and doesn't function properly**
5. Build a transparent encasing out of acrylic/plexiglass for safety and showcase.

<div style="background:  #000000; color: #ffffff; padding: 1% 0% 3% 0%; " >
	<div style="width: 80%; margin: 20px auto;" >
	<p >8-bit Computer - Learning how a computer works is supported by and developed with <b><a href="https://www.niser.ac.in/~smishra/clubs/rtc/">RoboTech Club NISER </a></b>. 
	</p>
	</div>
</div>
