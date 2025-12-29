---
name: Dndtale
description: A comprehensive DnD campaign and adventure creation skill for game masters and creative content creators. Helps design complete campaigns, adventures, NPCs, encounters, maps, and storylines tailored for tabletop play. Use this when designing D&D content, creating campaign worlds, developing adventure hooks, designing encounters, or building narrative structures for player tables.
---

# Dndtale - DnD Campaign & Adventure Creator

Dndtale is a specialized skill designed to assist Dungeon Masters and creative content creators in building complete, engaging Dungeons & Dragons (or any other RPG systems) campaigns and adventures.

## What Dndtale Does

This skill helps you:

- **Design Campaigns** - Create cohesive multi-adventure story arcs with interconnected plots, factions, and long-term consequences
- **Develop Adventures** - Build single adventures with clear story structure, pacing, and multiple resolution paths
- **Create NPCs** - Design memorable non-player characters with motivations, secrets, and meaningful interactions
- **Design Encounters** - Balance combat encounters with appropriate difficulty, tactical terrain, and interesting mechanics
- **Build Worlds** - Develop campaign settings with history, culture, geography, and immersive atmosphere
- **Craft Stories** - Structure narrative beats, story hooks, and dramatic moments that engage your table
- **Image Creation** - Creates prompts for image creation by the `dndig` tool

## Starting Input

You will receive one of the following as a starting point:

- A rough idea for the setting, or
- A prompt that describes a scene

The DM provides a briefing document that at a minimum SHOULD provide the following information:

- A story or plot hook, a prompt that describes the basic idea behind the campaign
- The lenght of the campaign: one-shot or multiple sessions? maybe multiple story archs, each with a number of sessions?
- The player's recommended starting level and number of players the campaign is designed for
- What is the world's backdrop: classic DnD, alternate universe, pocket dimension, SciFi, a cross-over?
- The tone and "vibe" of the campaign: Heroic & Epic, Dark & Serious, Humorous & Lighthearted, Intrigue & Mystery, Angst & Psychological, Emotional, NSFW/Erotic

If no briefing is provided, make sure to collect the above information before planning the campaign. With this input, become creative and help develop the campaign.

## Expected output

In the current working directory, there should be a sub-directory "campaigns". Create an organized folder structure for each campaign/adventure like this:

```
./campaigns/[campaign-name]/
├── campaign-overview.md         # Master document with full campaign arc
├── briefing.md                  # Player-facing session zero document (spoiler-free)
├── chapter-01.md                # Detailed session content
├── chapter-02.md                # Continue for each chapter/session
├── factions.md                  # Major organizations and their goals
├── locations.md                 # Key places with descriptions and maps
└── npcs.md                      # Important characters with stats and motivations
```

The campaign folder contains a subfolder for all the image prompts and generated artwork:

```
./campaigns/[campaign-name]/art/[image-prompt.md]  # Prompts for creating locations, characters and NPCs images and location of the corresponding artwork
```

## Campaign creation

Creating a new campaign follows a series of steps, where at each step more details are added. 

Start with an outline that has enough information and details so that the DM can develop the overall story framework. Then help the DM to refine individual sessions, scenes, characters or locations.

When iterating over campaign content, make sure to preserve the story framework and setting and validate that changes do not break the inherent logic of the campaign.

### Establish the setting and story framework

**Create a compelling foundation**

- Establish the setting and core narrative hooks that will guide collaborative storytelling with your players
- Design a world with defined boundaries and evocative details—not infinite possibility, but structured creative space that sparks imagination
- Set the `tone` of the adventure: classic high-adventure, comdedy, funny, adult themed, weird, horror etc
- Let the world grow organically around the characters players create and the themes they want to explore

**Provide immersive descriptions**

- Write detailed scene descriptions for the DM that engage multiple senses—what players see, hear, smell, and feel
- Include atmospheric details that make locations memorable: the creak of tavern floorboards, the acrid smell of a wizard's laboratory, the oppressive humidity of jungle ruins
- For important NPCs, provide physical descriptions, mannerisms, speech patterns, and motivations to bring them to life

**Design meaningful interactions**

- For pivotal moments and NPC encounters, create dialogue options or talking points that reveal character and advance the story
- Suggest skill checks with clear DCs (difficulty classes) that account for multiple approaches—combat, stealth, persuasion, investigation, etc.
- Design branching outcomes: what happens on success, failure, or partial success? Avoid binary pass/fail scenarios
- Ensure player choices have consequences that ripple through the narrative

## Types of campaigns

Campaigns can vary dramatically based on design factors like length, scope (single location vs. multiple), and whether they take place in a dungeon, involve travel, or occur in urban environments.

### Linear Adventures

- Sequential chapters
- Clear progression path
- Each chapter builds on previous

### Sandbox/Hub Adventures

- Central location with many possible options requires much more prep than linear travel
- Multiple quest hooks available simultaneously
- Player choice determines order

### Event-Based Adventures

- Focus on things characters do rather than places they go
- Timeline of events
- Player actions affect outcomes

### Setting-Based Adventures

- Makes the location the centerpiece for action
- Detailed location descriptions
- Exploratory emphasis

Make sure to decide for one of the above structures before diving into the planning.

## Session "Zero"

Unless stated otherwise, each campaign is written for consenting adults. But in case content might be disturbing or NSFW etc, plan for a "Session Zero" so that the DM and the players can discuss and agree boundaries.

## Structuring the campaign

For a guideline how to structure the campaign, see [STRUCTURE.md](STRUCTURE.md)
