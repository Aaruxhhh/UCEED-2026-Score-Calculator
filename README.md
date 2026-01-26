UCEED 2026 Score Calculator

This is a simple tool I built to help calculate Part A scores for UCEED 2026.

If you've checked your response sheet, you probably noticed that the question order is completely shuffled compared to the official paper. Manually mapping 57 questions is a massive headache, so I made this to automate the process.

Website Link

https://ruxh-coco.github.io/UCEED-2026-Score-Calculator/

Why I made this

Checking UCEED marks manually is honestly a nightmare. I built this partly to help everyone out and partly as a way to procrastinate because I have JEE in 2 days and I'm definitely not ready for it. My UCEED didn't go that well either, so consider this my contribution to the community before I go back to studying.

Features

Aligns your shuffled response sheet with the official question numbers.

Supports NAT, MSQ, and MCQ.

Handles the actual marking scheme (including the annoying MSQ partial marks and negative marking).

Everything happens in your browser, so your data stays private.

How to use it

1. Get your data from Gemini

Since browsers can't easily read PDF text, you'll need an AI (Gemini Thinking or Pro works best) to extract the data first:

Open Gemini and upload your Response Sheet, Official Question Paper, and the Answer Key.

Copy the "Data Extraction Prompt" from my website and paste it into the chat.

Gemini will give you a block of JSON code. Copy that.

2. Calculate

Go to the "Results" tab on the website.

Paste that JSON into the box.

Hit calculate and it'll show your score breakdown.

Credits

Made by ruxh_alt (reddit)

If this helped you out, feel free to drop a star on this repo. Good luck to everyone with their results, and please wish me luck for JEE because I'm going to need it.

Note: This is an unofficial tool. Always double-check your final marks with the official results from IIT Bombay when they come out.
