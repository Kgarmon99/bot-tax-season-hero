# Tax Season Hero - Game Brief

## 1. Game Snapshot

- **Title:** Tax Season Hero
- **One-line pitch:** Help quirky clients file their taxes before the deadline while avoiding audits and maximizing refunds
- **Target player:** High school students (ages 14-18)
- **Session length:** 3-5 minutes per level
- **Platform:** Mobile first, desktop supported
- **Status:** concept

## 2. Money Concept

- **Primary concept:** taxes / deductions / audit risk / filing strategy
- **What the player learns through play:** How to read tax forms (W-2, 1099), what deductions are legitimate, how filing status and timing affect refunds, what triggers audits
- **What behavior the game rewards:** Accuracy, claiming all legitimate deductions, filing on time, understanding tax concepts
- **What misconception the game corrects:** Taxes are scary/complicated (they're learnable), all deductions are good (some are risky), refunds are free money (they're your own money returned)

## 3. Core Loop

> The player reviews client documents, selects correct forms and deductions, files before the deadline, while avoiding audit triggers and maximizing legitimate refunds.

## 4. Controls

- **Mobile controls:** Touch taps, drag-and-drop for documents, swipe to navigate
- **Desktop controls:** Mouse clicks, drag-and-drop
- **Accessibility controls:** Keyboard navigation, high contrast mode

## 5. Systems

- **Scoring:** Points for accuracy, speed bonus, deduction discovery, audit avoidance
- **Progression:** 3 levels of increasing complexity
- **Difficulty curve:** Linear progression from simple W-2 to complex multi-income scenarios
- **Win condition:** File accurate return before deadline with no audit triggers
- **Loss condition:** Miss deadline, trigger audit, or file with major errors
- **Replay hook:** Beat your best score, discover all deductions, master faster times

## 6. MoneyBot Brand

- **Mascot role:** coach — MoneyBot appears as your tax sensei with tips and encouragement
- **MoneyBot colors used:** Primary cyan (#00D4FF), electric magenta (#FF00FF), gold (#FFD700)
- **Signature MoneyBot moment:** MoneyBot pops up with "Tax Tip!" when player discovers a deduction
- **Assets required:** MoneyBot mascot avatar, client portraits, document icons, audit monster

## 7. Screens

- Start/onboarding — Hero intro, select level
- Gameplay — Document review, form selection, deduction choices, countdown timer
- Pause — Resume or restart
- Level clear/win — Score summary, refund amount, time bonus
- Loss/game over — Audit triggered or missed deadline, what went wrong

## 8. Polish Targets

- [x] Particle bursts on correct filing
- [x] Score popovers
- [ ] Haptic feedback
- [x] Smooth modal transitions
- [x] Animated HUD changes
- [x] Background motion (subtle gradient shifts)
- [x] Mascot reaction animations
- [x] Progress meter (deadline countdown)
- [ ] Sound or voice feedback
- [x] Level-up animation

## 9. Technical Plan

- **Files:** index.html (single-file game), assets/ folder for images
- **State model:** Game state, client data, player choices, timer, score
- **Rendering approach:** Vanilla JS + CSS, canvas for animations
- **Responsive strategy:** CSS Grid/Flexbox, viewport units
- **Test plan:** Play through all 3 levels, verify scoring, check mobile viewport

## 10. Done Criteria

- [ ] Loads in browser
- [ ] Works on mobile viewport
- [ ] Complete game loop
- [ ] Win/loss/restart states
- [ ] Money concept is mechanical, not just text
- [ ] MoneyBot brand is clear
- [ ] No placeholder slop
- [ ] No console errors
- [ ] Codex challenge run
- [ ] Known issues documented
