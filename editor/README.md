[← All guides](../README.md#guides-for-every-tool) · [Editor](../editor/) · [Repair](../repair/) · [Pose](../pose/) · [Upload / Export](../upload-export/) · [Skins](../skins/) · [Profile](../profile/)

# Skin Editor

**Open it:** https://mc-engine.app/editor

The MC-ENGINE skin editor is where you paint a Minecraft skin pixel by pixel — on a live **3D model** or on the flat **64×64 template** (or HD 128 / 256 / 512). It has drawing tools, base and overlay layers, symmetry, palettes, templates, hair, stamps, a cape editor, armor and elytra preview, history and drafts. Everything is saved in your browser while you work.

**Quick start:** pick a colour → choose **Pencil** (key `P`) → click on the 3D model or the template → turn the model by dragging the empty space around it → press **Upload** in the top bar to download it for Minecraft.

## Every button (99)

- [Tools](#tools)
- [Top bar](#top-bar)
- [Side panel: brush & files](#side-panel-brush--files)
- [Side panel: body parts](#side-panel-body-parts)
- [Side panel: import](#side-panel-import)
- [Side panel: symmetry](#side-panel-symmetry)
- [Side panel: palette](#side-panel-palette)
- [Side panel: layers & more](#side-panel-layers--more)
- [Tool settings (side panel)](#tool-settings-side-panel)
- [3D view (shared by Editor, Pose and Repair)](#3d-view-shared-by-editor-pose-and-repair)

### Tools

#### Pencil — key `P`

- Draws pixels in your colour.
- Click a pixel, or hold and drag to draw. Works on the 2D texture and on the 3D model.
- Also called: draw, paint, brush.
- Full guide: [Minecraft skin editor tools explained (with shortcut keys)](https://mc-engine.app/docs/editor-tools#step-2)

#### Eraser — key `E`

- Erases pixels back to transparent.
- Drag over the pixels to remove them.
- Also called: erase, delete pixel, rubber.
- Full guide: [Minecraft skin editor tools explained (with shortcut keys)](https://mc-engine.app/docs/editor-tools#step-2)

#### Fill (bucket) — key `B`

- Fills a same-colour area at once.
- Tolerance (side panel) also fills similar colours; "Everywhere" recolours every matching pixel on the skin.
- Also called: bucket, paint bucket, flood, replace colour.
- Full guide: [Minecraft skin editor tools explained (with shortcut keys)](https://mc-engine.app/docs/editor-tools#step-2)

#### Picker (eyedropper) — key `I`

- Takes a colour from the skin.
- Click any pixel and it becomes your colour.
- Also called: eyedropper, pick colour, color picker.
- Full guide: [Minecraft skin editor tools explained (with shortcut keys)](https://mc-engine.app/docs/editor-tools#step-2)

#### Line — key `L`

- Draws a straight line.
- Press where it starts and drag to where it ends.
- Also called: straight line.
- Full guide: [Minecraft skin editor tools explained (with shortcut keys)](https://mc-engine.app/docs/editor-tools#step-3)

#### Box (rectangle) — key `R`

- Draws a box outline.
- Drag from one corner to the other.
- Also called: rectangle, square, shape.
- Full guide: [Minecraft skin editor tools explained (with shortcut keys)](https://mc-engine.app/docs/editor-tools#step-3)

#### Circle — key `C`

- Draws a circle outline.
- Drag to set its size.
- Also called: round, ellipse, shape.
- Full guide: [Minecraft skin editor tools explained (with shortcut keys)](https://mc-engine.app/docs/editor-tools#step-3)

#### Select — key `S`

- Picks the area other tools are allowed to change.
- Drag a box, or use Free Select to paint the exact pixels on the 3D model. Invert / Fill / Clear are in the side panel.
- Also called: selection, free select, invert.
- Full guide: [Minecraft skin editor tools explained (with shortcut keys)](https://mc-engine.app/docs/editor-tools#step-4)

#### Move — key `M`

- Moves pixels.
- Box some pixels, then drag them to a new spot.
- Also called: drag pixels, shift.
- Full guide: [Minecraft skin editor tools explained (with shortcut keys)](https://mc-engine.app/docs/editor-tools#step-4)

#### Shade — key `H`

- Darkens or lightens pixels you paint over.
- Hold Shift to flip between darken and lighten. Strength is in the side panel.
- Also called: darken, lighten, shadow, highlight.
- Full guide: [Minecraft skin editor tools explained (with shortcut keys)](https://mc-engine.app/docs/editor-tools#step-6)

#### Noise — key `N`

- Paints random shades of your colour for a textured look.
- Variation (side panel) sets how different the shades are.
- Also called: texture, random, grain.
- Full guide: [Minecraft skin editor tools explained (with shortcut keys)](https://mc-engine.app/docs/editor-tools#step-6)

#### Fade (gradient) — key `D`

- Fades between your two colours.
- Drag across the area. Bands and dither are in the side panel.
- Also called: gradient, blend, bands, dither.
- Full guide: [Minecraft skin editor tools explained (with shortcut keys)](https://mc-engine.app/docs/editor-tools#step-6)

#### Stamp — key `T`

- Adds ready-made eyes, mouths and more.
- Pick a stamp in the side panel and click the skin, or use "Put on face".
- Also called: eyes, mouth, face, sticker.
- Full guide: [Minecraft skin editor tools explained (with shortcut keys)](https://mc-engine.app/docs/editor-tools#step-6)

#### Mirror — key `F`

- Paints the left and right side at the same time.
- Turn it on, then paint one side.
- Also called: mirror x, symmetry, both sides.
- Full guide: [Minecraft skin editor tools explained (with shortcut keys)](https://mc-engine.app/docs/editor-tools#step-8)

#### Flip (mirror Y) — key `Y`

- Paints the top and bottom at the same time.
- Also called: mirror y, top and bottom.
- Full guide: [Minecraft skin editor tools explained (with shortcut keys)](https://mc-engine.app/docs/editor-tools#step-8)

#### Grid — key `G`

- Shows or hides the pixel grid on the texture.
- Also called: pixel grid, lines.
- Full guide: [Minecraft skin editor tools explained (with shortcut keys)](https://mc-engine.app/docs/editor-tools#step-8)

#### Second colour

- The colour a Fade (gradient) ends with. Press X to swap it with your first colour.
- Where: open **Gradient** first, then it shows.
- Also called: color 2, gradient colour, end colour.
- Full guide: [Minecraft skin editor tools explained (with shortcut keys)](https://mc-engine.app/docs/editor-tools#step-6)

#### Zoom in / out — key `+ / −`

- Makes pixels bigger or smaller (2D) or moves the camera closer (3D).
- Also called: zoom, bigger, smaller.
- Full guide: [Minecraft skin editor tools explained (with shortcut keys)](https://mc-engine.app/docs/editor-tools#step-8)

#### Reset (fit view)

- Shows the whole texture again (2D) or puts the 3D view back to the start.
- Also called: fit, center.
- Full guide: [Minecraft skin editor tools explained (with shortcut keys)](https://mc-engine.app/docs/editor-tools#step-8)

#### Swap colours — key `X`

- Swaps your first and second colour.
- Where: open **Gradient** first, then it shows.
- Also called: second colour, switch colour.
- Full guide: [Minecraft skin editor tools explained (with shortcut keys)](https://mc-engine.app/docs/editor-tools#options)

#### Colour

- The colour square at the bottom of the tool strip is your colour.
- Click it to choose any colour or type a hex code.
- Also called: color, colour picker, pick colour, hex.
- Full guide: [Colours, brush size, opacity and palettes](https://mc-engine.app/docs/colours-palette#step-2)

#### Edit toolbar

- Chooses which tools show in the strip and in which order.
- You can also change the shortcut keys there.
- Also called: customise, hide tools, reorder, shortcuts.
- Full guide: [Make the editor yours: toolbar, tips, panels and layout](https://mc-engine.app/docs/editor-workspace#step-1)

### Top bar

#### Tool names (A)

- The A button at the far left shows or hides the names under the tool icons.
- Also called: labels, text under icons, show names, font.
- Full guide: [Make the editor yours: toolbar, tips, panels and layout](https://mc-engine.app/docs/editor-workspace#step-1)

#### 2D / 3D view

- 2D Edit = the flat texture, 3D Edit = paint on the model, 2D + 3D = both side by side.
- Also called: 3d edit, 2d edit, 2d + 3d, split, view mode, editing view.
- Full guide: [The top bar: 2D / 3D view, HD size, undo and model](https://mc-engine.app/docs/editor-top-bar#step-1)

#### Skin size (64 / 128 / 256)

- Switches between a normal 64×64 skin and HD 128 or 256.
- Java needs 64×64 — switch back before you export for Java.
- Also called: hd, 64x64, 128, 256, resolution.
- Full guide: [How to make an HD Minecraft skin (128x128, 256x256 or 512x512)](https://mc-engine.app/docs/hd-skin#step-1)

#### Undo — key `Ctrl+Z`

- Takes back your last change.
- Also called: back, mistake.
- Full guide: [The top bar: 2D / 3D view, HD size, undo and model](https://mc-engine.app/docs/editor-top-bar#step-3)

#### Redo — key `Ctrl+Y`

- Puts back a change you undid.
- Also called: forward, again.
- Full guide: [The top bar: 2D / 3D view, HD size, undo and model](https://mc-engine.app/docs/editor-top-bar#step-3)

#### Clear part

- The red bin clears the part you have selected (shown at the right of the bar).
- Undo brings it back if you clicked by mistake.
- Also called: delete, trash, bin, empty, wipe.
- Full guide: [The top bar: 2D / 3D view, HD size, undo and model](https://mc-engine.app/docs/editor-top-bar#step-3)

#### Clear skin

- The red bin with "ALL" on it (next to the Clear part bin) makes the whole skin empty — every part, both layers.
- It asks first, and Undo brings the skin back.
- Also called: clear all, empty skin, blank, transparent, erase all, start over, wipe.
- Full guide: [The top bar: 2D / 3D view, HD size, undo and model](https://mc-engine.app/docs/editor-top-bar#step-3)

#### Repair this skin

- Sends the skin to Skin Repair / Layout to fix a broken or old layout face by face.
- Also called: fix, broken, old skin, layout.
- Full guide: [The top bar: 2D / 3D view, HD size, undo and model](https://mc-engine.app/docs/editor-top-bar#step-3)

#### Compare before / after

- Shows how the skin looked when you opened it next to how it looks now.
- Also called: before, after, original, difference.
- Full guide: [The top bar: 2D / 3D view, HD size, undo and model](https://mc-engine.app/docs/editor-top-bar#step-3)

#### Part names

- Writes the part and face name (Front, Back, Top…) on every face of the 2D texture.
- Only in the 2D views.
- Also called: labels, front back, face names, which face.
- Full guide: [Make the editor yours: toolbar, tips, panels and layout](https://mc-engine.app/docs/editor-workspace#step-2)

#### Selected part label

- Shows which part, layer and size you are working on, e.g. "Body Front · base · 8×12".
- Also called: body front, part layer size, what am i editing.
- Full guide: [Minecraft skin layers: base, overlay (hat & jacket) and body parts](https://mc-engine.app/docs/layers-body-parts#step-2)

#### Reset layout

- Puts panel sizes and the 2D / 3D split back to normal.
- It only shows after you resized something.
- Also called: panels, split, sizes.
- Full guide: [Make the editor yours: toolbar, tips, panels and layout](https://mc-engine.app/docs/editor-workspace#step-3)

#### Tips tour

- The ? button gives a quick tour of the editor.
- Also called: help, tour, question.
- Full guide: [Make the editor yours: toolbar, tips, panels and layout](https://mc-engine.app/docs/editor-workspace#step-2)

#### Show / hide side panel

- The button at the far right hides the side panel for a bigger canvas, and shows it again.
- Also called: properties, right panel, more space, hide panel.
- Full guide: [Side panels: symmetry, drafts, history, templates, cape and more](https://mc-engine.app/docs/editor-panels#step-1)

#### Restore draft

- The editor saves drafts in this browser.
- "Continue where you left off?" → Restore brings your last work back.
- Also called: continue, autosave, lost work, draft.
- Full guide: [Side panels: symmetry, drafts, history, templates, cape and more](https://mc-engine.app/docs/editor-panels#step-5)

### Side panel: brush & files

#### Brush size — key `[ / ]`

- How many pixels each click paints: 1×1 up to 6×6 (4–6 are round).
- Pick a square under Brush, or press [ and ].
- Where: open **Pencil** first, then it shows.
- Also called: size, thick, brush, 1x1, round.
- Full guide: [Colours, brush size, opacity and palettes](https://mc-engine.app/docs/colours-palette#step-1)

#### Opacity

- How strong each stroke is. Below 100% the colour mixes with what is already there.
- Where: open **Pencil** first, then it shows.
- Also called: transparent, see through, alpha, strength.
- Full guide: [Colours, brush size, opacity and palettes](https://mc-engine.app/docs/colours-palette#step-1)

#### Upload

- Opens a skin PNG or any picture from your device in the editor.
- Also called: open, import file, png, load skin, picture.
- Full guide: [Image to Minecraft skin: upload any picture or skin PNG](https://mc-engine.app/docs/upload-image#step-1)

#### Export

- Downloads your skin (PNG and more) to use in Minecraft.
- Also called: download, save, png, bedrock, java, mcpack.
- Full guide: [How to put a custom skin in Minecraft Java & Bedrock](https://mc-engine.app/docs/use-in-minecraft#step-1)

### Side panel: body parts

#### Base layer

- Paint on the base layer — the body itself.
- Also called: inner layer, body layer, first layer.
- Full guide: [Minecraft skin layers: base, overlay (hat & jacket) and body parts](https://mc-engine.app/docs/layers-body-parts#step-1)

#### Overlay (hat / jacket)

- Paint on the outer layer: hat, jacket, sleeves and pants. It sits on top of the base.
- Also called: outer layer, second layer, hat, jacket, sleeves, pants.
- Full guide: [Minecraft skin layers: base, overlay (hat & jacket) and body parts](https://mc-engine.app/docs/layers-body-parts#step-1)

#### Body parts figure

- Click a part on the little figure to hide or show it on the 3D model — handy to paint under the arms.
- Also called: hide part, show part, visibility, 3d visibility.
- Full guide: [Minecraft skin layers: base, overlay (hat & jacket) and body parts](https://mc-engine.app/docs/layers-body-parts#step-2)

#### Head / Body / Arms / Legs faces

- Open Head, Body, Arms or Legs and click a face (Front, Back, Left, Right, Top, Bottom) to jump straight to it.
- Also called: head front, face, right arm, left leg, top, bottom, jump to face.
- Full guide: [Minecraft skin layers: base, overlay (hat & jacket) and body parts](https://mc-engine.app/docs/layers-body-parts#step-2)

#### Extra → Full Skin / All

- Selects the whole skin instead of one part, so tools work everywhere.
- Where: open **Extra** first, then it shows.
- Also called: whole skin, all parts, extra.
- Full guide: [Minecraft skin layers: base, overlay (hat & jacket) and body parts](https://mc-engine.app/docs/layers-body-parts#step-2)

#### Steve (classic)

- Classic model with 4-pixel-wide arms.
- Also called: classic, wide arms, 4px.
- Full guide: [The top bar: 2D / 3D view, HD size, undo and model](https://mc-engine.app/docs/editor-top-bar#step-4)

#### Alex (slim)

- Slim model with 3-pixel-wide arms.
- Also called: slim, thin arms, 3px.
- Full guide: [The top bar: 2D / 3D view, HD size, undo and model](https://mc-engine.app/docs/editor-top-bar#step-4)

#### Free Draw / locked

- Free Draw paints anywhere. Turn it off to lock tools to the selected body part.
- Also called: lock, unlock, draw mode, stay inside.
- Full guide: [Minecraft skin layers: base, overlay (hat & jacket) and body parts](https://mc-engine.app/docs/layers-body-parts#step-2)

### Side panel: import

#### Import skin (username)

- Open Import skin and type a Minecraft player name.
- Load replaces the current skin (it is kept in History).
- Where: open **Import skin** first, then it shows.
- Also called: username, player name, mojang, copy skin.
- Full guide: [How to get a Minecraft skin from a username](https://mc-engine.app/docs/skin-from-username#step-2)

#### Skin history (username)

- Import a player by name, then pick one of their older skins under "Skin history".
- The list grows each time the player is looked up after changing skins.
- Where: open **Import skin** first, then it shows.
- Also called: old skins, past skins, previous skin, namemc, skin history.
- Full guide: [How to get a Minecraft skin from a username](https://mc-engine.app/docs/skin-from-username#step-3)

#### Share link

- Makes a short link that opens a copy of your skin in the editor — not posted to the gallery.
- The link is copied for you.
- Also called: share, link, send skin, url, copy link.
- Full guide: [How to put a custom skin in Minecraft Java & Bedrock](https://mc-engine.app/docs/use-in-minecraft#step-4)

### Side panel: symmetry

#### Symmetry → mirror left/right, top/bottom

- Same as Mirror (F) and Flip (Y): paint both sides, or top and bottom of the part, at once.
- Where: open **Symmetry** first, then it shows.
- Also called: mirror, both sides.
- Full guide: [Side panels: symmetry, drafts, history, templates, cape and more](https://mc-engine.app/docs/editor-panels#step-2)

#### Symmetry → Base / Sleeves / Both

- Chooses which layer the copy buttons copy: base, sleeves/pants, or both.
- Where: open **Symmetry** first, then it shows.
- Also called: which layer, sleeves, pants.
- Full guide: [Side panels: symmetry, drafts, history, templates, cape and more](https://mc-engine.app/docs/editor-panels#step-2)

#### Copy arm to the other arm

- Copies one arm onto the other, mirrored. It overwrites the other arm.
- Where: open **Symmetry** first, then it shows.
- Also called: copy limb, copy arm, right arm, left arm.
- Full guide: [Side panels: symmetry, drafts, history, templates, cape and more](https://mc-engine.app/docs/editor-panels#step-2)

#### Copy leg to the other leg

- Copies one leg onto the other, mirrored. It overwrites the other leg.
- Where: open **Symmetry** first, then it shows.
- Also called: copy limb, copy leg, right leg, left leg.
- Full guide: [Side panels: symmetry, drafts, history, templates, cape and more](https://mc-engine.app/docs/editor-panels#step-2)

#### Turn part upside down

- Flips the selected part upside down.
- Where: open **Symmetry** first, then it shows.
- Also called: flip part, rotate, upside down.
- Full guide: [Side panels: symmetry, drafts, history, templates, cape and more](https://mc-engine.app/docs/editor-panels#step-2)

### Side panel: palette

#### Shades of your colour

- Five darker and lighter shades of your colour. Click one to use it, or add all five to the palette.
- Where: open **Palette** first, then it shows.
- Also called: darker, lighter, tones, shade row.
- Full guide: [Colours, brush size, opacity and palettes](https://mc-engine.app/docs/colours-palette#step-2)

#### Saved palette

- Your saved colours. Pick another palette from the list, click a colour to use it.
- Where: open **Palette** first, then it shows.
- Also called: colours, swatches, saved colours, switch palette.
- Full guide: [Colours, brush size, opacity and palettes](https://mc-engine.app/docs/colours-palette#step-3)

#### Add colour to palette

- Adds your current colour to the palette.
- Where: open **Palette** first, then it shows.
- Also called: save colour, plus.
- Full guide: [Colours, brush size, opacity and palettes](https://mc-engine.app/docs/colours-palette#step-3)

#### Palette from this skin

- Makes a new palette from the colours used most on this skin.
- Where: open **Palette** first, then it shows.
- Also called: colours used, extract, most used.
- Full guide: [Colours, brush size, opacity and palettes](https://mc-engine.app/docs/colours-palette#step-3)

#### New / rename / delete palette

- Start an empty palette, rename it, click colours to remove them, or delete the palette.
- Where: open **Palette** first, then it shows.
- Also called: empty palette, rename, delete palette, remove colours.
- Full guide: [Colours, brush size, opacity and palettes](https://mc-engine.app/docs/colours-palette#step-3)

#### Import palette file

- Loads a palette file: .hex, .gpl (GIMP / Aseprite), .json or .txt (up to 200 KB).
- Where: open **Palette** first, then it shows.
- Also called: gpl, hex file, lospec, aseprite, json, txt.
- Full guide: [Colours, brush size, opacity and palettes](https://mc-engine.app/docs/colours-palette#step-3)

#### Download palette (.hex / .gpl)

- Saves the palette as .hex (Lospec, Aseprite) or .gpl (GIMP, Aseprite, Krita).
- Where: open **Palette** first, then it shows.
- Also called: save palette, export palette, gimp, krita.
- Full guide: [Colours, brush size, opacity and palettes](https://mc-engine.app/docs/colours-palette#step-3)

#### Palette from a picture

- Pulls the main colours out of any picture into a palette.
- Also called: colours from image, extract colours.
- Full guide: [Image to colour palette: get the colours of any picture](https://mc-engine.app/docs/palette-from-image#step-1)

### Side panel: layers & more

#### Layers

- Turn on layers to paint on extra layers above the skin.
- Export merges all visible layers into one skin.
- Where: open **Layers** first, then it shows.
- Also called: paint layer, turn on layers, extra layer.
- Full guide: [Minecraft skin layers: base, overlay (hat & jacket) and body parts](https://mc-engine.app/docs/layers-body-parts#step-3)

#### Manage layers

- Hide, fade, reorder, merge or delete a layer without touching the others.
- Also called: hide layer, layer opacity, merge, reorder, delete layer.
- Full guide: [Minecraft skin layers: base, overlay (hat & jacket) and body parts](https://mc-engine.app/docs/layers-body-parts#step-4)

#### Drafts

- Skins saved in this browser while you work. Click one to open it again.
- Also called: autosave, saved work, older draft.
- Full guide: [Side panels: symmetry, drafts, history, templates, cape and more](https://mc-engine.app/docs/editor-panels#step-5)

#### History

- Every change in order — click a step to go back to it.
- Also called: steps, go back, older version.
- Full guide: [Side panels: symmetry, drafts, history, templates, cape and more](https://mc-engine.app/docs/editor-panels#step-5)

#### Cape

- Make a cape → paint it, start from a template or upload a picture, and see it on the model.
- Where: open **Cape** first, then it shows.
- Also called: cape maker, make a cape.
- Full guide: [Side panels: symmetry, drafts, history, templates, cape and more](https://mc-engine.app/docs/editor-panels#step-6)

#### Upload a cape or picture

- Edit cape → Upload cape or picture (PNG, JPG, WebP up to 2 MB, GIF up to 5 MB).
- Crop it, pick Whole cape file / Picture on the cape / Picture on the wings and the size, then Use this.
- Where: open **Cape** first, then it shows.
- Also called: upload cape, cape picture, cape image, crop cape, import cape, cape png, cape jpg.
- Full guide: [Side panels: symmetry, drafts, history, templates, cape and more](https://mc-engine.app/docs/editor-panels#step-6)

#### HD cape size (128×64 – 512×256)

- Edit cape → Cape size: 64×32 is normal, the bigger sizes paint finer detail.
- Switch any time — going smaller and back up brings the full detail back. Brush sets the pencil size, Zoom makes the picture bigger.
- Where: open **Cape** first, then it shows.
- Also called: hd cape, cape size, cape resolution, 512x256, 256x128, 128x64, high resolution cape, cape brush, cape zoom.
- Full guide: [Side panels: symmetry, drafts, history, templates, cape and more](https://mc-engine.app/docs/editor-panels#step-6)

#### Moving GIF cape

- Upload a moving GIF and tick "Keep it moving" — it plays on the cape or elytra in 3D and in animated GIF / video exports.
- What you paint goes on every frame. Minecraft capes can't move, so PNG downloads use the first frame.
- Where: open **Cape** first, then it shows.
- Also called: gif cape, animated cape, moving cape, animated elytra, cape animation.
- Full guide: [Side panels: symmetry, drafts, history, templates, cape and more](https://mc-engine.app/docs/editor-panels#step-6)

#### Download the cape (PNG, HD or moving GIF)

- Edit cape → Download cape PNG at 64×32 or HD; a moving cape also has Moving GIF.
- Upload / Export → "Include my cape" puts it in the Java .zip or the Bedrock .mcpack.
- Where: open **Cape** first, then it shows.
- Also called: download cape, save cape, export cape, cape gif download, cape zip, cape mcpack.
- Full guide: [Side panels: symmetry, drafts, history, templates, cape and more](https://mc-engine.app/docs/editor-panels#step-6)

#### Character builder

- Pick skin tone, face, hair, hat, top, bottom and shoes in your colours — or press Random.
- Use this skin replaces the whole skin (Undo brings it back).
- Where: open **Templates & stamps** first, then it shows.
- Also called: make a character, pick hair, outfit, avatar maker, random skin, skin creator.
- Full guide: [Side panels: symmetry, drafts, history, templates, cape and more](https://mc-engine.app/docs/editor-panels#step-3)

#### Elytra (wear cape as wings)

- In Cape, switch "Cape / Elytra" to see your cape picture as elytra wings on the 3D model.
- Where: open **Cape** first, then it shows.
- Also called: elytra, wings, cape wings.
- Full guide: [Side panels: symmetry, drafts, history, templates, cape and more](https://mc-engine.app/docs/editor-panels#step-6)

#### Paint the cape in 3D

- Edit cape → paint straight on the 3D model next to the flat picture (left mouse paints, right mouse turns, wheel zooms; phone: one finger paints, two turn).
- For elytra, "Open wings" spreads them so both sides are easy to paint.
- Where: open **Cape** first, then it shows.
- Also called: cape 3d, draw on cape, paint elytra, open wings.
- Full guide: [Side panels: symmetry, drafts, history, templates, cape and more](https://mc-engine.app/docs/editor-panels#step-6)

#### Starter templates

- Starter Steve (classic arms), Starter Alex (slim arms) or a blank body in your skin tone.
- These replace the whole skin; Steve and Alex switch to their own model.
- Where: open **Templates & stamps** first, then it shows.
- Also called: starter steve, starter alex, blank body, start from, template.
- Full guide: [Side panels: symmetry, drafts, history, templates, cape and more](https://mc-engine.app/docs/editor-panels#step-3)

#### Clothing templates

- T-shirt, long sleeves, hoodie, pants, shorts, shoes, belt, gloves or a cap — painted in your colour.
- Where: open **Templates & stamps** first, then it shows.
- Also called: t-shirt, long sleeves, hoodie, pants, shorts, shoes, belt, gloves, cap, clothes.
- Full guide: [Side panels: symmetry, drafts, history, templates, cape and more](https://mc-engine.app/docs/editor-panels#step-3)

#### Hair templates

- Short, fringe, side part, spiky, bob, long, ponytail or buzz cut — painted in your colour, already shaded.
- Where: open **Templates & stamps** first, then it shows.
- Also called: short, fringe, side part, spiky, bob, long hair, ponytail, buzz cut, hairstyle.
- Full guide: [Side panels: symmetry, drafts, history, templates, cape and more](https://mc-engine.app/docs/editor-panels#step-3)

#### Hair shading tip

- A short how-to for shading hair so it looks less flat.
- Where: open **Templates & stamps** first, then it shows.
- Also called: shade hair, hair tips.
- Full guide: [Side panels: symmetry, drafts, history, templates, cape and more](https://mc-engine.app/docs/editor-panels#step-7)

#### Stamps (eyes, mouths…)

- Pick eyes, mouths, brows, hair or extras in a style (Classic, Big, Anime, Happy, Sleepy, Glowing, Steve, Alex).
- Extras → Steve face / Alex face puts their whole face on. Click the skin, or use "Put on face".
- Where: open **Templates & stamps** first, then it shows.
- Also called: eyes, mouths, brows, extras, anime, happy, sleepy, glowing, big eyes, alex face, alex eyes, alex stamp, steve face, steve eyes, steve stamp.
- Full guide: [Side panels: symmetry, drafts, history, templates, cape and more](https://mc-engine.app/docs/editor-panels#step-3)

#### Reference image

- Load image puts a picture beside the canvas to copy from (up to 15 MB). It stays on your device.
- Where: open **Reference image** first, then it shows.
- Also called: picture beside, trace, reference, load image.
- Full guide: [Side panels: symmetry, drafts, history, templates, cape and more](https://mc-engine.app/docs/editor-panels#step-4)

#### Skin check

- Checks the skin for common problems, like see-through pixels where Minecraft needs solid ones.
- Also called: problems, transparent, missing pixels, errors.
- Full guide: [Side panels: symmetry, drafts, history, templates, cape and more](https://mc-engine.app/docs/editor-panels#step-4)

#### More adjustments

- Sliders for opacity, brightness, contrast, saturation, highlights, hue, shadows and gamma of the skin.
- Also called: brightness, contrast, saturation, highlights, shadows, hue, gamma, colour correction.
- Full guide: [Side panels: symmetry, drafts, history, templates, cape and more](https://mc-engine.app/docs/editor-panels#step-5)

#### Invert colours

- Turns every colour into its opposite (in More adjustments).
- Where: open **More adjustments** first, then it shows.
- Also called: negative, opposite colours.
- Full guide: [Side panels: symmetry, drafts, history, templates, cape and more](https://mc-engine.app/docs/editor-panels#step-5)

### Tool settings (side panel)

#### Fill → Tolerance

- 0 fills only the exact same colour; higher also fills similar colours.
- Shows in the side panel when Fill is picked.
- Where: open **Bucket** first, then it shows.
- Also called: bucket tolerance, similar colours.
- Full guide: [Minecraft skin editor tools explained (with shortcut keys)](https://mc-engine.app/docs/editor-tools#step-7)

#### Fill → Everywhere

- Recolours every matching pixel on the whole skin, not just the touching area.
- Where: open **Bucket** first, then it shows.
- Also called: replace colour, recolour all, global fill.
- Full guide: [Minecraft skin editor tools explained (with shortcut keys)](https://mc-engine.app/docs/editor-tools#step-7)

#### Shade → Darken / Lighten, Strength

- Darken or lighten, and Strength = how much each pass changes the pixel.
- Where: open **Shade** first, then it shows.
- Also called: darker, lighter, cooler, warmer, strength.
- Full guide: [Minecraft skin editor tools explained (with shortcut keys)](https://mc-engine.app/docs/editor-tools#step-7)

#### Noise → Variation

- How far the random shades go from your colour.
- Where: open **Noise** first, then it shows.
- Also called: random amount, texture strength.
- Full guide: [Minecraft skin editor tools explained (with shortcut keys)](https://mc-engine.app/docs/editor-tools#step-7)

#### Fade → bands, dither, keep empty

- Smooth, or 2–8 flat bands; dither checker-mixes the band edges; "keep empty" only colours painted pixels.
- Where: open **Gradient** first, then it shows.
- Also called: gradient settings, smooth fade, flat bands, pixel art, dither.
- Full guide: [Minecraft skin editor tools explained (with shortcut keys)](https://mc-engine.app/docs/editor-tools#step-7)

#### Stamp → Put on face

- Puts the chosen stamp at its usual spot on the face.
- Where: open **Stamp** first, then it shows.
- Also called: place stamp, auto place.
- Full guide: [Minecraft skin editor tools explained (with shortcut keys)](https://mc-engine.app/docs/editor-tools#step-7)

#### Select → Free Select, Invert, Fill, Clear

- Free Select paints the exact pixels on the 3D model. Invert / Fill / Clear change or remove the selection.
- Where: open **Select** first, then it shows.
- Also called: free select, invert selection, fill selection, clear selection.
- Full guide: [Minecraft skin editor tools explained (with shortcut keys)](https://mc-engine.app/docs/editor-tools#step-5)

### 3D view (shared by Editor, Pose and Repair)

#### Background colour

- The small squares next to the grid button change the 3D background.
- Also called: bg, background, checker, dark, black, white.
- Full guide: [The top bar: 2D / 3D view, HD size, undo and model](https://mc-engine.app/docs/editor-top-bar#step-4)

#### Grid floor

- The grid button shows or hides the floor under the 3D model.
- Also called: floor, ground, front marker.
- Full guide: [The top bar: 2D / 3D view, HD size, undo and model](https://mc-engine.app/docs/editor-top-bar#step-4)

#### Pose on / off

- The little figure button turns the model’s pose on or off.
- Also called: stand, figure, walking.
- Full guide: [The top bar: 2D / 3D view, HD size, undo and model](https://mc-engine.app/docs/editor-top-bar#step-4)

#### Armor preview

- The shield button puts armor on the 3D model: a full set or each piece, in any material.
- Only a preview — armor is never painted into the skin.
- Also called: armor, armour, helmet, chestplate, leggings, boots, diamond, netherite, iron, gold, leather.
- Full guide: [The top bar: 2D / 3D view, HD size, undo and model](https://mc-engine.app/docs/editor-top-bar#step-4)

#### Classic / Slim

- Classic = 4-pixel arms (Steve), Slim = 3-pixel arms (Alex).
- Also called: arm width, alex, steve.
- Full guide: [The top bar: 2D / 3D view, HD size, undo and model](https://mc-engine.app/docs/editor-top-bar#step-4)

#### Reset Camera

- Puts the 3D view back to the start. Drag to turn the model, scroll to zoom.
- Also called: camera, view, rotate back.
- Full guide: [The top bar: 2D / 3D view, HD size, undo and model](https://mc-engine.app/docs/editor-top-bar#step-4)

## Step-by-step guides on this page

- [How to make a Minecraft skin: your first skin in 5 minutes](#how-to-make-a-minecraft-skin-your-first-skin-in-5-minutes)
- [Minecraft skin editor tools explained (with shortcut keys)](#minecraft-skin-editor-tools-explained-with-shortcut-keys)
- [The top bar: 2D / 3D view, HD size, undo and model](#the-top-bar-2d--3d-view-hd-size-undo-and-model)
- [Minecraft skin layers: base, overlay (hat & jacket) and body parts](#minecraft-skin-layers-base-overlay-hat--jacket-and-body-parts)
- [Colours, brush size, opacity and palettes](#colours-brush-size-opacity-and-palettes)
- [Image to colour palette: get the colours of any picture](#image-to-colour-palette-get-the-colours-of-any-picture)
- [Side panels: symmetry, drafts, history, templates, cape and more](#side-panels-symmetry-drafts-history-templates-cape-and-more)
- [Make the editor yours: toolbar, tips, panels and layout](#make-the-editor-yours-toolbar-tips-panels-and-layout)
- [How to make an HD Minecraft skin (128x128, 256x256 or 512x512)](#how-to-make-an-hd-minecraft-skin-128x128-256x256-or-512x512)
- [Minecraft skin template explained (64x64 layout)](#minecraft-skin-template-explained-64x64-layout)
- [How to get a Minecraft skin from a username](#how-to-get-a-minecraft-skin-from-a-username)
- [Keyboard shortcuts](#keyboard-shortcuts)
- [How to make a Minecraft skin on your phone (Android & iPhone)](#how-to-make-a-minecraft-skin-on-your-phone-android--iphone)

## How to make a Minecraft skin: your first skin in 5 minutes

From an empty editor to a skin you can wear in Minecraft: pick a model, choose colours, paint, check it in 3D and download it.

*On the website, with screenshots: https://mc-engine.app/docs/first-skin*

### Step 1 · Open the Editor

Click **Editor** (the brush icon) in the menu on the left. You don't need an account: your work is saved in your browser automatically.

The editor has four areas. You will use all of them in the next steps.

1. **Tool strip**: pencil, eraser, bucket, shapes and more.
2. **Top bar**: view (2D / 3D), skin size, undo / redo, model type.
3. **Canvas**: where you paint, on the flat skin or right on the 3D model.
4. **Side panel**: brush size, layers, body parts, palette and more.

### Step 2 · Start from a skin, or from scratch

Already have a skin or a picture? Press **Upload** in the side panel and choose the file.

Want a clean start? Open **Templates & stamps** in the side panel and pick **Starter Steve**, **Starter Alex** or **Blank body**.

1. **Upload** opens a skin or any picture. **Export** goes to the download page.

> 💡 You can also type a Minecraft player name in **Import skin** to load their current skin.

### Step 3 · Choose Steve or Alex

Minecraft has two body shapes. **Steve** (Classic) has arms 4 pixels wide, **Alex** (Slim) has arms 3 pixels wide.

Pick the one you want under **Player model**. When you put the skin in Minecraft, choose the same one.

The editor starts on **Steve** with the Steve skin ready to edit, and remembers which model you picked. Picking **Alex** loads the Alex skin and **Steve** the Steve skin — while the canvas is empty or still holds the untouched starter skin, with nothing to undo. A skin you made (or could undo back to) is never replaced; use **Starter Steve / Starter Alex** for that.

1. **Steve** = Classic arms, **Alex** = Slim arms.

### Step 4 · Pick a colour and paint

Click the big round **colour button** at the bottom of the tool strip and choose a colour.

Select the **Pencil** (key **P**) and click on the model or the flat skin to paint pixels. Hold the mouse button and drag to paint many pixels.

Made a mistake? Press **Ctrl + Z** to undo.

1. **Pencil**: paints one pixel (or more with a bigger brush).
2. **Colour button**: your current colour. The small dots above it are recent colours.

> 💡 Turn on **Mirror X** (key **F**) to paint the left and right side at the same time.

### Step 5 · Check every side in 3D

In **3D Edit**, drag on an empty part of the canvas to turn the model and scroll to zoom. Press **Reset Camera** to go back to the start view.

Switch to **2D Edit** to see the whole flat skin at once. Each body part has 6 faces: front, back, left, right, top and bottom.

1. The **skin texture**: this flat picture is exactly what Minecraft wraps around the model.

### Step 6 · Download it

Press **Export** in the side panel (or **Upload** in the top bar) — the **Upload / Export** window opens. In **2 · Export**, pick **Java Edition** or **Bedrock Edition**, keep **Only download** chosen, then press **Download**.

The guide **How to put a custom skin in Minecraft Java & Bedrock** shows how to wear it.

1. **Java** or **Bedrock**.
2. **Download**: a PNG for Java, a .mcpack for Bedrock.


## Minecraft skin editor tools explained (with shortcut keys)

What each button in the tool strip does — pencil, eraser, bucket, shapes, select, move, shade, noise, gradient, stamps, mirror and zoom — their settings (tolerance, replace colour, gradient bands, free select) and their keyboard keys.

*On the website, with screenshots: https://mc-engine.app/docs/editor-tools*

### Step 1 · The tool strip

The tools are in the strip on the left of the editor, from top to bottom. Hover over any tool to see its name and key, like the Pencil tip in the picture.

Only one tool is active at a time; it is shown in green.

1. **Drawing tools**: Pencil, Eraser, Bucket, Eyedropper, Line, Rectangle, Circle, Select, Move.
2. **Effect tools**: Shade, Noise, Gradient, Stamp.
3. **Mirror X, Mirror Y and Grid**.
4. **Zoom in, zoom out** and Reset camera / Fit to view.
5. **Colours**: recent colours and your current colour.

### Step 2 · Paint, erase and fill

**Pencil (P)** paints in your colour. Change how big it is with **Size** in the side panel, and how see-through with **Opacity**.

**Eraser (E)** makes pixels transparent again. In the side panel, **Eraser mode** has **Erase** and **Restore Original**: after you upload a skin or picture, Restore Original brings back the uploaded pixels instead of a hole.

**Bucket (B)** fills a whole area of the same colour at once.

**Eyedropper (I)** copies a colour from the skin: click any pixel and it becomes your colour.

### Step 3 · Lines and shapes

**Line (L)**, **Rectangle (R)** and **Circle (C)**: press where the shape starts, drag, and let go where it ends.

Shapes are great for belts, stripes, buttons and eyes.

### Step 4 · Select and Move

**Select (S)** marks an area. After that, every tool only changes pixels inside it, so you can't paint over the edge by mistake. Click Select again to remove the selection.

With a selection you can fill it, copy (**Ctrl + C**), cut (**Ctrl + X**), paste (**Ctrl + V**), flip or rotate it.

**Move (M)**: draw a box around some pixels, then drag them to a new place.

### Step 5 · More ways to select

When **Select** is on, the side panel shows **Selection** buttons:

**Free Select**: instead of a box between two points, drag on the 3D model to paint exactly the pixels you want selected — any mix of parts and faces in one selection.

**Invert**: swaps selected and unselected pixels across the whole skin. **Fill Selection** paints every selected pixel in your colour. **Clear Selection** removes the selection so tools work everywhere again.

Click without dragging to select a single pixel. The small arrow next to **Selection** shows a short tip for the tool.

### Step 6 · Shade, Noise, Gradient and Stamp

**Shade (H)** makes pixels a bit darker each time you paint over them. Hold **Shift** to make them lighter instead. Perfect for folds in clothes and shadows under hair.

**Noise (N)** paints random shades of your colour, so a flat area looks like fabric, stone or fur.

**Gradient (D)** fades from your first colour to your second colour. Drag across the area. Set the second colour next to the colour button, and press **X** to swap the two.

**Stamp (T)** adds ready-made eyes, mouths, brows and more with one click.

### Step 7 · Tool settings in the side panel

Many tools have extra settings at the top of the side panel. They change when you pick another tool.

**Shade**: choose **Darken** or **Lighten**, and set the **Strength**. Each pixel changes once per stroke — lift the mouse and paint again to go further.

**Noise**: **Variation** sets how different the random shades are. Low = subtle fabric, high = rough stone or grass.

**Bucket**: **Tolerance** (0 = only the exact same colour, higher = similar colours get filled too). Switch **Connected area only** to **Everywhere (replace colour)** to recolour every matching pixel on the whole skin at once — great for changing a shirt or hair colour everywhere.

**Gradient**: shows your two colours and a swap button. **Bands** picks **Smooth** or 2–8 flat colour bands (pixel-art style). With bands, **Dither between bands** mixes the edges in a checker pattern. **Keep empty pixels empty** only colours pixels that are already painted. The gradient fills the selection if there is one, otherwise the part (or the face you start on).

**Stamp**: pick a stamp, then click the canvas or model — or press **Put on face** to place it at its usual spot. Pixels marked "P" use your colour.

### Step 8 · Mirror, grid and zoom

**Mirror X (F)** paints the left and right side at the same time. **Mirror Y (Y)** paints top and bottom at the same time.

**Grid (G)** shows or hides the lines between pixels.

**Zoom in (+)** and **Zoom out (−)** make the pixels bigger or smaller. In 3D they move the camera.

### All tools and keys

| Option | Key | What it does |
|---|---|---|
| Pencil | `P` | Draw pixels in your colour. |
| Eraser | `E` | Erase pixels back to transparent. |
| Bucket | `B` | Fill a same-colour area at once. |
| Eyedropper | `I` | Click the skin to pick its colour. |
| Line | `L` | Drag to draw a straight line. |
| Rectangle | `R` | Drag to draw a box outline. |
| Circle | `C` | Drag to draw a circle outline. |
| Select | `S` | Pick the area tools can change. |
| Move | `M` | Box some pixels, then drag them. |
| Shade | `H` | Darken or lighten pixels — Shift flips. |
| Noise | `N` | Paint random shades for a textured look. |
| Gradient | `D` | Drag to fade between your two colours. |
| Stamp | `T` | Click to add eyes, mouths and more. |
| Mirror X | `F` | Paint left and right sides at once. |
| Mirror Y | `Y` | Paint top and bottom at once. |
| Grid | `G` | Show or hide the pixel grid. |
| Swap colours | `X` | Swap your first and second colour. |
| Zoom in / out | `+ / −` | Bigger or smaller pixels; closer or further camera in 3D. The number between them is the pixel size. |
| Fit / Reset camera |  | Show the whole texture (2D) or put the 3D view back to the start. |

### Tool settings

| Option | Key | What it does |
|---|---|---|
| Shade → Darken / Lighten, Strength |  | Direction and how much each pass changes the pixel. |
| Noise → Variation |  | How far the random shades go from your colour. |
| Bucket → Tolerance |  | 0 = exact colour only; higher fills similar colours too. |
| Bucket → Everywhere (replace colour) |  | Recolour every matching pixel on the whole skin. |
| Gradient → Bands |  | Smooth, or 2–8 flat bands. |
| Gradient → Dither between bands |  | Checker-mix the band edges. |
| Gradient → Keep empty pixels empty |  | Only colour pixels that are already painted. |
| Stamp → Put on face |  | Place the stamp at its usual spot. |
| Select → Free Select |  | Paint the exact pixels to select on the 3D model. |
| Select → Invert / Fill / Clear Selection |  | Swap, fill or remove the selection. |


## The top bar: 2D / 3D view, HD size, undo and model

Switch between 2D, 3D and side-by-side, make HD 128×128, 256×256 or 512×512 skins, undo / redo, compare before and after, and change the background.

*On the website, with screenshots: https://mc-engine.app/docs/editor-top-bar*

### Step 1 · Choose how you see the skin

Click the first button in the top bar (it shows the current view) to open the view menu.

**2D Edit** shows the flat skin texture, **3D Edit** lets you paint straight on the model, and **2D + 3D** shows both side by side.

1. The **view button**.
2. The **view menu**: 2D Edit, 3D Edit, 2D + 3D.

> 💡 Beginners: paint in **3D Edit** — you see exactly where each pixel lands on the body.

### Step 2 · Make an HD skin

The second button sets the skin size: **64×64** (normal), **128×128**, **256×256** or **512×512** (HD).

Java Edition uses 64×64. Bedrock also accepts 128×128. HD skins give you more detail, like a real face.

1. **Skin size**: 64×64, 128×128, 256×256 or 512×512.

### Step 3 · Undo, redo, clear, repair and compare

The next buttons are: **Undo** (Ctrl + Z), **Redo** (Ctrl + Y), **Clear part** (the red bin — empties the selected body part), **Repair** (sends the skin to Skin Repair) and **Before / after** (compare with how the skin looked when you opened the editor).

Every change is also listed in the **History** panel, where you can click any step to go back to it.

1. **Undo · Redo · Clear part · Repair · Before / after**.

### Step 4 · Background, grid floor, pose, model and camera

The round dots change the **background colour** of the 3D view. The grid button shows or hides the **floor grid**, and the person button turns the walking **animation** on or off.

**Classic / Slim** switches the model, and **Reset Camera** puts the 3D view back to the start.

The **shield** button is the **Armor preview**: put on a full set (leather, chain, iron, gold, diamond or netherite) or pick each piece — helmet, chestplate, leggings, boots. Leather takes any dye colour. It is only a preview; armor is never painted into your skin.

On the right of the top bar you always see which **part, layer and size** you are working on (for example "Body Front · base · 8×12").

1. **Background colours**.
2. **Floor grid** and **animation**.
3. **Classic / Slim** model.
4. **Reset Camera**.


## Minecraft skin layers: base, overlay (hat & jacket) and body parts

Paint hats, jackets and sleeves on the second layer, lock painting to one body part, hide parts in 3D and use extra paint layers.

*On the website, with screenshots: https://mc-engine.app/docs/layers-body-parts*

### Step 1 · Base and Overlay

Every Minecraft skin has two layers. **Base** is the body itself. **Overlay** is a second, outer layer that floats just above it — use it for hats, hair, jackets, sleeves and pants.

Switch with the **Base / Overlay** buttons under **Body parts**. Overlay pixels can be see-through, so the base shows through the gaps.

1. **Base / Overlay**: which layer you paint on.
2. **Body parts (visual)**: click a part to show or hide it in 3D — handy for painting under the arms.
3. **Head, Body, Arms, Legs, Extra**: open one to jump to a single face (Front, Back, Left…).

### Step 2 · Free Draw or locked to one part

When **Draw mode** says **Free Draw (unlocked)**, tools work anywhere on the skin.

Click it to lock: then tools only change the body part you picked, so you can't paint into the next part by mistake.

1. **Player model**: Steve or Alex.
2. **Draw mode**: Free Draw (unlocked) or locked to the part.

### Step 3 · Extra paint layers

Open **Layers** and press **Turn on layers** to paint on separate layers, for example body, clothes and details.

You can hide, fade or change one layer without touching the others. When you export, all visible layers are merged into one skin.

### Step 4 · Manage your layers

Click a layer to paint on it. The **eye** hides or shows it, and the **Opacity** slider fades the selected layer. **Double-click** a name to rename it.

The buttons under the list: **+** adds a new empty layer above, the **copy** button duplicates the layer, the **arrows** move it up or down, **Merge** joins it into the layer below and **Delete** removes it.

**Flatten** merges all visible layers into one image and turns layers off. You can undo it with **Ctrl + Z**.


## Colours, brush size, opacity and palettes

Pick colours, use shades of your colour, save your own palettes, build a palette from the skin or from any picture, and import .hex / .gpl files.

*On the website, with screenshots: https://mc-engine.app/docs/colours-palette*

### Step 1 · Brush size and opacity

At the top of the side panel, **Size** sets how many pixels the Pencil, Eraser and effect tools paint at once (1 pixel up to a big round brush).

**Opacity** makes the paint see-through: 100% is solid, lower values mix with the colour underneath.

1. **Brush**: Size buttons and the Opacity slider.

### Step 2 · Shades of your colour

Open **Palette**. The top row shows **shades of your colour** — from dark to light. Click one to use it. This is the easiest way to add shadows and highlights.

**Save all** keeps those shades in your own palette.

1. The **Palette** panel.

### Step 3 · Your own palettes

**My colours** is a list of palettes you make. **+ Colour** adds your current colour, **From skin** builds a palette from every colour in the skin, **New** starts another palette and **Rename** / **Remove** / **Delete** manage them.

**Import** loads a palette file (.hex, .gpl, .json or .txt); **.hex** and **.gpl** save your palette for other apps (like Lospec, Aseprite, GIMP or Krita).

To remove one colour, right-click it, or press **Remove** and click the colours you don't want.

### Step 4 · Palette from a picture

Want the colours of a picture, a character or a photo? Open **Reference image**, press **Load image**, then press **Palette from this image**.

MC-ENGINE finds the main colours of the picture (up to 16) and saves them as a new palette named after the file. Click a colour under the button to paint with it, or find the palette later in **Palette → My colours**.

> 💡 The guide **Image to colour palette** shows this step by step.


## Image to colour palette: get the colours of any picture

Load any picture as a reference image and turn its main colours into a palette you can paint with — perfect for matching a character, a logo or a photo.

*On the website, with screenshots: https://mc-engine.app/docs/palette-from-image*

### Step 1 · Load the picture

In the editor's side panel, open **Reference image** and press **Load image**. Pick any picture (up to 15 MB). It stays on your device — nothing is uploaded.

1. **Reference image**.

### Step 2 · Make the palette

Press **Palette from this image**. The picture is shrunk, alike colours are grouped together and the most-used ones come first — up to 16 colours.

They are saved as a new palette called "From <file name>". The colours also show right under the button: click one to paint with it.

### Step 3 · Use it

Open **Palette → My colours** to find the new palette any time. Add, remove or rename colours there, or download it as **.hex** / **.gpl** for other apps.

Tip: use **Floating** or **Trace** in Reference image to keep the picture in view while you paint with its colours.


## Side panels: symmetry, drafts, history, templates, cape and more

Copy a limb to the other side, load starter skins and clothing, add face stamps, use a reference picture, find hidden pixels, adjust colours, keep drafts and make a cape.

*On the website, with screenshots: https://mc-engine.app/docs/editor-panels*

### Step 1 · Where the panels are

Scroll down the side panel of the editor. Every section opens and closes with a click on its name.

1. **Import skin**: type a Minecraft Java player name and press **Import** to load their skin (and cape). Your current skin is kept in Drafts.
2. **Symmetry, Palette, Layers, Drafts, Cape, History, Templates & stamps, Reference image, Skin check**.
3. **Adjustments**: brightness and more for the whole skin.

### Step 2 · Symmetry: copy a limb

Painted one arm and want the other one the same? Open **Symmetry**, choose **Base**, **Overlay** or **Both**, then **Right → Left** or **Left → Right** for the arms or legs.

**Flip part upside down** turns the selected part over. **Mirror X / Mirror Y** are here too.

1. The **Symmetry** panel.

### Step 3 · Templates & stamps

**Character builder** makes a whole skin from parts: skin tone, eyes, brows, mouth, extras (beard, glasses, freckles…), hair, hat, top, bottom and shoes — each in your own colour, with a live 3D preview and a **Random** button. **Use this skin** puts it in the editor (Undo brings your old skin back; it is kept in Drafts too).

**Starter skins** replace the whole skin with Starter Steve, Starter Alex or a Blank body. **Starter Steve** is the Steve skin with classic arms and **Starter Alex** the Alex skin with slim arms; each switches to its own model.

**Clothing in your colour** adds a T-shirt, long sleeves, hoodie, pants, shorts, shoes, belt, gloves or a cap — in your current colour.

**Face stamps** add eyes (Classic, Big, Anime, Happy, Sleepy, Glowing, Steve, Alex), mouths (including Steve and Alex), brows, hair (including Steve hair and the Alex fringe) and extras with one click. **Extras → Steve face / Alex face** puts their whole face on the head; the Steve and Alex stamps keep their own colours.

1. **Starter skins**.
2. **Clothing** in your colour.
3. **Face stamps**: eyes, mouths, brows, extras.
4. **Reference image**.
5. **Skin check**.

### Step 4 · Reference image and Skin check

**Reference image**: press **Load image** to add a picture (a character, a photo, another skin) to look at while you paint. It stays on your device. **Change** swaps it and **×** removes it.

Choose where it shows: **Here** (in the panel), **Floating** (a small window over the corner of the canvas — works in 3D too; drag it to move, drag the corner to resize, or set **Size**) or **Trace** (laid faintly over the 2D texture so you can copy it; set how see-through with **See-through**).

**Palette from this image** turns the picture's main colours into a new palette — see the guide **Image to colour palette**.

**Skin check** lists what Minecraft will show differently from the editor, each with a one-click fix:

• **See-through overlay pixels** (half-transparent hat / jacket pixels): **Make solid** or **Remove**. • **Holes in the base layer** (they show up black in game): **Fill from neighbours**. • **Pixels outside the skin layout** (never shown in game): **Clear them**.

**Show** selects those pixels, so they light up on the 3D model and only they can be edited until you clear the selection. When everything is fine it says **Looks good**.

### Step 5 · Drafts, history and adjustments

**Drafts**: your skin is auto-saved as a draft. Click the restore arrow to go back to one (your current skin is kept as a draft too), or delete drafts you don't need.

**History**: every change shows up here; click a step to jump back to it. The first row goes back to before your first step. Undone steps stay greyed out — click one to redo up to there.

**Adjustments**: Brightness, Contrast, Saturation, Highlights, Hue, Shadows, Gamma and **Invert Colors** change the whole skin at once. Press **More adjustments** to see them all.

### Step 6 · Make a cape

Open **Cape** and press **Make a cape** (or **Edit cape**) to open the **Cape editor**. Paint on the flat picture or straight on the 3D model next to it — left mouse paints, right mouse turns, the wheel zooms; on a phone switch to **3D model**, one finger paints and two fingers turn. **Back / Side / Front** turn the model for you.

Tools: **Pencil**, **Eraser**, **Fill** (stays inside one part), **Pick a colour**, **Brush** size and **Undo**. **Zoom** (1×–4×) makes the flat picture bigger. Only the outlined parts show in game: Outside, Inside, Edges, Top, Bottom and the Elytra. **Same on both sides** copies what you paint on the outside to the inside (flipped), and the other way round.

**Cape size**: 64×32 is the normal Minecraft size; **128×64**, **256×128** and **512×256** are HD for finer detail (HD capes work in OptiFine-style launchers and mods; Bedrock packs and the 64×32 download get a shrunk copy). Switch any time — going smaller and back up brings the full detail back, with what you painted on top.

**Start from** gives a ready cape in your colour and your second colour: **Solid**, **Gold trim**, **Stripe**, **Fade**, **Checker** or **Shaded**.

**Upload cape or picture** loads a cape file or any picture — PNG, JPG or WebP up to 2 MB, GIF up to 5 MB. Crop it, choose where it goes (**Whole cape file**, **Picture on the cape** or **Picture on the wings**) and its size; ★ marks the most detail your crop has.

**Moving GIFs**: tick **Keep it moving** and the GIF plays on the cape or elytra in every 3D preview and in animated GIF / video exports. What you paint goes on every frame. Minecraft capes can’t move, so PNG downloads and packs use the first frame.

**Download cape PNG** saves 64×32 or a sharp HD copy (128×64 to 512×256 — the elytra is in the same file); a moving cape also has **Moving GIF** downloads. **Show on the model** hides or shows the cape and **Remove cape** deletes it. Vanilla Minecraft only shows official capes — custom capes work in launchers and mods that support them.

In the **Upload / Export** window (**Upload** in the top bar), **Include my cape** adds it to the download: Java gives a .zip with the skin, the cape PNG (and the moving GIF), Bedrock puts it inside the .mcpack (64×32). **More** (in the **2 · Export** title bar) has **Cape PNG**, **Moving cape** and **Cape picture** — your skin from behind wearing it.

**Wear as: Cape / Elytra** shows the same picture as a cape or as **elytra wings** — the wings use the Elytra part. Both wings share one picture, so painting one shows on the other (mirrored), like in Minecraft. **Open wings** spreads them so the inner side is easy to reach, and **Copy cape design to elytra** starts empty wings with your cape.

### Step 7 · Hair shading tip

In **Templates & stamps**, open **Hair shading tip** for a quick how-to: use 3 shades of one colour (light, middle, dark), light on top where light hits, dark at the tips and in thin 1–2 pixel strands.

The **Shade** tool (Darken / Lighten) or the **Hair** face stamps make the strands quickly. For 3D volume, paint a few hair pixels on the hat layer too.


## Make the editor yours: toolbar, tips, panels and layout

Hide and reorder tools, show tool names, change shortcut keys, replay the editor tour, show part names, hide the side panel and resize or reset the panels.

*On the website, with screenshots: https://mc-engine.app/docs/editor-workspace*

### Step 1 · Customise the toolbar

At the bottom of the tool strip, press **Edit** (the sliders button) to open **Toolbar**.

Tick the tools you want to see and use the **arrows** to change their order. **Mirror X**, **Mirror Y**, **Grid** and the **Zoom buttons** can be hidden too. Hidden tools still work with their keys.

**Show names under the tools** adds a small label to every button. **Reset** brings back every button in the original order. **Change shortcuts** opens the key settings.

### Step 2 · Tips and part names

The **?** button on the right of the top bar (**Show tips**) replays the short editor tour: tools, 2D / 3D, the canvas, colours and the side panel. It also plays once on your first visit.

The **tag** button (**Part names**, in 2D views) writes the part name and Front / Back / Left / Right / Top / Bottom on every face of the flat skin.

The **panel** button next to it hides or shows the side panel (properties), so the canvas gets more room.

### Step 3 · Resize the panels

Drag the edges between the canvas and the panels — and between 2D and 3D in **2D + 3D** — to make them bigger or smaller. Double-click a handle to reset it.

When you changed something, a **Reset layout** button appears in the top bar: it puts the panel sizes and the 2D / 3D split back to normal.

Next to the zoom buttons you see the **pixel size** (for example 12px): how big one skin pixel is on screen right now.


## How to make an HD Minecraft skin (128x128, 256x256 or 512x512)

Switch the editor to 128x128, 256x256 or 512x512 for more detail, paint or import in HD, and learn where HD skins work in Java and Bedrock.

*On the website, with screenshots: https://mc-engine.app/docs/hd-skin*

### Step 1 · Pick the skin size

In the editor's top bar, click the size button (it shows **64×64**) and choose **128×128**, **256×256** or **512×512**. Each body face now has 2×, 4× or 8× as many pixels across, so you can paint finer eyes, hair and clothes.

An HD skin file you upload keeps its own size (a 512×512 file opens as 512×512).

1. **Skin size**: 64×64 (normal), 128×128, 256×256 or 512×512 (HD).

### Step 2 · Start an HD skin from a photo or picture

HD shines with pictures. In **Repair → Photo to Skin**, choose **128** or **256** under Model & size; the photo is redrawn at the new size, so the face keeps its detail.

In **Repair**, the 64 / 128 / 256 buttons do the same when you place each face from your own picture.

1. **Model & size**: Classic / Slim and 64 / 128 / 256.

### Step 3 · Where HD skins work

**Bedrock** (phone, tablet, Windows) accepts **128×128** skins — download a **.mcpack** from Export.

**Java** only takes **64×64** skins in the official launcher. Keep a 64×64 copy for Java, or use HD in mods and launchers that support it.

**512×512** is for mods and HD skin launchers, and for very fine detail while you paint. A .mcpack is saved at 128×128, and the gallery takes skins up to 100 KB.

> 💡 Painting in HD but playing Java? Switch the size back to 64×64 before you export.


## Minecraft skin template explained (64x64 layout)

What every part of the flat 64x64 Minecraft skin template is — head, hat, body, arms, legs and their outer layers — and how to start from a blank template.

*On the website, with screenshots: https://mc-engine.app/docs/skin-template*

### Step 1 · The flat skin is a map of the 3D body

A Minecraft skin is a 64×64 PNG. Minecraft cuts it into boxes and folds them around the head, body, arms and legs. Switch the editor to **2D Edit** to see it, and turn on **part names** in the top bar to label every box.

Each body part has 6 faces — top, bottom, front, back, right and left — laid out next to each other.

1. **Head** (top-left quarter of the top band).
2. **Hat** — the head's outer layer, right next to it.
3. **Right leg, body, right arm** (second band).
4. **Their outer layers**: pants, jacket and sleeve (third band).
5. **Left leg and left arm**, each with its outer layer beside it (bottom band).

### Step 2 · Steve and Alex arms

Steve (Classic) arms are 4 pixels wide; Alex (Slim) arms are 3 pixels wide, so an Alex arm box is a little narrower and the last column of it is unused.

**Skin check** in the side panel warns you about pixels painted in unused parts of the template — they never show in the game.

### Step 3 · Start from a blank template

Open **Templates & stamps** and pick **Blank body**, **Starter Steve** or **Starter Alex**. Add clothing in your colour and face stamps, then paint the rest.

HD templates work the same way at 128×128 or 256×256 — every box is just 2× or 4× bigger.

1. **Starter skins**: Starter Steve, Starter Alex, Blank body.
2. **Clothing** in your colour.


## How to get a Minecraft skin from a username

Load any Minecraft Java player's current skin (and cape) by their username, then edit it, remix it or download it.

*On the website, with screenshots: https://mc-engine.app/docs/skin-from-username*

### Step 1 · Open Import skin

In the editor's side panel (on a phone: the **More** button), open **Import skin**.

1. **Import skin**: a box for the player name and an **Import** button.

### Step 2 · Type the player name and import

Type a **Minecraft Java** username (for example "Notch") and press **Import**. Their current skin — and cape, if they have one — loads into the editor.

The skin you were working on is kept in **Drafts**, so nothing is lost.

> 💡 Only Java Edition names work here. Please only re-share someone else's skin with their permission — on MC-ENGINE, posting another person's skin as your own leads to a copyright strike.

### Step 3 · Skin history

Under the box, **Skin history** shows the skins MC-ENGINE has seen this player wear, newest first (the current one has a coloured border). Click one to load it.

Minecraft itself keeps no skin history, so the list starts the first time anyone looks the player up here, and grows each time they are looked up after changing skins.

### Step 4 · Edit, remix or download it

Change anything you like with the drawing tools, then press **Export**, choose Java or Bedrock and **Download**.


## Keyboard shortcuts

Every key for the editor and for moving between pages — and how to change them to your own keys.

*On the website, with screenshots: https://mc-engine.app/docs/shortcuts*

### Step 1 · Switch pages with number keys

**1** Home · **2** or **5** Upload / Export window · **3** Editor · **4** Preview · **6** Settings · **7** Docs. (They don't work while you type in a box.)

### Step 2 · Change a key

Open **Settings → Shortcuts** (or **Change shortcuts** in the editor's toolbar settings). Click a key, then press the new one. **Esc** cancels and **Backspace** clears it.

Every single-key editor shortcut can be changed. Ctrl shortcuts (like Ctrl + Z) and Delete are listed but fixed. **Reset** puts all keys back to the original ones.


## How to make a Minecraft skin on your phone (Android & iPhone)

The editor, Repair, Photo to Skin and Custom Pose have phone versions. How the phone editor works, and how to download and wear your skin from a phone.

*On the website, with screenshots: https://mc-engine.app/docs/phone*

### Step 1 · The phone editor

On a phone, the Editor opens full screen: a thin top bar, the tools in one row you can scroll sideways, and the canvas below.

Tap a tool, then tap or drag on the skin. The **Brush** bar opens size and opacity. Shade, Noise, Gradient, Stamp and Mirror Y work like on a computer.

Your work is auto-saved. When you come back you see **Continue where you left off?**.

> 💡 The **More** button opens the other panels: layers, palettes, templates and hair, reference image, cape, history, Skin Check, Export, **Share link** and the tips again. The **magnifier** at the top finds any button: type what you want, then **Show me** opens the right panel and points at it — on the Editor, Custom Pose and Repair.

### Step 2 · Repair, Photo to Skin and Custom Pose on a phone

Open the menu (the three lines at the top left) and pick **Repair** or **Custom Pose**. Both open full screen like the editor: the 3D model or picture on top and the options in a panel at the bottom that you can open up for more room.

In Repair, **Photo to Skin** can take a photo straight from your phone's gallery or camera. The photo stays on your phone.

The **?** button at the top of each of these screens explains what the tool does and how it works.

### Step 3 · Download and wear the skin from your phone

Press **Upload** in the top bar, pick **Bedrock Edition** in **2 · Export** and press **Download** to get a **.mcpack**.

Then open that file: on **Android**, tap it in your Downloads; on **iPhone or iPad**, find it in the **Files** app, tap **Share** and choose **Minecraft**. Minecraft imports the skin; pick it in **Dressing Room → Classic skins**.

For **Minecraft Java** (which has no phone version), download the **Java** PNG and change your skin on the Minecraft website while logged in to your Java account, or later in the Minecraft Launcher on a computer.

> 💡 Your skin is saved in the phone's browser. To carry on on a computer, log in and save it to your account, or make a **Share link** and open it there.


---

[← All guides](../README.md#guides-for-every-tool) · [Editor](../editor/) · [Repair](../repair/) · [Pose](../pose/) · [Upload / Export](../upload-export/) · [Skins](../skins/) · [Profile](../profile/)

<sub>Made from the website's own help texts. MC-ENGINE is not an official Minecraft product and is not associated with Mojang or Microsoft.</sub>
