# blender_select_objects_with_near_origins
Script for Blender, to help select objects that sit very close to each other, within a defined threshold, used to clean-up undesired duplicates
Sometimes accidentally or because of importing an object from another software, objects clones are created in the exact place or very close to original object, this script helps clean up the mess of objects, by deselecting the active object and keep all other objects in close range selected, so the procedure will be as easy as deleting these objects.
This is how it works:
1- Select all objects in your scene
2- Activate the desired object
3- Run the script
4- Nearby objects to the active object will stay selected, while everything else including active object will be deselected.
5- Now you have all the duplicates selected, you can delete them or move them to a different layer
6- To modify the definition of (near by), meaning to increase or decrease the threshold of detection, change the value of the variable called (value) in line 11 of the script, you should use a float number.
