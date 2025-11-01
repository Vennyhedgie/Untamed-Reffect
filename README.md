# Untamed-Reffect
A more visible UI element for Ranger's Untamed Elite Specialization.

Helps tracking Unleash Pet / Unleash Ranger state. It also tracks Unleashed Power (trait) cooldown to let you know when you are ready to unleash.

<img width="823" height="318" alt="image" src="https://github.com/user-attachments/assets/e617e719-b668-439c-8203-88936027db9e" />

When in Unleash Pet state, and Unleashed Power is available (both icons on the left side line up) you'll be ready to Ambush.

<img width="768" height="309" alt="image" src="https://github.com/user-attachments/assets/f9852d0f-d7ac-4179-b78a-0f2abf321e00" />

During Ambush windows, the Untamed icon will light up. This checks for if your skill slot 1 has any of the ambush skills available.

<img width="802" height="312" alt="image" src="https://github.com/user-attachments/assets/5fb17e78-ca3d-4da9-95fc-b5594d581782" />

# Let Loose

If the Let Loose trait is equipped, an additional element will be added. This time lining up on the right side, as you must be in Unleashed Ranger state to perform this. It will indicate when you are ready to get an Ambush by weapon swapping:

<img width="928" height="330" alt="image" src="https://github.com/user-attachments/assets/592945b3-5224-4736-9abb-f294958f5c4e" />

- Note: Due to technical limitations with reffect, this is achieved by tracking your current weapon swap cooldown. Bear in mind this trait only works in combat, so it will appear to have a very short 1 second cooldown out of combat. Additionally, any change to your weapon swap reduction, like Relic of the Warrior, will shorten your weapon swap and make it not align with the trait cooldown, and thus is not recommended to be used with this trait.

<img width="809" height="305" alt="image" src="https://github.com/user-attachments/assets/4aae5a6d-831f-44d9-a326-6ce160a7a3ae" />


# How to use
Simply download the zip file to your reffect root folder like so:

<img width="578" height="300" alt="image" src="https://github.com/user-attachments/assets/13b88547-6cf1-4451-b8a3-9370b38abefb" />

Then right click > Extract here (the necessary files will be added to the packs and icons subfolders).

Then, return to reffect ingame and refresh packs.

# Notes

This effect is made with Normal interface size. If you use a different one, you can resize all the elements at once by right-clicking on the pack and selecting resize. Alternatively, you can move the pack's position on screen if needed, though it should be aligned by default.
