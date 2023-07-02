![sm64coop mod resource logo](https://github.com/TrashcamSaysFrick/sm64ex-coop-modding-resources/assets/90653075/e1b8bc34-fd5a-42d5-a69e-85f3500e8b04)
# Welcome to sm64ex-coop Modding Resources!
This is a github full of information for sm64ex-coop modding due to many people wondering how to do so. So, here are some resources that may help with the modding of sm64ex-coop!

this page features tutorials that I find helpful for coop modding

# Table of Contents

- Dynos Packs
https://github.com/TrashcamSaysFrick/sm64ex-coop-modding-resources/README.md#12

# DynOS Player Models
DynOS models that replace mario may seem to be a daughnting task but when you learn the basics it's pretty simple!

## What you need!
- Blender 3.2 or higher https://www.blender.org/
- Fast64 https://github.com/Fast-64/fast64

## Setting Up Blender and Fast 64

Once you got blender downloaded, install the Fast 64 plugin by going to Edit/Prefrences/Add-ons/Install in blender and selecting your release version of fast 64, as you can see below.

![blender 1](https://github.com/TrashcamSaysFrick/sm64ex-coop-modding-resources/assets/90653075/3b6ad543-176d-4723-b336-2c0f36b57046)

Next, you want to turn on the Fast 64 plugin by scrolling down in add-ons and hitting the checkbox beside it.

![blender 2](https://github.com/TrashcamSaysFrick/sm64ex-coop-modding-resources/assets/90653075/534394f5-28a7-44e6-93a9-bb3ba807be3d)

## Getting Mario's Model

Now you'll need the mario.blend file you can get from the Fast 64 github, which can be found here: https://github.com/Fast-64/fast64/blob/main/mario.blend

## Replacing Mario's Model

You'll now need a model to replace mario, I would suggest making an original model for this but placing an already existing model is ok with proper credit and permission (if possible provided) if released.

I would explain how to slap a model on top of Mario but I find that KeyBlader Tutorials' tutorial on doing this is excellent and it will help you figure this out.

I'll put their video right here: https://youtu.be/D-ZQsYedBt8

Another thing that is important is eye states, which fznmeatpopsicle made a great tutorial that'll show you how to do this.

I'll also put their video here too: https://youtu.be/hsRK8mzbABg

## Exporting Mario

Go to the SM64 Geolayout Exporter tab, select the custom export path. You'll want your path to be bin/dynos/packs/(insert-folder-of-your-dynos-here)

It should look like this.

![blender 3](https://github.com/TrashcamSaysFrick/sm64ex-coop-modding-resources/assets/90653075/fcf9a721-09d8-4306-8d50-26aec0769e9f)

Select Mario's armature and press the Export Armature Geolayout button, if this works correctly, it will say sucess somewhere.

![blender 4](https://github.com/TrashcamSaysFrick/sm64ex-coop-modding-resources/assets/90653075/3b60a177-5b1a-4f93-92a7-7ecb917b2597)

This should've created a folder called mario.

![blender 5](https://github.com/TrashcamSaysFrick/sm64ex-coop-modding-resources/assets/90653075/f9abf387-9ee1-48ee-91ec-fb17bc5f30c8)

Inside that mario folder there should be 3 files which are shown in the image below.

![blender 6](https://github.com/TrashcamSaysFrick/sm64ex-coop-modding-resources/assets/90653075/5c8bef53-6161-48cb-9241-0a9aeb3f8030)

## Building Your DynOS

Simply open up your sm64ex-coop game and your dynos character should show.

If not, Check to see if you have the pack on.

## Recolorability

sm64ex-coop allows you to change the color pallet of your character by either using preset or costum color pallets.

You can add this to your DynOS pack by making all or some of your model recolorable. 

Here's the guide by AngelicMiracles: https://cdn.discordapp.com/attachments/755910307167076393/1037930270768238622/How_to_Add_Color_Support.png yeah it's png

- Also you can also use CAP to get the color of Mario's cap!

## Hud Icon

This will replace the Mario head icon on the hud, simply go in to your dynos pack and make 2 new folders. They should be named like this bin/dynos/packs/textures/segment2/

In you segment2 folder, create a 16 x 16 image 

The title depends on what character it is for.

  Mario: segment2.05A00.rgba16.png
  Luigi: custom_luigi_head.rgba16.png
  Toad: custom_toad_head.rgba16.png
  Wario: custom_wario_head.rgba16.png
  Waluigi: custom_waluigi_head.rgba16.png

- though, the image can be larger than that, for example 32 x 32 or something like that

Open up the game to compile this icon.

![under construction](https://github.com/TrashcamSaysFrick/sm64ex-coop-modding-resources/assets/90653075/e92a2c52-0ff5-40f7-b1f9-28f0664c243c)
Everything here is still under construction! Some info may be missing!


