#  AI-Generated Deep Fake Interview — Task 6

As an extension of the earlier statistical and LLM-based analysis on cricket bowling performance, this task involved generating a **video-based AI street interview** using generative tools.

The narrative, questions, and answers were taken directly from the prior **LLM analysis task** (ChatGPT + DeepSeek) using the same structured dataset:  
 `llm_ready_bowling_with_match_context.csv`

---

##  Tool Used
- **Video Generation Model:** Google Labs **Veo (Fast 3)**
- **Prompt Type:** Text-to-video with natural language script
- **Voice & Gestures:** AI generated automatically by Veo

---

##  Files in This Repo
- `interview_script.txt` — Full dialogue used in the video
- `veo_prompt_retrofan.txt` — Prompt for retro street interview
- `veo_prompt_campus.txt` — Prompt for college campus setting
- `README.md` — This file

---

##  Watch the Videos

 [Click here to view the AI interview videos (Google Drive)] ( https://drive.google.com/drive/folders/1U1lAghcsESMu1fn_qKAQUKiJWdvVq-lD?dmr=1&ec=wgc-drive-hero-goto )

This includes:
- A **retro cricket fan** being interviewed on a city street  
- A **college student** giving statistical cricket insights on campus

---

##  Prompted Questions (Based on LLM Analysis)

Questions asked were from the previous task using bowling performance data:

1. Who had the best economy rate across all matches?  
2. Who bowled the most overs in the tournament?  
3. Which team won the most matches?  
4. Who was the most effective bowler overall? *(high wickets + low economy)*  
5. Who improved the most across the tournament? *(increasing wickets or decreasing economy)*

---

##  Sample Script (interview_script.txt)

**Interviewer:** “Who improved the most across the tournament?”  
**Fan:** “Gerald Coetzee. Started all over the place, but by the end? He was on point. 18 wickets, economy dropped to 6.23. Real growth.”

---

##  Veo Prompt 1 — Retro Fan (veo_prompt_retrofan.txt)

Realistic 4K footage of a casual street interview in a lively urban city. Captured with a handheld camera and slight motion blur. A human interviewer with a microphone (logo: “BowlTalk”) stops a retro cricket fan wearing an old-school India jersey, sunglasses, and sweatband.

Fan is expressive and nostalgic. Ambient sounds include traffic, city bustle, neon signs.

**Dialogue Sample:**  
Interviewer: “Who was the most effective bowler overall?”  
Fan: “Mohammed Shami. 23 wickets, 5.10 economy. Cool as Gavaskar in the slips.”

---

##  Veo Prompt 2 — College Campus (veo_prompt_campus.txt)

Realistic 4K footage of a casual interview on a vibrant college campus. Handheld camera with ambient student activity — walking, chatting, biking. Interviewer approaches a student with one earbud in and a backpack.

**Dialogue:**  
Interviewer: “Who improved the most across the tournament?”  
Fan: “Gerald Coetzee. Started all over the place, but by the end? He was on point. 18 wickets, economy dropped to 6.23.”

---

##  Observations from Generated Outputs

1. In one of the videos above, the **fan asked the interviewer a question**, flipping the roles.
2. Another video had a **popcorn bag disappear and reappear mid-animation** during an emote gesture.
3. In one clip, a **white interviewer had an Asian voice accent**, likely due to voice model mismatch.

These quirks demonstrate the **experimental nature of AI video generation**, blending realism with unexpected generative artifacts.

---

##  Summary

This task showcases how narrative + data + generative media can work together to tell stories from structured datasets in creative formats. It builds directly on the previous LLM analysis and adds visual, human-like expression to AI-generated cricket insights.

