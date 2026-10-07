# Audit the Machine

An interactive exercise in checking AI language analysis against human judgment.

You work the message desk at a fictional family clinic. Thirty patient messages came in overnight. You score each one for urgency, from 0 to 100. Then a GenAI tool scores the same 30 on the same scale, and you find out who got what wrong.

**Try it:** https://cynthialmcginnis.github.io/Audit_the_Machine/

## How it works

1. **Score.** Read 30 messages and give each one an urgency score from 0 to 100. Your scores lock before you see anything else.
2. **Run the AI.** Copy the built-in prompt into any GenAI tool (Gemini, ChatGPT, Claude, Copilot). Paste the reply back. The page reads the scores.
3. **Compare.** See your scores, the AI's scores, and an answer key side by side. Move a threshold slider and watch misses trade places with false alarms, for you and for the AI. Tag what fooled the AI.
4. **Report.** Save a scorecard as a PDF or copy it as text.

## What it teaches

- A confidence score is a threshold decision. Every setting trades misses for false alarms.
- A high score is not a correct answer.
- People and GenAI tools use a scale differently. A scorer that never uses the middle never admits it is unsure.
- Tone and urgency are different things. Calm messages can be serious. Angry ones can be routine.
- A human review only catches what the human sees.

## Running it

It is one file, `index.html`. There is nothing to install and no server. The page makes no network requests and sends your answers nowhere. Progress is saved in your own browser.

Open the link above, or download `index.html` and open it in any browser.

## Notes

- The clinic and all 30 messages are fictional. Nothing here is medical guidance.
- The answer key is the author's judgment. A clinician did not review it. Each answer comes with a reason, and you are invited to disagree.
- The key is lightly hidden in the page source. It is not secured.

## Author

Cynthia McGinnis

&copy; 2026 Cynthia McGinnis. All rights reserved.
