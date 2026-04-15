# How to Turn One Sketch Into Polished Client-Ready Architectural Renders

![Banner](assets/banner-start.png)

## Start with the still

One sketch is enough to create polished client-ready architectural renders in Sogni. The fastest path is simple: make one still worth showing, expand it into more angles, and add motion only when the presentation needs it.

What this walkthrough builds:

- one polished still
- one reusable angle set
- one optional reveal video

## Proof first

Start with the sketch, then get the first still working, then expand it.

![Source sketch](assets/article-x-houses/0.jpg)
![First polished still](assets/article-x-houses/7po.png)
![Angle-set example](assets/article-x-houses/12.png)

This tutorial still runs in 10 steps. They are grouped into 3 phases so readers can scan the workflow quickly without losing the step-by-step path.

## Phase 1 - Create the first still worth showing

Stay inside Sogni Create until you have one image you would actually put in front of a client.

### Step 1 - Start in Sogni Create

For the clearest first pass, start in [Sogni Create](https://app.sogni.ai/create) in the browser. It gets you into the workflow immediately and keeps the focus on the image instead of setup.

![Sogni Create landing screen](assets/article-x-houses/1.png)

### Step 2 - Choose the fastest path to a first render

Start with **Qwen Image Edit** for the quickest route from sketch to believable render. If you want to combine multiple references later, switch to **Flux 2** after the first still is already working.

![Model selection](assets/article-x-houses/2.png)

### Step 3 - Upload your sketch as the anchor

Upload the sketch and leave most settings at their defaults for the first pass. The point here is to protect the original structure and composition while you improve realism around it.

![Reference image setup](assets/article-x-houses/3.png)

### Step 4 - Write the prompt like a design brief

Focus first on materials, lighting, landscaping, and mood. Those are the biggest visual levers, and they are enough to get a strong first pass without overcomplicating the setup.

```text
Transform this architectural concept into a highly realistic modern luxury house.

Add a large infinity swimming pool in front of the building, with realistic water reflections and subtle ripples. Use high-end materials such as white concrete, natural wood panels, glass walls, and metal details. Enhance lighting to golden hour with warm sunlight, soft shadows, and realistic ambient occlusion. Add natural landscaping with grass, trees, and subtle terrain details. Improve textures and details to achieve photorealism, including reflections on glass, interior lighting, and outdoor furniture. Keep the original structure and composition but make it look like a real built house. Ultra realistic, 8k, cinematic, high detail, archviz style.
```

![Prompt and outputs](assets/article-x-houses/4.png)

### Step 5 - Choose the best output, then push it further with Enhance

Once you have a promising still, use **Enhance** to move it from "good enough" to something you would actually show. In this example, **Boost Realism** and **Fine Details** do most of the work.

![Enhance tools](assets/article-x-houses/5.png)

#### Before and after

![Before enhancement](assets/article-x-houses/6przed.jpg)
![After enhancement](assets/article-x-houses/7po.png)

At the end of Phase 1, you should have one polished still you can show, approve, and build the rest of the workflow around.

## Phase 2 - Expand the still into an angle set

Move into 360 only after the base image is already strong enough to deserve more viewpoints.

### Step 6 - Open 360 by Sogni and generate your first angle set

Bring the enhanced still into [360 by Sogni](https://360.sogni.ai/), save the project, choose a preset camera path, and let the tool expand one strong image into multiple viewpoints.

- upload the still and name the project so you can return to it later
- choose a ready-made preset for the first pass instead of building a custom camera path
- for this example, use **360 Spin High+Wide (9)** and click **Generate 8 Angles**

![Upload to 360](assets/article-x-houses/8.png)
![Name the project](assets/article-x-houses/8.1.png)
![Choose the preset](assets/article-x-houses/9.png)
![Generated angle set](assets/article-x-houses/10.png)

### Step 7 - Build the polished still-image set

This is the point where many readers can stop. You already have a strong still package for a catalog, concept sheet, or client presentation. Motion is optional from here.

![Finished angle one](assets/article-x-houses/11.png)
![Finished angle two](assets/article-x-houses/12.png)

At the end of Phase 2, the still-image workflow is complete.

## Phase 3 - Add motion only when it earns its place

Keep motion as the upgrade path, not the default expectation.

### Step 8 - Generate transitions

Start with a short draft before you customize everything. Use default transition settings first, choose one video model, and make sure the base motion works before you spend time polishing it.

- choose the transition type or write a custom prompt
- pick a video model: **LTX** or **Wan**
- set duration, quality, and resolution only after the first draft feels right

![Transition settings](assets/article-x-houses/13.png)
![Transition progress](assets/article-x-houses/14.png)

### Step 9 - Adjust pacing and render the final video

Compare pacing options, keep only the shots that improve the story, and stitch the strongest sequence into a finished draft. The workflow stays editable, so you can refine without restarting from scratch.

<video src="assets/article-x-houses/15.1.mp4" autoplay muted loop controls playsinline></video>

<video src="assets/article-x-houses/15.2.mp4" autoplay muted loop controls playsinline></video>

<video src="assets/article-x-houses/16.1.mp4" autoplay muted loop controls playsinline></video>

### Step 10 - Turn the sketch into a cinematic reveal

For the strongest before-and-after moment, use the original sketch as the **Start Frame** and the polished still as the **End Frame**. This turns the tutorial into a presentation payoff instead of just another feature demo.

![Sketch-to-final setup](assets/article-x-houses/17.png)

<video src="assets/article-x-houses/18.mp4" autoplay muted loop controls playsinline></video>

## Final takeaway

The highest-leverage version of this workflow is still simple: make the first still work, expand it into angles, and add motion only when it earns its place.

## Explore it yourself

- [Sogni Create](https://app.sogni.ai/create)
- [360 by Sogni](https://360.sogni.ai/)
- [Sogni Studio](https://www.sogni.ai/studio)
