---
description: >-
  The Editor Page is where you add, edit, and update Widgets that display as
  graphics.
---

# Editor Page

## **Scene Panel**

The Scene Panel within the Editor Page is similar to the Scene Panel in Preview Page with two additional functions: Adding a Scene, and Collapsing the Scene Panel.&#x20;

### Adding a Scene  <a href="#addingscene" id="addingscene"></a>

To add a scene click the **+ Add** button in the scene panel.&#x20;

Then give the scene a name and click **Add**.&#x20;

A new empty Scene will then appear in your Scenes Panel.&#x20;

### Collapse Scene Panel

You can click the **<< button** to collapse the Scene Panel into the Widgets Panel providing more canvas space.

![Scene Panel Expanded (Left) | Scene Panel Collapsed (Right)](https://ucarecdn.com/9518978e-f019-41ec-a026-fd1322f7398e/)

### Additional Scene Panel Information

To learn more about Scene Panel functions please view the Preview Page.&#x20;

{% content-ref url="../preview-page.md" %}
[preview-page.md](../preview-page.md)
{% endcontent-ref %}

## **Scene Inspector**

The scene inspector is located in right side panel of the editor here you can resize the **Layout** of your scene's canvas, or copy your Scene Output URL. &#x20;

If a widget is selected this panel will become a **Widget Inspector**.&#x20;

***

### Layout

Layout controls the size of the canvas.&#x20;

To update the layout change the values in the **Width** and **Height** fields.

***

### Scene Output URL

The scene output URL is the outputs the selected scene to a webpage that can be added to an encoder as a browser input.

For more information about the Scene and Broadcast Output URLS please view the [**Output URLs section**](https://hovercast.crunch.help/hovercat-pro/preview-page#OutputURLs) of the Preview Page article.  &#x20;

***

## **Widget Panel**

The Widget Panel is located in the second column from the left (or if the Scene Panel is Collapsed the leftmost panel).

For a full list of Hovercast Pro Widgets please visit **this article**.&#x20;

![](https://ucarecdn.com/1ec31c56-4359-40dd-a9ed-b5922e9a470e/)

***

### Adding a Widget

To add a Widget click the **+ Add** button to open up the add Widget menu.

Select the widget you would like to add to the canvas.&#x20;

A new Widget will then be added to the Widgets Panel and Canvas (by default in the transparent state), the Widget inspector will also populate in the right side panel.&#x20;

***

### Widget Visibility

Widgets have two visibility states, Shown and Hidden. You can toggle visibility using the eye icon.&#x20;

To change the default visibility of a new widget choose **Shown** or **Hide** in the Add Widget menu.&#x20;

![](https://ucarecdn.com/4646f39d-da96-4099-bbd3-c85fc7dad26b/)

**Shown Widgets** are both visible in the editor and the output.&#x20;

**Hidden Widgets** are NOT visible in the output, but are semi-transparent when selected in the editor's Widget Panel.

This semi-transparency allows for you to edit a Widget's position, content, or design without showing the changes to your audience.&#x20;

## **Widget Inspector**

The Widget Inspector populates the right panel when you select a Widget. Here you can customize the contents and design of a widget to fit your broadcast.

![](https://ucarecdn.com/b26515a1-54b8-4dce-b673-7f12a08f4310/)

## **Widget Position and Bounding Box**

is controlled by the positional properties (x, y, w, h) in the widget panel and is displayed in the canvas as a thin teal line with  square nodes.

![](https://ucarecdn.com/c979ad4d-73fa-474c-a53d-b722a0ababdf/)

You can click and drag the Widget or update the x and y properties to change the Widgets position.&#x20;

You can click and drag the nodes or update the width (w) and height (h) properties to change the dimensions of the bounding box.&#x20;

## **Content Tab**

Allows you to add and update the content that is being displayed within the Widget. For example:

* In a Title Widget you can update the text that is being shown.&#x20;
* In a Poll Widget you can choose which poll you want to run next.
* In a User Comment Widget you can select which chat you want to feature. &#x20;

When content is added to a widget the wrapper will expand towards the empty space within the bounding box first horizontally, then vertically to contain the text.&#x20;

![](https://ucarecdn.com/20b8a9c2-7ec0-44db-84d2-ebe773991073/)

## **Design Tab**&#x20;

The design tab is where you stylize the components of a widget. The default design is inherited from the broadcast's theme.&#x20;

If you would like to update the design of all Widgets at once check out our Theme article.&#x20;

{% content-ref url="../../organizations/managing-and-creating-themes.md" %}
[managing-and-creating-themes.md](../../organizations/managing-and-creating-themes.md)
{% endcontent-ref %}

### **Wrapper**

The Wrapper is located within the Bounding Box and had its size and location defined by the amount of content being displayed along with the wrapper position properties.&#x20;

* **Fill:** The background color of the wrapper.&#x20;
* **Background Media:** Image or video content that is arranged on top of the fill. &#x20;
* **Border Color:** The color of the boarder.&#x20;
* **Wrapper Position:** Where within the bounding box the wrapper is located. As more content is added the wrapper will expand towards the empty area first horizontally, then vertically.&#x20;
* **Padding:** Sets the spacing between the side of the wrapper and the component within it.&#x20;

![](https://ucarecdn.com/1fc72716-5128-4edd-8b5e-db2ad12320e5/)

### **Text (Primary / Secondary / Tertiary / Ect)**&#x20;

Widgets may have multiple text components like primary and secondary or username and comment that can each be independently stylized.&#x20;

* **Font:** The font being displayed.&#x20;
* **Weight:** The boldness of the font.
* **Size:** The height of the font.&#x20;
* **Tracking:** Controls the spacing between characters.&#x20;
* **Line Height:** Sets the vertical spacing between multiple lines of text.&#x20;
* **Alignment:** Specifies the horizontal alignment of text within its component.&#x20;
* **Upper:** Updates all text to be uppercase.
* **Italic:** Updates all text to be italicized.&#x20;
* **Text Position:** If multiple text components exist within a widget allows you to set the position in respect to the other text components.&#x20;
* **Text Padding:** Sets the spacing between the edges of the text and the components around them.&#x20;

User Comment - Username Position and Format

Poll - Results, Timer, Bar Colors

Poll Results

Line Meter - Bar

Notification - Notifications, Comment

List - List Options

Leaderboard - Ranking, Score

Emoji - Size

### **Custom CSS**

Allows you to add any CSS field to change components of a widget like adding a shadow, a custom gradient, or adding or removing a component. For more about custom CSS please visit the Custom CSS Tricks Article.

{% content-ref url="../../misc/custom-css-tricks.md" %}
[custom-css-tricks.md](../../misc/custom-css-tricks.md)
{% endcontent-ref %}

## Animation Tab

The animation tab of a widget controls how a widget transitions on when:&#x20;

* A widget is hidden or shown
* The scene a widget is located within is activate or deactivated.
* The content within a User Comment, Sticker, or Poll widget is changed.

### **Transition Preview**&#x20;

The transition preview shows how a widget looks with the current animation settings. If you **select multiple widgets** you can also view how they animate together.

### **Transition In / Out**

Gives you the option to select different animations for when a widget is shown or hidden, along with the duration and delay.&#x20;

**Pro Tip:** Stack different widgets with delays to create professional looking animations. &#x20;

**Transition Animate On Scene Change**

Toggle that enables or disables a animation when a scene is activated or deactivated.

### **Transition Animate On Content Change**

Toggle that enables or disables a animation when a content within a User Comment, Sticker, or Poll widget is changed.

**Pause Between** controls how long in seconds between the transition out and in for a content change animation.

***

## **Widget Templates**

Widget Templates are saves of widgets that store position, content, and design settings. With them you can:

* Create a duplicate of a widget that has been edited.  &#x20;
* Apply position, content, or design data onto an existing widget.&#x20;

Widget templates are located in the bottom portion of the Widgets Panel.

![](https://ucarecdn.com/ad2eb4b8-1b17-4331-a304-cb8afc9d2f3f/)

### Creating a Template

To create a template select a widget or group of widgets in the widgets panel or canvas then click the **+ Save** button in the widgets panel.&#x20;

### Adding a Template as a New Widget

To add a new widget using a template you can click the templates name.&#x20;

This method will not work if you are currently selected a widget that is the same type as the template. See **Applying a Template Over an Existing Widget**.

Alternatively you can click on the down facing caret of the template you want to add and click **Add as new widget**.

### Applying a Template Over an Existing Widget

To use a template to paste properties like design, content, or position from one widget to another first select the widget you want to paste onto, then you can either:&#x20;

* Use the template menu to apply one or more properties

![](https://ucarecdn.com/5c3b678a-a184-4b99-8a85-c82563e0e459/)

* Use the Apply Shortcuts at the top of the Template Panel and click the name of the widget you would like to paste from.

![In this example both Position and Design would be applied, but not Content. ](https://ucarecdn.com/31b79d0d-74f8-447c-8f63-39ac55d622d7/)

### Renaming a Template

To rename a template open the downward caret menu of the template click **Rename template.**

### Overwriting a Template

To overwrite a template with another widget that is on the canvas first select the widget on the canvas, then within downward caret menu of the template click **Overwrite with selected widget.**

### Deleting a Template

To delete a template open the downward caret menu of the template click **Delete template.**

## **Canvas**

The canvas is the graphical portion of the selected scene. The canvas mirrors the output so what you see there is what the viewers are seeing.&#x20;

### **Selecting Widgets**

All of these commands also function in the widget panel.&#x20;

To select a widget on the canvas click it.&#x20;

To select multiple widgets on a canvas, click the first one, the hold shift and click additional widgets.

To deselect all widgets click on a blank space of the canvas.&#x20;

To deselect an individual widget hold shift and click on it.&#x20;

### **Positioning**

You can also update these properties in the Widget Inspector (x, y, w, h). &#x20;

To change the location (x, y) of a widget first select, then click and drag.

To change the width or height of a widget first select it, then click and drag on a node.&#x20;

### **Draft Mode**

Draft mode allows you to edit a widget's position, content, or design without it being pushed to the output until you click **Save.**&#x20;

This is useful for editing text or the location of a widget without your viewer seeing the incremental changes.

### **Group Selection**

Select or deselect more than one widget by holding shift and clicking on a widget on the canvas or widget panel.&#x20;

* **Alignment:** Located within the design tab. Allows you to align the selected widgets within the group.
* **Grouping:** Located within the design tab. Allows you to easily toggle all widgets within the group on and off simultaneously, perfect for animations.&#x20;
* **Transition Preview:** Located within the Animation tab. Allows you to view the animations of all widgets selected in the group.
