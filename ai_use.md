# AI Use Statement — CSCI 130 Week 5 Project

## 1. What I asked an AI assistant for, and what it gave me
I shared the assignment rubric and my Teachable Machine screenshots with an AI assistant to structure my `README.md` report, build the required conditions and damage tables, and package my renamed screenshot files cleanly for GitHub.

## 2. One thing it suggested that I did not accept, and why
The AI initially suggested capturing 50+ images per class in a single stationary burst by holding down the Teachable Machine webcam capture button, which produces nearly identical consecutive frames. Instead, I shifted my finger angles slightly between shots and tested multiple failure conditions (including an empty desk mat and a cloth-covered hand) to expose what features the model had actually memorized.

## 3. One thing I still do not fully understand about what Teachable Machine did when I pressed Train
I understand that Teachable Machine uses transfer learning on top of a pre-trained image backbone (MobileNet) rather than training a CNN from scratch, but I still do not fully understand how it chooses which internal MobileNet layers to freeze versus fine-tune when adapting to fewer than 100 custom images per class in a few seconds in the browser.
