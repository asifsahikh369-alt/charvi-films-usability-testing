# Usability Testing & Design Analysis: Charvi Films

**Product:** [Charvi Films](https://charvifilms.in)  
**Evaluator:** Asif Anwar Shaikh  
**Date:** October 2026  
**Focus:** Visual storytelling discovery, mobile media performance, and client inquiry experience  

---

## What We Tested & Why

Charvi Films has a strong, cinematic visual identity. But for a creative production house, looking visually striking is only half the battle—the site also needs to quickly convince prospective clients and make reaching out frictionless.

I wanted to find out:
1. When a filmmaker, agency producer, or client lands on the site, do they immediately understand the studio's range of work?
2. Does the video-heavy interface hold up smoothly on everyday devices and mobile networks?
3. How effortless is it to go from watching a reel to sending a collaboration inquiry?

---

## How the Sessions Ran

I ran 1-on-1 moderated testing sessions with **4 participants** (two design-literate peers and two general web users). 

* **Format:** 15–20 minute casual walkthroughs over Google Meet and in-person screen sharing.
* **Method:** Think-Aloud protocol (asking participants to speak out loud about what they were thinking, looking for, or getting confused by as they navigated).
* **Setup:** 2 on laptop browsers (Chrome/Edge) and 2 on mobile phones (Android Chrome / iOS Safari).

---

## Tasks Given to Participants

Instead of giving direct instructions like "click the contact button," I gave participants open, goal-oriented scenarios:

1. **Task 1: First Impression & Showreel**  
   *"Imagine you're looking for a production team to shoot a music video. Explore the site and find their main reel or recent video work."*
2. **Task 2: Exploring Services**  
   *"Find out if they handle end-to-end post-production (like editing and color grading), and see if you can find samples of past commercial work."*
3. **Task 3: Starting a Project Inquiry**  
   *"You like what you see and want to ask for a project quote. Figure out how to get in touch with them."*

---

## Key Numbers at a Glance

After each task, I asked participants to rate how easy or frustrating it felt on a scale of **1 (painful)** to **7 (effortless)** using the Single Ease Question (SEQ).

| Task Scenario | Success Rate | Avg. Time | Avg. Ease Rating (1–7) | Takeaway |
| :--- | :---: | :---: | :---: | :--- |
| **1. Find the Showreel** | 100% | ~45 sec | **6.5 / 7** | Visually engaging; users loved the look right away. |
| **2. Explore Specific Services** | 75% | ~2 min 10 sec | **4.8 / 7** | Took some digging; categories felt slightly blended. |
| **3. Reach Out for an Inquiry** | 75% | ~1 min 55 sec | **4.2 / 7** | Noticeable hesitation finding and verifying the main contact trigger. |

---

## What Actually Happened: Key Observations & Friction Points

### 1. The "Is It Frozen?" First Impression on Mobile
* **What happened:** On desktop Wi-Fi, the background video reel looked stunning. But on mobile data, two participants sat looking at a dark, empty hero block for nearly 5 seconds while the video buffered in the background.
* **Participant reaction:** *"Wait, is my network dead or is the site still loading?"*
* **The issue:** There was no placeholder poster image or skeleton loader giving immediate visual feedback while the heavy video asset fetched.

### 2. Button Camouflage on the Inquiry Flow
* **What happened:** When participants decided to get in touch, their eyes scanned right past the contact action. Because the call-to-action button used muted, minimalist styling similar to surrounding decorative tags and status chips, it didn't look like an interactive button.
* **Participant reaction:** One user spent almost 30 seconds scrolling up and down the page looking for a standalone contact page or email link.
* **The issue:** The site prioritized subtle dark-mode minimalism over visual hierarchy, so the most important business action blended into the background.

### 3. Mobile Footer Overload
* **What happened:** On mobile viewports, the multi-column links in the lower sections required excessive vertical scrolling. Participants trying to skim back up accidentally tapped adjacent links with their thumbs.
* **The issue:** Desktop-first link grids don't translate well to narrow mobile screens without collapsible sections.

---

## Practical Fixes & Next Steps

Based on watching real people use the site, here are the most impactful changes to make:

1. **Add an Instant Video Poster Frame**  
   * Load an ultra-lightweight WebP screenshot of the reel immediately so the screen looks complete from millisecond zero. The actual video can silently replace it once buffered.
2. **Make the "Get in Touch" Action Unmissable**  
   * Give the main inquiry trigger a distinct accent color and stronger contrast. On mobile, keep a discreet floating "Inquire / Collaborate" button visible as users scroll through portfolio pieces.
3. **Turn Mobile Navigation into Clean Accordions**  
   * Collapse dense link lists into simple tap-to-expand accordions on screens under 768px to keep thumb navigation effortless and prevent misclicks.
4. **Touch-Friendly Media Controls**  
   * Ensure audio toggles and video restart triggers have generous touch targets (at least 44×44px) so mobile users aren't relying on hover states that don't exist on phones.

---

## Final Reflection
The visual craft and atmosphere of Charvi Films are already strong. The main takeaway from this testing is that high-end aesthetics shouldn't come at the cost of basic signposting. Adding clear loading cues, prominent buttons, and mobile-friendly tap areas will immediately help turn casual visitors into paying clients.
