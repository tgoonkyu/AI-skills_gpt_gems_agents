# 🌴 Goa Trip Planner — AI Skill / Agent / Gem / GPT Collection

A collection of experiments exploring how different AI platforms can be used to build a **Goa Trip Planner** in the form of a **Skill, Agent, Gem, or GPT**.

## 📌 About

This repository is a **personal trial / experimentation project**.

The goal is to explore how different AI models can be configured to act as a practical travel-planning assistant for a real-world Goa trip.

The planner is intended to handle things such as:

* 📅 Travel dates
* 👨‍👩‍👧 Number of travellers
* 🚗 Mode of travel
* ✈️ Flights
* 🚆 Trains
* 🚌 Buses
* 🚘 Car / road travel
* 🏨 Accommodation
* 🗓️ Length of stay
* 💰 Budget
* 📍 Places to visit
* 🧭 Daily itinerary
* 🍽️ Food and dining preferences
* 👶 Family / child-friendly requirements
* 🎯 Special requirements
* 🚕 Local transportation
* 💵 Cost estimates
* ⏱️ Travel time and logistics

The idea is for the AI to **adapt to the user's requirements and constraints rather than rely on a fixed trip template**.

## 🧪 Personal Experiment

This is primarily a **personal AI experimentation project**.

The objective is to explore how different models and platforms perform when given the same travel-planning problem.

Some of the areas being explored include:

* 🧠 Understanding user requirements
* ❓ Asking useful questions before making assumptions
* 🗺️ Building practical itineraries
* 🔒 Maintaining user-defined constraints
* 💰 Staying within a defined budget
* 📍 Considering geography and travel time
* 🔄 Adapting plans when requirements change
* 🔎 Researching and comparing available options
* 📋 Producing a clear and usable final plan

This is **not intended to be a formal benchmark or scientific comparison**.

## 🤖 AI Models / Platforms Used

### 🔵 Google Gemini

**Model:** `Gemini 3.1 Pro Extended`

Used to experiment with building a **Gem** for Goa trip planning and itinerary generation.

### 🟢 OpenAI ChatGPT

**Plan:** `Free Plan`
**Mode:** `Think`

Used to experiment with building a **GPT / travel-planning agent** using ChatGPT's Think mode for requirement gathering, itinerary planning, comparison, and iterative refinement.

### 🟠 Anthropic Claude

**Model:** `Claude Sonnet 5`

Used to experiment with a **Skill / Agent-based travel planner**, with an emphasis on reusable instructions and structured planning workflows.

## ⚙️ Core Planning Philosophy

The planner is built around a few core principles:

### 1. 👤 User requirements come first

The AI should not assume:

* Fixed travel dates
* Fixed number of travellers
* Flights as the only travel option
* A specific accommodation
* A predefined trip duration
* A fixed budget
* A fixed itinerary

Instead, these should be **configurable based on the user's needs**.

### 2. ❓ Ask before assuming

When important information is missing, the planner should ask relevant questions rather than making unnecessary assumptions.

Typical inputs may include:

* 📅 Travel dates
* 👥 Number of travellers
* 📍 Starting location
* 🌴 Destination
* 🚗 Mode of travel
* ✈️ Flight / train / bus / car details
* 🏨 Accommodation preference
* 🗓️ Length of stay
* 💰 Budget
* 🎯 Interests and priorities
* 🧳 Special requirements

### 3. 🔒 Respect constraints

User-defined constraints should be treated as actual planning requirements.

For example:

> "Day 3 cannot change."

should mean that Day 3 remains unchanged unless the user explicitly requests a change.

Similarly:

> "Budget cannot exceed ₹65,000."

should be treated as a planning constraint rather than a suggestion.

### 4. 🧮 Optimize rather than simply recommend

The goal is not just to provide a list of popular places.

The planner should consider factors such as:

* 📍 Location
* ⏱️ Travel time
* 💰 Cost
* 🕐 Opening / closing times
* 🗺️ Geographic clustering
* 🏨 Accommodation location
* 🚕 Transportation availability
* 👤 User priorities
* 🗓️ Trip duration
* 😌 Travel pace and fatigue
* 💸 Overall budget

### 5. 🔄 Iterate and refine

Travel planning is expected to be an iterative process.

A change to one part of the trip may require other parts to be reconsidered.

For example:

```text
Initial Plan
     ↓
Change Accommodation
     ↓
Recalculate Travel Distances
     ↓
Change Day 2 Activity
     ↓
Preserve Day 3
     ↓
Adjust Budget
     ↓
Recalculate Logistics
     ↓
Refine Final Itinerary
```

The planner should ideally **preserve existing requirements while changing only what is necessary**.

## 📊 What This Experiment May Compare

The different AI implementations may be compared across areas such as:

| Area                     | What is evaluated                                        |
| ------------------------ | -------------------------------------------------------- |
| 📝 Requirement Gathering | Does the AI ask the right questions?                     |
| 🔒 Constraint Handling   | Does it preserve user requirements?                      |
| 🗺️ Planning Quality     | Is the itinerary practical and coherent?                 |
| 💰 Budget Optimization   | Does it work within the specified budget?                |
| 📍 Geography             | Are locations logically grouped?                         |
| 🚗 Travel Logistics      | Are routes and travel times practical?                   |
| 🔄 Adaptability          | Can the plan handle requirement changes?                 |
| 🔎 Research              | Does it validate current information?                    |
| 📋 Output Quality        | Is the final plan clear and usable?                      |
| 🧠 Context Handling      | Does it maintain context across iterations?              |
| 🛠️ Tool Usage           | Does it make effective use of available tools?           |
| 🎯 Personalization       | Does it adapt to individual preferences and constraints? |

This is **not intended to be a scientific benchmark**. Results may vary depending on the model, platform, instructions, tools, available data, and the way the task is presented.

## 🎯 Experiment Objective

The main question behind this project is:

> **How effectively can different AI models turn a collection of personal travel requirements and constraints into a realistic, practical, and cost-conscious trip plan?**

Rather than simply asking:

> *"Plan my Goa trip."*

the experiment explores whether AI can behave more like a **personal travel planner** that:

* 🧠 Understands requirements
* ❓ Asks useful questions
* 🔒 Maintains constraints
* 🔎 Researches relevant options
* 💰 Considers the budget
* 🗺️ Accounts for geography and logistics
* 🔄 Refines the plan iteratively
* 📋 Produces a practical final itinerary

## ⚠️ Disclaimer

This repository is a **personal experiment** and is not an official travel-planning service.

AI-generated information may be inaccurate or become outdated, especially for:

* 💰 Prices
* 🏨 Accommodation availability
* ✈️ Flight / transport schedules
* 🕐 Opening hours
* 🚗 Travel times
* 🎟️ Activity availability
* 📍 Local travel information

Information generated through these experiments should therefore be **independently verified before making bookings or spending money**.

## 🚧 Project Status

🧪 **Personal Experiment / Work in Progress**

The prompts, instructions, skills, agents, Gems, and GPT configurations may evolve as different AI platforms and models are tested and compared.
