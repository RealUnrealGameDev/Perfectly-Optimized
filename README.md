# Perfectly Optimized
## UE5 Lightweight Starter Template for Low-End Hardware

**Perfectly Optimized** is a streamlined Unreal Engine 5 starter template engineered to deliver substantial performance gains on lower-end and legacy hardware.

Unreal Engine 5’s default configuration heavily prioritizes ray-traced global illumination and virtualized geometry. While systems such as **Nanite** and **Lumen** scale effectively on modern GPUs, their baseline overhead can overwhelm older discrete GPUs and integrated graphics solutions.

This template reconfigures the UE5 rendering pipeline around **stability, predictability, and low GPU cost**, delivering performance characteristics closer to Unity-style forward renderers while preserving Unreal Engine’s robust editor workflow and toolset.

---

## Overview

- Vulkan-based rendering backend  
- High-end UE5 rendering features disabled by default  
- Optimized for consistent frame times on low-spec systems  
- Clean, lightweight baseline for performance-first UE5 projects  

---

## Key Modifications

### Rendering Backend

- Switched from **DirectX 12** to **Vulkan**
- Improved driver compatibility on older and lower-tier GPUs
- Reduced shader overhead and runtime cost
- Avoids DX12-specific performance pitfalls on legacy hardware

### Anti-Aliasing

- Anti-aliasing forced to **FXAA**
- **MSAA disabled (0 samples)** to eliminate multi-sample performance cost

### Lighting Pipeline

- **Lumen fully disabled**
- No real-time global illumination or reflections
- Project configured for **baked lighting workflows**
- Predictable and stable frame times during runtime

### Geometry and Virtualization

- **Nanite disabled by default**
- Avoids virtualized geometry processing overhead
- Ensures compatibility with GPUs lacking sufficient compute throughput

### Additional Performance-Focused Changes

- Reduced post-processing features
- Virtual Shadow Maps disabled
- Distance field-based effects disabled
- Simplified default rendering and material settings
- Clean project configuration with no unnecessary runtime systems

---

## Technical Details

**Features**
- Vulkan-rendered UE5 template optimized for low-end hardware  
- Lightweight sample maps with performance-focused settings  
- Engine-level optimizations only (no gameplay systems included)

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

- Developers targeting older PCs, budget laptops, and integrated GPUs  
- Performance-sensitive prototypes and experiments  
- Indie projects requiring a lightweight UE5 baseline  
- Stylized, low-poly, or small-scale 3D projects  
- Developers transitioning from Unity-style rendering workflows to UE5

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
3. Build lighting
4. Begin development with a performance-optimized baseline
---


