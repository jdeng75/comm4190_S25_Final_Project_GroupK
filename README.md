# COMM4190 Final Project: Motiva  
**An AI Running Coach for Everyday Athletes**  
By [Your Name]

---

## Introduction

Throughout this course, we’ve come to realize that artificial intelligence is no longer just a futuristic concept,it’s an everyday presence. We’ve interacted with LLMs as collaborators, not just tools, and considered how these systems shape and influence the way we communicate. We explored how to prompt, question, critique, and co-create with AI, learning that thoughtful design and meaningful human-AI interactions go hand-in-hand.

These insights inspired us to build something that could be genuinely helpful: a chatbot that doesn’t just respond, but supports. Something practical, approachable, and purpose-driven.

And so, we turn to running.

From 3Ks to ultramarathons, there’s a wide spectrum of races people train for, and just as many reasons for doing so. Maybe you're trying to complete your first race, or perhaps you’re chasing a personal record. No matter the goal, the training process can be intimidating. There’s a flood of information out there: blog posts, paid apps, pacing calculators, heart rate zones, gear reviews, YouTube tutorials… the list goes on.

But even with all this information, many runners are still left wondering:  
*Am I training the right way? Why do my knees hurt? Should I be doing tempo runs? What even is a tempo run?*

And unless you’re willing to shell out money for a premium coaching app or hire a coach, that guidance can be hard to come by.

This is the gap that **Motiva** aims to fill.

Motiva is an AI-powered chatbox that acts as a running coach, motivator, and resource hub. It’s especially designed for runners who use free tools like Strava—or don’t use anything at all—and still want the benefits of a personalized, flexible training program.

Whether you’re trying to PR your 5K, coming back from an injury, or running for mental clarity, Motiva meets you where you are. It’s built to be your co-pilot on the path to your goal.

---

## Outlining the Agent’s Value Proposition

### Background

Running apps are everywhere—Strava, Nike Run Club, Garmin Connect, to name a few. They offer impressive analytics and data visualizations, but they often fall short when it comes to personalization. Many users don’t know how to interpret their data, and even fewer feel confident adjusting their plans based on that information.

Even more, a lot of existing training plans are static. They don’t respond when you miss a workout. They don’t know when your legs feel like bricks or when you had a breakthrough long run. They don’t answer your questions at 10pm the night before race day.

Motiva does.

Inspired by the “duet” model of AI-human collaboration, Motiva is not a passive tool—it’s an interactive coach that adapts to your feedback, evolves with your progress, and offers support along the way.

---

### Type of LLM Application: Co-Pilot / Duet Tool

Motiva was built as a co-pilot experience, meaning it works *with* the user, not *for* the user. It’s not just about giving advice—it’s about helping runners make informed, confident decisions.

#### The Chatbox Can:
- Act as a virtual coach, guiding users through dynamic training plans.
- Tailor recommendations based on fitness level, race goals, timeline, and experience.
- Integrate with optional Strava data uploads to fine-tune suggestions.
- Function without any existing data—just a conversation is enough to get started.

---

### Key Features

- **Personalized Training Plans**  
  Create structured programs based on race type (5K, half marathon, etc.), timeline, and current ability. The chatbox asks the right questions, not just fills in a template.

- **Check-Ins and Plan Adjustments**  
  Offers motivational nudges, tracks progress through user interactions, and adjusts plans as needed.

- **Pace and Zone Guidance**  
  Helps users understand heart rate and effort zones, not just how fast they’re going.

- **Gear Recommendations**  
  Provides advice on shoes, apparel, and recovery tools tailored to running style and terrain.

- **Injury Prevention and Recovery Support**  
  Shares evidence-based tips for common issues like shin splints, runner’s knee, stomach cramps, and more—before they derail your training.

---

### Tools in Use

- **Strava Data Integration (Optional)**  
  Users can upload a `.csv` file of their running data to improve personalization.

- **DuckDuckGo Search API**  
  Seamlessly finds up-to-date online resources for anything the chatbot can’t generate internally—like stretching routines or current gear reviews.

- **Gradio Interface**  
  A user-friendly front end that allows runners to interact with Motiva through an intuitive web interface. Simple, clean, and approachable.

---

### Project Idea: At a Glance

| Step | What Happens |
|------|---------------|
| **Input** | Users upload Strava data **OR** enter race type, timeline, and experience level. |
| **Interaction** | The chatbot generates a plan and responds to feedback, updates goals, and shares advice. |
| **Output** | A customized, flexible training plan that evolves with the user and answers their questions. |

Motiva is more than just a chatbot—it’s an AI companion that listens, adapts, and helps you become the runner you want to be.

---

## Check Out the Other Notebooks!

- **Overview**
- **User Case Flow Charts**
- **Evaluating Existing LLMs**
- **Model Design**
- **Project Evaluation**

---
