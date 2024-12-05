# bpSRF: An extra robotic finger powered by wrist movements
 Github site for the bpSRF, a body-powered supernumerary robotic finger that requires no electronic components.
## Project Overview
This guide introduces the assembly and operation of the **Body-Powered Supernumerary Robotic Finger (bpSRF)**. The bpSRF is an innovative, lightweight device designed to enhance users' grasping capabilities by utilizing wrist movements to control an additional robotic finger. Unlike conventional SRFs, the bpSRF eliminates the need for electronic components and relies solely on body-powered mechanics. 
The device is particularly suited for helping people with hand impairments that limit finger but not wrist movements. It is also an excellent tool for healthy individuals seeking to explore additional degrees of freedom and novel hand grasping patterns. The bpSRF is easily manufacturable using 3D printing, making it a cost-effective and replicable solution.

<p align="center">
  <img src="Figures/Fig0_cover_2.png" alt="The bpSRF"/>
</p>


## Folder structure
The STL files are organized into folders as follows:
- **Finger**
    * Proximal phalanx
    * Distal phalanx
    * Inner link
- **Wrist**
    * Wrist side brace 1
    * Wrist side brace 2
    * Wrist buckle
    * Wrist posterior brace
    * Wrist anterior brace + driving link (in one part)
- **Palm support**
    * Available in S, M and L sizes
- **Cable tensioner**

The following figure shows the different components of the bpSRF. Although not shown, the finger's inner link is inside the proximal phalanx and will be shown in the assembly guide.


<p align="center">
  <img src="Figures/bpSRF_components.jpeg" alt="Components of the bpSRF"/>
</p>

Each folder contains the parts required for printing. Please print one piece from each file in the respective folders.

## Getting Started
### Download the Files
Clone the repository or download the zip file to access all the STL files:

```bash
git clone https://github.com/yourusername/Prosthetic-Finger.git
```
## Parameters for 3D-printing

The following are the recommended specifications for 3D-printing:

* Layer height: 0.2 - 0.24 mm
* Infill: 15%
* Print speed: 60 mm/s
* Support structure: Tree with 0% density (contours only)

The recommended orientations for printing the parts are as follows:

* **Finger components**

* **Wrist components**

* **Palm support**

## Additional materials
To assemble the bpSRF, the following additional tools and materials are required.

### Tools

* Cutting pliers
* Needle-nose pliers
* Metal File Set
* Soldering iron
* Super glue

### 4. Materials
* 3D-printed components for the bpSRF (as listed in the folder structure)
* Velcro straps:
    * 1.2 cm width
    * 3.5 cm width 
* ⌀ 2.5 mm aluminum (or other metal) pins for joints in the following quantities and lengths: 
    * 5 x 33 mm, 
    * 1 x 17 mm, 
    * 1 x 14 mm, 
    * 2 x 8 mm.
* ⌀ 2 mm elastic wire.
* ⌀ 0.25 mm rigid nylon wire.

## Step-by-Step assembly instructions

### 1. Finger

Use the 8 mm pin to secure the inner link to the upper-most axis of the distal phalanx. Then, with the help of a soldering iron, we can slightly melt the plastic around the hole where the pin was inserted to prevent it from slipping out. Any other method to fixate it axially should also work.

Then, use the 17 mm pin to connect the distal phalanx with the proximal phalanx. We again ensure they do not slip by using a soldering iron to seal the hole. Another alternative to secure the shafts is to apply a drop of super glue.
Once assembled, verify that both phalanges and the inner link slide smoothly against each other, without any significant friction.

Is best to try the assembly without glueing first and, if there was any high friction between surfaces, these should be smoothed using the metal files.

### 2. Wrist bracelet

Next, attach the finger to the wrist using the 17 mm and 8 mm pins. The longer pin joins the proximal phalanx while the shorter connects the inner link to the palm.

For the wrist braces, we will use the 33 mm pins. First, we connect the wrist buckle to the wrist anterior brace by passing the pin through the hole located at the bottom of the pieces.

Before attaching the other wrist braces, pass the rigid nylon wire through the sphere of the wrist anterior brace and through the wrist side brace 1. Then, pass the pin through the hole to connect the wrist side brace 1 to the wrist anterior brace.
Next, add the wrist side brace 2 to the connection by passing the rigid nylon wire through it. Then, pass the pin through the hole to secure it.

Finally, attach the wrist posterior brace to the entire assembly by passing the rigid nylon wire through and securing it with the pin through the hole.

Using the 3.5 cm Velcro strap, pass it through the hole of the wrist posterior brace and sew it to ensure it is securely fixed.

### 3. Palm support

### 4. Securing the elastic wire

### 5. Securing the rigid nylon

### Extra: Add a silicon rubber fingertip
