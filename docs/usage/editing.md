# Editing
After having connected to the server you can start editing your inventory. To get there we will start by opening the admin-panel.

## Opening the admin-panel
Inside the search page, click the three dots in the top right corner to open the dropdown.

![Dots menu](../assets/images/usage/editing/dots_menu_web.png)

From the dropdown, select "Edit".

![Edit button](../assets/images/usage/editing/edit_button_web.png)

Enter you admin credentials and click "Login". If you have not set up an admin user yet, one should have been created automaticly, see the [Server setup](../getting_started/server_setup.md) guide.

![Login form](../assets/images/usage/editing/login_form_web.png)

## The admin-panel
The admin-panel is where you can edit all aspects of your server. For now we will focus editing your inventory.
![Admin-panel](../assets/images/usage/editing/admin_panel_web.png)

Click the "Browse" button to open an file explorer-like view of your inventory.
![Browse button](../assets/images/usage/editing/browse_button_web.png)

## The browse view
Skapersøk is a hirarchical inventory system, meaning that your inventory is structured in a tree-like structure.

The browse view allows you to navigate through this structure and edit your inventory.

![Browse view](../assets/images/usage/editing/browse_view_web.png)

Lets get a little more familiar with the browse view.

Centered on the top is a section with information about our current location in the inventory. The location is represented as a path, similar to how file paths are represented on your computer.

![Browse view location info](../assets/images/usage/editing/browse_view_location_info.png)

Here is an example of the browse view when we have navigated deeper into the inventory. The path section now shows us that we are currently inside a crate called "Micro kontrollere & misc", which is inside another crate called "Arbeidsbenk".

![Deeply navigated browse view](../assets/images/usage/editing/deeply_navigated_browse_view.png)

The other important part of the browse view is the list of items. This is where you can see all the items that are in your current location in the inventory. Meaning all items in your currently selected crate.

![Browse view items list](../assets/images/usage/editing/browse_view_items_list.png)

For example, in the above image we can see that there are four crates at the top of our tree (the root): "Arbeidsbenk", "Skap", "Komponenter" and "Skråvegg".

## Creating a new crate
Anyways, lets get back to editing. To create a new crate, click the "New crate" button in the bottom right corner.

![New crate button](../assets/images/usage/editing/browse_view_new_crate_btn.png)

NOT FINISHED


## Editing an existing crate
To edit an existing crate, click the three dots on the right side of the crate you want to edit. This will open a dropdown with options for that crate.

![Crate options dropdown](../assets/images/usage/editing/browse_view_crate_dropdown.png)

Select "Edit" from the dropdown to open the edit form for that crate. On mobile this will open a bottom sheet with the edit form, while on desktop it will open a modal window with the edit form.

![Crate edit button](../assets/images/usage/editing/browse_view_crate_edit_btn.png)

Now you can edit the name, placementcode, description and lots of other properties of the crate. When you are done, click "Save" to save your changes.

![Browse view crate edit form](../assets/images/usage/editing/browse_view_edit_form.png)