# Product Requirements Document (PRD) v1.0
## Project Highlight: AI Personal Sports Highlight System
### "The Individual Era Edition" - Social Era Edition

---

**Version:** 1.0 (Social Era Edition)  
**Date:** February 5, 2026  
**Document Owner:** Hugo Li (Project Manager / Business Scientist)  
**Status:** Initial Version - Team Assembly in Progress

**v1.0 Core Features:**
- 📹 AI Camera Rig - Automatically capture sports highlight moments
- 💾 Basic NAS Storage System - Local video storage and management
- 🧠 LOCAL AI (M4 Mac Mini) - On-device AI computation and action recognition
- 📱 Social Media One-Click Publish - Seamless sharing to IG/TikTok/YouTube
- 🏆 Personal Brand Highlight Wall - Build athletes' personal social image

---

## 📋 Table of Contents

1. [Executive Summary](#1-executive-summary)
2. [Market Opportunity](#2-market-opportunity)
3. [Product Goals & Success Metrics](#3-product-goals--success-metrics)
4. [Feature Specifications](#4-feature-specifications)
5. [Technical Architecture](#5-technical-architecture)
6. [Team Organization & Operations](#6-team-organization--operations)
7. [App Product Specifications](#7-app-product-specifications)
8. [Product Roadmap](#8-product-roadmap)
9. [Monetization Strategy](#9-monetization-strategy)
10. [Risk Management](#10-risk-management)

---

## 1. Executive Summary

### 1.1 Product Vision

Project Highlight v1.0 is an **AI-driven personal sports highlight capture system**, designed for sports enthusiasts who value their social media presence in the "Individual Era." We're not just a camera—we're an **intelligent engine that transforms every sports session into social media content**.

### 1.2 The Era Shift: From "Collective Era" to "Individual Era"

> **The fundamental change social media brought:** The past was the "Collective Era"—people sought to blend into groups and act collectively. Now is the "Individual Era"—everyone is their own brand, their own media outlet.

> **Especially prominent in sports:** Athletes and sports enthusiasts care more about their social media image than any other group. A beautiful slam dunk, a perfect goal, a game-winning three-pointer—these aren't just sports moments, they're **social currency**.

> **Our solution:** AI automatically captures every best move during your sports sessions. Every game is an opportunity to build your social media presence. Just focus on playing—we'll handle the rest.

### 1.3 Mission Statement

> "To give every sports enthusiast their own dedicated AI photographer, transforming every sports session into a personal brand highlight moment, standing out in the Individual Era."

### 1.4 Product Positioning

**What we are:** An AI-powered personal sports highlight auto-capture and social media content generation system  
**What we're NOT:**  
- ❌ Professional sports broadcasting system (we don't do pro game live streams)
- ❌ Ordinary sports camera (GoPro requires manual operation)
- ❌ Video editing software (we're not Premiere or CapCut)
- ❌ Social media platform (we're not Instagram or TikTok)

**Metaphor:** Just like Tesla Autopilot frees your hands—our AI photographer frees your attention. **You focus on playing, AI captures your highlights.**

**Core Principle:**
> "Every sports session is a social media opportunity. You perform, AI records."

### 1.5 The Hardware Trifecta

```
Project Highlight Hardware Architecture:

1. 📹 AI Camera Rig
   - Multi-angle HD camera setup
   - Automatic person tracking during sports
   - Real-time high frame rate recording

2. 💾 Basic NAS (Network Attached Storage)
   - Local video storage
   - High-speed read/write for multi-stream input
   - Automatic backup and video management

3. 🧠 LOCAL AI (M4 Mac Mini)
   - On-device AI inference computation
   - Action recognition and highlight detection
   - Video clipping and post-processing
   - No cloud required, protecting user privacy
```

---

## 2. Market Opportunity

### 2.1 Social Media Drivers in the Individual Era

**Macro Trends:**
```
Social media's impact on sports:

📊 Data speaks:
- Global social media sports content growing > 25% annually
- Athletes' personal accounts average 3-5x engagement vs. brand accounts
- "Sports highlight" short videos on TikTok/Reels average > 2x views vs. regular content
- > 70% of Gen Z consume sports content through social media

🎯 Core Insight:
- In the "Individual Era," every athlete (pro or amateur) wants to build their personal brand
- Pain point: Can't play and record simultaneously → best moments often missed
- Current solutions: Ask friends to film → unreliable, bad angles, frequently missed
```

### 2.2 Target Users

**Primary Users:**

| User Type | Description | Pain Point | Our Value |
|-----------|-------------|------------|-----------|
| 🏀 Recreational Court Players | Enthusiasts playing 2-3 times/week | No one to film, miss great moments | AI auto-captures every highlight |
| ⚽ Community Team Members | Players in amateur leagues | Want game highlights but no dedicated filmer | Auto-generate personal highlights post-game |
| 🎾 Individual Sport Enthusiasts | Tennis/Badminton/Table Tennis players | Want to analyze form or show off great plays | AI identifies best shot moments |

**Secondary Users:**

| User Type | Description | Potential Value |
|-----------|-------------|----------------|
| 🏟️ Venue Operators | Indoor/outdoor sports facilities | Value-added service, increase rental competitiveness |
| 🏋️ Fitness Coaches | Personal trainers/group instructors | Record student progress, create teaching materials |
| 🎓 School Athletics | School sports departments | Team game records, recruitment content |

### 2.3 Competitive Landscape

```
Existing Solutions vs. Project Highlight:

❌ GoPro / Action Cameras:
   - Requires manual operation and mounting
   - No AI action recognition
   - Post-editing entirely self-service

❌ Ask Friends to Film:
   - Unreliable, frequently miss moments
   - Takes one person out of the game
   - Uncontrollable angles and quality

❌ Professional Film Crew:
   - Expensive ($500-2000/session)
   - Only viable for important games
   - Cannot cover everyday sports

✅ Project Highlight:
   - AI auto-capture, zero manual operation
   - Local AI real-time highlight detection
   - Receive edited highlights immediately after session
   - One-click share to social media
   - Monthly subscription covers every session
```

---

## 3. Product Goals & Success Metrics

### 3.1 Core Goals

| Goal | Metric | Target | Timeframe |
|------|--------|--------|-----------|
| 🎯 Highlight Capture Accuracy | % of key moments correctly captured | > 85% | v1.0 |
| ⏱️ End-to-End Latency | From action to video generation | < 15 minutes | v1.0 |
| 📱 Social Share Rate | % of users sharing after receiving highlights | > 40% | 3 months post-launch |
| 🔄 User Retention | Users returning ≥ 4x/month | > 60% | 6 months post-launch |
| ⭐ User Satisfaction | NPS Score | > 50 | 6 months post-launch |

### 3.2 North Star Metric

> **Monthly number of highlight videos shared to social media per user**
> 
> This metric simultaneously reflects:
> 1. AI capture quality (users deem it worthy of sharing)
> 2. User engagement (continued usage)
> 3. Core product value (helping users build social presence)
> 4. Organic growth potential (sharing = free user acquisition)

---

## 4. Feature Specifications

### 4.1 Core Feature Modules

#### 4.1.1 AI Smart Capture Engine 📹

**Core Logic:** AI automatically identifies "highlight actions" during sports and captures them in real-time

**Action Recognition Capabilities (v1.0 Priority):**

| Sport Type | Detectable Actions | Detection Method | Priority |
|-----------|-------------------|-----------------|----------|
| 🏀 Basketball | Goals, Dunks, Blocks, Steals | Ball trajectory tracking + Rim vibration sensing | P0 |
| ⚽ Football/Soccer | Goals, Skillful dribbles, Long shots | Net vibration detection + Ball trajectory | P1 |
| 🎾 Tennis/Badminton | Smashes, Winners, Spectacular rallies | Swing action recognition + Ball speed | P2 |

**Capture Pipeline:**
```
During Sports Session:
1. Multi-camera synchronized recording (continuous)
2. M4 Mac Mini runs AI action recognition in real-time
3. Highlight action detected → Timestamp marked
4. Auto-clip 10-30 seconds before/after
5. Select best camera angle
6. Generate highlight video → Store in NAS
7. Push notification to user's phone

User Receives Notification:
8. Preview highlight clip
9. Select filter/music/text overlay
10. One-click share to IG/TikTok/YouTube Shorts
```

**AI Capture Decision Logic:**
```python
class HighlightDetector:
    """AI Highlight Detection Engine"""
    
    def __init__(self):
        self.action_models = {
            'basketball': BasketballActionModel(),
            'football': FootballActionModel(),
            'tennis': TennisActionModel()
        }
        self.highlight_threshold = 0.75  # Highlight confidence threshold
    
    def detect_highlight(self, video_frame, sport_type, sensor_data):
        """
        Real-time highlight action detection
        
        Args:
            video_frame: Current video frame
            sport_type: Sport type
            sensor_data: Sensor data (rim vibration, net detection, etc.)
        
        Returns:
            {
                'is_highlight': bool,
                'confidence': float,    # 0-1
                'action_type': str,     # 'goal', 'dunk', 'save', etc.
                'timestamp': datetime,
                'camera_angles': list,  # Recommended angles
                'clip_range': tuple     # (start_sec, end_sec)
            }
        """
        model = self.action_models.get(sport_type)
        if not model:
            return {'is_highlight': False}
        
        # Combine visual recognition with sensor data
        visual_score = model.analyze_frame(video_frame)
        sensor_score = model.analyze_sensor(sensor_data)
        
        # Weighted fusion
        combined_score = visual_score * 0.6 + sensor_score * 0.4
        
        if combined_score >= self.highlight_threshold:
            return {
                'is_highlight': True,
                'confidence': combined_score,
                'action_type': model.classify_action(video_frame),
                'timestamp': datetime.now(),
                'camera_angles': self.rank_camera_angles(video_frame),
                'clip_range': self.calculate_clip_range(combined_score)
            }
        
        return {'is_highlight': False, 'confidence': combined_score}
```

#### 4.1.2 Local AI Engine (M4 Mac Mini) 🧠

**Core Logic:** All AI computation completed locally, no cloud upload required, protecting user privacy

**M4 Mac Mini Compute Architecture:**
```
M4 Mac Mini Local AI Pipeline:

┌─────────────────────────────────────────────────────┐
│  📹 Multi-Camera Input (Camera Feeds)                │
│  → 2-4 streams at 1080p/60fps                        │
├─────────────────────────────────────────────────────┤
│  🧠 AI Inference Engine (Neural Engine)              │
│  → Action Detection Model                            │
│  → Person Tracking Model                             │
│  → Object Recognition Model (Ball/Rim/Net)           │
├─────────────────────────────────────────────────────┤
│  ✂️ Smart Clip Engine                                │
│  → Auto-select optimal time range                    │
│  → Auto-select best camera angle                     │
│  → Auto-add slow-motion replay                       │
├─────────────────────────────────────────────────────┤
│  💾 Store to NAS → 📱 Push notification to App      │
└─────────────────────────────────────────────────────┘
```

**Why M4 Mac Mini?**
```
M4 Mac Mini Advantages:

1. Apple Neural Engine
   - 38 TOPS (38 trillion operations/second)
   - Optimized for AI/ML inference
   - Low power, high performance

2. Unified Memory Architecture
   - 16/24GB unified memory
   - GPU and Neural Engine share memory
   - Multi-stream video processing with ease

3. Local Compute Advantages
   - Zero network latency (critical!)
   - User data never leaves the venue
   - No cloud GPU costs
   - Works even without internet

4. Cost Efficiency
   - One-time purchase ~$600-800 USD
   - vs Cloud GPU: $0.5-3/hour
   - ROI within 6 months
```

#### 4.1.3 NAS Storage System 💾

**Core Logic:** High-speed local storage ensuring multi-stream simultaneous writes without frame drops

**NAS Architecture:**
```
Basic NAS Configuration:

Hardware Specs:
- 2-Bay NAS (e.g., Synology DS224+)
- 2 × 4TB HDD (RAID 1 Mirror)
- Effective Storage: 4TB
- 10GbE Network Connection

Storage Strategy:
- Raw video: Retain 7 days, then auto-purge
- Highlight clips: Permanent (user can manually delete)
- AI decision logs: Permanent
- Est. raw video per session: ~50GB
- Est. highlight clips per session: ~2GB

Storage Capacity Estimate:
- 4TB effective space
- 2 sessions/day = ~104GB raw + ~4GB highlights
- 7-day raw video cycle = ~728GB
- Highlight accumulation: ~60GB/month
- Expected usable > 12 months before expansion needed
```

#### 4.1.4 Social Media Integration 📱

**Core Logic:** Enable users to share to social media within 3 steps of receiving a highlight notification

**Sharing Flow:**
```
User Experience Flow:

Step 1: 📱 Receive Push Notification
   "That dunk was insane! Tap to view your highlight clip"

Step 2: 👀 Preview Highlight
   - Auto-clipped 15-60 second segment
   - Best angle auto-selected
   - Slow-motion replay auto-added

Step 3: 🎨 Customize (Optional)
   - Select filter style
   - Add background music
   - Add text/hashtags
   - Adjust clip length

Step 4: 🚀 One-Click Publish
   - Instagram Reels
   - TikTok
   - YouTube Shorts
   - WhatsApp / WeChat (private share)
```

**Social Media Templates:**
```
Pre-built Template Library:

🔥 "Highlight Reel" Template
   - Multiple highlights compiled
   - High-energy background music
   - Auto session/date watermark

💪 "Best Play" Template
   - Single spectacular moment
   - Slow-motion + normal speed replay
   - Bold action label ("DUNK!", "GOAL!")

📊 "Stats Card" Template
   - Data card style
   - Display sports stats (points, shooting %, etc.)
   - Optimized for Story format

🏆 "MVP" Template
   - Best performance compilation
   - Paired with hype music
   - Optimized for Reels/Shorts
```

---

## 5. Technical Architecture

### 5.1 System Architecture Diagram

```
┌─────────────────────────────────────────────────────────────┐
│                    On-Site (Venue)                           │
│                                                             │
│  ┌─────────┐   ┌─────────┐   ┌─────────┐   ┌──────────┐   │
│  │ Camera 1│   │ Camera 2│   │ Camera 3│   │ Camera 4 │   │
│  └────┬────┘   └────┬────┘   └────┬────┘   └────┬─────┘   │
│       │             │             │              │          │
│       └─────────────┼─────────────┼──────────────┘          │
│                     │             │                          │
│                     ▼             ▼                          │
│              ┌──────────────────────────┐                    │
│              │   🧠 M4 Mac Mini         │                    │
│              │   (Local AI Engine)      │                    │
│              │   - Action Detection     │                    │
│              │   - Person Tracking      │                    │
│              │   - Smart Clipping       │                    │
│              └────────────┬─────────────┘                    │
│                           │                                  │
│                           ▼                                  │
│              ┌──────────────────────────┐                    │
│              │   💾 NAS Storage          │                    │
│              │   - Raw Video (7-day)    │                    │
│              │   - Highlight Clips      │                    │
│              │   - AI Decision Logs     │                    │
│              └────────────┬─────────────┘                    │
│                           │                                  │
└───────────────────────────┼──────────────────────────────────┘
                            │ (WiFi / 4G)
                            ▼
┌───────────────────────────────────────────────────────────────┐
│                    User Side                                   │
│                                                               │
│  ┌─────────────────────────────────────────────────────────┐  │
│  │  📱 Mobile App (Flutter)                                 │  │
│  │  - Highlight Preview                                    │  │
│  │  - Social Media Share                                   │  │
│  │  - Highlight Wall (Personal Brand)                      │  │
│  │  - Stats & Analytics                                    │  │
│  └─────────────────────────────────────────────────────────┘  │
│                                                               │
└───────────────────────────────────────────────────────────────┘
```

### 5.2 Tech Stack

| Layer | Technology | Rationale |
|-------|-----------|-----------|
| AI Inference | CoreML + Apple Neural Engine | M4 native optimization, low latency |
| Video Processing | FFmpeg + AVFoundation | Industrial-grade video processing |
| Local Server | Swift/Python on macOS | M4 native development |
| NAS Communication | SMB / NFS | High-speed local transfer |
| Mobile App | Flutter | iOS/Android dual-platform |
| Backend API | FastAPI (Python) | Lightweight, high performance |
| Database | SQLite (local) + PostgreSQL (cloud) | Local-first architecture |
| Push Notifications | Firebase Cloud Messaging | Cross-platform push |

### 5.3 AI Model Architecture

```
AI Model Hierarchy:

Level 1: Base Vision Models
- Person Detection (YOLO v8)
- Ball Tracking (Custom Tracking)
- Court Boundary Recognition

Level 2: Action Recognition Models
- Skeleton Estimation (Pose Estimation)
- Action Classification
- Trigger Condition Recognition (Goals, Dunks, etc.)

Level 3: Highlight Scoring Model
- Action Fluidity Score
- Difficulty Coefficient Assessment
- Entertainment Index Calculation
- Final Confidence Output

Level 4: Video Generation Model
- Best Angle Selection
- Optimal Time Clipping
- Slow-Motion Generation
- Image Stabilization
```

### 5.4 End-to-End Latency Budget

```
Latency Budget (Target < 15 minutes):

Action Detection:          ~200ms (real-time)
Video Segment Extraction:  ~30s
AI Highlight Scoring:      ~10s
Smart Clipping:            ~2 min
Post-Processing (filter/stabilize): ~3 min
NAS Write:                 ~1 min
Push Notification:         ~5s
App Preview Load:          ~10s
─────────────────────────
Total:                     ~7 min (well below 15-min target)

⚠️ Peak loads (multiple simultaneous highlights) may stack to ~12 min
```

---

## 6. Team Organization & Operations

### 6.1 Team Philosophy

```
Lean Team Philosophy:

In the "Individual Era," we achieve maximum AI product output with minimum headcount.

Core Principles:
1. One person, multiple roles: Role overlap permitted during early stages
2. Technical isolation: Lawrence does NOT participate in daily development, 
   provides only underlying AI algorithm consultation
3. Decision ownership: All product feature and monetization decisions 
   belong to Hugo Li and his team

Team Configuration:
- Hugo Li (Project Manager/BS): 1 person, confirmed
- Remaining 4 roles: All tentative, pending recruitment or outsourcing

Advantages:
✅ Rapid decision-making (PM has direct control)
✅ Minimal cost (≤ 5 people initially)
✅ Technical focus (local AI, no complex cloud architecture)
✅ Efficient communication (flat structure)
```

### 6.2 Team Structure

#### 6.2.1 The Commander 🎖️ — Project Lead

**Personnel:** Hugo Li  
**Role:** Project Manager / Business Scientist (BS)  
**Status:** ✅ Confirmed

**PM Responsibilities:**
- **Requirements Definition:** Interface with clients (venue operators or sports brands) to define social media requirement specs for the "Individual Era"
- **Use Case Planning:** Define AI capture use cases (e.g., basketball goal detection, football net vibration recognition)
- **Progress Control:** Ensure hardware (camera rig, NAS) and software (Local AI) integration stays on track with the product roadmap
- **Business Decisions:** Pricing strategy, partnership development, market positioning

**BS Responsibilities:**
- **Client Communication:** Interface with venue operators, sports brands for requirements
- **Spec Definition:** Translate client needs into technical specifications
- **Acceptance Criteria:** Define acceptance criteria and QA process for each feature

**Time Commitment:** Full-time  
**Key Deliverables:**
- Product roadmap and milestones
- Client requirements documentation
- Feature acceptance criteria
- Team recruitment and management

#### 6.2.2 The Architect 🎨 — Visual & Experience Design

**Personnel:** [TBD - Pending Recruitment]  
**Role:** UI/UX Designer  
**Status:** ⏳ Planned Recruitment

**Responsibilities:**
- **Interface Design:** Create a Highlight Wall and Reels editing panel that embodies personal brand aesthetics
- **User Flows:** Design seamless experience from "session ends" to "receiving highlight notification"
- **Brand Visual Identity:** Establish Project Highlight's brand identity system
- **Social Media Templates:** Design template library (Highlight Reel, Best Play, Stats Card, MVP)

**Time Commitment:** Part-time / Contract  
**Key Deliverables:**
- Complete App UI/UX design files (Figma)
- Social media share template designs
- Brand identity system
- Highlight Wall interface design

#### 6.2.3 The Face 💻 — Frontend Development

**Personnel:** [TBD - Pending Recruitment]  
**Role:** Frontend Developer  
**Status:** ⏳ Planned Recruitment

**Responsibilities:**
- **Cross-Platform Development:** Build iOS/Android dual-platform App using Flutter
- **Visual Implementation:** Implement frontend interface for AI highlight preview and social media sharing flow
- **Video Player:** Develop high-performance video preview and editing components
- **Real-Time Notifications:** Integrate push notification system

**Time Commitment:** Full-time / Contract  
**Key Deliverables:**
- Flutter App MVP version
- Video preview and editing components
- Social media sharing functionality
- Push notification integration

#### 6.2.4 The Engine ⚙️ — Backend & Data Architecture

**Personnel:** [TBD - Pending Recruitment]  
**Role:** Backend Developer / Database Designer  
**Status:** ⏳ Planned Recruitment

**Responsibilities:**
- **System Architecture:** Manage data upload logic from M4 Mac Mini local compute and NAS storage integration
- **Database Design:** Build AI decision log tables and user video database, ensure 24/7 high availability
- **API Development:** Develop communication API between local system and App
- **Video Pipeline:** Build complete pipeline from capture to storage to push notification

**Core Database Schema:**
```sql
-- Users table
CREATE TABLE users (
    id UUID PRIMARY KEY,
    display_name VARCHAR(100),
    avatar_url TEXT,
    social_accounts JSONB,  -- Linked social media accounts
    sport_preferences JSONB,
    created_at TIMESTAMP DEFAULT NOW()
);

-- Highlights table
CREATE TABLE highlights (
    id UUID PRIMARY KEY,
    user_id UUID REFERENCES users(id),
    sport_type VARCHAR(50),
    action_type VARCHAR(50),
    confidence FLOAT,
    video_url TEXT,
    thumbnail_url TEXT,
    duration_sec INT,
    camera_angle VARCHAR(20),
    ai_score FLOAT,
    shared_to JSONB,  -- Platforms shared to
    created_at TIMESTAMP DEFAULT NOW()
);

-- AI Decision Logs table
CREATE TABLE ai_decision_logs (
    id BIGSERIAL PRIMARY KEY,
    session_id UUID,
    timestamp TIMESTAMP,
    action_detected VARCHAR(50),
    confidence FLOAT,
    was_highlight BOOLEAN,
    processing_time_ms INT,
    model_version VARCHAR(20)
);

-- Sessions table
CREATE TABLE sessions (
    id UUID PRIMARY KEY,
    venue_id UUID,
    sport_type VARCHAR(50),
    start_time TIMESTAMP,
    end_time TIMESTAMP,
    total_highlights INT,
    participants JSONB
);
```

**Time Commitment:** Full-time / Contract  
**Key Deliverables:**
- Complete database architecture
- Local API service
- NAS storage pipeline
- Video processing pipeline

#### 6.2.5 The Gatekeeper 🛡️ — Quality Assurance

**Personnel:** [TBD - Pending Recruitment / Internal Assignment]  
**Role:** QA / Testing  
**Status:** ⏳ Expected to be initially handled by Backend Developer

**Responsibilities:**
- **Functional Testing:** Stress test multi-camera synchronization and AI action recognition accuracy
- **Latency Monitoring:** Ensure action-to-video generation meets end-to-end latency requirements (target < 15 minutes)
- **AI Accuracy Validation:** Regularly assess highlight capture accuracy (target > 85%)
- **Compatibility Testing:** Ensure App runs correctly across major phone models

**Test Matrix:**
```
QA Test Scope:

📹 Hardware Testing:
- Multi-camera sync precision (frame-level alignment)
- NAS write speed (multi-stream simultaneous writes)
- M4 Mac Mini long-run stability

🧠 AI Accuracy Testing:
- Highlight detection accuracy > 85%
- False positive rate (non-highlights marked) < 10%
- False negative rate (highlights missed) < 15%

📱 App Testing:
- Video preview smoothness
- Social media share success rate
- Push notification delivery rate
- Cross-platform compatibility (iOS/Android)

⏱️ Performance Testing:
- End-to-end latency < 15 minutes
- Peak load stability (multiple simultaneous highlights)
- 8-hour continuous operation without crashes
```

**Time Commitment:** Part-time (initially handled by Backend Developer)  
**Key Deliverables:**
- Test plan and test cases
- Per-release test reports
- AI accuracy tracking reports
- Performance benchmark reports

### 6.3 Team Collaboration

**Weekly Sync:**
- **Time:** Every Monday [TBD]
- **Participants:** Hugo Li (PM) + All members
- **Agenda:**
  1. Previous week progress report
  2. Current week goal setting
  3. Technical issue discussion
  4. Test results review

**Communication:**
- **Tools:** Slack (instant messaging), GitHub (code), Figma (design), Notion (docs)
- **Response Time:** < 4 hours (business days)
- **Emergency Contact:** Phone / WhatsApp

**Technical Advisor:**
```
Lawrence's Role Definition:

⚠️ Clear Boundary: Lawrence does NOT participate in daily development

✅ Can Provide:
- Underlying AI algorithm logic consultation
- Action recognition model architecture suggestions
- CoreML optimization guidance

❌ Not Responsible For:
- Day-to-day code development
- Testing and deployment
- Project management and progress tracking
- Client communication
```

---

## 7. App Product Specifications

### 7.1 App Architecture (Flutter)

**Platform Support:**
- iOS 14.0+
- Android 8.0+ (API Level 26+)

**Core Feature Modules:**
1. **Highlight Viewer** - Real-time preview of AI-captured highlights
2. **Social Share Hub** - One-click publish to multiple platforms
3. **Highlight Wall** - Showcase personal sports highlights, build personal brand
4. **Sports Analytics** - Sports performance data visualization

### 7.2 Core Page Designs

**Home - Highlight Wall:**
```
┌─────────────────────────────────────────────┐
│  🏆 Project Highlight                       │
│  ─────────────────────────────────────────  │
│                                             │
│  📅 Today's Highlights                      │
│  ┌───────┐  ┌───────┐  ┌───────┐           │
│  │ 🏀    │  │ 🏀    │  │ 🏀    │           │
│  │ Dunk  │  │ 3-Ptr │  │ Steal │           │
│  │ 95pts │  │ 88pts │  │ 82pts │           │
│  └───────┘  └───────┘  └───────┘           │
│                                             │
│  📊 This Week                               │
│  ┌─────────────────────────────────────┐    │
│  │ Sessions: 5 │ Highlights: 23 │ Shared: 12│
│  └─────────────────────────────────────┘    │
│                                             │
│  🔥 Best Play                               │
│  ┌─────────────────────────────────────┐    │
│  │  [Video Thumbnail - Today's Best Dunk] │  │
│  │  ▶️ AI Score: 97/100                │    │
│  │  [Share] [Download] [Edit]           │    │
│  └─────────────────────────────────────┘    │
│                                             │
│  [Home] [Wall] [Share] [Stats] [Settings]   │
└─────────────────────────────────────────────┘
```

**Share Page:**
```
┌─────────────────────────────────────────────┐
│  ← Back        Share Highlight       ✓ Post │
│  ─────────────────────────────────────────  │
│                                             │
│  [Video Preview Area - 16:9]                │
│  ┌─────────────────────────────────────┐    │
│  │                                     │    │
│  │         ▶️ Play Preview             │    │
│  │                                     │    │
│  └─────────────────────────────────────┘    │
│                                             │
│  🎨 Template                                │
│  [Highlight] [Best Play] [Stats] [MVP]      │
│                                             │
│  🎵 Background Music                        │
│  [🔥 Hype] [🎵 Chill] [🎸 Rock] [No Music]│
│                                             │
│  📝 Caption/Hashtags                        │
│  "That dunk was insane 🔥 #basketball #dunk"│
│                                             │
│  📤 Publish to                              │
│  [✅ Instagram] [✅ TikTok] [YouTube]       │
│                                             │
└─────────────────────────────────────────────┘
```

---

## 8. Product Roadmap

### 8.1 Phase Planning

```
Phase 0: Team Assembly & Planning (Month 1-2)
──────────────────────────────────────
✅ PRD Complete
⬜ Recruit team (UI/UX, Frontend, Backend)
⬜ Hardware procurement planning (cameras, NAS, M4 Mac Mini)
⬜ Technical feasibility validation (AI model POC)

Phase 1: Core MVP (Month 3-6)
──────────────────────────────────────
⬜ Single camera + Basketball goal detection
⬜ M4 Mac Mini AI Pipeline setup
⬜ Basic highlight clipping functionality
⬜ Flutter App base architecture
⬜ NAS storage integration
⬜ Internal testing

Phase 2: Multi-Camera + Social Integration (Month 7-10)
──────────────────────────────────────
⬜ Multi-camera synchronization (2-4 streams)
⬜ Social media sharing features
⬜ Highlight Wall
⬜ Share template library
⬜ First partner venue Beta test

Phase 3: AI Enhancement + Sport Expansion (Month 11-15)
──────────────────────────────────────
⬜ Football/Soccer action recognition
⬜ Tennis/Badminton action recognition
⬜ AI highlight scoring optimization
⬜ Personal analytics dashboard
⬜ Multi-venue deployment

Phase 4: Commercialization + Scale (Month 16+)
──────────────────────────────────────
⬜ Official commercial launch
⬜ B2B venue partnership program
⬜ B2C subscription launch
⬜ Brand partnerships & advertising system
```

### 8.2 Milestones

| Milestone | Timeline | Deliverable | Success Criteria |
|-----------|----------|-------------|-----------------|
| M0: Team Ready | Month 2 | Complete team + Hardware in place | All roles filled |
| M1: AI POC | Month 4 | Single-camera basketball goal detection | Accuracy > 70% |
| M2: MVP Complete | Month 6 | Usable end-to-end system | Latency < 15min |
| M3: Beta Launch | Month 10 | First partner venue deployment | User satisfaction > 70% |
| M4: Commercial Launch | Month 16 | Paid service live | MRR > $5K |

---

## 9. Monetization Strategy

### 9.1 Business Model

**Dual-Track Model:**

```
B2B Model (Venue Partnerships):
┌─────────────────────────────────────────┐
│  💰 Installation Fee: $X,XXX (one-time) │
│  📅 Monthly Fee: $XXX/mo (maintenance   │
│     + AI upgrades)                      │
│  💡 Value: Attract more customers,      │
│     increase venue competitiveness      │
└─────────────────────────────────────────┘

B2C Model (Individual Users):
┌─────────────────────────────────────────┐
│  🆓 Free: 1 highlight/session           │
│     (with watermark)                    │
│  ⭐ Basic: $X.99/mo - Unlimited         │
│     highlights + no watermark           │
│  🏆 Pro: $XX.99/mo - All templates     │
│     + analytics                         │
└─────────────────────────────────────────┘
```

### 9.2 Revenue Projections (Conservative)

| Timeline | B2B Revenue | B2C Revenue | Monthly Total |
|----------|------------|------------|---------------|
| Month 10-12 | 2 venues × $XXX | 50 users × $X | ~$X,XXX |
| Month 13-18 | 5 venues × $XXX | 200 users × $X | ~$X,XXX |
| Month 19-24 | 15 venues × $XXX | 1000 users × $X | ~$XX,XXX |

*Note: Specific pricing to be determined after market research*

---

## 10. Risk Management

### 10.1 Technical Risks

**Risk 1: AI Action Recognition Accuracy Insufficient**
- **Likelihood:** Medium-High (early models need extensive training data)
- **Impact:** High (core product experience)
- **Mitigation:**
  - Focus initially on basketball goals (easiest to detect)
  - Combine sensor data (rim vibration) to reduce pure visual dependency
  - Continuously collect data to improve models
  - Lawrence provides AI algorithm consultation

**Risk 2: M4 Mac Mini Compute Bottleneck**
- **Likelihood:** Low-Medium (M4 Neural Engine is powerful)
- **Impact:** Medium (affects latency and throughput)
- **Mitigation:**
  - Optimize model quantization (INT8/FP16)
  - Prioritize high-confidence actions
  - Upgrade to M4 Pro/Max if expansion needed

**Risk 3: Multi-Camera Synchronization Challenges**
- **Likelihood:** Medium (time sync is a common challenge)
- **Impact:** Medium (affects multi-angle highlight quality)
- **Mitigation:**
  - Use NTP time synchronization
  - Audio sync as backup method
  - Start with 2 cameras initially

### 10.2 Business Risks

**Risk 4: Low Venue Partnership Willingness**
- **Likelihood:** Medium (new concept requires market education)
- **Impact:** High (B2B is core revenue source)
- **Mitigation:**
  - Offer free trial period (1-3 months)
  - Prove customer attraction effectiveness with data
  - Build a showcase case from 1 venue

**Risk 5: User Privacy Concerns**
- **Likelihood:** Medium-High (cameras in public spaces raise concerns)
- **Impact:** High (may hinder adoption)
- **Mitigation:**
  - All AI computation done locally (no cloud upload)
  - Clear privacy policy and venue signage
  - Users must actively register to be tracked by AI
  - Non-registered individuals' faces auto-blurred

### 10.3 Operational Risks

**Risk 6: Team Recruitment Difficulty**
- **Likelihood:** Medium (requires specific skill combinations)
- **Impact:** Medium-High (affects development timeline)
- **Mitigation:**
  - Allow remote/part-time/contract work
  - Early-stage role overlap (Backend + QA)
  - Consider outsourcing portions if needed

**Risk 7: Hardware Cost Overrun**
- **Likelihood:** Low-Medium
- **Impact:** Medium (affects per-venue deployment cost)
- **Mitigation:**
  - Start with minimal configuration (2 cameras + basic NAS + M4 Mac Mini)
  - Prepare detailed hardware BOM (Bill of Materials)
  - Seek volume purchase discounts

---

## Document Revision History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | 2026-02-05 | Hugo Li (PM) | Initial PRD creation |

---

**Next Action Items:**

1. **Hugo Li (PM/BS):**
   - Begin UI/UX Designer recruitment
   - Begin Frontend / Backend Developer recruitment
   - Hardware procurement list and budget
   - First partner venue outreach

2. **[TBD] UI/UX Designer:**
   - App home page and Highlight Wall design
   - Social media sharing flow design
   - Initial share template designs

3. **[TBD] Frontend Developer:**
   - Flutter development environment setup
   - App architecture design
   - Video player component research

4. **[TBD] Backend Developer:**
   - M4 Mac Mini development environment setup
   - Database architecture design
   - AI Pipeline prototype development

5. **[TBD] QA:**
   - Develop test plan
   - Establish AI accuracy baselines

6. **All:**
   - Kickoff meeting: Confirm timeline and responsibilities
   - Establish Slack collaboration channels
   - Set weekly meeting schedule

---

*This document is the core product requirements document for Project Highlight. Distribution without permission is prohibited.*

**In the Individual Era, make every sports session your highlight moment.**

> "Every sports session is a social media opportunity. You perform, AI records."
