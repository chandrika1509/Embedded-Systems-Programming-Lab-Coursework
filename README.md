# Embedded-Systems-Programming-Lab-Coursework
Assignment 1 :
Scheduling of real time periodic and aperiodic tasks with event handling and setting specific priorities for tasks in the linux environment .
This involved the concepts of POSIX threads in Linux environment .Involved creation, running, suspending and killing of multiple pthreads. Gained good understanding of the thread lifecycle.
Building , cross compiling and setting up the software development environment on the target board of Intel Galileo Gen 2 to run the user application.
Analysis of CPU time scheduling with Linux Trace tools of Kernelshark.

Assignment 2:
GPIO Programming and using PWM pins for performing basic operations of glowing LEDs for a specific time and with varying intensities on mouse click events.
This involved usage of concepts of signal handlers , Pin multiplexing concepts , using High resolution timers and setting PWM parameters of dutycycle and period for the various GPIO pins created in the Linux file system.

Assignment 3 :
Developing and running Kernel modules , Character device drivers for performing user defined applications . Involved implementing basic read, write , IOCTL configuration functions for a specific character device . Loading .ko modules on the target board. This provided us with deep insights of device driver programming. 

Assignment 4 :
Understanding of SPI protocol . Displaying animation sequence on the peripheral device of 8*8 led matrix module by implementing the High level SPI device driver . Modulating the speed and direction of the animation sequence by simultaneous detection of obstacle placed before an ultrasonic sensor. This is implemented using multiple Pthreads with specific priorities.
Removal of the existing spidev module from the kernel and custom implementation of Read, write , IOCTL commands of the spi device provided us with good understanding of device driver programming.
