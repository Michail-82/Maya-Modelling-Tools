# :octicons-tools-16: **<span style="color:rgb(221, 80, 191);">Installing Baking Manager</span>**  

![Baking Manager](images/Baking_Manager_window.jpg){ .img-small} 
### **<span style="color:rgb(221, 80, 191);">Step 1 - Setting up</span>** 
<div class="grid cards" markdown>

-   :octicons-copy-16:{ .lg .middle } __[`Setting up`](#)__

    ---

    1.Unzip the [`Baking_Manager.zip`](#) file.
    
    2.Copy paste the [`Baking_Manager Folder`](#) in your [`\Documents\Maya\Scripts`](#) folder.
    
    3.Open [`Maya`](#). 

    <!-- [:octicons-arrow-right-24: Getting started](#) -->
    


</div>



### **<span style="color:rgb(221, 80, 191);">Step 2- Activating</span>** 

<div class="grid cards" markdown>

-   :octicons-copy-16:{ .lg .middle } __[`Python Code`](#)__

    ---

    Copy the 2 ^^**python**^^  lines below on a ^^**shelf**^^  or bind these to a ^^**hotkey**^^  to load the tool.

    ``` py linenums="1"
    from Baking_Manager_Pro.Scripts import Baking_Manager
    Baking_Manager.OpenImportDialog.show_dialog()
    ```


</div>


Click the button below to learn how to create hotkeys and shelf buttons.

[Creating Hotkeys/Shelf Buttons](../Create%20Hotkeys%20Shelf%20Buttons/index.md){ .md-button .md-button--primary }