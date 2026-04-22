# 3D printable drone frames and parts

![Small 3D printed Y4 quadcopter](/res/ydrone_thumb.png)

Hiii! This repository contains printable models and various info for my 3D printed drone projects. These models are designed to be very easy to print (with flat, no support PLA parts where possible) while staying stiff and dusable enough to handle crashes, allow proper-ish tuning, and not commit spontaneous self-disassembly.

## General info and build tips

### Disclaimer

I do not assume any responsibility for damages or injuries from your use of (or misuse of (or taking inspiration from)) these projects. Be careful, copters bite regardless of size. These ones use homemade plastic parts, building them is easy but leaves a lot of room for error and oversight - including on my side. These are my hobby projects, not certified bombproof designs.

Feel free to share, use, modify or remix. Do not sell project sources, builds, prints, or derivative works. Please give credit and link to the original source.

Take care and have fun!

### Purchasing from AliExpress

AliExpress text based search is barely usable and makes it very difficult to find the right item or compare prices between listings for the same product. Your best option is to use the site's image based search, especially when comparing prices. I have included pictures for most parts you can directly paste into AliExpress's image search to find matching listings.

![AliExpress image search demo](/res/aliexpress.png)


# 3" Y4 Quad (made with illegally cheap motors)

I found some ~~cursed~~ cheap motors on AliExpress (about 0.75$ each, similar to the ones that are commonly used in cheap Chinese camera drones and DJI lookalikes) and felt like making a 3D printed quad with them, and some spare parts. I decided to go with a Y4 configuration, mainly because it looks cool.

The design is not perfect; the FC can't be easily removed after assembly (so finish soldering first and only *then* glue the frame) and there are many areas left for improvement, but I'm overall happy with the design.

Parts used:
- **AIO FC** (30.5x30.5 mounting, 4S compatible)
  - eg. SpeedyBee F405 AIO; or GEPRC TAKER G4 AIO (I strongly recommend against buying GEP)
- **HGLRC Zeus nano**  (w/ monopole antenna)
- **ELRS nano receiver** (w/ dipole antenna)
- **Camera** (w=14mm)
- **Tattu 850mAh 4S 95C Lipo HV Battery**
- **20x M1.7 screws (!)** (*18x h=5mm* for the props and motors, 2x h=10mm for the inverted prop)
- **7x small thread forming screws** *d=1.2mm h=5mm*, for the reverse mounting plate)
- **XT30 female connector**
- **Motors and matching props**, *see below*
- The 3D printed parts of course
- Small cable ties
- Tons of super glue

> [!NOTE]
> ### Printing
>
> **Print parts from PLA.** Not PETG, not PA, not other materials unless you really know what you're doing.
>
> **Lay parts flat, use 100% infill, and an alternating/rectilinear infill and surface pattern.**
> 
> **Use liquid cyanoacrylate / super glue** generously. Glue all touching surfaces, except for the cover plate and inverse motor mounting plate. Those should be held in place with screws only.
>
> The **battery holder should be printed from TPU**. Position it upright and use supports. 


> [!NOTE]
> ### Motors, props
>
> **The motors use M1.7 screws**, and have unusual thread spacing and keying on the bell. They are - afaik - only compatible with made to match propellers (or interference fit "no screw" props; however no such props (should) really exist in a 3" format.)
>
> Matching propellers are very cheap but also break easily. Make sure to pick up a lot of them. A 20x pack sould be in the <$10 range.
>
> Some of my pictures show motors without an exposed shaft. **Make sure to buy motors with exposed shafts**. This is required for inverse-mounting the propeller. You can use the included images to find the correct parts.
>
> Use a spacer when inverse mounting the bottom tail propeller.

> [!TIP]
> Unlike carbon composite, cracked and snapped PLA parts can be repaired with super glue. *Use a lot of glue and make sure the surfaces are properly covered and in full contact*.

## Build steps

I haven't documented the build step-by-step, but the craft is very simple to assemble. The steps are briefly as follows;
1. Print all parts (found in *models/01_y4mini/*). File names starting with `b_`, `w_`, and `c_` indicate black, white, and colored parts in my build. `tpu_` should be printed from 90-95A TPU.
2. Fasten the AIO (along with the battery holder) to the main plate, and mount the motors.
3. Solder leads to the VTX and receiver, then pass them through the holes in the top plate.
4. Loosely assemble the frame (do not glue yet), then trim all leads to the correct length and solder them to the AIO. Solder the battery connector to the AIO.
5. Fasten the VTX and receiver to the top plate. Use cable ties for the receiver.
6. Glue the frame pieces together (except the top cover and inverse motor mounting plate). Thoroughly glue all adjacent surfaces.
7. Secure the motor leads to the frame with cable ties. Snap the receiver antenna into the slots below the tail.
8. Secure the top cover and motor mounting plate to the frame with screws.

### WIPs

![Y4 quadcopter work in progress, base plate](/res/ydrone_wip1.jpg)

![Y4 quadcopter work in progress, top plate and side panels assembled](/res/ydrone_wip2.jpg)

![Y4 quadcopter work in progress, top plate and side panels assembled, side panel missing](/res/ydrone_wip3.jpg)

### 3D / exploded view

> [!NOTE]
> Parts in the 3D views may slightly differ from the current up to date models. Assembly and mounting *should be* unchanged.

![Y4 quadcopter parts, exploded view](/res/ydrone_exploded.jpg)

![Y4 quadcopter parts, assembled view](/res/ydrone_assembled.jpg)



