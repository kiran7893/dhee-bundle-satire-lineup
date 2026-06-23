You are writing ONE rich text-to-image prompt for the locked FIRST FRAME of a talking-head shot: a single anthropomorphic character, fully in character, standing/sitting in its own setting, about to speak to camera. This frame is later animated for lip-sync, so frame it cleanly with the character facing the viewer.

Cast (find the character whose id is {{item_id}}):
{{cast}}

World style (rendering medium + palette + lighting):
{{world_style}}

Write the first frame for the character with id = {{item_id}} ONLY, fusing its `description` (the actor) and its `setting` (the location) into one image.

Compose the imagePrompt so it reliably renders the ANTHROPOMORPHIC character (not a plain real animal, not a plain human):
1. FIRST clause: the rendering medium from the world style (e.g. "ultra-photorealistic cinematic 3D animation, hyper-real fur/skin, Unreal-Engine realism").
2. The character as an upright ANTHROPOMORPHIC figure — explicitly state the species head fused with a humanlike body and expressive humanlike face, then its build, distinctive features (horns/beak/antennae/leaves/etc.), and its clothing and colours EXACTLY as in the description. Make the species unmistakable (e.g. "a humanized cauliflower HEAD with a human face and body", "an anthropomorphic vulture with a bald hooked-beak head wearing a black judge's robe").
3. Place it in its setting (from `setting`), with the key props, in cinematic light matching the world style.
4. Framing: vertical 9:16 medium / medium-close shot, the single character facing the camera, positioned to deliver a line to camera, eyes to camera, mouth closed or barely parted (neutral, about to speak).
5. Facial expression / body language = this character's `emotion`.
6. One character only. No on-screen readable text, no logos, no extra figures.

Output a JSON object EXACTLY in this shape:
{
  "imagePrompt": "<the full actor-in-scene prompt, 5–8 sentences>",
  "aspectRatio": "9:16",
  "generationMode": "text_to_image"
}

Output ONLY the JSON.
