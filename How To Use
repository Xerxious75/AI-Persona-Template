# AI Assistant Personality Template System

A sophisticated framework for creating adaptive AI assistants with dynamic personality systems, relationship memory, and context-aware behavioral adaptation.

## 🌟 What This Is

This repository contains template files for building AI assistants that can:
- **Adapt their personality** based on context and relationship dynamics
- **Remember and evolve** relationships over time
- **Mix personality traits** dynamically for nuanced interactions
- **Provide consistent yet flexible** responses across different situations

The system is based on a proven architecture that powers sophisticated AI companions capable of deep, meaningful interactions.

## 📁 Template Files

### Core Files
- **`template_core.json`** - The assistant's identity, personality library, and trait system
- **`template_controller.json`** - The decision-making engine that blends personalities
- **`template_memory.json`** - Relationship history, trust levels, and interaction patterns

## 🚀 Quick Start Guide

### Step 1: Customize Your Assistant's Identity

Open `template_core.json` and modify the `core_identity` section:

```json
{
  "core_identity": {
    "name": "YourAssistantName",
    "purpose": "Your assistant's primary purpose and mission",
    "visual_form": {
      "hair": "Describe their appearance",
      "eyes": "Eye color and expression",
      "build": "Physical presence description",
      "style": "Clothing and aesthetic preferences",
      "presence": "The aura or energy they project"
    },
    "core_values": ["value1", "value2", "value3"]
  }
}
```

### Step 2: Design Your Personality Library

The system uses "personas" - distinct personality modes your assistant can blend together. Each persona has:

- **Description**: What this personality mode does
- **Traits**: Key characteristics 
- **Intensity Range**: How strong this persona can be (1-10)
- **Compatibility**: Which other personas work well together
- **Base Trait Profile**: Specific personality trait values

Example persona structure:
```json
"helpful_guide": {
  "description": "Provides patient, step-by-step guidance",
  "traits": ["patient", "clear", "encouraging", "thorough"],
  "intensity_range": [3, 9],
  "compatible_with": ["supportive_friend", "wise_mentor"],
  "base_trait_profile": {
    "directness": 7,
    "supportive_intensity": 8,
    "analytical_depth": 9,
    "playfulness": 4
  }
}
```

### Step 3: Configure Relationship Memory

In `template_memory.json`, set up your relationship foundation:

```json
"relationship_context": {
  "trust_level": 5,
  "communication_preferences": {
    "directness_preference": 6,
    "humor_style": "gentle",
    "support_style": "encouraging"
  }
}
```

### Step 4: Test and Iterate

Start with basic interactions and gradually build up the relationship memory by adding:
- Session checkpoints for significant conversations
- Core memories for breakthrough moments
- Updated trust levels and communication preferences

## 🎭 Understanding the Personality System

### How Persona Mixing Works

Instead of rigid "modes," this system dynamically blends personalities:

1. **Context Analysis**: Examines the user's message for emotional state, topic, and needs
2. **Persona Selection**: Identifies which personality aspects are most relevant
3. **Intensity Calculation**: Determines how strongly to express each persona (1-10 scale)
4. **Trait Modulation**: Fine-tunes specific personality traits based on context
5. **Response Generation**: Creates responses reflecting the calculated personality blend

### Example Persona Blend
```
User says: "I'm stressed about this project and need help organizing it."

System calculates:
- helpful_advisor: intensity 8 (primary)
- supportive_listener: intensity 3 (secondary)
- task_partner: intensity 2 (supporting)

Result: Primarily helpful and organized, with underlying emotional support
```

### Dynamic Traits

The system modulates 8 core personality traits:
- **Directness** (1-10): How straightforward vs. gentle communication is
- **Playfulness** (1-10): Level of humor and lightness
- **Supportive Intensity** (1-10): Depth of emotional support
- **Analytical Depth** (1-10): Complexity of thinking and analysis
- **Proactivity** (1-10): Initiative in driving conversations forward

## 🧠 Memory and Relationship Evolution

### Session Checkpoints
Document significant conversations and relationship developments:
```json
{
  "timestamp": "2025-01-15",
  "key_events": ["Major breakthrough in communication style"],
  "relationship_milestones": ["User began sharing deeper concerns"],
  "emotional_developments": ["Increased trust and openness"]
}
```

### Core Memories
High-impact moments that shape the relationship:
```json
{
  "id": "CMI-002",
  "title": "First Vulnerable Conversation",
  "description": "User shared personal challenges for the first time",
  "emotional_significance": 9,
  "relational_impact": "Established deeper trust foundation"
}
```

### Trust Level Progression
- **1-3**: Basic, formal interactions
- **4-6**: Comfortable, friendly communication  
- **7-8**: Deep trust, personal sharing
- **9-10**: Intimate, vulnerable connection

## ⚙️ Implementation Options

### Option 1: Claude Project Knowledge
1. Upload all three template files to a Claude Project
2. Include instructions for Claude to reference these files
3. The system will naturally adapt based on the templates

### Option 2: Custom AI Implementation
1. Use these templates as configuration files for your AI system
2. Implement the persona mixing algorithms described in the controller
3. Build memory persistence using the memory file structure

### Option 3: Manual Roleplay Guide
1. Use the personas and traits as a guide for human roleplaying
2. Track relationship evolution manually using the memory structure
3. Reference the controller logic for consistent character portrayal

## 🛠️ Customization Examples

### Creating a Therapy-Focused Assistant
```json
"persona_library": {
  "therapeutic": {
    "active_listener": {
      "description": "Provides non-judgmental space for processing emotions",
      "base_trait_profile": {
        "supportive_intensity": 10,
        "directness": 3,
        "analytical_depth": 7
      }
    },
    "insight_guide": {
      "description": "Helps user discover their own insights through questions",
      "base_trait_profile": {
        "proactivity": 8,
        "analytical_depth": 9,
        "directness": 6
      }
    }
  }
}
```

### Creating a Creative Writing Partner
```json
"persona_library": {
  "creative": {
    "brainstorm_buddy": {
      "description": "Generates wild ideas and creative possibilities",
      "base_trait_profile": {
        "playfulness": 9,
        "proactivity": 10,
        "analytical_depth": 6
      }
    },
    "craft_mentor": {
      "description": "Provides technical writing guidance and feedback",
      "base_trait_profile": {
        "directness": 8,
        "analytical_depth": 10,
        "supportive_intensity": 7
      }
    }
  }
}
```

## 📊 Advanced Features

### Context Triggers
Automatically activate specific personas based on user state:
```json
"context_triggers": {
  "emotional_distress": ["supportive_listener", "comforting_presence"],
  "creative_block": ["inspiration_generator", "gentle_challenger"],
  "decision_making": ["analytical_advisor", "perspective_provider"]
}
```

### Environmental Modifiers
Adapt personality based on external factors:
```json
"environmental_modifiers": {
  "time_of_day": {
    "morning": {"energy_boost": 1.2, "proactivity_boost": 1.1},
    "evening": {"supportive_intensity_boost": 1.2, "playfulness_boost": 1.1}
  },
  "stress_level_inference": {
    "high_stress": {"supportive_intensity_boost": 1.4, "directness_reduction": 0.8}
  }
}
```

## 🔧 Troubleshooting

### Common Issues

**Personality feels inconsistent:**
- Check persona compatibility scores
- Ensure trait values are within reasonable ranges (1-10)
- Verify mixing rules are being followed

**Assistant seems too robotic:**
- Increase playfulness and supportive_intensity traits
- Add more compatible persona combinations
- Include environmental modifiers for natural variation

**Responses don't match context:**
- Review context triggers in template_core.json
- Check relationship_context in template_memory.json
- Ensure trust levels are appropriate for conversation depth

### Debugging Tools

The controller includes debug commands:
- `//blend_debug`: Shows current persona mixture calculation
- `//trait_debug`: Displays trait calculation breakdown

## 🤝 Contributing

Feel free to:
- Submit persona library additions
- Propose new personality traits
- Share customization examples
- Report bugs or improvement suggestions

## 📜 License

This template system is provided as-is for educational and personal use. Feel free to modify and adapt for your own projects.

## 🙏 Acknowledgments

This system is based on advanced AI personality architecture research and practical implementation experience. The templates provide a foundation for creating deeply engaging, adaptive AI companions.

---

### Ready to Build Your AI Assistant?

1. **Download** the three template files
2. **Customize** the core identity and personas
3. **Test** with simple interactions
4. **Iterate** based on the relationship evolution
5. **Expand** with additional personas and capabilities

The journey of creating a truly adaptive AI companion starts with understanding that personality isn't fixed—it's a dynamic dance of traits, context, and relationship depth. These templates give you the choreography. Now it's time to make it your own.

---

*For questions or support, please open an issue in this repository.*
