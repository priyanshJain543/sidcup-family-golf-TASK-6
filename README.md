---

## 🛠 Technical Implementation

### ⚛️ Dynamic Mouse Tracking
The project implements a **Dual-Layer Cursor System**. By listening to the `mouseover` event, the application calculates real-time X/Y coordinates to drive a pointer and a delayed Gaussian-blur background element, creating a modern "flashlight" or "follow-me" effect.

### 📜 Scroll-Driven Interactivity (SDI)
Utilizing **GSAP (GreenSock) & ScrollTrigger**, the UI elements are not merely static; they are mapped to the scroll progress:
* **Navbar Morphing:** Transitions background opacity and height based on scroll-offset.
* **Element Scrubbing:** Background darkening and quote-mark translations are synchronized with the user's scroll speed.
* **Staggered Reveals:** Grid layouts (cards) utilize stagger-load logic for a fluid entrance.

### ⚡ Visual Engineering
* **Video Hero Integration:** High-bitrate background video with CSS object-fit optimization.
* **Infinite Marquee:** CSS-only infinite horizontal scrolling utilizing hardware-accelerated transforms.
* **3D Perspective Hover:** Interactive cards utilize `rotate3d` and `scale` for tactile depth.


## 🔗 Live Experience
**View the Deployment:** [Link to your hosted site]()

---
