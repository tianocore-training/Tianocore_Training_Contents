---?image=assets/images/gitpitch-audience.jpg
@title[Tianocore Open Source Training contents]
<br><br><br><br><br>
## <span class="gold"   >UEFI & EDK II Training</span>

#### Training Table of contents

<br>
<span style="font-size:0.75em" ><a href='http://www.tianocore.org'>tianocore.org</a></span>
Note:
  PITCHME.md for UEFI / EDK II Training  Contents and Overview

  Copyright (c) 2018, Intel Corporation. All rights reserved.<BR>

  Redistribution and use in source (original document form) and 'compiled'
  forms (converted to PDF, epub, HTML and other formats) with or without
  modification, are permitted provided that the following conditions are met:

  1) Redistributions of source code (original document form) must retain the
     above copyright notice, this list of conditions and the following
     disclaimer as the first lines of this file unmodified.

  2) Redistributions in compiled form (transformed to other DTDs, converted to
     PDF, epub, HTML and other formats) must reproduce the above copyright
     notice, this list of conditions and the following disclaimer in the
     documentation and/or other materials provided with the distribution.

  THIS DOCUMENTATION IS PROVIDED BY TIANOCORE PROJECT "AS IS" AND ANY EXPRESS OR
  IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF
  MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO
  EVENT SHALL TIANOCORE PROJECT  BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
  SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
  PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS;
  OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY,
  WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR
  OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS DOCUMENTATION, EVEN IF
  ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

---  
@title[Schedule]
#### <p align="center"<span class="gold"   >Suggested Schedule </span></p><br>

The next slides will have links to the appropriate slide show in the suggested order. <br>
- <font color="yellow">Unit 1:</font>  <span style="font-size:0.9em">Overview of EDK II, UEFI Shell Lab, and overview of UEFI aware OS</span><br>
- <font color="yellow">Unit 2:</font>  <span style="font-size:0.9em">More details of the EDK II infrastructure and Labs with writing UEFI Applications and Drivers</span><br>
- <font color="yellow">Unit 3:</font>  <span style="font-size:0.9em">Porting and Debugging using a Open Source example with EDK II</span><br>
- <font color="yellow">Unit 4:</font>  <span style="font-size:0.9em">Advanced topics for a shorter session after Units 1-3 completed</span>

 
Note:
Unit 1
  - Overview UEFI / FSP Boot Flow, EDK II Build Environment & Process, EDK II Build Spec Files, Open Source UEFI Platforms, EDK II Platform Build Lab, UEFI Shell & Edk II Build Lab, UEFI Aware OS -UEFI Secure boot-Capsule Update
Unit 2
  - EDK II Libraries and Modules and Drivers, EDK II Platforms configuration Database (PCD),  UEFI Application Writers Lab, UEFI Driver Wizard Lab - Driver Model

Unit 3
  - Porting w/ EDK II using Open Source example, Porting Beyond the Shell w/ EDK II,  EDK II Debugging Lab, Source Level Debugging w/ UDK Debugger
Unit 4
  - UEFI / EDK II Network,  UEFI / EDK II Security,  UEFI / EDK II - HII Lab, EDK Compatibility Package



---  
@title[Schedule 01]
<br>
### <p align="center"<span class="gold"   >Suggested Schedule - Unit 1</span></p><br>

<!---  Add bullets using https://fontawesome.com/cheatsheet certificate
-->
@fa[certificate gp-bullet-green]&nbsp;&nbsp;<span style="font-size:0.9em"><a href='https://gitpitch.com/Laurie0131/UEFI_Boot_Flow_Pres2/master#/' >Overview UEFI Boot Flow </a> </span><br>
@fa[certificate gp-bullet-cyan]&nbsp;&nbsp;<span style="font-size:0.9em"><a href='https://gitpitch.com/Laurie0131/EDK__II_Build_Process_Pres_2/master#/' >EDK II Build Process</a> and <a href='https://gitpitch.com/Laurie0131/EDK_II_Build_Spec_Files_Pres/master#/' >Build Spec Files </a> </span><br>
@fa[certificate gp-bullet-magenta]&nbsp;&nbsp;<span style="font-size:0.9em"><a href='https://gitpitch.com/Laurie0131/OpenSource_Platforms_Pres/master#/' >EDK II Open Source Platforms </a> </span><br>
@fa[certificate gp-bullet-ltgreen]&nbsp;&nbsp;<span style="font-size:0.9em"><a href='https://gitpitch.com/Laurie0131/Platform_Build_LAB/master#/'>EDK II Platform Build LABs </a>
(<a href='https://gitpitch.com/Laurie0131/Platform_Build_LAB/master#/2'>Ovmf </a>| <a href='https://gitpitch.com/Laurie0131/Platform_Build_LAB/master#/16'>Max HW setup</a> | <a href='https://gitpitch.com/Laurie0131/Platform_Build_LAB/master#/24'>Max </a>)  </span><br>
@fa[certificate gp-bullet-yellow]&nbsp;&nbsp;<span style="font-size:0.9em"><a href='https://gitpitch.com/Laurie0131/UEFI_Shell_App_pres/master#/' >UEFI Shell Overview</a> & <a href='https://gitpitch.com/Laurie0131/UEFI_Shell_Lab/master#/' >Shell LAB </a> </span><br>
@fa[certificate gp-bullet-cyan]&nbsp;&nbsp;<span style="font-size:0.9em"><a href='https://gitpitch.com/Laurie0131/UEFI_Aware_OS_pres/master#/' >UEFI Aware OS</a> , 
<a href='https://gitpitch.com/Laurie0131/UEFI_Aware_OS_pres/master#/14'>Secure Boot</a> , 
<a href='https://gitpitch.com/Laurie0131/UEFI_Aware_OS_pres/master#/22'>Smm/MMI</a> , 
<a href='https://gitpitch.com/Laurie0131/UEFI_Aware_OS_pres/master#/29'>coreboot</a> </span><br>
@fa[certificate gp-bullet-magenta]&nbsp;&nbsp;<span style="font-size:0.9em"><a href='https://gitpitch.com/Laurie0131/Capsule_Update_pres/master#/' >UEFI Capsule Update </a> </span> <br>


---  
@title[Schedule 02]
<BR>
### <p align="center"<span class="gold"   >Suggested Schedule - Unit 2</span></p><br>

<!---  Add bullets using https://fontawesome.com/cheatsheet certificate
-->
@fa[certificate gp-bullet-green]<span style="font-size:0.5em">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:0.9em"><a href='https://gitpitch.com/Laurie0131/EDK_II_Modules_Libs_Drivers_pres/master#/' >EDK II Libraries and Modules and Drivers </a> </span><br>
@fa[certificate gp-bullet-cyan]<span style="font-size:0.5em">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:0.9em"><a href='https://gitpitch.com/Laurie0131/Platform_Config_DB_PCD_pres/master#/' >EDK II Platforms Configuration Database (PCD)  </a> </span><br>
@fa[certificate gp-bullet-yellow]<span style="font-size:0.5em">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:0.9em"><a href='https://gitpitch.com/Laurie0131/Writing_UEFI_App_Lab/master#/' >UEFI Application Writers LAB</a> </span> <br>
@fa[certificate gp-bullet-magenta]<span style="font-size:0.5em">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:0.9em"><a href='https://gitpitch.com/Laurie0131/UEFI_Driver_pres/master#/' >UEFI Driver Model</a> - <a href="https://gitpitch.com/Laurie0131/UEFI_Driver_Wizard_lab/master#/">UEFI Driver Wizard </a> and <a href='https://gitpitch.com/Laurie0131/UEFI_Driver_Porting_lab/master#/' >Porting Lab </a> </span> 

---  
@title[Schedule 03]
<BR>
### <p align="center"<span class="gold"   >Suggested Schedule - Unit 3</span></p><br>

<!---  Add bullets using https://fontawesome.com/cheatsheet certificate
-->
 @fa[certificate gp-bullet-green]&nbsp;&nbsp;<span style="font-size:0.9em"><a href='https://gitpitch.com/Laurie0131/EDK_II_Porting_Projects_pres/master#/' >Porting an Existing Platform w/ EDK II example</a> </span><br>
 @fa[certificate gp-bullet-cyan]&nbsp;&nbsp;<span style="font-size:0.9em"><a href='https://gitpitch.com/Laurie0131/EDK_II_Porting_beyond_Shell_pres/master#/' >Porting Beyond the Shell w/ EDK II </a> </span><br>
 @fa[certificate gp-bullet-yellow]&nbsp;&nbsp;<span style="font-size:0.9em"><a href='https://gitpitch.com/Laurie0131/EDK_II_Debugging_pres/master#/' >EDK II Debugging Presentation and Lab </a> </span> <br>
 @fa[certificate gp-bullet-magenta]&nbsp;&nbsp;<span style="font-size:0.9em"><a href='https://gitpitch.com/Laurie0131/EDK_II_UDK_Debugger_pres/master#/' >Source Level Debugging w/ Intel® UDK Debugger</a> </span> 

---  
@title[Schedule 04]
<BR>
### <p align="center"<span class="gold"   >Suggested Schedule - Unit 4</span></p><br>

<!---  Add bullets using https://fontawesome.com/cheatsheet certificate
-->
 @fa[certificate gp-bullet-green]&nbsp;&nbsp;<span style="font-size:0.9em"><a href='https://gitpitch.com/Laurie0131/UEFI_EDK_II_Network_pres/master#/' >UEFI / EDK II Network </a> - &nbsp;&nbsp;<a href="https://gitpitch.com/Laurie0131/UEFI_EDK_II_Network_pres/master#/13">EDK II Network Features</a>&nbsp;&nbsp;,<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        <a href="https://gitpitch.com/Laurie0131/UEFI_EDK_II_Network_pres/master#/26">UEFI Protocols for EDK II</a>&nbsp;&nbsp; , &nbsp;&nbsp;<a href="https://gitpitch.com/Laurie0131/UEFI_EDK_II_Network_pres/master#/50">HTTP(s) Boot</a> </span><br>
 @fa[certificate gp-bullet-cyan]&nbsp;&nbsp;<span style="font-size:0.9em"><a href='' >UEFI / EDK II Security </a> </span><br>
 @fa[certificate gp-bullet-yellow]&nbsp;&nbsp;<span style="font-size:0.9em"><a href='' >UEFI / EDK II - HII Lab  </a> </span> <br>
 @fa[certificate gp-bullet-magenta]&nbsp;&nbsp;<span style="font-size:0.9em"><a href='' >EDK 1.0  Compatibility Package (ECP)</a> </span> <br>



---?image=assets/images/binary-strings-black2.jpg
@title[UEFI Boot Flow Section]
<br><br><br><br><br>
## <span class="gold"  >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Section Divider example</span>
<span style="font-size:0.9em" > &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This is an example for a section divider</span>


---?image=assets/images/gitpitch-audience.jpg
@title[Questions]
<br>
![Questions](/assets/images/Questions.png =10x) 


---?image=assets/images/gitpitch-audience.jpg
@title[Logo Slide]
<br><br><br>
![Logo Slide](/assets/images/TianocoreLogo.png =10x)



---
@title[Acknowledgements]
#### <p align="center"><span class="gold"   >Acknowledgements</span></p>

```c++
/**
Redistribution and use in source (original document form) and 'compiled' forms (converted
to PDF, epub, HTML and other formats) with or without modification, are permitted provided
that the following conditions are met:

Redistributions of source code (original document form) must retain the above copyright 
notice, this list of conditions and the following disclaimer as the first lines of this 
file unmodified.

Redistributions in compiled form (transformed to other DTDs, converted to PDF, epub, HTML
and other formats) must reproduce the above copyright notice, this list of conditions and 
the following disclaimer in the documentation and/or other materials provided with the 
distribution.

THIS DOCUMENTATION IS PROVIDED BY TIANOCORE PROJECT "AS IS" AND ANY EXPRESS OR IMPLIED 
WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND 
FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL TIANOCORE PROJECT BE 
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES 
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, 
DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, 
WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) 
ARISING IN ANY WAY OUT OF THE USE OF THIS DOCUMENTATION, EVEN IF ADVISED OF THE POSSIBILITY 
OF SUCH DAMAGE.

Copyright (c) 2018, Intel Corporation. All rights reserved.
**/

```
