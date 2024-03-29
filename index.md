<!-- [Please Click Here To Go The Website For Animations](https://bloop132435.github.io) -->
- [About Me](#about-me)
- [Projects](#projects)
	- [AI](#ai)
		- [HERO Quantization](#hero-quantization)
		- [Iterative Quantization](#iterative-quantization)
	- [8-bit CPU](#8-bit-cpu)
- [USA Physics Olympiad (USAPhO)](#usapho)

---

# About Me
[Back to top](#) <br>
A high school student passionate about pursuing a career in Electrical Engineering or Physics.
<p align="center">
  <img src="./GQ_Soldering_IMG_8379.jpg" width="500"/>
</p>


---

# Projects

---

## AI
[Back to top](#)<br>
My focus within the large field of AI is on the effecient quantization of neural networks. The two specific projects listed here are both mixed precision quantization schemes, meaning that the
different layers within the networks don't necessarily have the same quantization bit precision

---

### HERO-based Quantization
This method aims to reduce the weight perturbation-induced loss while maintaining low bit-widths.
<!-- by only giving large bit precisions to layers with a rough loss surface. -->
It uses each layer's Hessian eigenvalue to determine how the bit configuration is formed, as it represents the smoothness of the loss function.
It is especially powerful for models trained with HERO (**H**essian-**e**nhanced **R**obust **O**ptimization).
Fig.3 is an example of a 2x performance gain over fixed precision quantization.




---

### Iterative Quantization
This method is based on the intuition of gradient descent. It chooses the optimal bit configuration by learning the local optimal choice, and works for pre-trained models of all varieties. The gif below and Fig.2 show the evolution of iterative quantization. <br>

<p align="center">
  <img src="./movie.gif" />
</p> <br>
Iterative Quantization performs well on a variety of models, even ones that weren't trained using HERO, as shown in Fig.4.
I am preparing a paper about this method which will be published in the IEEE International Symposium on Circuits and Systems (ISCAS).


---
<p align="center">
  <img src="./FourPlotProjectIllustration.JPG" />
</p>

<!-- ### Paper -->
<!-- <embed src="https://drive.google.com/viewerng/ -->
<!-- viewer?embedded=true&url=https://drive.google.com/file/d/19IFQgGhKFh1XMOsL2GOOchiFfUBrrfb3/view" width="500" height="375"> -->
<!-- This is my paper that I submitted to the 2023 IEEE International Symposium on Circuits and Systems (ISCAS) https://drive.google.com/file/d/19IFQgGhKFh1XMOsL2GOOchiFfUBrrfb3/view -->
<!-- --- -->
## 8-bit CPU

[Back to top](#)<br>
This project involved building a mostly-functioning CPU from scratch, using only logic circuits offered in TI's 74-series of integrated circuits. Right now each of the components are working (Arithmetic Logic Unit (ALU), RAM, Registers A/B, and the Decimal Display).
I am currently working on building the control logic, the part of the computer that will read and process instructions and command each part to do the appropriate operations. So far, I have finished the Ring Counter and the Program Counter portion of this final leg of the computer. <br> <br>
![threpics](./threepics.png)
Below is my computer in action, counting up by 2.
<p align="center">
  <img src="./ezgif.com-gif-maker_skipframe.gif" />
</p>
### Videos
1. [ALU Explanation](https://youtu.be/4WzkkjmJwrw)
2. [Demonstration of Debugging with an Oscilloscope](https://www.youtube.com/watch?v=CqOThA3p5UY)
3. [Decimal Display and Implementing Truth Table using EEPROM](https://youtu.be/yc6WBX6zgWk)
4. [Ring Counter Explanation](https://youtu.be/4z909RtefZI)

---


# USAPhO

[Back to top](#)<br>
I have made a couple videos about some USAPhO problems. [This one](https://www.youtube.com/watch?v=I8NZ346rRkQ) is about Problem A1 of the [2013 USAPhO Semi-Final Exam](https://www.aapt.org/physicsteam/2014/upload/E3-1-7.pdf).
<p align="center">
  <img src="./physics.png" />
</p>


---

