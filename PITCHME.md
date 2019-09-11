---?image=assets/images/gitpitch-audience.jpg
@title[Tianocore Open Source Training contents]
<br><br><br><br><br>
## <span class="gold"   >UEFI & EDK II Training</span>

#### Training Table of contents

<br>
<span style="font-size:0.75em" ><a href='http://www.tianocore.org'>tianocore.org</a></span>
Note:
  PITCHME.md for UEFI / EDK II Training  Contents and Overview

  Copyright (c) 2019, Intel Corporation. All rights reserved.<BR>

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
#### <p align="center"<span class="gold"   >Suggested Schedule </span></p>

<span style="font-size:0.8em">The next slides will have links to the appropriate slide show in the suggested order. </span>
- <font color="yellow">Unit 1:</font>  <span style="font-size:0.8em">Overview of EDK II, UEFI Shell Lab, Platform Build Lab</span><br>
- <font color="yellow">Unit 2:</font>  <span style="font-size:0.8em">UEFI Aware OS -UEFI Secure boot, More details of the EDK II infrastructure and Labs with writing UEFI Applications, UEFI Driver Model with writing Lab</span><br>
- <font color="yellow">Unit 3:</font>  <span style="font-size:0.8em">Porting and Debugging using a Open Source example with EDK II</span><br>
- <font color="yellow">Unit 4:</font>  <span style="font-size:0.8em">Advanced topics for a shorter session after Units 1-3 completed: UEFI Network, UEFI Platform FW security, UEFI HII overview and lab</span>

<span style="font-size:0.8em">Presentations with Labs support @fa[linux gp-bullet-gold] Linux and @fa[windows gp-bullet-cyan] Windows</span>
 
 
Note:
Unit 1
  - Overview UEFI / FSP Boot Flow, EDK II Build Environment & Process, EDK II Build Spec Files, Open Source UEFI Platforms, EDK II Platform Build Lab, UEFI Shell & Edk II Build Lab, 
Unit 2
  - UEFI Aware OS -UEFI Secure boot, EDK II Libraries and Modules and Drivers, EDK II Platforms configuration Database (PCD),  UEFI Application Writers Lab, UEFI Driver Wizard Lab - Driver Model

Unit 3
  - Porting w/ EDK II using Open Source example, Porting Beyond the Shell w/ EDK II,  EDK II Debugging Lab, Source Level Debugging w/ UDK Debugger
Unit 4
  - UEFI / EDK II Network,  UEFI / EDK II Security, UEFI Capsule Update, UEFI / EDK II - HII Lab, EDK Compatibility Package


 
---  
@title[Schedule 01]

### <p align="center"<span class="gold"   >Suggested Schedule - Unit 1</span></p><br>

<!---  Add bullets using https://fontawesome.com/cheatsheet certificate
-->
@fa[certificate gp-bullet-green]&nbsp;&nbsp;<span style="font-size:0.8em"><a href='https://gitpitch.com/tianocore-training/UEFI_Boot_Flow_Pres/master#/' >Overview UEFI Boot Flow </a> </span><br>
@fa[certificate gp-bullet-cyan]&nbsp;&nbsp;<span style="font-size:0.8em"><a href='https://gitpitch.com/tianocore-training/EDK_II_Build_Process_Pres/master#/' >EDK II Build Process</a> and <a href='https://gitpitch.com/tianocore-training/EDK_II_Build_Spec_Files_Pres/master#/' >Build Spec Files </a> </span><br>
@fa[certificate gp-bullet-magenta]&nbsp;&nbsp;<span style="font-size:0.8em"><a href='https://gitpitch.com/tianocore-training/OpenSource_Platforms_Pres/master#/' >EDK II Open Source Platforms </a> </span><br>
@fa[certificate gp-bullet-ltgreen]&nbsp;&nbsp;<span style="font-size:0.8em">EDK II Build Labs <a href="https://gitpitch.com/tianocore-training/Platform_Build_Linux_Ovmf_Lab/master#/">@fa[linux gp-bullet-gold] Ovmf</a> @color[yellow](<i>OR</i>) <a href="https://gitpitch.com/tianocore-training/Platform_Build_Win_Emulator_Lab/master#/">@fa[windows gp-bullet-cyan] Emulator</a> </span><br>
@fa[certificate gp-bullet-blue]&nbsp;&nbsp;<span style="font-size:0.8em">Platform Build Labs MinnowBaord MAX <a href="https://gitpitch.com/tianocore-training/Platform_Build_Lab_MAX_Linux/master#/"> @fa[linux gp-bullet-gold]</a> Or <a href="https://gitpitch.com/tianocore-training/Platform_Build_Lab_MAX_Win/master#/"> @fa[windows gp-bullet-cyan]</a> </span><br>
@fa[certificate gp-bullet-cyan]&nbsp;&nbsp;<span style="font-size:0.8em">Platform Build Lab Apollo Lake (UP<sup>2</sup> board) <a href='https://gitpitch.com/tianocore-training/Platform_Build_Lab_UP2_Linux/master#/' >@fa[linux gp-bullet-gold]</a> Or <a href="https://gitpitch.com/tianocore-training/Platform_Build_Lab_UP2_Win/master#/"> @fa[windows gp-bullet-cyan]</a> </span><br>
@fa[certificate gp-bullet-yellow]&nbsp;&nbsp;<span style="font-size:0.8em"><a href='https://gitpitch.com/tianocore-training/UEFI_Shell_App_Pres/master#/' >UEFI Shell Overview</a> & <a href='https://gitpitch.com/tianocore-training/UEFI_Shell_Lab/master#/' >@fa[linux gp-bullet-gold] Shell Lab </a> Or <a href="https://gitpitch.com/tianocore-training/UEFI_Shell_Win_Lab/master#/"> @fa[windows gp-bullet-cyan]Nt32 Shell Lab</a> </span><br>


---  
@title[Schedule 02]
<BR>
### <p align="center"<span class="gold"   >Suggested Schedule - Unit 2</span></p><br>

<!---  Add bullets using https://fontawesome.com/cheatsheet certificate
-->
@fa[certificate gp-bullet-blue]&nbsp;&nbsp;<span style="font-size:0.8em"><a href='https://gitpitch.com/tianocore-training/UEFI_Aware_OS_Pres/master#/' >UEFI Aware OS</a> , 
<a href='https://gitpitch.com/tianocore-training/UEFI_Aware_OS_Pres/master#/14'>Secure Boot</a> , 
<a href='https://gitpitch.com/tianocore-training/UEFI_Aware_OS_Pres/master#/22'>Smm/MMI</a> , 
<a href='https://gitpitch.com/tianocore-training/UEFI_Aware_OS_Pres/master#/29'>coreboot</a> </span><br>
@fa[certificate gp-bullet-green]<span style="font-size:0.5em">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:0.9em"><a href='https://gitpitch.com/tianocore-training/EDK_II_Modules_Libs_Drivers_Pres/master#/' >EDK II Libraries and Modules and Drivers </a> </span><br>
@fa[certificate gp-bullet-cyan]<span style="font-size:0.5em">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:0.9em"><a href='https://gitpitch.com/tianocore-training/Platform_Config_DB_PCD_Pres/master#/' >EDK II Platforms Configuration Database (PCD)  </a> </span><br>
@fa[certificate gp-bullet-yellow]<span style="font-size:0.5em">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:0.9em"><a href='https://gitpitch.com/tianocore-training/Writing_UEFI_App_Lab/master#/' >UEFI Application Writers LAB-@fa[linux gp-bullet-gold] </a> &nbsp;&nbsp;OR&nbsp; <a href="https://gitpitch.com/tianocore-training/Writing_UEFI_App_Win_Lab/master#/">@fa[windows gp-bullet-cyan]</a> </span> <br>
@fa[certificate gp-bullet-magenta]<span style="font-size:0.5em">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:0.9em"><a href='https://gitpitch.com/tianocore-training/UEFI_Driver_Pres/master#/' >UEFI Driver Model</a> - <a href="https://gitpitch.com/tianocore-training/UEFI_Driver_Wizard_lab/master#/">@fa[linux gp-bullet-gold] UEFI Driver Wizard </a> & <a href='https://gitpitch.com/tianocore-training/UEFI_Driver_Porting_lab/master#/' >Porting Lab </a>
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;OR&nbsp;<a href='https://gitpitch.com/tianocore-training/UEFI_Driver_Wizard_Win_Lab/master#/'>@fa[windows gp-bullet-cyan] UEFI Driver Wizard </a>&nbsp;&nbsp;& <a href='https://gitpitch.com/tianocore-training/UEFI_Driver_Porting_Win_Lab/master#/'> Porting Lab </a>   </span> 

---  
@title[Schedule 03]
<BR>
### <p align="center"<span class="gold"   >Suggested Schedule - Unit 3</span></p><br>

<!---  Add bullets using https://fontawesome.com/cheatsheet certificate
-->
 @fa[certificate gp-bullet-green]&nbsp;&nbsp;<span style="font-size:0.9em"><a href='https://gitpitch.com/tianocore-training/EDK_II_OpenBoard_Platform/master#/' >EDK II OpenBoard Platform Design </a> </span><br>
 @fa[certificate gp-bullet-gold]&nbsp;&nbsp;<span style="font-size:0.9em"><a href='https://gitpitch.com/tianocore-training/EDK_II_OpenBoard_Porting/master#/' >EDK II OpenBoard Platform Porting</a> </span><br>
 @fa[certificate gp-bullet-yellow]&nbsp;&nbsp;<span style="font-size:0.9em"><a href='https://gitpitch.com/tianocore-training/EDK_II_Debugging_Pres_Lab/master#/' >EDK II Debugging Presentation and @fa[linux gp-bullet-gold] Lab</a> 
 <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Or <a href='https://gitpitch.com/tianocore-training/EDK_II_Debugging_Pres_Win_Lab/master#/' >Presentation and @fa[windows gp-bullet-cyan] Lab</a></span> <br>
 @fa[certificate gp-bullet-magenta]&nbsp;&nbsp;<span style="font-size:0.9em"><a href='https://gitpitch.com/tianocore-training/EDK_II_UDK_Debugger_Pres/master#/' >Source Level Debugging w/ Intel® UDK Debugger</a> </span> <br>
 @fa[certificate gp-bullet-cyan]&nbsp;&nbsp;<span style="font-size:0.9em">Outdated, <a href='https://gitpitch.com/tianocore-training/EDK_II_Porting_Board_Pres/master#/' >Porting a New Board ( Apollo Lake) </a> </span><br>

---  
@title[Schedule 04]
<BR>
### <p align="center"<span class="gold"   >Suggested Schedule - Unit 4</span></p><br>

<!---  Add bullets using https://fontawesome.com/cheatsheet certificate
-->
 @fa[certificate gp-bullet-green]&nbsp;&nbsp;<span style="font-size:0.9em"><a href='https://gitpitch.com/tianocore-training/UEFI_EDK_II_Network_Pres/master#/' >UEFI / EDK II Network </a> - &nbsp;&nbsp;<a href="https://gitpitch.com/tianocore-training/UEFI_EDK_II_Network_Pres/master#/13">EDK II Network Features</a>&nbsp;&nbsp;,<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        <a href="https://gitpitch.com/tianocore-training/UEFI_EDK_II_Network_Pres/master#/26">UEFI Protocols for EDK II</a>&nbsp; , &nbsp;<a href="https://gitpitch.com/tianocore-training/UEFI_EDK_II_Network_Pres/master#/50">HTTP(s) Boot</a> </span><br>
 @fa[certificate gp-bullet-cyan]&nbsp;&nbsp;<span style="font-size:0.9em"><a href='https://gitpitch.com/tianocore-training/UEFI_Platform_Security_Pres/master#/' >UEFI / EDK II Platform Firmware Security </a> </span><br>
 @fa[certificate gp-bullet-magenta]&nbsp;&nbsp;<span style="font-size:0.9em"><a href='https://gitpitch.com/tianocore-training/Capsule_Update_Pres/master#/' >UEFI Capsule Update </a> </span> <br>
 @fa[certificate gp-bullet-yellow]&nbsp;&nbsp;<span style="font-size:0.9em"><a href='https://gitpitch.com/tianocore-training/UEFI_HII_Overview_Pres_Lab/master#/' >UEFI / EDK II - HII Overview Presenation and Lab  </a> </span> <br>
 
---
@title[Lab Material]
<p align="center"<span class="gold"   ><b>Lab Material</b></span><br>
<span style="font-size:0.75em">The following github repositories contain the Lab Material :  </span></p>
<ul style="list-style-type:disc; line-height:0.67;">
 <li><span style="font-size:0.67em"><a href="https://github.com/tianocore-training/Lab_Material_FW">Lab Material FW</a></span></li>
 <ul style="list-style-type:disc" style="line-height:0.6;">
   <li><span style="font-size:0.6em">Documentation</span></li>
   <li><span style="font-size:0.6em">DriverWizard</span></li>
   <li><span style="font-size:0.6em">edk2-ws </span></li>
   <ul style="list-style-type:disc" style="line-height:0.56;">
     <li> <span style="font-size:0.56em">edk2(- Same as https://github.com/tianocore/edk2 )</span></li>
     <li> <span style="font-size:0.56em">edk2-libc(- Same as https://github.com/tianocore/edk2-libc )</span></li>
   </ul>
   <li> <span style="font-size:0.6em">LabSampleCode</span></li>
 </ul>
 <li><span style="font-size:0.67em"><a href="https://github.com/tianocore-training/PlatformBuildLab2_FW">PlatformBuildLab2_FW</a></span></li>
 <ul style="list-style-type:disc" style="line-height:0.6;">
  <li> <span style="font-size:0.6em">PlatformBuildLab</span></li>
   <ul style="list-style-type:disc" style="line-height:0.56;">
     <li><span style="font-size:0.56em">MaxWS (- source code for the Minnowboard Max ) </span></li>
	</ul> 
  </ul>
 <li><span style="font-size:0.67em"><a href="https://github.com/tianocore-training/PlatformBuildLab_UP2_FW">PlatformBuildLab_UP2_FW</a></span></li>
 <ul style="list-style-type:disc" style="line-height:0.6;">
  <li> <span style="font-size:0.6em">PlatformBuildLab</span></li>
   <ul style="list-style-type:disc" style="line-height:0.56;">
     <li><span style="font-size:0.56em">MV3 (- source code for - Apollo Lake (Broxton - UP<sup>2</sup> board)) </span></li>
	</ul> 
  </ul>
 <li><span style="font-size:0.67em"><a href="https://github.com/tianocore-training/Presentation_FW">Presentation_FW</a></span></li>
   <ul style="list-style-type:disc" style="line-height:0.6;">
     <li><span style="font-size:0.6em">Presentations - PDFs of all slides  </span></li>
   </ul> 
</ul>
 
 
---  
@title[GitPitch]
<p align="center"<span class="gold"   ><b>About GitPitch</b></span></p>
<p style="line-height:70%">The Markdown Presentation Service on Git <span style="font-size:0.7em">see documentation at: https://gitpitch.com/docs/ </span></p>
<span style="font-size:0.9em">GitPitch Key press controls:</span>
<ul style="line-height:0.8;">
 <li><span style="font-size:0.7em">Press<font color="yellow"> **F** </font>for full screen</span></li>
 <li><span style="font-size:0.7em">Press<font color="yellow"> **O** </font>for Overview</span></li>
 <li><span style="font-size:0.7em">Press<font color="yellow"> **B** </font>for Blackout </span></li>
 <li><span style="font-size:0.7em">Press<font color="yellow"> **M** </font>for menu</span></li>
 <li><span style="font-size:0.7em">Press<font color="yellow"> **?** </font>for help</span></li>
 <li><span style="font-size:0.7em">Press<font color="yellow"> **S** </font>for Speaker notes</span></li>
 <li><span style="font-size:0.7em">To get a <font color="yellow"> PDF </font>of the presentation, use the lower left white bars ( "&equiv;" ) and select "Print Version(.pdf)"</span></li>
 <li><span style="font-size:0.7em"><font color="yellow">Navigation</font>  Space - Arrow keys - Page Down ( Arrows at bottom right show Next slide or sub-slides) ( " < &or; > ") see <a href="https://gitpitch.com/docs/foundation-features/keyboard-controls/"> full list</a> </span></li>
</ul> 
 
---  
@title[Schedule 2]
<p align="right"><span class="gold" >@size[1.1em](<b>Github links of Suggested Schedule </b>)</span><br>
<table id="recTable">
	<tr>
		<td bgcolor="#0071c5" height=".0025"><p style="line-height:001%"><span style="font-size:0.5em" ><b>Unit 1</b></span></p></td>
		<td bgcolor="#0071c5" height=".0025"><p style="line-height:001%"><span style="font-size:0.5em" ><b>Unit 2</b></span></p></td>
		<td bgcolor="#0071c5" height=".0025"><p style="line-height:001%"><span style="font-size:0.5em" ><b>Unit 3</b></span></p></td>
		<td bgcolor="#0071c5" height=".0025"><p style="line-height:001%"><span style="font-size:0.5em" ><b>Unit 4</b></span></p></td>
	</tr>
	<tr>
		<td bgcolor="#121212" height=".0025"><p style="line-height:001%"><span style="font-size:0.45em" ><a href="https://github.com/tianocore-training/UEFI_Boot_Flow_Pres">UEFI Overview</a></span></p></td>
		<td bgcolor="#121212" height=".0025"><p style="line-height:001%"><span style="font-size:0.45em" ><a href="https://github.com/tianocore-training/UEFI_Aware_OS_Pres">UEFI Aware OS </a></span></p></td>
		<td bgcolor="#121212" height=".0025"><p style="line-height:001%"><span style="font-size:0.45em" ><a href="https://github.com/tianocore-training/EDK_II_OpenBoard_Platform">OpenBoard Platform</a></span></p></td>
		<td bgcolor="#121212" height=".0025"><p style="line-height:001%"><span style="font-size:0.45em" ><a href="https://github.com/tianocore-training/UEFI_EDK_II_Network_Pres">UEFI Network</a></span></p></td>
	</tr>
	<tr>
		<td bgcolor="#323232" height=".0025"><p style="line-height:001%"><span style="font-size:0.45em" ><a href="https://github.com/tianocore-training/EDK_II_Build_Process_Pres">Build Env </a></span></p></td>
		<td bgcolor="#323232" height=".0025"><p style="line-height:001%"><span style="font-size:0.45em" ><a href="https://github.com/tianocore-training/EDK_II_Modules_Libs_Drivers_Pres">Libs, Modules, Drivers </a></span></p></td>
		<td bgcolor="#323232" height=".0025"><p style="line-height:001%"><span style="font-size:0.45em" ><a href="https://github.com/tianocore-training/EDK_II_OpenBoard_Porting">OpenBoard Porting</a></span></p></td>
		<td bgcolor="#323232" height=".0025"><p style="line-height:001%"><span style="font-size:0.45em" ><a href="https://github.com/tianocore-training/UEFI_Platform_Security_Pres">UEFI FW Security </a></span></p></td>
	</tr>
	<tr>
		<td bgcolor="#121212" height=".0025"><p style="line-height:001%"><span style="font-size:0.45em" ><a href="https://github.com/tianocore-training/EDK_II_Build_Spec_Files_Pres">Build Spec Files</a></span></p></td>
		<td bgcolor="#121212" height=".0025"><p style="line-height:001%"><span style="font-size:0.45em" ><a href="https://github.com/tianocore-training/Platform_Config_DB_PCD_Pres">PCDs</a></span></p></td>
	    <td bgcolor="#121212" height=".0025"><p style="line-height:001%"><span style="font-size:0.45em" >EDK II Debugging <a href="https://github.com/tianocore-training/EDK_II_Debugging_Pres_Lab">@fa[linux gp-bullet-gold]</a>&nbsp; <a href="https://github.com/tianocore-training/EDK_II_Debugging_Pres_Win_Lab">@fa[windows gp-bullet-cyan]</a></span></p></td>
		<td bgcolor="#121212" height=".0025"><p style="line-height:001%"><span style="font-size:0.45em" ><a href="https://github.com/tianocore-training/Capsule_Update_Pres">UEFI Capsules</a></span></p></td>
	</tr>
	<tr>
		<td bgcolor="#323232" height=".0025"><p style="line-height:01%"><span style="font-size:0.45em" ><a href="https://github.com/tianocore-training/OpenSource_Platforms_Pres">Open Source</a></span></p></td>
		<td bgcolor="#323232" height=".0025"><p style="line-height:001%"><span style="font-size:0.45em" >Writing UEFI Apps <a href="https://github.com/tianocore-training/Writing_UEFI_App_Lab">@fa[linux gp-bullet-gold]</a>&nbsp; <a href="https://github.com/tianocore-training/Writing_UEFI_App_Win_Lab">@fa[windows gp-bullet-cyan]</a></span></p></td>
		<td bgcolor="#323232" height=".0025"><p style="line-height:001%"><span style="font-size:0.45em" ><a href="https://github.com/tianocore-training/EDK_II_UDK_Debugger_Pres">UDK Debugger Tool </a></span></p></td>
		<td bgcolor="#323232" height=".0025"><p style="line-height:001%"><span style="font-size:0.45em" ><a href="https://github.com/tianocore-training/UEFI_HII_Overview_Pres_Lab">UEFI HII</a></span></p></td>
	</tr>
	<tr>
		<td bgcolor="#121212" height=".0025"><p style="line-height:001%"><span style="font-size:0.45em" >EDK II Build Lab <a href="https://github.com/tianocore-training/Platform_Build_Linux_Ovmf_Lab">@fa[linux gp-bullet-gold]</a> &nbsp; <a href="https://github.com/tianocore-training/Platform_Build_Win_Emulator_Lab">@fa[windows gp-bullet-cyan]</a></span></p></td>
		<td bgcolor="#121212" height=".0025"><p style="line-height:001%"><span style="font-size:0.45em" ><a href="https://github.com/tianocore-training/UEFI_Driver_Pres">UEFI Drivers</a></span></p></td>
		<td bgcolor="#121212" height=".0025"><p style="line-height:001%"><span style="font-size:0.45em" ><a href="https://github.com/tianocore-training/EDK_II_Porting_Board_Pres">Outdated: Porting Board </a></span></p></td>
	    <td bgcolor="#121212" height=".0025"><p style="line-height:001%"><span style="font-size:0.45em" >&nbsp; </span></p></td>
	</tr>
	<tr>
		<td bgcolor="#323232" height=".0025"><p style="line-height:001%"><span style="font-size:0.45em" ><a href="https://github.com/tianocore-training/UEFI_Shell_App_Pres">UEFI Shell App </a></span></p></td>
		<td bgcolor="#323232" height=".0025"><p style="line-height:001%"><span style="font-size:0.45em" >Driver Wizard Lab <a href="https://github.com/tianocore-training/UEFI_Driver_Wizard_Lab">@fa[linux gp-bullet-gold]</a>&nbsp; <a href="https://github.com/tianocore-training/UEFI_Driver_Wizard_Win_Lab">@fa[windows gp-bullet-cyan]</a></span></p></td>
		<td bgcolor="#323232" height=".0025"><p style="line-height:001%"><span style="font-size:0.45em" >Platform Build Lab MAX <a href="https://github.com/tianocore-training/Platform_Build_Lab_MAX_Linux">@fa[linux gp-bullet-gold]</a>  <a href"https://github.com/tianocore-training/Platform_Build_Lab_MAX_Win"> @fa[windows gp-bullet-cyan]</a></span></p></td>
		<td bgcolor="#323232" height=".0025"><p style="line-height:001%"><span style="font-size:0.45em" >&nbsp; </span></p></td>
	</tr>
	<tr>
		<td bgcolor="#121212" height=".0025"><p style="line-height:001%"><span style="font-size:0.45em" >Shell Lab<a href="https://github.com/tianocore-training/UEFI_Shell_Lab">@fa[linux gp-bullet-gold]</a>&nbsp; <a href="https://github.com/tianocore-training/UEFI_Shell_Win_Lab">@fa[windows gp-bullet-cyan]</a></span></p></td>
		<td bgcolor="#121212" height=".0025"><p style="line-height:001%"><span style="font-size:0.45em" >UEFI Driver Lab<a href="https://github.com/tianocore-training/UEFI_Driver_Porting_Lab">@fa[linux gp-bullet-gold]</a>&nbsp; <a href="https://github.com/tianocore-training/UEFI_Driver_Porting_Win_Lab">@fa[windows gp-bullet-cyan]</a></span></p></td>
		<td bgcolor="#121212" height=".0025"><p style="line-height:001%"><span style="font-size:0.45em" >Platform Build Lab UP<sup>2</sup> <a href="https://github.com/tianocore-training/Platform_Build_Lab_UP2_Linux">@fa[linux gp-bullet-gold]</a>  <a href"https://github.com/tianocore-training/Platform_Build_Lab_UP2_WIN"> @fa[windows gp-bullet-cyan]</a></span></p></td>
		<td bgcolor="#121212" height=".0025"><p style="line-height:001%"><span style="font-size:0.45em" >&nbsp; </span></p></td>
	</tr>
</table>


Note:

#### Archived Presentations: 
The OpenBoard Platform and OpenBoard Porting have replaced these
- https://github.com/tianocore-training/EDK_II_Porting_Projects_Pres Porting Project
- https://github.com/tianocore-training/EDK_II_Porting_Beyond_Shell_Pres  Porting Beyond Shell
- https://github.com/tianocore-training/Platform_Build_Lab  Platform Build Lab - OVMF - MAX 1.00 Linux
- https://github.com/tianocore-training/Platform_Build_Win_Lab Platform Build Lab - NT32 - MAX 1.00 Windows

  
---?image=assets/images/gitpitch-audience.jpg
@title[Questions]
<br>
![Questions](/assets/images/questions.JPG =10x) 

---
@title[return to main]
<p align="center"><span class="gold"   >@size[1.2em](<b>Return to Main Training Page</b>)</span></p>
<br>
<br>
<br>
<br>
<br>
<p align="center"><span style="font-size:0.9em">Return to Training Table of contents for next presentation <a href="https://github.com/tianocore-training/Tianocore_Training_Contents/wiki#schedule--outline">link</a></span></p>

@snap[north span-30 ]
<br>
<br>
<br>
<a href="https://github.com/tianocore-training/Tianocore_Training_Contents/wiki#schedule--outline">
![trainingLogo](/assets/images/returnTrainingLogo.png)</a>
@snapend

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

Copyright (c) 2019, Intel Corporation. All rights reserved.
**/

```

