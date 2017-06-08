# ABOUT:
This project is being undertaken under the FOSSEE organisation of IIT BOMBAY under MHRD under the guidance of Dr.D B         Phatak(Patron),Rajesh Kushalkar(Manager, FOSSEE Projects) and Akshay Chipkar(Project Mentor).The project aims at developing open source hardware and software for 3D scanning of objects.

# DESCRIPTION:
This project is undertaken by four interns during the Summer of 2017 under the Ekalavya Project sponsored by the MHRD,India.
  ##  1. Sagar Satapathy, NIT Rourkela
  ##  2. Animesh Srivastava, NIT Hamirpur
  ##  3. Anchal Singh, NIT Uttarakhand
  ##  4. Soumya Sambit Rath, NIT Rourkela
  
# CONTENTS:
  ## 1.Hardware Used:
  ### 1.1 Arduino UNO:          
      Microcontroller-ATmega328
      Operating Voltage- 5V
      Input Voltage (recommended)- 7-12V
      Input Voltage (limits)- 6-20V
      Digital I/O Pins- 14 (of which 6 provide PWM output)
      Analog Input Pins- 6
      DC Current per I/O Pin- 40 mA
      DC Current for 3.3V Pin- 50 mA
      Flash Memory- 32 KB of which 0.5 KB used by bootloader
      SRAM- 2 KB (ATmega328)
      EEPROM- 1 KB (ATmega328)
      Clock Speed- 16 MHz

  ### 1.2 Laser Module(INT 2549):
      Output Power:
      Min:2.5mW  
      Typical:3.0mW 
      Max:5.0mW
      Working current:
      Min:10mA
      Typical:20mA
      Max:25mA
      Working voltage:
      Min:2.3V
      Typical:4.5V
      Max:8.0V
      Wavelength:
        650nm
      Focused Dot Width:
        < 2mm spotting 3 meters away
    
  ### 1.3 Stepper Motor(28BYJ-48):
        Rated voltage ： 5V DC
        Number of Phase ： 4
        Speed Variation Ratio ： 1/64
        Stride Angle ： 5.625° /64
        Frequency : 100Hz
        DC resistance ： 200Ω±7%(25℃)
        Idle In-traction Frequency : >600Hz
        Idle Out-traction Frequency : >1000Hz
        In-traction Torque : >34.3mN.m(120Hz)
        Self-positioning Torque : >34.3mN.m
        Friction torque : 800-1800 gf.cm
        Pull in torque  : 450 gf.cm
        Insulated resistance : >10MΩ(500V)

  ## 2.Open Source Technologies Used:
  
  ### 2.1 Python 2.7
      Python was chosen as the default language for writing all the programs throughout the project. The version used by the developers was 2.7.6
      
  ### 2.2 PyOpenGL 
      PyOpenGL is the most common cross platform Python binding to OpenGL and related APIs. The binding is created using the standard ctypes library, and is provided under an extremely liberal BSD-style Open-Source license.
      Url: http://pyopengl.sourceforge.net/
      
  ### 2.3 OpenCV 3.2.0
      OpenCV (Open Source Computer Vision Library) is released under a BSD license and hence it’s free for both academic     and commercial use. Written in optimized C/C++, the library can take advantage of multi-core processing.
      Url: http://opencv.org/
 
  ### 2.4 Numpy 
      NumPy is the fundamental package for scientific computing with Python.Besides its obvious scientific uses, NumPy can also be used as an efficient multi-dimensional container of generic data. Arbitrary data-types can be defined. This allows NumPy to seamlessly and speedily integrate with a wide variety of databases.NumPy is licensed under the BSD license, enabling reuse with few restrictions.
      Url: http://www.numpy.org/
      
  ### 2.5 Matplotlib
      Matplotlib is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms.
      Url: https://matplotlib.org/
      
  ### 2.6 Pygame 
      Pygame is a cross-platform set of Python modules designed for writing video games. It includes computer graphics and sound libraries designed to be used with the Python programming language.
      It was used in the project for rendering the graphics in the display window.
      Url: https://www.pygame.org/news
      
  ### 2.7 Tkinter
      Tkinter is Python's de-facto standard GUI (Graphical User Interface) package.It was used for creating the windows and the widgets.
      Url: https://wiki.python.org/moin/TkInter
      
  ### 2.8 Python Imaging Library
      The Python Imaging Library (PIL) adds image processing capabilities to your Python interpreter. This library supports many file formats, and provides powerful image processing and graphics capabilities. the version that was used is 1.1.7
      Url: http://www.pythonware.com/products/pil/
      
  ### 2.9 Pyserial 
      Python Serial Port Extension package
      Since a MicroController was used, this package was used for serial communications.
      Url: https://pypi.python.org/pypi/pyserial
  
# INSTALLATION

# USAGE:
  
# CONTRIBUTING

# CREDITS

# LICENSE
MIT License

Copyright (c) 2017 Team SAAS

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
  
