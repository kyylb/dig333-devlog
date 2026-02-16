[<](README.md)

# Week 04 - DevLog




## Outcomes 

<!-- 
Using the backslash preserves the list number 
https://stackoverflow.com/a/50916345/441878 
-->



1\. 📚Read Philip K. Dick Pay for the Printer (1956) and The Preserving Machine (1953). Write a reflection below:

“Pay for the Printer” and “The Preserving Machine” both explore how technology meant to preserve human knowledge can instead distort or degrade it over time. Dick suggests that when systems operate beyond human understanding, they evolve in unpredictable ways. They turn creativity into mechanical imitation and even transform art into something unrecognizable. Together, the stories feel like warnings that preservation without comprehension risks losing the very humanity and meaning we are trying to save.



2\. Connect a concept from [Synthesizing with Moog | Lesson 4: Resonance](https://www.youtube.com/watch?v=6spVzRqOsVw) to an aspect of the interface in the [Learning Synth Playground](https://learningsynths.ableton.com/en/playground) by Ableton 

A key concept from the lesson is that resonance boosts frequencies at the filter’s cutoff, creating a sharper, more “nasal” tone as feedback increases—a hallmark of designs pioneered by Bob Moog. In the Ableton Learning Synth Playground interface, the resonance knob in the filter section directly demonstrates this by making the sound peak and whistle around the cutoff frequency as you raise it. This hands-on control shows how resonance shapes timbre over time, turning a simple oscillator tone into a more expressive and dynamic sound.




3\. 📚Read Chapter 1 Get to know your  Raspberry Pi Pico (8-19) in [Get Started with MicroPython on Raspberry Pi Pico](https://www.mclibre.org/descargar/docs/revistas/hackspace-books/hackspace-get-started-with-micropython-on-pico-01-202101.pdf). Read and follow tutorial to install the MicroPython firmware on Pico.

p.20–25 - Read and follow tutorial to install Thonny and run the "Hello, World!" Add documentation below to show you can save and run python code on the Pico.

I am able to run many types of script on the Pico including the traffic light simulation.




4\. What is the difference between a microcontroller and a regular computer? (Chapter 1)

A microcontroller is a small, self-contained chip with a processor, memory, and input/output built in, designed to run one dedicated task (like controlling an appliance or sensor). A regular computer is a general-purpose system with separate components and far more processing power, built to run many different programs and tasks.



5\. 📚Read Chapter 2 (20–33) Programming with MicroPython. Summarize steps to program the Pico from your computer.

To program a Raspberry Pi Pico from your computer with MicroPython, the steps are:

1. Install an IDE (usually Thonny) on your computer and connect the Pico to the computer with a micro-USB cable.

2. Open Thonny and select the MicroPython (Raspberry Pi Pico) interpreter so programs run on the Pico instead of the computer.

3. Write code in the script editor, then run or save it to the Pico so it executes on the microcontroller.



6\. 📚Read Chapter 2: "Challenge: New Message" (26) - You can display programming code in a markdown file using three backticks, a new line, and then three more backticks on the following line. 

```python
print("Loop starting!")

```


7\. Chapter 2: "Challenge: Loop the Loop" (26)

```python
print("Loop starting!")
for i in range(10000):
  print("Loop running!")
print("Loop finished!")
```

8\. Chapter 2: "Challenge: Add More Questions" (26)

```python
user_name = input ("What is your name? ")
while user_name != "Clark Kent":
  print("You are not Superman - try again!")
  user_name = input("What is your name? ")
  print("You are Superman!")
  preference = input("Would you like to be Superman? ")

```






9\.  📚Read Chapter 3 (34–43) Physical Computing. How many Ground pins are on the Pico?

There are 8.



10\. Post sketches for your musical instrument and a parts list.














## Other experiments

<!-- 
Share details about other electronic experiments you are working on this week?
-->

- 



## Questions to bring up in class

<!-- 
Share questions you would like to bring up in class.
-->

- 
