<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Troubleshooting tools for Group Policy Objects in Active Directory</h1>

This post highlights some of the main tools that can be used to troubleshoot Active Directory Group Policy Objects (GPOs).<br/>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop
- Active Directory Domain Services

<h2>1 - Resultant Set of Policy (rsop)</h2>
  
The Result Set of Policy (RSOP) is a feature in Windows that allows administrators to simulate the resultant policy settings that apply to a user or computer. It helps in troubleshooting and understanding how Group Policy settings are being applied in a given environment.</br>
  
  1. Click on the Start button and type rsop.msc. Then press Enter
 
  <p>
<img src="https://imgur.com/R07cx0R.png" width="40%" alt="Disk Sanitization Steps"/>
</p>

  
  2. Rsop will run
  
  <p>
<img src="https://imgur.com/gOZkTFp.png" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>  
  
  
  3. A new window similiar to Group Policy Management will appear. Here you can search through the options and find how your GPOs are being applied.
 
  <p>
<img src="https://imgur.com/nDP2Drj.png" width="40%" alt="Disk Sanitization Steps"/>
</p>


<h2>2 - gpresult /r</h2>

The gpresult /r command in Windows displays the Resultant Set of Policy (RSOP) for the current user, summarizing which Group Policy settings are applied and from where they are sourced within the system environment. This helps administrators quickly ascertain the effective policy configuration on a specific computer or user account.</br>

1. Type CMD in the search bar to open the command-line
   


<p>
<img src="https://imgur.com/d4QJCTs.png" width="40%" alt="Disk Sanitization Steps"/>
</p>    
    
    
2. At the command-line, type gpresult /r and press Enter

<p>
<img src="https://imgur.com/yExcGE5.png" width="40%" alt="Disk Sanitization Steps"/>
</p>

3. A report detailing how your GPOs are being applied will appear. Use this to troubleshoot. 

<p>
<img src="https://imgur.com/6UjO15N.png" width="40%" alt="Disk Sanitization Steps"/>
</p> 
  
END

