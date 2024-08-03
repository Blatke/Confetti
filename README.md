# Confetti
HS2/AIS Studio Item

![AI_2023-10-01-04-32-24-411](https://github.com/user-attachments/assets/519b9a32-8e14-4c86-986f-99c4ac0e6b43)

![AI_2023-10-01-04-37-36-165](https://github.com/user-attachments/assets/3d0c6f87-2fba-4b50-93ae-e492324ea5ce)

## v0.0.2 on September 30, 2023
This mod provides two studio items of confetti:
	1. Confetti
	2. Confetti (Erasable)
of which one is a common item shaping like a hemisphere, and the other is an erasable one that is shaped like the other half of a sphere. 

![AI_2023-09-30-03-22-49-195](https://github.com/user-attachments/assets/ce69fe63-3695-4b29-abfc-41deddd2ebfe)

Since each piece of confetti is a plane, you can use Material Editor to import main and bump (normal) maps to change the textures, to select a emission color and rise up the emission strength value to let it shine, or change the glossiness or metallic value to make it smooth or more like metal. For the main texture, an image containing alpha path is suggested, and this makes the background of texture transparent. 

![AI_2023-09-30-03-29-46-028](https://github.com/user-attachments/assets/9f516184-f88c-46ab-b9ed-3de9de4ec50f)

![AI_2023-09-30-03-29-05-690](https://github.com/user-attachments/assets/c1d4d167-afae-4744-9bf0-51d5c934d18e)


You can modify the pose of the items. Select one item and click HS2PE or AIPE, then click adv. mode on the panel to open the advance mode tab. On this tab, choose Blend Shapes, and click Confetti. Now you can see in the Demonstration video, there are 4 options to modify:
	0. Straighten
		Make every piece of confetti as flat as possible.
	1. Vary Scales
		Make the scales of the pieces different in range from 0.2 to 1.0.
	2. Toward to Core
		Rotate the pieces to let them head to the origin of the item.
	3. Spread
		Increase the distances among the pieces without rescaling them.

Sometimes the confetti pieces do cover the character's face and this is not what we want to see. This issue becomes hard to solve in some circumstances we've already set up the items and don't want to move anyway. This mod provides some simple tools to hide the pieces between the character and the camera:
	1. Confetti Eraser Cube
	2. Confetti Eraser Sphere
	3. Confetti Eraser Plane
Their difference is only in the shapes. When there is an Eraser putting between our view (or camera) and the pieces of Confetti (Erasable), what part of pieces the Eraser covers, from our angle of view, will be hidden. When an Eraser is covering the character's head or body, it creates a path from the covered area to our view, and in this path there is no piece of Confetti (Erasable) showing to us. This system could be useful in forming up a foreground. For the background in which we don't need the pieces to be erased, we just use Confetti which is the common and unerasable one.

### Demonstration Videos
1. https://youtu.be/i_2w8-33oUk
2. https://youtu.be/p0xD4D15KQg

## v0.0.8 on October 1, 2023
In this update, some new items are added to make confetti have more textures. Combining with the original items, all these items are now listed as:
1. Confetti 1
2. Confetti 1 Erasable
3. Confetti 2
4. Confetti 2 Erasable
5. Confetti 3
6. Confetti 3 Erasable
7. Confetti 4
8. Confetti 4 Erasable
9. Confetti 5
10. Confetti 5 Erasable
11. Confetti DualFace
12. Confetti DualFace Erasable
13. Confetti Eraser Cube
14. Confetti Eraser Sphere
15. Confetti Eraser Plane

in which the number behind the letters are the amount of materials the item has. Like Confetti 5 means this item has 5 different materials in total that can be adjusted in it, and each material can be imported a main texture and a bump texture. 

![AI_2023-10-01-04-34-07-729](https://github.com/user-attachments/assets/2d1c8f8d-26c5-439f-8e0e-6bc72ea0de09)

![AI_2023-10-01-04-37-36-165](https://github.com/user-attachments/assets/8e63d538-8981-4b8b-a13b-d474d5780c14)

There are two items with "DualFace", which means each piece in a item has different materials between its front and back sides, and that are 2 materials in total. You can now use it to make a cash rain!

The Erasers have no change.

![AI_2023-10-01-04-47-13-142](https://github.com/user-attachments/assets/7080b206-6a00-42d1-83eb-f0ff0d2aea50)

![AI_2023-10-01-04-47-28-375](https://github.com/user-attachments/assets/502fcd3a-2f21-4f08-8828-b6c6f8b39fad)

![AI_2023-10-01-04-47-32-862](https://github.com/user-attachments/assets/80788f7d-b653-4089-b0cc-3469a39c832c)

For Blend Shapes, there comes newly an option of Scale Up, which can increase the size of pieces by the same proportion. So if you enlarge the distances among the pieces too much, this option can make them look not too small to see. 

![AI_2023-10-01-04-39-50-069](https://github.com/user-attachments/assets/bb526be5-b7b2-43e2-8547-4f36823193a5)

Also, the minimum distance among the pieces are now resized to a very small value, and you can reduce it to 0 to make them so tight. 

![AI_2023-10-01-04-38-22-718](https://github.com/user-attachments/assets/6759089d-9926-48b0-83de-ee54a4044366)

For the shaders, the issue that pieces might be seen through themselves seems now to be solved. 

## v0.0.9 on October 1, 2023
As considering the size of mod file, this update tries to increase the reusability of models that reduced the weight of file from 122mb of the last version to the current 58mb.

There is a tiny change in item list:
1. Confetti 1
2. Confetti 1 Erasable
3. Confetti 2
4. Confetti 2 Erasable
5. Confetti 3
6. Confetti 3 Erasable
7. Confetti 6
8. Confetti 6 Erasable
9. Confetti DualFace
10. Confetti DualFace Erasable
11. Confetti Eraser Cube
12. Confetti Eraser Sphere
13. Confetti Eraser Plane

where the previous Confetti 4 and its erasable edition changes to Confetti 6 and its erasable one (meaning 6 materials in total), and the previous Confetti 5 and its erasable one are deleted. 

## v0.0.11 on October 6, 2023
There are 3 items of Erasers newly added to the mod:
14. Confetti Eraser Cube OL
15. Confetti Eraser Sphere OL
16. Confetti Eraser Plane OL
where "OL" stands for "outlined" which means there is an outline for each eraser so that users can better distinguish where the transparent erasers are. After making poses, the outline can be removed by toggling the Enable option of the Outliner to OFF on Material Editor tab. 

![AI_2023-10-06-09-44-18-808](https://github.com/user-attachments/assets/0bb9d229-51c6-474e-a5ee-22abae9e7fde)
![AI_2023-10-06-09-45-08-754](https://github.com/user-attachments/assets/e49b7616-eaeb-403e-8ed5-93152d599b33)
![AI_2023-10-06-09-45-15-924](https://github.com/user-attachments/assets/77b6a1f8-2882-404a-99fa-32010de93e28)
