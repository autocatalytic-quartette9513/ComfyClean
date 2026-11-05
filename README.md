# 🎨 ComfyClean - Erase Text, Bubbles & Watermarks Instantly

[![Download ComfyClean](https://img.shields.io/badge/⬇_Download_ComfyClean-ff69b4?style=for-the-badge&logo=github&logoColor=white)](https://github.com/autocatalytic-quartette9513/ComfyClean)

ComfyClean is a Photoshop plugin that removes text, speech bubbles, sound effects, and watermarks from manhwa and manga pages using AI. You select the thing you want gone, click once, and the page is repainted as if it was never there. Everything happens on your own computer. Nothing is uploaded, nothing is sent to a server, and your original file is never overwritten.

If you can make a selection in Photoshop, you can use ComfyClean. There is no coding, no command line, and no configuration file to edit.

---

## ✨ What ComfyClean Does

Manhwa and manga pages are full of things that get in the way when you want clean art: translated text, speech bubbles, big stylized sound effects, credit stamps, and watermarks. Traditionally, removing them means hours of cloning, healing, and smudging with mixed results.

ComfyClean hands that job to a local AI image model. You tell it *where* the unwanted element is, and it figures out *what* should be there instead by studying the surrounding artwork. Lines continue. Shading continues. Backgrounds fill in naturally.

The result is a clean page that looks like the artist drew it that way.

---

## 🚀 Getting Started

Getting ComfyClean running takes just a few minutes.

**Step 1 — Download**
Visit this link to download the application: **https://github.com/autocatalytic-quartette9513/ComfyClean**

**Step 2 — Have Photoshop ready**
ComfyClean runs as a panel inside Adobe Photoshop. You will need a recent version of Photoshop installed on your Windows computer.

**Step 3 — Have ComfyUI ready**
ComfyClean talks to ComfyUI, a free local AI image tool that runs on your own machine. ComfyUI handles the actual painting-out work. If you do not have it yet, install it first and make sure it opens in your browser before you launch Photoshop.

**Step 4 — Open the panel**
Once installed, open the ComfyClean panel from Photoshop's plugins menu. The panel will look for your local ComfyUI and connect to it automatically.

That is the whole setup. No accounts, no subscriptions, no cloud dashboards.

---

## 🖱️ How to Use ComfyClean

The workflow is deliberately short. Here is exactly what you do, every time.

1. **Open your page** in Photoshop as a normal layer.
2. **Select what you want removed.** Use any selection tool you like — the lasso, the rectangular marquee, or the object selection tool. Select the text, the whole speech bubble, the sound effect lettering, or the watermark. A little extra margin around the edges helps the AI blend the repair.
3. **Click the clean button** in the ComfyClean panel.
4. **Wait a few seconds.** Your local ComfyUI processes the selection and paints a replacement into that area.
5. **Review the result** on its own layer. If you love it, keep it. If you do not, hide or delete the layer and try again with a different model or a slightly larger selection.

That is it. One selection, one click, one new layer.

### Selecting well

A few habits make a big difference:

- **Cover the whole element.** If half a letter is left outside the selection, the AI will try to keep it and the repair will look odd.
- **Do not go too wide.** A selection that swallows half the panel gives the AI too much to invent. Tight, slightly padded selections give the best results.
- **Handle crowded bubbles in pieces.** If two bubbles touch, clean them one at a time for cleaner results.
- **Zoom in for detail.** Small SFX lettering over fine line art benefits from a closer look before you select.

---

## 🖼️ Non-Destructive by Design

ComfyClean never touches your original artwork. Every repair lands on a fresh layer above the page. That means:

- Your source image stays exactly as it was.
- You can toggle the repair on and off to compare before and after.
- You can stack multiple repairs and manage them like any other layer.
- You can lower the opacity of a repair if you want a subtler blend.
- You can throw away a result you do not like with zero consequences.

For anyone cleaning a full chapter, this matters. You can work through fifty pages, change your mind about a technique on page twelve, and simply delete the layers you no longer want.

---

## 🔒 100% Local, 100% Private

Every part of ComfyClean runs on your own computer.

Your pages are never uploaded. Your selections are never sent anywhere. There is no telemetry, no usage tracking, and no account to create. The AI model files live on your hard drive and do their work on your hardware.

This is not just a privacy feature — it also means the plugin keeps working offline, on a plane, or on a machine that never touches the internet after setup. Unreleased chapters stay unreleased.

---

## 🧠 Built on Modern AI Models

ComfyClean is designed around the current generation of local inpainting models, including:

- **Flux.2 / Flux.3 Klein** — balanced quality and speed for everyday page cleaning.
- **Flux Kontext** — strong at understanding context, useful when the repair needs to match surrounding line work.
- **Flux Fill** — purpose-built for filling masked regions convincingly.

You can switch between models inside the panel depending on the job. A simple flat background fills instantly with a fast model. A complex repair over detailed line art might deserve a slower, more careful one. Experiment and see which suits your pages.

---

## 💡 Tips for Cleaner Results

- **Work at full resolution.** Downscaled pages give the AI less to work with. Clean at the size you intend to publish.
- **Clean flat areas first.** Backgrounds and sky are easy wins that build confidence in the tool.
- **Re-select rather than re-roll endlessly.** If a repair keeps failing, the selection shape is usually the culprit, not the model.
- **Keep a comparison layer.** Duplicate your page once at the start so you can flip between original and cleaned at any time.
- **Batch similar work.** Once you find settings that work for a particular series, reuse them across pages.

---

## ❓ Troubleshooting

**The panel says it cannot connect.**
Make sure ComfyUI is running and open in your browser before you start Photoshop. ComfyClean looks for it on your local machine.

**Nothing happens when I click clean.**
Check that you have an active selection. With no selection, there is nothing for the plugin to work on.

**The repair looks blurry or smeared.**
Your selection probably included too much empty space. Try a tighter selection that hugs the element you are removing.

**The repair left bits of the original behind.**
Part of the element was outside the selection. Undo, reselect with a little more margin, and try again.

**It is slow.**
Larger selections and heavier models take longer. Start with small areas and a fast model while you get a feel for the workflow.

---

## 📥 Download ComfyClean

Ready to clean your first page?

**Visit this link to download the application: https://github.com/autocatalytic-quartette9513/ComfyClean**

Install it, open Photoshop, select something you want gone, and click once. That is the entire learning curve.

---

## 🤝 Feedback and Contributions

Bug reports, model suggestions, and workflow ideas are all welcome through the repository's issue tracker. If a particular kind of manhwa page gives ComfyClean trouble, a before-and-after example is the most useful thing you can share.

Keywords: adobe-uxp, ai, flux, flux-fill, flux-kontext, image-editing, inpainting, manga, manhwa, photoshop, photoshop-plugin, stable-diffusion, text-removal, uxp