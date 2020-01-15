**SmaC Tool**
================
Technological framework to facilitate the development of smart contracts.

**SmaC DSL**

Definition of a textual language (terminals, rules, patterns) using Xtext for the construction of Solidity smart contract's.
_______________
**Install INNoVaServ for use SmaC tool**

The fastest and most recommended way to use the SmaC tool is to use the INNoVaSerV IDE which already incorporates the SmaC plugins to implement smart contracts in Solidity.

You just need to download the tool, unzip the file and click on the executable. The tool already incorporates 3 contracts obtained from the official Solidity documentation

Download INNoVaServ: [Link download](http://www.kybele.es/innovaserv/downloads/INNoVaServSmaCToolkit.rar)

**If you want a more recent version of the eclipse IDE, you can download this version of Obeo Designer with the plugins already installed and with smart contracts built into it.**

Download ObeoDesigner: [Link download](http://www.kybele.es/innovaserv/downloads/ObeoDesignerSmaCTool.rar)
_______________
**Install SmaC from Update Site**

**It is necessary to have the Xtext and Sirius plugins installed previously so that the installation does not generate conflicts.**

* If you have an Eclipse running :

  1.Download the SmaC Update Site: [Link download](https://github.com/KybeleGroup/SmaC/blob/master/SmacUpdateSite.rar)

  2.Unzip the SmaCUpdateSite file.
  
  3.Choose Help -> Install New Software... from the menu bar and click Add...

  4.Choose the SmaC Update Site File and choose a name. Then, you click Add...

  5.Choose the SmaC archive and click Next.

  6.Check the plugins that Eclipse will proceed to install.

  7.Accept the license's terms.

  8.Skip the warning message about download source trust.

  9.After a quick download and a restart of Eclipse
_______________

**SmaC Guide**

* If you have an Eclipse running:

  1.Choose New -> Project -> Choose a name for your project -> Click Finish

  2.Choose New -> Other -> Search by: "SmaC Model" in the search box -> Choose option "SmaC model"

  3.Choose Smac Model's name -> Choose "File" element as the root of the model -> Ok

  4.Write a Solidity Smart contract.
  
Download a SmaC Guide PDF: [Link download](https://github.com/KybeleGroup/SmaC/blob/master/GuideSmaC.pdf)

There are two video guides that show the construction of a smart contract model from the developed DSL [Link download](http://www.kybele.es/innovaserv/downloads/VideoSmartContract.mp4) and the generation of EMF models from the smart contracts models generated with the tool (In this repository).
_______________________
**Tips**

* Language Patterns:

  1.Define compiler's version **(Obligatory).**

  2.Define libraries.
  
  3.Define import(s).
  
  4.Define interface(s).

  5.Define global variable(s).

  6.Define contracts **(At least 1).**

  7.Define local variable(s).

  8.Define contract's constructor(s).

  9.Define contract's modifier(s).

  10.Define contract's event(s).

  11.Define contract's function(s).

* When defining a contract using the tool, it proposes code autocomplete suggestions using the CTRL + SPACE key combination

* Language demands a gas restriction within the loops.
