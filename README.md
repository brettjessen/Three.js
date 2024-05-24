# Build an Interactive 3D Portfolio Website with Three.js

## Introduction
This tutorial guides you through creating a personalized interactive 3D avatar for your portfolio using Three.js. By the end, you'll have a unique and engaging portfolio to capture hiring managers' attention.

## Table of Contents
- [Choosing an Avatar Platform](#choosing-an-avatar-platform)
- [Creating Your Avatar](#creating-your-avatar)
- [Adding Animations with Mixamo](#adding-animations-with-mixamo)
- [Combining Animations in Blender](#combining-animations-in-blender)
- [Setting Up Three.js](#setting-up-threejs)
- [Adding Interactivity](#adding-interactivity)
- [Enhancing Visuals](#enhancing-visuals)
- [Final Touches](#final-touches)
- [Conclusion](#conclusion)
- [Key Points](#key-points)

## Choosing an Avatar Platform
### Avatar Options
- **Avaturn**: Realistic avatars.
        https://www.avaturn.me
- **Ready Player Me**: Stylized avatars.
        https://www.readyplayer.me

For this tutorial, we'll use Avatar for its realistic appearance.

## Creating Your Avatar
### Step-by-Step Guide
1. **Create an Account**: Sign up on Avaturn.
2. **Upload Selfies**: Upload three selfies.
3. **Customize Avatar**: Customize and export the model as a GLB file **Important - set skin as "without skin" when downloading avatar.

## Adding Animations with Mixamo
### Animating Your Avatar
1. **Upload to Mixamo**: Upload the model.
2. **Select Animations**: Choose and download animations in FBX format.

## Combining Animations in Blender
### Blender Integration
1. **Import Avatar**: Import the GLB model into Blender.
2. **Add Animations**: Import FBX animations and bind them.
3. **Create NLA Strips**: Use Blender's NLA editor.
4. **Export Combined Model**: Export as a single GLB file.

## Setting Up Three.js
### HTML and JavaScript Integration
1. **Include Three.js**: Add dependencies to your HTML.
2. **Create HTML Structure**: Set up HTML with navigation and content sections.
3. **Load 3D Model**: Use GLTF loader to display the avatar.

## Adding Interactivity
### Making the Avatar Interactive
1. **Event Listeners**: Add listeners for animations.
2. **Raycasting**: Detect mouse interactions with the avatar.

## Enhancing Visuals
### Lighting and Shadows
1. **Lighting Setup**: Add ambient and directional lights.
2. **Shadows**: Enable shadows for realism.

### Adding a Pedestal
1. **Create Pedestal**: Use a cylinder geometry for the pedestal.

## Final Touches
### Animation Mixer
1. **Animation Mixer**: Blend animations smoothly.
2. **Default Animation**: Set a waving animation.
3. **Interactive Animation**: Trigger animations on click.

## Conclusion
You've learned to create a personalized 3D avatar, animate it using Mixamo and Blender, and display it with Three.js. This feature can significantly enhance your portfolio.

## Key Points
- **Avatar Creation**: Use Avatar for realistic 3D avatars.
- **Customization**: Upload selfies and customize your avatar.
- **Export Process**: Export the model as a GLB file.
- **Animation**: Add animations using Mixamo.
- **Blender Integration**: Combine animations in Blender.
- **Three.js Setup**: Include Three.js dependencies and set up HTML structure.
- **Model Loading**: Load the avatar model using GLTF loader.
- **Interactivity**: Add event listeners for user interaction.
- **Lighting and Shadows**: Configure lights and shadows.
- **Animation Mixer**: Blend animations using the animation mixer.

By incorporating these elements, you can create a dynamic and engaging 3D portfolio that showcases your skills and creativity.

Credit goes to dgreenheck - https://github.com/dgreenheck
