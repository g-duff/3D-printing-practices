# **Formlabs Preform 3**
Instructions for printing, cleaning and baking 3D printed models using Formlabs' Preform 3 3D printer, found [here](https://www.goprint3d.co.uk/form-3.html?keyword=%2Bformlabs%20%2B3&gclid=CjwKCAiAyeTxBRBvEiwAuM8dnZw1MOTg00WQdfe4pjk0TH3vMxEbvg29Lxvv94uacQDpjO-iOZt6MhoCjnYQAvD_BwE).

## **Part Design**
* Use any CAD software, such as Autodesk Inventor
* Ensure measurements are set to mm (default is inches)
* Once finished:
  * Export as CAD format
  * Ensure part is exported with ".STL" file extension
  * Ensure export measurements are set to mm (default is inches)

## **Printing**
* Formlabs' Preform printers come with Preform software
* Import STL file into Preform:
  * File
  * Open
  * Select part
  * Multiple parts may be added to the same print
* Ensure parts are equally spread across the print bed
  * Note that the "base" on Preform will be upside down during printing
* Use the orientation and support tools to ensure all aspects of the part is supported
  * Orientation tool is indicated by the square with a circular arrow
  * Support struts is underneath orientation in the side menu
  * Note that parts may be printed directly onto the print bed
    * It is advisable to add a chamfer during design to allow for removal of the part from print bed
    * This is one method to ensure a perfectly flat surface on the part
  * Support struts will increase print time
  * Support struts can be manually adjusted to remove minima spots (indicated with a red highlight on the part)
* Before submitting the print, ensure that the resolution and resin settings are as desired/required
* Resolution is determined by the smallest designed feature in the part
  * Note that a higher resolution will increase print time
* Once part is oriented, supported and set to the desired ink and resolution push the orange print button in the side menu - this sends the part to the printer but does not begin printing process
* Save the Preform job for future prints if necessary
* Preform 3 3D printer:
  * Select job from job list (side menu) if not already on the screen
  * Ensure correct ink cartridge is in the back of the printer
  * Ensure vent on top of ink cartridge is open
  * When job is selected and ink cartridge is correct, hit print
  * Printer will give an estimated completion time

## **Part Removal**
* Once part is finished remove stage from printer
  * The print stage is clamped onto the z-stage
* Using provided spatula remove part(s) from print bed
* Clean print bed with IPA and clean wipe
* Replace print bed in z-stage clamp

## **Cleaning**
* Clean part(s) with IPA:
  * First use the "coarse" IPA bucket, this will likely be the "dirtiest" IPA bucket
  * Then use a "fine" IPA bucket, this will be the "cleanest" IPA bucket
  * Finally use IPA sonicator bath to clean part for at least 15 minutes, though longer is advisable
  * This is controlled through the menu
  * **REMEMBER** the sonicator bath has an automatic open/close function, **DO NOT** use force
    * If part(s) contain(s) covered channels or small recesses/channels it is advisable to use N<sub>2</sub> gun to blow part between each IPA cleaning step

## **Bake**
* Once part is cleaned blow dry with N<sub>2</sub> gun and ensure part is dry
* Using the provided UV oven bake part with the minimum parameters:
  * 60 degrees Celsius
  * 60 minutes
* These parameters are accessed through the menu on the oven
* Allow for ramp-up time
* Oven will automatically switch off once timer has counted down
* Use caution when removing part(s) from oven, it is likely the part(s) will be hot

## **Finishing Touches**
* 3D printing is a highly iterative process
* If a part is not printed exactly to desired parameters, sand paper can be used to reduce dimensions
* Often parts shrink during baking
