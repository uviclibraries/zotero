---
layout: default
title: 1-Word & Browser Connector
nav_order: 2
parent: Workshop Activities
customjs: http://code.jquery.com/jquery-1.4.2.min.js
---

# Adding Browser and Word Connectors

<img src="images/act-1/1-icon.png" alt="icons" style="float:right;width:240px;">

In this exercise you will:
- Add the browser connector so you can automatically download source information from websites
- Install the Word plugin so you can add citations to your papers

If you have any questions or get stuck as you work through this, please ask your instructor for assistance. Have fun!

1.  Navigate to the Zotero downloads page: [https://www.zotero.org/download/](https://www.zotero.org/download/){:target="_blank"}
2.  If you are using **Chrome**, you will be directed to the Chrome Web Store. Add the plugin here.
    
    <img src="images/act-1/2-plugin.png" alt="zotero in app store" style="width:720px;">
    
    <img src="images/act-1/2-firefox.png" alt="firefox option" style="float:right;width:360px;margin-bottom:10px;">
    
    If you are using **Firefox** you will be asked to confirm installation. Please do so.
    
    **Safari** is supported through BETA builds, so we will not be learning about this today (but it should be available soon!)

<button onclick="toggle('gif1')">Show / Hide Animation </button>
<div id="gif1">
      <img src="images/act-1/3-plugin.gif" alt="add plugin" style="width:720px;">
      </div>
      
**Congratulations**, you have now installed the browser plugin! You should now see something that looks like this in your browser toolbar:
    
<img src="images/act-1/3-example.png" alt="toolbar" style="width:720px;">
    
    If you are using **Google Docs**, the browser connector will also add Zotero functionality to your documents.

## Adding the Word Plugin

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
