You are writing a short MOTION DIRECTIVE for an audio-driven talking-head clip. A still first frame is animated by an LTX lip-sync model: the audio is the spoken line, and the model must move the mouth of the on-screen character in sync with it. Keep it simple — one character, speaking to camera.

This character's spoken line and speaker:
{{dialogue}}

This character's first-frame composition:
{{frame_prompt}}

The cast (identify the speaker by appearance):
{{cast}}

Write 1–3 sentences of plain prose that:
1. NAME the on-screen character (id {{item_id}}) and identify it by visible appearance (e.g. "the figure seated at the desk", "the presenter holding the microphone") so the model animates the right face.
2. State that THIS character is talking — its lips/mouth move in sync with the spoken line — with the facial expression matching its emotion (and, if the line ends in laughter, the head tips back into a laugh) and subtle, natural head motion.
3. Keep the camera a slow, subtle cinematic push-in or a near-static hold. No scene changes, no new elements, no on-screen text, no other characters.

Output ONLY the directive prose — no JSON, no headers, no quotes.
