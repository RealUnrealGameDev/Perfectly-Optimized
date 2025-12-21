![Title Image lol](https://media.fab.com/image_previews/gallery_images/16328483-1ab7-4212-836d-73c0d0414df2/ac4d0eec-e992-4e98-a13b-cbfa3b242c41.jpg)
**Perfectly Optimized** is a Unreal Engine 5 starter template made to deliver performance gains on lower-end hardware.

Unreal Engine 5’s default configuration prioritizes ray-traced global illumination and virtualized geometry. While systems such as **Nanite** and **Lumen** work effectively on modern GPUs, they can overwhelm older GPUs and integrated graphics.

This template changes the UE5 rendering pipeline for **stability and low GPU cost**, delivering performance closer to Unity forward rendered games.

---

## Overview

- Vulkan-based rendering  
- High-end UE5 rendering features disabled by default  
- Optimized for high and stable frame rates on low-spec systems  
- Clean, lightweight template for performance  

---

## Key Modifications

### Rendering Backend

- Switched from **DirectX 12** to **Vulkan**
- Improved compatibility with mobile and VR systems
- Reduced shader runtime cost

### Anti-Aliasing

- Anti-aliasing changed to **FXAA**
- **MSAA disabled (0 samples)**

### Lighting Pipeline

- **Lumen fully disabled**
- No real-time global illumination or reflections
- Project configured for **baked lighting**

### Geometry and Virtualization

- **Nanite disabled by default**
- Avoids virtualized geometry processing
- Ensures compatibility with GPUs lacking powerful compute resources

### Reduced Package Size

- **Disabled Prerequisites installer**
- Exclude Editor Content While Cooking
- Exclude Movies while staging

### Additional Performance-Focused Changes

- Reduced unecessary post processing
- Virtual Shadow Maps disabled
- Clean project configuration with no unnecessary runtime systems

---

## Technical Details

**Features**
- Vulkan-rendered UE5 template optimized for low-end hardware  
- Lightweight sample maps with performance-focused settings  

**Number of Blueprints**
- None

**Number of Maps**
- 1

**Input**
- None
*(No gameplay input bindings beyond engine defaults.)*

**Network Replicated**
- No

**Supported Development Platforms**
- Windows: Yes  
- Mac: No  

**Documentation**
- Included in this repository

---

## Intended Use Cases

- Developers targeting older PCs, budget laptops, VR Systems, Mobile Games and integrated GPUs  
- Performance-sensitive prototypes and experiments  
- Indie projects requiring a lightweight UE5 Project
- Stylized, low-poly, or small-scale 3D projects  
- Developers transitioning from Unity rendering to UE5

---

## What This Template Is Not

- Not a gameplay framework  
- Not a visual showcase  
- Not a Nanite or Lumen demonstration  
- Not intended for high-end or cinematic rendering

This template exists to provide a **clean, fast, and predictable starting point** for Unreal Engine 5 projects where performance is a primary concern.

---

## Getting Started

1. Clone/download this repository or download from fab
2. Open the `.uproject` file using Unreal Engine 5  
3. **Build lighting**
4. Begin development with a performance-optimized baseline
---


