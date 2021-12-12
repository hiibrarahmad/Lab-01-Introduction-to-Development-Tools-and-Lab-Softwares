# Lab-01-Introduction-to-Development-Tools-and-Lab-Softwares
Objectives   · Learn to use software development tools such as Arduino, Integrated Development Environment (IDE) (Atmel Studio, AVR Studio), Compiler (WinAVR), and Simulator (Proteus) for the AVR ATmega 328P microcontroller.  · Learn to program Arduino and ATmega328P


<p><span style="font-family: courier;">&nbsp;</span></p><p class="MsoNormal"><!--[if gte vml 1]><v:shapetype id="_x0000_t75" coordsize="21600,21600"
 o:spt="75" o:preferrelative="t" path="m@4@5l@4@11@9@11@9@5xe" filled="f"
 stroked="f">
 <v:stroke joinstyle="miter"/>
 <v:formulas>
  <v:f eqn="if lineDrawn pixelLineWidth 0"/>
  <v:f eqn="sum @0 1 0"/>
  <v:f eqn="sum 0 0 @1"/>
  <v:f eqn="prod @2 1 2"/>
  <v:f eqn="prod @3 21600 pixelWidth"/>
  <v:f eqn="prod @3 21600 pixelHeight"/>
  <v:f eqn="sum @0 0 1"/>
  <v:f eqn="prod @6 1 2"/>
  <v:f eqn="prod @7 21600 pixelWidth"/>
  <v:f eqn="sum @8 21600 0"/>
  <v:f eqn="prod @7 21600 pixelHeight"/>
  <v:f eqn="sum @10 21600 0"/>
 </v:formulas>
 <v:path o:extrusionok="f" gradientshapeok="t" o:connecttype="rect"/>
 <o:lock v:ext="edit" aspectratio="t"/>
</v:shapetype><v:shape id="Picture_x0020_1" o:spid="_x0000_s1026" type="#_x0000_t75"
 style='position:absolute;margin-left:355.7pt;margin-top:.05pt;width:171pt;
 height:152.3pt;z-index:251658240;visibility:visible;mso-wrap-style:square;
 mso-wrap-distance-left:9pt;mso-wrap-distance-top:0;mso-wrap-distance-right:9pt;
 mso-wrap-distance-bottom:0;mso-position-horizontal:absolute;
 mso-position-horizontal-relative:text;mso-position-vertical:absolute;
 mso-position-vertical-relative:text'>
 <v:imagedata src="file:///C:/Users/AEGON/AppData/Local/Temp/msohtmlclip1/01/clip_image001.jpg"
  o:title=""/>
 <w:wrap type="through"/>
</v:shape><![endif]--></p><div class="separator" style="clear: both; text-align: center;"><a href="https://lh3.googleusercontent.com/-dWXeQrfElsc/YbWxOQ28pBI/AAAAAAABGpo/z7wxj8q1wvkoIGjR1DTf08aCZsip1LWKACNcBGAsYHQ/image.png" style="margin-left: 1em; margin-right: 1em;"><span style="font-family: courier;"><img alt="" data-original-height="317" data-original-width="356" height="240" src="https://lh3.googleusercontent.com/-dWXeQrfElsc/YbWxOQ28pBI/AAAAAAABGpo/z7wxj8q1wvkoIGjR1DTf08aCZsip1LWKACNcBGAsYHQ/image.png" width="270" /></span></a></div><span style="font-family: courier;"><br /><b><span style="font-size: 28pt; line-height: 107%;"><o:p></o:p></span></b></span><p></p>

<p class="MsoNormal"><b><span style="font-size: 36pt; line-height: 107%;"><span style="font-family: courier;">COMSATS
UNIVERSITY ISLAMABAD<o:p></o:p></span></span></b></p><p class="MsoNormal"><b><span style="font-size: 36pt; line-height: 107%;"><span></span></span></b></p><!--more--><b><span style="font-family: courier;"><br /></span></b><p></p>

<p class="MsoNormal"><b><span style="font-size: 24pt; line-height: 107%;"><o:p><span style="font-family: courier;">&nbsp;</span></o:p></span></b></p>

<p class="MsoNormal"><b><span style="font-size: 24pt; line-height: 107%;"><span style="font-family: courier;">MICROPROCESSOR SYSTEMS AND INTERFACING<o:p></o:p></span></span></b></p>

<p class="MsoNormal"><b><span style="font-size: 24pt; line-height: 107%;"><span style="font-family: courier;"><span style="mso-spacerun: yes;">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;</span>LAB REPORT 1<o:p></o:p></span></span></b></p>

<p class="MsoNormal"><span style="font-family: courier;"><b><u><span style="font-size: 14pt; line-height: 107%;">SUBMITTED TO:</span></u></b><b><span style="font-size: 14pt; line-height: 107%;"><o:p></o:p></span></b></span></p>

<p class="MsoNormal"><span style="font-size: 14pt; line-height: 107%;"><span style="font-family: courier;"><span style="mso-spacerun: yes;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span><span style="mso-spacerun: yes;">&nbsp;&nbsp;&nbsp;</span><span style="mso-spacerun: yes;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>SIR KHIYAM IFTIKHAR<o:p></o:p></span></span></p>

<p class="MsoNormal"><b><u><span style="font-size: 14pt; line-height: 107%;"><span style="font-family: courier;">SUBMITTED BY:<o:p></o:p></span></span></u></b></p>

<p class="MsoNormal" style="tab-stops: 150.45pt;"><span style="font-size: 14pt; line-height: 107%;"><span style="font-family: courier;"><span style="mso-spacerun: yes;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span>JUNAID AHMAD<o:p></o:p></span></span></p>

<p class="MsoNormal" style="tab-stops: 150.45pt;"><span style="font-size: 14pt; line-height: 107%;"><span style="font-family: courier;"><span style="mso-spacerun: yes;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span>IBRAR AHMAD<o:p></o:p></span></span></p>

<p class="MsoNormal" style="tab-stops: 150.45pt;"><span style="font-size: 14pt; line-height: 107%;"><span style="font-family: courier;"><span style="mso-spacerun: yes;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span>JARRAR MALIK<b><u><o:p></o:p></u></b></span></span></p>

<p class="MsoNormal"><b><u><span style="font-size: 14pt; line-height: 107%;"><span style="font-family: courier;">REGISTRATION NO:<o:p></o:p></span></span></u></b></p>

<p class="MsoNormal"><span style="font-size: 14pt; line-height: 107%;"><span style="font-family: courier;"><span style="mso-spacerun: yes;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span>CIIT/FA19-BEE-089/ISB<o:p></o:p></span></span></p>

<p class="MsoNormal"><span style="font-size: 14pt; line-height: 107%;"><span style="font-family: courier;"><span style="mso-spacerun: yes;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span>CIIT/FA19-BEE-083/ISB<o:p></o:p></span></span></p>

<p class="MsoNormal"><span style="font-size: 14pt; line-height: 107%;"><span style="font-family: courier;"><span style="mso-spacerun: yes;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span>CIIT/FA19-BEE-087/ISB<o:p></o:p></span></span></p>

<p class="MsoNormal"><b><u><span style="font-size: 14pt; line-height: 107%;"><span style="font-family: courier;">DATE:<o:p></o:p></span></span></u></b></p>

<p class="MsoNormal"><span style="font-size: 14pt; line-height: 107%;"><span style="font-family: courier;"><span style="mso-spacerun: yes;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span>26-09-2021<o:p></o:p></span></span></p>

<p class="MsoNormal"><span style="font-size: 24pt; line-height: 107%;"><span style="font-family: courier;">Introduction
to Development Tools and Lab Software’s<o:p></o:p></span></span></p>

<p class="MsoNormal"><span style="font-size: 24pt; line-height: 107%;"><o:p><span style="font-family: courier;">&nbsp;</span></o:p></span></p>

<p class="MsoNormal"><b><u><span style="font-size: 20pt; line-height: 107%;"><span style="font-family: courier;">Objectives<o:p></o:p></span></span></u></b></p>

<p class="MsoNormal"><span style="font-family: courier;"><span style="mso-spacerun: yes;">&nbsp;</span><span style="mso-char-type: symbol; mso-symbol-font-family: Symbol;">·</span> <span style="font-size: 14pt; line-height: 107%;">Learn to use software development tools such as
Arduino, Integrated Development Environment (IDE) (Atmel Studio, AVR Studio),
avrdudes, and Simulator (Proteus) for the AVR ATmega 328P
microcontroller. <o:p></o:p></span></span></p>

<p class="MsoNormal"><span style="font-family: courier;"><span style="font-size: 14pt; line-height: 107%;"><span style="mso-char-type: symbol; mso-symbol-font-family: Symbol;">·</span></span><span style="font-size: 14pt; line-height: 107%;"> Learn to program Arduino and ATmega328P<o:p></o:p></span></span></p>

<p class="MsoNormal"><span style="font-size: 14pt; line-height: 107%;"><o:p><span style="font-family: courier;">&nbsp;</span></o:p></span></p>

<p class="MsoNormal"><b><u><span style="font-size: 18pt; line-height: 107%;"><span style="font-family: courier;">IN LAB
TASKS:<o:p></o:p></span></span></u></b></p>

<p class="MsoNormal"><b><u><span style="font-size: 16pt; line-height: 107%;"><span style="font-family: courier;">Task
1: Arduino Learning Tutorial</span></span></u></b></p><p class="MsoListParagraphCxSpFirst" style="line-height: 115%; mso-list: l1 level1 lfo2; text-indent: -0.25in;"><!--[if !supportLists]--><span style="font-family: courier;"><span style="font-size: 16pt; line-height: 115%;">·<span style="font-size: 7pt; font-stretch: normal; font-variant-east-asian: normal; font-variant-numeric: normal; line-height: normal;">&nbsp;</span></span></span></p><p class="MsoListParagraphCxSpMiddle" style="line-height: 115%;"><span style="font-size: 12pt; line-height: 115%;"><span style="font-family: courier;">In this task I opened the ARDUINO IDE software and open the example code
of blinking led. Then sketch that code on the Arduino uno which have ATmega
328p microprocessor chip on it. Then from one pin of digital port I take an out
put and give it to an LED and ground the led. When the Arduino is powered then
led have started blinking with time delay of 1ms.<o:p></o:p></span></span></p><p align="center" class="MsoListParagraphCxSpMiddle" style="line-height: 115%; text-align: center;"><u><span style="font-size: 12pt; line-height: 115%;"><span style="font-family: courier;">The code
for delay is as.<o:p></o:p></span></span></u></p><p class="MsoListParagraphCxSpMiddle" style="line-height: 115%;"><span style="font-size: 11pt; line-height: 115%;"><span style="font-family: courier;">void setup()<o:p></o:p></span></span></p><p class="MsoListParagraphCxSpMiddle" style="line-height: 115%;"><span style="font-size: 11pt; line-height: 115%;"><span style="font-family: courier;">&nbsp;{// initialize digital pin LED_BUILTIN as an
output.<o:p></o:p></span></span></p><p class="MsoListParagraphCxSpMiddle" style="line-height: 115%;"><span style="font-size: 11pt; line-height: 115%;"><span style="font-family: courier;">&nbsp;
pinMode(LED_BUILTIN, OUTPUT);<o:p></o:p></span></span></p><p class="MsoListParagraphCxSpMiddle" style="line-height: 115%;"><span style="font-size: 11pt; line-height: 115%;"><span style="font-family: courier;">}<o:p></o:p></span></span></p><p class="MsoListParagraphCxSpMiddle" style="line-height: 115%;"><span style="font-size: 11pt; line-height: 115%;"><span style="font-family: courier;">&nbsp;</span></span></p><p class="MsoListParagraphCxSpMiddle" style="line-height: 115%;"><span style="font-size: 11pt; line-height: 115%;"><span style="font-family: courier;">// the loop function runs over and
over again forever<o:p></o:p></span></span></p><p class="MsoListParagraphCxSpMiddle" style="line-height: 115%;"><span style="font-size: 11pt; line-height: 115%;"><span style="font-family: courier;">void loop() {<o:p></o:p></span></span></p><p class="MsoListParagraphCxSpMiddle" style="line-height: 115%;"><span style="font-size: 11pt; line-height: 115%;"><span style="font-family: courier;">&nbsp;
digitalWrite(LED_BUILTIN, HIGH);&nbsp;&nbsp;
// turn the LED on (HIGH is the voltage level)<o:p></o:p></span></span></p><p class="MsoListParagraphCxSpMiddle" style="line-height: 115%;"><span style="font-size: 11pt; line-height: 115%;"><span style="font-family: courier;">&nbsp;
delay(1000); &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// wait for a second<o:p></o:p></span></span></p><p class="MsoListParagraphCxSpMiddle" style="line-height: 115%;"><span style="font-size: 11pt; line-height: 115%;"><span style="font-family: courier;">&nbsp;
digitalWrite(LED_BUILTIN, LOW);&nbsp;&nbsp;&nbsp;
// turn the LED off by making the voltage LOW<o:p></o:p></span></span></p><p class="MsoListParagraphCxSpMiddle" style="line-height: 115%;"><span style="font-size: 11pt; line-height: 115%;"><span style="font-family: courier;">&nbsp;
delay(1000);&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
// wait for a second<o:p></o:p></span></span></p><p class="MsoListParagraphCxSpMiddle" style="line-height: 115%;"><span style="font-size: 11pt; line-height: 115%;"><span style="font-family: courier;">}<o:p></o:p></span></span></p><p class="MsoNormal">































</p><p class="MsoListParagraphCxSpLast" style="line-height: 115%;"><span style="font-size: 11pt; line-height: 115%;"><span style="font-family: courier;">&nbsp;</span></span></p>

<p class="MsoNormal"><span style="font-size: 16pt; line-height: 107%;"><o:p><span style="font-family: courier;">&nbsp;</span></o:p></span></p>

<p class="MsoNormal"><span style="font-size: 16pt; line-height: 107%;"><span style="font-family: courier;">PROCEDURE:<o:p></o:p></span></span></p>

<p class="Default" style="margin-bottom: 9.55pt;"><span style="font-size: 14pt;"><span style="font-family: courier;">Firstly, Launch Arduino IDE. Then
Click on the toolbar menu: File &gt; Examples &gt; Basics &gt; Blink. This will
turn an LED on Arduino board on and off with some delay. After which Compile
the sketch and upload the code to the Arduino board. Following results were
obtained</span></span></p>

<p class="Default" style="margin-bottom: 9.55pt;"><b><span style="font-size: 16pt;"><span style="font-family: courier;">CODE:<o:p></o:p></span></span></b></p>

<p class="Default" style="margin-bottom: 9.55pt;"><span style="mso-no-proof: yes;"><span style="font-family: courier;"><!--[if gte vml 1]><v:shape
 id="Picture_x0020_2" o:spid="_x0000_i1030" type="#_x0000_t75" alt="Graphical user interface, text, application&#10;&#10;Description automatically generated"
 style='width:468pt;height:263.25pt;visibility:visible;mso-wrap-style:square'>
 <v:imagedata src="file:///C:/Users/AEGON/AppData/Local/Temp/msohtmlclip1/01/clip_image003.png"
  o:title="Graphical user interface, text, application&#10;&#10;Description automatically generated"/>
</v:shape><![endif]--></span></span></p><div class="separator" style="clear: both; text-align: center;"><span style="font-family: courier;"><a href="https://lh3.googleusercontent.com/-DUHxYRwAlwc/YbWxT6vHIsI/AAAAAAABGps/8PD2koFiZv8DDpjGqMmGQQzQ_8hJIfFxwCNcBGAsYHQ/image.png" style="margin-left: 1em; margin-right: 1em;"><img alt="" data-original-height="548" data-original-width="975" src="https://lh3.googleusercontent.com/-DUHxYRwAlwc/YbWxT6vHIsI/AAAAAAABGps/8PD2koFiZv8DDpjGqMmGQQzQ_8hJIfFxwCNcBGAsYHQ/s16000/image.png" /></a></span></div><p></p><p class="Default" style="margin-bottom: 9.55pt;"><span style="font-family: courier;"><br /></span></p>

<p class="Default" style="margin-bottom: 9.55pt;"></p><div class="separator" style="clear: both; text-align: center;"><a href="https://lh3.googleusercontent.com/-IGva6dw9oHU/YbWxbhZDpkI/AAAAAAABGpw/Fu1HE4KANC4Z8mrabcngq8RQcBRMoNPlACNcBGAsYHQ/image.png" style="margin-left: 1em; margin-right: 1em;"><span style="font-family: courier;"><img alt="" data-original-height="608" data-original-width="975" src="https://lh3.googleusercontent.com/-IGva6dw9oHU/YbWxbhZDpkI/AAAAAAABGpw/Fu1HE4KANC4Z8mrabcngq8RQcBRMoNPlACNcBGAsYHQ/s16000/image.png" /></span></a></div><span style="font-family: courier;"><br /></span><p class="Default" style="margin-bottom: 9.55pt;">AS WE SEE THE<b><u> L </u></b>LED IS ON</p><div class="separator" style="clear: both; text-align: center;"><img border="0" data-original-height="564" data-original-width="696" height="564" src="https://roboticsbackend.com/wp-content/uploads/2021/09/arduino_builtin_led.png" width="696" /></div><p></p>

<p class="Default" style="margin-bottom: 9.55pt;"><b><u><span style="font-size: 16pt;"><span style="font-family: courier;">Task 2: AVR
Studio Learning Tutorial<o:p></o:p></span></span></u></b></p>

<p class="Default" style="margin-bottom: 9.55pt;"><span style="font-size: 16pt;"><span style="font-family: courier;">PROCEDURE:<o:p></o:p></span></span></p>

<p class="MsoListParagraphCxSpFirst" style="line-height: 115%;"><span style="font-family: courier;"><span style="font-weight: normal; line-height: 115%;">For this task the
code in given in the lab manual. I copied that code and run the code and
generate .hex file for the code and will use it further for simulation and
hardware implementation of program</span><span style="font-size: 11pt; font-weight: normal; line-height: 115%; mso-bidi-font-weight: bold;">.<o:p></o:p></span></span></p><p class="MsoListParagraphCxSpFirst" style="line-height: 115%;"><span style="font-size: 11pt; font-weight: normal; line-height: 115%; mso-bidi-font-weight: bold;"><span style="font-family: courier;"><br /></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="color: green; font-size: 9.5pt;"><span style="font-family: courier;">/*</span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="color: green; font-size: 9.5pt;">&nbsp;*</span><span style="font-size: 9.5pt;"><o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="color: green; font-size: 9.5pt;">&nbsp;* Created: 9/21/2021 10:19:52 AM</span><span style="font-size: 9.5pt;"><o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="color: green; font-size: 9.5pt;"><span style="font-family: courier;">&nbsp;*&nbsp;
Author: MENDUPMIDCODE</span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="color: green; font-size: 9.5pt;">&nbsp;*/</span><span style="color: maroon; font-size: 9.5pt;"> </span><span style="font-size: 9.5pt;"><o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-size: 9.5pt;"><span style="font-family: courier;">&nbsp;</span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="color: blue; font-size: 9.5pt;">#include</span><span style="color: maroon; font-size: 9.5pt;"> </span><span style="font-size: 9.5pt;">&lt;avr/io.h&gt;<o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="color: blue; font-size: 9.5pt;">#define</span><span style="color: maroon; font-size: 9.5pt;"> </span><span style="font-size: 9.5pt;">F_CPU<span style="color: maroon;"> </span>16000000UL<o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="color: blue; font-size: 9.5pt;">#include</span><span style="color: maroon; font-size: 9.5pt;"> </span><span style="font-size: 9.5pt;">&lt;util/delay.h&gt;<o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-size: 9.5pt;"><span style="font-family: courier;">&nbsp;</span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="color: blue; font-size: 9.5pt;">int</span><span style="color: maroon; font-size: 9.5pt;"> </span><span style="font-size: 9.5pt;">main(<span style="color: blue;">void</span>)<o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-size: 9.5pt;"><span style="font-family: courier;">{<o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="color: maroon; font-size: 9.5pt;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span><span style="font-size: 9.5pt;">DDRB=0b11111111;<o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="color: maroon; font-size: 9.5pt;">&nbsp;&nbsp;&nbsp; </span><span style="color: blue; font-size: 9.5pt;">while</span><span style="font-size: 9.5pt;">(1)<o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="color: maroon; font-size: 9.5pt;">&nbsp;&nbsp;&nbsp; </span><span style="font-size: 9.5pt;">{<o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="color: maroon; font-size: 9.5pt;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span><span style="font-size: 9.5pt;">PORTB=0b00100000;<o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="color: maroon; font-size: 9.5pt;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span><span style="font-size: 9.5pt;">_delay_ms(1000);<o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="color: maroon; font-size: 9.5pt;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span><span style="font-size: 9.5pt;">PORTB=0b00000000;<o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="color: maroon; font-size: 9.5pt;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span><span style="font-size: 9.5pt;">_delay_ms(1000);<o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="color: maroon; font-size: 9.5pt;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span><span style="font-size: 9.5pt;"><o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="color: maroon; font-size: 9.5pt;">&nbsp;&nbsp;&nbsp; </span><span style="font-size: 9.5pt;">}<o:p></o:p></span></span></p><p class="MsoListParagraphCxSpFirst" style="line-height: 115%;">











































</p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-size: 9.5pt;"><span style="font-family: courier;">}<o:p></o:p></span></span></p>

<p class="MsoListParagraphCxSpMiddle" style="line-height: 115%;"><span style="mso-no-proof: yes;"><span style="font-family: courier;"><!--[if gte vml 1]><v:shape id="Picture_x0020_4"
 o:spid="_x0000_i1028" type="#_x0000_t75" alt="A screenshot of a computer&#10;&#10;Description automatically generated"
 style='width:468pt;height:263.25pt;visibility:visible;mso-wrap-style:square'>
 <v:imagedata src="file:///C:/Users/AEGON/AppData/Local/Temp/msohtmlclip1/01/clip_image007.png"
  o:title="A screenshot of a computer&#10;&#10;Description automatically generated"/>
</v:shape><![endif]--></span></span></p><div class="separator" style="clear: both; text-align: center;"><span style="font-family: courier;"><br /></span></div><div class="separator" style="clear: both; text-align: center;"><span style="font-family: courier;"><img alt="" data-original-height="548" data-original-width="975" src="https://lh3.googleusercontent.com/-I1KW85b3c-I/YbWxjvh5XjI/AAAAAAABGp4/jUO13JraVXAVscSCSt7QivyEeqzYmcmUQCNcBGAsYHQ/s16000/image.png" /></span></div><p></p>

<p class="MsoNormal" style="line-height: 115%;"><b><u><span style="font-size: 16pt; line-height: 115%; mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;"><span style="font-family: courier;">Task
3: Atmel Studio Learning Tutorial<o:p></o:p></span></span></u></b></p>

<p class="MsoNormal" style="line-height: 115%;"><span style="font-size: 16pt; line-height: 115%; mso-bidi-font-family: Calibri; mso-bidi-theme-font: minor-latin;"><span style="font-family: courier;">PROCEDURE:<o:p></o:p></span></span></p>

<p class="MsoListParagraphCxSpFirst" style="line-height: 115%;"><span style="font-family: courier;"><span style="font-weight: normal; line-height: 115%;">For this task the
code in given in the lab manual. I copied that code and run the code and
generate .hex file for the code and will use it further for simulation and
hardware implementation of program</span><span style="font-size: 11pt; font-weight: normal; line-height: 115%; mso-bidi-font-weight: bold;">.<o:p></o:p></span></span></p><p class="MsoListParagraphCxSpFirst" style="line-height: 115%;"><span style="font-size: 11pt; font-weight: normal; line-height: 115%; mso-bidi-font-weight: bold;"><span style="font-family: courier;"><br /></span></span></p><p class="MsoListParagraphCxSpFirst" style="line-height: 115%;"><span style="font-size: 11pt; font-weight: normal; line-height: 115%; mso-bidi-font-weight: bold;"><span style="font-family: courier;"><br /></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="background: white; color: green; font-size: 10pt;">/*</span><span style="background: white; font-size: 10pt;"><o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="background: white; color: green; font-size: 10pt;">&nbsp;* MAIN.c</span><span style="background: white; font-size: 10pt;"><o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="background: white; color: green; font-size: 10pt;">&nbsp;*</span><span style="background: white; font-size: 10pt;"><o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="background: white; color: green; font-size: 10pt;">&nbsp;* Created: 9/21/2021 10:47:41 AM</span><span style="background: white; font-size: 10pt;"><o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="background: white; color: green; font-size: 10pt;">&nbsp;* Author : MENDUPMINDCODE</span><span style="background: white; font-size: 10pt;"><o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="background: white; color: green; font-size: 10pt;">&nbsp;*/</span><span style="background: white; color: #a31515; font-size: 10pt;"> </span><span style="background: white; font-size: 10pt;"><o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="background: white; font-size: 10pt;"><o:p><span style="font-family: courier;">&nbsp;</span></o:p></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="background: white; color: blue; font-size: 10pt;">#include</span><span style="background: white; color: #a31515; font-size: 10pt;"> </span><span style="background: white; font-size: 10pt;">&lt;avr/io.h&gt;<o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="background: white; color: blue; font-size: 10pt;">#define</span><span style="background: white; color: #a31515; font-size: 10pt;"> </span><i><span style="background: white; color: #a000a0; font-size: 10pt;">F_CPU</span></i><span style="background: white; color: #a31515; font-size: 10pt;"> </span><span style="background: white; font-size: 10pt;">16000000UL<o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="background: white; color: blue; font-size: 10pt;">#include</span><span style="background: white; color: #a31515; font-size: 10pt;"> </span><span style="background: white; font-size: 10pt;">&lt;util/delay.h&gt;<o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="background: white; font-size: 10pt;"><o:p><span style="font-family: courier;">&nbsp;</span></o:p></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="background: white; color: blue; font-size: 10pt;">int</span><span style="background: white; color: #a31515; font-size: 10pt;"> </span><span style="background: white; color: #880000; font-size: 10pt;">main</span><span style="background: white; font-size: 10pt;">(</span><span style="background: white; color: blue; font-size: 10pt;">void</span><span style="background: white; font-size: 10pt;">)<o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="background: white; font-size: 10pt;"><span style="font-family: courier;">{<o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="background: white; color: #a31515; font-size: 10pt;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span><span style="background: white; color: #a000a0; font-size: 10pt;">DDRB</span><span style="background: white; font-size: 10pt;">=0b11111111;<o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="background: white; color: #a31515; font-size: 10pt;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span><span style="background: white; color: blue; font-size: 10pt;">while</span><span style="background: white; font-size: 10pt;">(1)<o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="background: white; color: #a31515; font-size: 10pt;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span><span style="background: white; font-size: 10pt;">{<o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="background: white; color: #a31515; font-size: 10pt;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span><span style="background: white; color: #a000a0; font-size: 10pt;">PORTB</span><span style="background: white; font-size: 10pt;">=0b00100000;<o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="background: white; color: #a31515; font-size: 10pt;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span><i><span style="background: white; color: #880000; font-size: 10pt;">_delay_ms</span></i><span style="background: white; font-size: 10pt;">(1000);<o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="background: white; color: #a31515; font-size: 10pt;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span><span style="background: white; color: #a000a0; font-size: 10pt;">PORTB</span><span style="background: white; font-size: 10pt;">=0b00000000;<o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="background: white; color: #a31515; font-size: 10pt;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span><i><span style="background: white; color: #880000; font-size: 10pt;">_delay_ms</span></i><span style="background: white; font-size: 10pt;">(1000);<o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="background: white; color: #a31515; font-size: 10pt;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span><span style="background: white; font-size: 10pt;"><o:p></o:p></span></span></p><p class="MsoNormal" style="line-height: normal; margin-bottom: 0in; margin-left: .5in; margin-right: 0in; margin-top: 0in; margin: 0in 0in 0in 0.5in; mso-layout-grid-align: none; text-autospace: none;"><span style="font-family: courier;"><span style="background: white; color: #a31515; font-size: 10pt;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span><span style="background: white; font-size: 10pt;">}<o:p></o:p></span></span></p><p class="MsoListParagraphCxSpFirst" style="line-height: 115%;">











































</p><p class="MsoListParagraph" style="line-height: 115%; margin-left: 1in; mso-add-space: auto;"><span style="font-family: courier;"><span style="background: white; font-size: 10pt; line-height: 115%;">}</span><span style="font-size: 12pt; line-height: 115%; mso-bidi-font-weight: bold;"><o:p></o:p></span></span></p><p class="MsoListParagraph" style="line-height: 115%; margin-left: 1in; mso-add-space: auto;"><span style="background: white; font-size: 10pt; line-height: 115%;"><span style="font-family: courier;"><br /></span></span></p>

<p class="MsoListParagraphCxSpMiddle" style="line-height: 115%;"><span style="mso-no-proof: yes;"><span style="font-family: courier;"><!--[if gte vml 1]><v:shape id="Picture_x0020_5"
 o:spid="_x0000_i1027" type="#_x0000_t75" alt="A screenshot of a computer&#10;&#10;Description automatically generated"
 style='width:468pt;height:263.25pt;visibility:visible;mso-wrap-style:square'>
 <v:imagedata src="file:///C:/Users/AEGON/AppData/Local/Temp/msohtmlclip1/01/clip_image007.png"
  o:title="A screenshot of a computer&#10;&#10;Description automatically generated"/>
</v:shape><![endif]--></span></span></p><div class="separator" style="clear: both; text-align: center;"><span style="font-family: courier;"><img alt="" data-original-height="548" data-original-width="975" src="https://lh3.googleusercontent.com/-lOAUeI_wpvc/YbWxm8adKWI/AAAAAAABGp8/ua8-a5PLI6YPIHy6fD9kkkISGluBkvntgCNcBGAsYHQ/s16000/image.png" /></span></div><p></p>

<p class="Default" style="margin-bottom: 9.55pt;"><b><u><span style="font-size: 16pt;"><span style="font-family: courier;">Task 4(1):
Proteus Introductory Learning Tutorial</span></span></u></b></p>

<p class="Default" style="margin-bottom: 9.55pt;"><span style="font-size: 16pt;"><span style="font-family: courier;">PROCEDURE:<o:p></o:p></span></span></p>

<p class="Default"><span style="font-size: 14pt;"><span style="font-family: courier;">Open the proteus to simulate microcontroller using proteus. Then
construct the circuit as shown below containing microcontroller ATmega328P from
pick library and animated LED in series with resistor. Following circuit is
obtained, after loading a program in microcontroller through hex file created
in atmel in previous task and then changing frequencies of AT mega 328P to 1Mhz
and clock frequency to 16MH, the circuit was simulated and run and observed
that led started blinking.<o:p></o:p></span></span></p>

<p class="Default" style="margin-bottom: 9.55pt;"><span style="mso-no-proof: yes;"><span style="font-family: courier;"><!--[if gte vml 1]><v:shape
 id="Picture_x0020_7" o:spid="_x0000_i1026" type="#_x0000_t75" alt="A picture containing table&#10;&#10;Description automatically generated"
 style='width:468pt;height:263.25pt;visibility:visible;mso-wrap-style:square'>
 <v:imagedata src="file:///C:/Users/AEGON/AppData/Local/Temp/msohtmlclip1/01/clip_image010.png"
  o:title="A picture containing table&#10;&#10;Description automatically generated"/>
</v:shape><![endif]--></span></span></p><div class="separator" style="clear: both; text-align: center;"><span style="font-family: courier;"><a href="https://lh3.googleusercontent.com/-WplmMLedhns/YbWxp6IQzHI/AAAAAAABGqA/B9xgfMM_7IMBfcSD6b4PGp4QWkTRPoTOACNcBGAsYHQ/image.png" style="margin-left: 1em; margin-right: 1em;"><img alt="" data-original-height="548" data-original-width="975" src="https://lh3.googleusercontent.com/-WplmMLedhns/YbWxp6IQzHI/AAAAAAABGqA/B9xgfMM_7IMBfcSD6b4PGp4QWkTRPoTOACNcBGAsYHQ/s16000/image.png" /></a></span></div><p></p><p class="Default" style="margin-bottom: 9.55pt;"><b><u><span style="font-size: 16pt;"><span style="font-family: courier;">Task 4(2):</span></span></u></b></p>

<p class="Default" style="margin-bottom: 9.55pt;"><span style="font-size: 14pt;"><span style="font-family: courier;">a. The following code is written
to generate Fibonacci series output at PortB which is given as (0, 1, 2, 3, 5,
8, 13, 21, 34, 55). <o:p></o:p></span></span></p>

<p class="Default" style="margin-bottom: 9.55pt;"><span style="font-size: 14pt;"><span style="font-family: courier;">b. Build the following code in AVR
Studio or Atmel Studio. Read the error messages, identify, and correct any
syntax errors and rebuild the solution. <o:p></o:p></span></span></p>

<p class="Default" style="margin-bottom: 9.55pt;"><span style="font-size: 14pt;"><span style="font-family: courier;">c. Use Debugging mode of AVR
Studio or Atmel Studio to debug and correct the code to get the desired output.
In debug mode, open watch window to check the value of the variables.<o:p></o:p></span></span></p>

<p class="Default" style="margin-bottom: 9.55pt;"><span style="font-size: 14pt;"><o:p><span style="font-family: courier;">&nbsp;</span></o:p></span></p>

<p class="Default" style="margin-bottom: 9.55pt;"><b><u><span style="font-size: 16pt;"><span style="font-family: courier;">CORRECT CODE:<o:p></o:p></span></span></u></b></p>

<p class="Default" style="margin-bottom: 9.55pt;"><span style="font-size: 14pt;"><o:p><span style="font-family: courier;">&nbsp;</span></o:p></span></p>

<p class="Default" style="margin-bottom: 9.55pt;"><span style="mso-no-proof: yes;"><span style="font-family: courier;"><!--[if gte vml 1]><v:shape
 id="Picture_x0020_9" o:spid="_x0000_i1025" type="#_x0000_t75" alt="A screenshot of a computer&#10;&#10;Description automatically generated"
 style='width:468pt;height:263.25pt;visibility:visible;mso-wrap-style:square'>
 <v:imagedata src="file:///C:/Users/AEGON/AppData/Local/Temp/msohtmlclip1/01/clip_image012.png"
  o:title="A screenshot of a computer&#10;&#10;Description automatically generated"/>
</v:shape><![endif]--></span></span></p><div class="separator" style="clear: both; text-align: center;"><span style="font-family: courier;"><a href="https://lh3.googleusercontent.com/-WNLrNb7W2T0/YbWxs_w__hI/AAAAAAABGqI/XcXplSDogic8fPAQk13sxnmPCZrwVW4GwCNcBGAsYHQ/image.png" style="margin-left: 1em; margin-right: 1em;"><img alt="" data-original-height="548" data-original-width="975" src="https://lh3.googleusercontent.com/-WNLrNb7W2T0/YbWxs_w__hI/AAAAAAABGqI/XcXplSDogic8fPAQk13sxnmPCZrwVW4GwCNcBGAsYHQ/s16000/image.png" /></a></span></div><p></p><p class="Default" style="margin-bottom: 9.55pt;"><b><span style="font-size: 20pt;"><o:p><span style="font-family: courier;"><br /></span></o:p></span></b></p><p class="MsoNormal"><u><span style="font-size: 14pt; line-height: 107%;"><span style="font-family: courier;">POST LAB
TASKS<br />
TASK#1:&nbsp; Blink 5 leds in sequence using Arduino.<o:p></o:p></span></span></u></p><p class="MsoNormal"><u><span style="font-size: 14pt; line-height: 107%;"><span style="font-family: courier;">CODE:<o:p></o:p></span></span></u></p><p class="MsoNormal"><u><span style="font-size: 14pt; line-height: 107%;"><span style="font-family: courier;"></span></span></u></p><div class="separator" style="clear: both; text-align: center;"><u><span style="font-family: courier;"><img alt="" data-original-height="401" data-original-width="533" height="240" src="https://lh3.googleusercontent.com/-F0Mp0EGfHZw/YbW0pkZjwoI/AAAAAAABGq4/o81chG4Q1f0tz5NLo8Fk5sJv9mV8J_nqQCNcBGAsYHQ/image.png" width="319" /><div class="separator" style="clear: both; text-align: center;"><img alt="" data-original-height="113" data-original-width="468" height="77" src="https://lh3.googleusercontent.com/-oW9qen35Mh0/YbW0smuJhQI/AAAAAAABGq8/db79FXYPXnoipVEzGFIR19DN4GSNAIKcgCNcBGAsYHQ/image.png" width="320" /></div></span></u></div><u><span style="font-family: courier;"><br /></span></u><p></p><p class="MsoNormal"><span style="font-family: courier;"><v:shapetype coordsize="21600,21600" filled="f" id="_x0000_t75" o:preferrelative="t" o:spt="75" path="m@4@5l@4@11@9@11@9@5xe" stroked="f">
 <v:stroke joinstyle="miter">
 <v:formulas>
  <v:f eqn="if lineDrawn pixelLineWidth 0">
  <v:f eqn="sum @0 1 0">
  <v:f eqn="sum 0 0 @1">
  <v:f eqn="prod @2 1 2">
  <v:f eqn="prod @3 21600 pixelWidth">
  <v:f eqn="prod @3 21600 pixelHeight">
  <v:f eqn="sum @0 0 1">
  <v:f eqn="prod @6 1 2">
  <v:f eqn="prod @7 21600 pixelWidth">
  <v:f eqn="sum @8 21600 0">
  <v:f eqn="prod @7 21600 pixelHeight">
  <v:f eqn="sum @10 21600 0">
 </v:f></v:f></v:f></v:f></v:f></v:f></v:f></v:f></v:f></v:f></v:f></v:f></v:formulas>
 <v:path gradientshapeok="t" o:connecttype="rect" o:extrusionok="f">
 <o:lock aspectratio="t" v:ext="edit">
</o:lock></v:path></v:stroke></v:shapetype><v:shape id="Picture_x0020_8" o:spid="_x0000_i1029" style="height: 192.75pt; mso-wrap-style: square; visibility: visible; width: 255.75pt;" type="#_x0000_t75">
 <v:imagedata cropbottom="16946f" cropright="36759f" croptop="10089f" o:title="" src="file:///C:/Users/AEGON/AppData/Local/Temp/msohtmlclip1/01/clip_image001.png">
</v:imagedata></v:shape><v:shape id="Picture_x0020_9" o:spid="_x0000_i1028" style="height: 83.25pt; mso-wrap-style: square; visibility: visible; width: 279pt;" type="#_x0000_t75">
 <v:imagedata cropbottom="12727f" cropleft="-1f" cropright="43163f" croptop="40940f" o:title="" src="file:///C:/Users/AEGON/AppData/Local/Temp/msohtmlclip1/01/clip_image002.png">
</v:imagedata></v:shape><u><span style="font-size: 14pt; line-height: 107%;"><o:p></o:p></span></u></span></p><p class="MsoNormal"><u><span style="font-size: 14pt; line-height: 107%;"><span style="font-family: courier;">Results:<o:p></o:p></span></span></u></p><p class="MsoNormal"><u><span style="font-size: 14pt; line-height: 107%;"><span style="font-family: courier;"></span></span></u></p><div class="separator" style="clear: both; text-align: center;"><u><span style="font-family: courier;"><a href="https://lh3.googleusercontent.com/-ADwJa6xc3m0/YbW03WoS8hI/AAAAAAABGrI/Rude7QqFADUS3Wnj7sgfdezheejDoNvPgCNcBGAsYHQ/image.png" style="margin-left: 1em; margin-right: 1em;"><img alt="" data-original-height="280" data-original-width="308" height="240" src="https://lh3.googleusercontent.com/-ADwJa6xc3m0/YbW03WoS8hI/AAAAAAABGrI/Rude7QqFADUS3Wnj7sgfdezheejDoNvPgCNcBGAsYHQ/image.png" width="264" /></a></span></u></div><u><span style="font-family: courier;"><br /><div class="separator" style="clear: both; text-align: center;"><a href="https://lh3.googleusercontent.com/-6jPie2PG0Ug/YbW0049_RiI/AAAAAAABGrE/O_kGK-0dt7MIhyOUGsqIOH0lysiswQS1gCNcBGAsYHQ/image.png" style="margin-left: 1em; margin-right: 1em;"><img alt="" data-original-height="284" data-original-width="314" height="240" src="https://lh3.googleusercontent.com/-6jPie2PG0Ug/YbW0049_RiI/AAAAAAABGrE/O_kGK-0dt7MIhyOUGsqIOH0lysiswQS1gCNcBGAsYHQ/image.png" width="265" /></a></div><br /><div class="separator" style="clear: both; text-align: center;"><a href="https://lh3.googleusercontent.com/-_ztPcWkFzhE/YbW0yF79i0I/AAAAAAABGrA/jqmwpImfwiU97k8V9oe16TYF3XyrDPpdgCNcBGAsYHQ/image.png" style="margin-left: 1em; margin-right: 1em;"><img alt="" data-original-height="279" data-original-width="335" height="240" src="https://lh3.googleusercontent.com/-_ztPcWkFzhE/YbW0yF79i0I/AAAAAAABGrA/jqmwpImfwiU97k8V9oe16TYF3XyrDPpdgCNcBGAsYHQ/image.png" width="288" /></a></div><div class="separator" style="clear: both; text-align: center;">etc</div><br /><br /></span></u><p></p>

<p class="MsoNormal"><b><span style="font-size: 14pt; line-height: 107%;"><span style="font-family: courier;">Conclusion:<o:p></o:p></span></span></b></p>

<p class="MsoNormal"><span style="font-family: courier;"><span style="font-size: 12pt; line-height: 107%;">In this lab
we were able to get a brief overview about AVR studio and Proteus. It is
clearly evidential that AVR studio is one of those platforms used to program
microcontrollers. We discussed about the different types of Arduinos and its
working. Although this was a general overview which explained how to create
project, running the program and to upload it on proteus we could have done a
bit more in this lab such as helping us understanding the limitations of this
software and to debug a problem when the software is not working or when the
output files are not being generated.</span><b><span style="font-size: 12pt; line-height: 107%;"><o:p></o:p></span></b></span></p>

<p class="MsoNormal"><b><span style="font-size: 14pt; line-height: 107%;"><span style="font-family: courier;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span><span style="font-family: Algerian;"><o:p></o:p></span></span></b></p>
