<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Troubleshooting tools for Group Policy Objects in Active Directory</h1>

This post highlights some of the the main tools that can be used to troubleshoot Active Directory Group Policy Objects (GPOs).<br/>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop
- Active Directory Domain Services

<h2>1 - Resultant Set of Policy (rsop)</h2>
  
Resultant Set of Policy (rsop) is a tool that can be run that will show all of the GPOs that are being applied. 
  
  
  1. Click on the Start button
 
  <p>
<img src="https://imgur.com/EeWQTis.png" width="40%" alt="Disk Sanitization Steps"/>
</p>

  
  2. Type rsop.msc
  
  <p>
<img src="https://imgur.com/EeWQTis.png" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>  
  
  
  3. Enter
 
  <p>
<img src="https://imgur.com/rRF1Q3n.png" width="40%" alt="Disk Sanitization Steps"/>
</p>


<h2>2 - gpresult /r</h2>

gpresult /r is a command-line tool that will provide you with a convenient report that will list a lot of information reference you GPOs, including a list of applied GPOs.
</br>

    1. Type CMD in the search bar
   
       <p>
<img src="https://imgur.com/yRH45CG.png" width="40%" alt="Disk Sanitization Steps"/>
</p>    
    
    
    2. At the command-line, type gpresult /r and press Enter

    <p>
<img src="https://imgur.com/yRH45CG.png" width="40%" alt="Disk Sanitization Steps"/>
</p>

  
 
  
FINISHED

