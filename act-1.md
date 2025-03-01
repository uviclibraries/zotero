---
layout: default
title: 1-Install Zotero & Browser Connector
nav_order: 2
parent: Workshop Activities
customjs: http://code.jquery.com/jquery-1.4.2.min.js
---

# Install Zotero, Browser & Word Connectors
<img src="images/act-1/1-icon.png" alt="icons" style="float:right;width:240px;">
In this exercise, you will download & install the Zotero app from Zotero.org, the Zotero Browser Connector, and the Microsoft Word/LibreOffice Add-in.

Before you begin please **Remember**:
- **Zotero** is a program that resides on your computer that may or may not sync to the web depending on your preferences
- In order to capture sources from the web with the click of a button, you must install a **browser connector**
- In order to easily insert citations and create bibliographies, double-check the the **Word or Google Docs Add-in** has been installed

If you have any questions or get stuck as you work through this, please ask your instructor for assistance. Have fun!

## Install Zotero App
1. Downloading Zotero:
   - Navigate to the Zotero downloads page: [https://www.zotero.org/download/](https://www.zotero.org/download/){:target="_blank"}
   - Click **Download** under “Zotero for Mac/Windows”
   <img src="images/act-1/zotero-download.png" alt="Zotero Download web page & button" style="width:8000px;">
   - Save the file to your disk
   - Double-click on the Zotero  file you just downloaded and follow the installation instructions
   - Congratulations! You’ve downloaded and installed Zotero on  your computer!
  
## Install Zotero Browser Connector
1.  When you open Zotero for the first time, you will be welcomed by the start screen. It may even prompt you to install the “Browser Connector” automatically. If so, follow the prompts to install the connector. If not, follow these directions:
2.  Navigate to the Zotero downloads page and find the Connector box [https://www.zotero.org/download/](https://www.zotero.org/download/){:target="_blank"}
3.  Click on the Install Firefox/Chrome/Safari Connector button.
<img src="images/act-1/zotero-connector.png" alt="zotero connector button" style="width:800px;">
   - If you are using Firefox, you will be prompted to install the Connector through the URL pane. Click **Continue to Installation**
    <img src="images/act-1/2-firefox.png" alt="firefox option" style="float:right;width:360px;margin-bottom:10px;">
   - **Safari** is supported through BETA builds, so we will not be learning about this today (but it should be available soon!)
   - When you are finished, you should see a new Browser Connector icon in your browser’s icon bar (unless you’re in Chrome)
<button onclick="toggle('gif1')">Show / Hide Animation </button>
<div id="gif1">
      <img src="images/act-1/3-plugin.gif" alt="add plugin" style="width:720px;">
      </div>
**Congratulations**, you have now installed the browser plugin! You should now see something that looks like this in your browser toolbar:
<img src="images/act-1/3-example.png" alt="toolbar" style="width:800px;">
If you are using **Google Docs**, the browser connector will also add Zotero functionality to your documents.

## Double-check the Word Process Add-in has been Installed
1.  In Zotero, go to the **Preferences** Menu (on a Mac: **Zotero -> Preferences**; on a PC: **Edit -> Preferences**).
 
    <img src="images/act-1/3-final.png" alt="preference menu" style="width:720px;">

2.  Click on the tab that says “**Cite**”.
3.  Then, click the tab that says "**Word Processors**"
4.  Click the button the says “**Install Microsoft Word Add-in**” (or "Install Microsoft Word Plugin")
    <img src="images/act-1/4-add-plugin.png" alt="install add-in" style="width:720px;">
    <button onclick="toggle('gif2')">Show / Hide Animation </button>
<div id="gif2">
      <img src="images/act-1/4-add-plugin.gif" alt="add plugin" style="width:720px;">
      </div>
5.  **Restart WORD & Zotero**
    **Congratulations!** You should now have a Zotero tab in Microsoft Word that looks like this:    
    <img src="images/act-1/4-example.png" alt="final Zotero tab" style="width:720px;">
 <script>  

    function toggle(input) {
        var x = document.getElementById(input);
        if (x.style.display === "none") {
            x.style.display = "block";
        } else {
            x.style.display = "none";
        }
    }
</script>

[NEXT STEP: Adding Your First Citations & Collections to Zotero](act-2.html){: .btn .btn-blue }
