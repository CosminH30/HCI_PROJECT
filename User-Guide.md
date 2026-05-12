-----------
# MOBILE

## Navigation
At the bottom of the screen are four tabs:

Tab	What it does
Home	Your player profile and quick stats
Stats	Detailed performance analytics
History	Your recent match log
Awards	Achievements and progress
Tap any tab to switch screens instantly.

## Home
Your main dashboard. At the top you'll see your online status and the GAMAR branding.

Select Game — Tap FORTNITE or CALL OF DUTY to switch between your stats for each game. The active game highlights in red and all numbers update automatically.

Below that you'll see your Player Profile with:

Total Kills
Wins
K/D Ratio
Win Rate
And two quick-glance cards: Matches Today and Play Time.

## Stats
A deep dive into your performance.

Timeframe dropdown (top-right) — Tap it to cycle between:

Last 7 Days
Last 30 Days
All Time
All four performance numbers (Avg Accuracy, Avg Damage, Avg Kills, Avg Duration) update to match the selected period.

Below that, Trend Analysis shows bar graphs for Performance, Win Rate, and Accuracy trends, and Detailed Stats lists totals like playtime, headshot percentage, and your longest kill.

## History
Your full match log, sorted newest first.

Filter button (top-right) — Tap to cycle through:

Filter → shows all matches
WINS → shows only victories
LOSSES → shows only losses
Each match card shows the game mode, result placement (1st, 8th, 23rd…), kills, deaths, K/D ratio, and match duration.

## Awards
Your achievement showcase.

Unlocked achievements appear at full brightness with a red icon background and your earned points shown in red.
Locked achievements appear dimmed with a progress bar showing how close you are to unlocking them.
The Overall Progress bar at the top tracks how many of the 8 achievements you've unlocked.
Total Points updates automatically as you earn achievements.
Status Indicator
The Online badge in the top-right of the Home screen confirms your tracker is live and connected.


# Tactical Assistant Smartwatch - User Guide

## Table of Contents
1. [Introduction](#introduction)
2. [Interface Overview](#interface-overview)
3. [Navigation](#navigation)
4. [Main Screens](#main-screens)
5. [Alert System](#alert-system)
6. [Game Profiles](#game-profiles)
7. [Settings & Controls](#settings--controls)
8. [BPM Monitor](#bpm-monitor)
9. [Haptic Feedback](#haptic-feedback)
10. [Tips & Best Practices](#tips--best-practices)

---

## Introduction

The Tactical Assistant Smartwatch is a cyberpunk-styled heads-up display (HUD) designed to provide instant, actionable alerts during gaming sessions. Built with a focus on minimal interaction and maximum readability, this smartwatch interface delivers critical information at a glance with immersive visual and haptic feedback.

### Key Features
- **Automatic Alert System**: Notifications appear and dismiss automatically
- **Game Profile Modes**: Customized alerts for FPS, MOBA, and RPG games
- **Biometric Monitoring**: Real-time BPM tracking with dynamic responses
- **Haptic Feedback Simulation**: Visual feedback that simulates watch vibration
- **Swipe Navigation**: Gesture-based controls for quick access to settings

---

## Interface Overview

### Display Layout
The smartwatch features a **circular display** with:
- **Outer Ring**: Physical watch bezel with indicator dot
- **Corner Accents**: Four red corner markers for tactical aesthetic
- **Central Display**: Main content area showing current screen
- **Haptic Rings**: Pulsing red rings during alert events (when haptic is enabled)

### Color System
The interface uses a **cyberpunk color palette**:
- **#ff0844** (Neon Red): Primary alerts, danger, active states
- **#00d4ff** (Cyan): Party invites, calm states, low BPM
- **#ffcc00** (Yellow): Objectives, medium urgency, elevated BPM
- **#6b7b8f** (Muted Gray): Inactive elements, labels
- **#0a0e1a** (Deep Black): Background
- **#1a2332** (Dark Gray): Borders, inactive panels

---

## Navigation

### Swipe Gestures
The interface uses **simple horizontal swipes** for navigation:

| Gesture | Action |
|---------|--------|
| **Swipe Right** | Open Quick Controls (from Idle screen) |
| **Swipe Left** | Close Quick Controls (return to Idle) |

**Important**: The swipe threshold is set to **10 pixels** for easy access. Swiping on sliders or buttons will not trigger navigation.

### Screen Flow
```
Idle Screen ⟷ Quick Controls
     ↓
Alert Screen (auto-appears)
     ↓
Idle Screen (auto-dismiss after 3s)
```

---

## Main Screens

### 1. Idle Screen - Monitoring Mode

**When Alerts are ON:**
- Shows "MONITORING..." status
- Activity icon in red (#ff0844)
- **Heartbeat waveform** with color-coded BPM
- BPM number changes color based on stress level:
  - **Cyan (68-76 BPM)**: Resting state
  - **Yellow (80-100 BPM)**: Active/Alert
  - **Red (115-125 BPM)**: High stress/danger

**When Alerts are OFF:**
- Shows "ALERTS OFF" status
- Activity icon in gray (#6b7b8f)
- **Muted heartbeat waveform** (gray, low opacity)
- BPM still tracks but displayed in gray
- No automatic alerts will appear

**Bottom Hint**: "Swipe Right for Controls"

---

### 2. Alert Screen - Active Notifications

Alerts appear **automatically** when triggered and display:

#### Directional Alerts
For spatial threats (enemies, objectives with distance):
- **Large directional arrow** (128x128px) pointing to threat direction:
  - ↑ Front
  - ↓ Back  
  - ← Left
  - → Right
- **Distance in meters** (48px bold text)
- **Short label** describing the alert

#### Contextual Alerts
For non-spatial information (status updates, achievements):
- **Contextual icon** instead of arrow:
  - 🎯 Target: Ammo-related
  - ⚠️ Alert Triangle: Enemy warnings
  - ❤️ Heart: Health/damage-related
  - ⚡ Lightning: Ultimate/special abilities
  - 🛡️ Shield: Quest updates
  - 🏆 Award: Level ups/achievements
- **Custom information** (level number, percentage, progress)
- **Short label** describing the event

#### Party Invites (Special)
Party/team invites display a **unique interface**:
- Large users/party icon
- "PARTY INVITE" / "SQUAD INVITE" / "TEAM INVITE" / "GUILD INVITE" label
- **Sender's name** prominently displayed
- **Two action buttons**:
  - ✓ Accept (cyan, left button)
  - ✗ Deny (red outline, right button)
- **Does not auto-dismiss** - requires user action

#### Alert Behavior
- **Auto-appears** when triggered (every ~8 seconds when monitoring)
- **Auto-dismisses** after 3 seconds (except party invites)
- **Haptic feedback** triggers on appearance (if enabled)
- **BPM increases** based on alert urgency
- **Screen shake effect** simulates vibration (intensity scales with haptic setting)

---

### 3. Quick Controls - Settings Panel

Access via **swipe right** from Idle screen.

**Header**: "QUICK CONTROLS" with red divider line

**Controls** (top to bottom):

#### Alerts Toggle (Semicircle Top Button)
- **Shape**: Wide semicircular button (rounded top)
- **Active State** (Red): "ALERTS ON" with bell icon
- **Inactive State** (Gray): "ALERTS OFF" with bell-off icon
- **Function**: Enable/disable automatic alert notifications

#### Haptic Intensity Slider
- **Container**: Rounded rectangle with border
- **Range**: 0% to 100%
- **Display**: Current percentage shown on right
- **Visual**: Red gradient fill indicating intensity level
- **Function**: Adjusts strength of haptic feedback simulation
  - 0%: No haptic effects
  - 100%: Maximum screen shake and ring pulses

#### Game Profile Toggle (Semicircle Bottom Button)
- **Shape**: Wide semicircular button (rounded bottom)
- **States**: Cycles through three profiles
  - FPS (First-Person Shooter)
  - MOBA (Multiplayer Online Battle Arena)
  - RPG (Role-Playing Game)
- **Display**: Current profile name in red text with gamepad icon
- **Function**: Changes alert types to match game genre

**Bottom Hint**: "Swipe Left to Close"

---

## Alert System

### Alert Priority Levels

The system categorizes alerts into priority levels that affect display and urgency:

| Priority | Color | BPM Range | Examples |
|----------|-------|-----------|----------|
| **High** | Red | 115-125 | Taking damage, enemy <10m |
| **Medium** | Yellow | 90-100 | Enemy detected, objectives |
| **Low** | Cyan | 80-90 | Quest updates, achievements |
| **Social** | Cyan | 75-82 | Party invites |

### Visual Urgency Indicators

**High-Priority Alerts** (enemies within 10m, critical damage):
- **Corner pulse dots**: Four pulsing red dots in screen corners
- **Stronger glow**: Enhanced shadow effects
- **Screen shake**: More intense vibration simulation
- **Haptic rings**: Bright pulsing rings around watch bezel

---

## Game Profiles

Each game profile delivers **genre-specific alerts** optimized for that type of gameplay.

### FPS Mode (First-Person Shooter)

**Spatial awareness and combat-focused alerts:**

| Alert | Type | Direction | Info |
|-------|------|-----------|------|
| Enemy Left | Enemy | ← | Distance in meters |
| Hostile Right | Enemy | → | Distance in meters |
| Grenade Nearby | Damage | ↑ | Distance in meters |
| Sniper Detected | Enemy | ↓ | Distance in meters |
| Low Ammo | Status | 🎯 | Remaining rounds |
| Squad Invite | Social | 👥 | Player name |

**Best For**: Call of Duty, Battlefield, Counter-Strike, Valorant

---

### MOBA Mode (Multiplayer Online Battle Arena)

**Strategic awareness and objective-focused alerts:**

| Alert | Type | Icon | Info |
|-------|------|------|------|
| Enemy Missing | Warning | ⚠️ | Lane position (e.g., "MID") |
| Tower Attack | Damage | ❤️ | Remaining HP % |
| Dragon Spawned | Objective | ⚡ | Spawn time (e.g., "45s") |
| Gank Incoming | Enemy | ↓ | Enemy count (e.g., "3v1") |
| Ultimate Ready | Objective | ⚡ | Charge % (100%) |
| Team Invite | Social | 👥 | Player name |

**Best For**: League of Legends, Dota 2, Heroes of the Storm, Mobile Legends

---

### RPG Mode (Role-Playing Game)

**Quest progression and exploration-focused alerts:**

| Alert | Type | Direction/Icon | Info |
|-------|------|----------------|------|
| Boss Spawned | Enemy | ↑ | Distance in meters |
| Quest Updated | Objective | 🛡️ | Progress (e.g., "3/5") |
| Low Health | Damage | ❤️ | HP percentage |
| Rare Loot | Objective | → | Distance in meters |
| Level Up! | Achievement | 🏆 | New level number |
| Guild Invite | Social | 👥 | Player name |

**Best For**: World of Warcraft, Final Fantasy XIV, Elder Scrolls Online, Genshin Impact

---

## Settings & Controls

### Alerts Toggle

**Purpose**: Master switch for notification system

**States**:
- **ON** (Red button): Monitoring active, alerts will appear automatically
- **OFF** (Gray button): Silent mode, no automatic alerts

**When to Use**:
- Turn **ON** during active gameplay
- Turn **OFF** during cutscenes, menus, or breaks

---

### Haptic Intensity

**Purpose**: Controls the strength of visual haptic feedback simulation

**Range**: 0% - 100%

**Effects**:
- **Screen Shake**: Horizontal vibration effect on alert screens
  - 0%: No shake
  - 50%: Moderate shake
  - 100%: Strong shake with multiple cycles
- **Ring Pulses**: Glowing rings expanding from watch bezel
  - Opacity scales with intensity
  - More visible at higher settings
- **Glow Effects**: Drop shadow and color intensity on alerts

**Recommended Settings**:
- **0-25%**: Minimal/subtle feedback (for sensitive users)
- **50-75%**: Balanced feedback (recommended)
- **75-100%**: Maximum immersion (for intense sessions)

---

### Game Profile Selection

**Purpose**: Tailors alert types to match your current game genre

**How to Change**:
1. Swipe right to open Quick Controls
2. Tap the bottom semicircle button repeatedly to cycle through profiles
3. Current profile name is displayed (FPS → MOBA → RPG → FPS...)

**Profile Changes**:
- Takes effect immediately
- Next alert will use new profile's notification set
- BPM responses remain consistent across profiles

---

## BPM Monitor

### Overview

The **Biometric Monitoring System** displays a real-time heart rate simulation that responds dynamically to in-game events.

### Display Components

**Heartbeat Waveform** (Left):
- ECG-style line graph showing heart rhythm
- Pulses at rate matching current BPM
- Color changes based on stress level

**BPM Number** (Right):
- Large numeric display of current heart rate
- Color-coded by urgency level
- Updates every 800ms with realistic variations

### BPM States and Color Coding

| BPM Range | Color | State | Context |
|-----------|-------|-------|---------|
| 68-76 | Cyan | Resting | Idle, no threats |
| 75-82 | Cyan | Calm | Social interactions, minimal stress |
| 80-90 | Yellow | Active | Objectives, tasks, exploration |
| 90-100 | Yellow | Alert | Enemies detected at distance |
| 115-125 | Red | Danger | Critical threats, taking damage |

### Realistic Heartbeat Simulation

The BPM system includes **natural variations**:
- **Random fluctuations**: ±2 BPM every 800ms
- **Range constraints**: BPM stays within realistic bounds for each state
- **Gradual transitions**: Heart rate changes smoothly between states
- **Persistent monitoring**: BPM continues updating even with alerts off

### BPM Response Triggers

**Increases BPM**:
- Enemy alerts (especially close range)
- Damage notifications
- Critical objective updates
- High-priority events

**Maintains Elevated BPM**:
- Active gameplay states
- Multiple consecutive alerts
- Ongoing combat situations

**Returns to Resting**:
- Idle screen with no alerts
- Alerts turned off
- Extended period without events

**Example Scenario**:
1. **Idle**: BPM at 72 (cyan)
2. **"Enemy Left" 12m alert**: BPM jumps to 95-100 (yellow)
3. **Alert dismisses**: BPM gradually returns to 75-80
4. **"Taking Damage" alert**: BPM spikes to 120 (red)
5. **Return to Idle**: BPM slowly settles back to 72 over ~5 seconds

---

## Haptic Feedback

### Visual Haptic Simulation

Since this is a software interface, haptic feedback is **simulated visually** through multiple effects:

### 1. Screen Shake Effect
- **What**: Entire alert screen shakes horizontally
- **Intensity**: Scales with haptic intensity setting (0-100%)
- **Pattern**: Multiple rapid shakes (more shakes at higher intensity)
- **Timing**: Triggers immediately when alert appears

### 2. Ring Pulse Effect
- **What**: Two concentric rings expand outward from watch bezel
- **Color**: Neon red (#ff0844)
- **Opacity**: Controlled by haptic intensity percentage
- **Animation**: 600ms duration, staggered timing
- **Purpose**: Simulates vibration spreading from device edges

### 3. Icon Pulse
- **What**: Alert icon/arrow scales up briefly (110%)
- **Duration**: 300ms
- **Effect**: Creates "pop" sensation on alert appearance

### 4. Glow Intensity
- **What**: Shadow and glow effects around icons and text
- **Scaling**: Brightness increases with haptic setting
- **Purpose**: Enhances visual urgency of haptic event

### Haptic Feedback Settings

**At 0% Intensity**:
- No screen shake
- No ring pulses
- Minimal glow effects
- Alerts still appear normally

**At 50% Intensity**:
- Moderate screen shake (1-2 cycles)
- Semi-transparent ring pulses
- Balanced glow effects

**At 100% Intensity**:
- Strong screen shake (3-4 cycles)
- Bright ring pulses
- Maximum glow and shadow effects
- Most immersive experience

---

## Tips & Best Practices

### For Optimal Experience

**1. Profile Selection**
- Always match your **game profile** to the game you're playing
- Switch profiles when changing game genres for relevant alerts

**2. Haptic Settings**
- Start at **75%** and adjust based on preference
- Lower intensity for longer gaming sessions to reduce eye strain
- Higher intensity for competitive matches when urgency matters

**3. Alert Management**
- Keep alerts **ON** during active gameplay
- Turn **OFF** during story segments, inventory management, or breaks
- Remember: BPM monitor continues even with alerts off

**4. Swipe Gestures**
- Use **light swipes** to navigate (only 10px threshold)
- Swipe on empty space, not on buttons/sliders
- Quick Controls are always one swipe away

### Understanding Visual Cues

**Color = Urgency**:
- Red = Immediate action needed
- Yellow = Be aware/prepare
- Cyan = Information/social

**Size = Importance**:
- Largest: Directional arrow or main icon (what/where)
- Medium: Distance/info (how far/how much)
- Smallest: Label text (description)

**Movement = Feedback**:
- Shake = Haptic simulation
- Pulse = Active state
- Rings = Event trigger

### Troubleshooting

**Problem**: Alerts not appearing
- **Solution**: Check that Alerts toggle is ON (red button in Quick Controls)

**Problem**: Can't access Quick Controls
- **Solution**: Ensure you're on Idle screen, swipe right from anywhere on display

**Problem**: Slider exits to Idle when dragging left
- **Solution**: This has been fixed - sliders now prevent swipe gestures. Update to latest version.

**Problem**: BPM stuck at one value
- **Solution**: Normal - BPM has realistic variations (±2 BPM). Large changes occur during alerts.

**Problem**: Haptic effects too strong/weak
- **Solution**: Adjust Haptic Intensity slider in Quick Controls (0-100%)

---

## Technical Specifications

### Display
- **Size**: 420x420px circular display
- **Font**: Rajdhani (Bold & Regular weights)
- **Frame Rate**: Smooth 60fps animations
- **Color Depth**: Full RGB with glow effects

### Alert Timing
- **Appearance Frequency**: ~8 seconds (when monitoring)
- **Display Duration**: 3 seconds (auto-dismiss)
- **Party Invites**: Manual dismiss only
- **Haptic Duration**: 600ms pulse effect

### BPM System
- **Update Rate**: 800ms per variation
- **Variation Range**: ±2 BPM per update
- **Transition Speed**: Smooth 300ms color transitions
- **Pulse Animation**: Synced to actual BPM value

### Gesture Detection
- **Swipe Threshold**: 10 pixels
- **Swipe Direction**: Horizontal only
- **Touch Priority**: Controls > Gestures (sliders don't trigger swipes)

---

## Keyboard Shortcuts

This smartwatch interface is **gesture-based** and does not use keyboard shortcuts. All interactions are performed through:
- **Mouse clicks** (buttons)
- **Mouse drag** (sliders, swipe simulation)
- **Touch gestures** (on touch-enabled devices)
