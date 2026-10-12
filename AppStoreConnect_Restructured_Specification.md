# DeskStacks — App Store Connect (Restructured Layout) Master Specification

> **Application**: DeskStacks  
> **Platform**: macOS 14.0 Sonoma & newer (Apple Silicon M1–M4 & Intel x86_64)  
> **Target Release**: Version 1.0.0 (Build 27)  
> **Developer Entity**: Rareș-Mihail Cristea  
> **Official Public Repository**: [https://github.com/raresmihailcristea-cmyk/deskstacks](https://github.com/raresmihailcristea-cmyk/deskstacks)  
> **Live Documentation Base**: [https://raresmihailcristea-cmyk.github.io/deskstacks/](https://raresmihailcristea-cmyk.github.io/deskstacks/)

---

## A. Secțiunea Product Page Information

### 1. Promotional Text (max 170 caractere)
```text
Organize your Mac desktop with floating Liquid Glass stacks, smart reminders, natural language scheduling, quick scratchpad, and 1-click desktop sweeps.
```
*(Exact character count: 153 / 170)*

---

### 2. Description (max 4000 caractere)
```text
DeskStacks transforms your macOS desktop into an organized, high-efficiency command center.

Say goodbye to cluttered desktop screens, lost downloads, and scattered finder windows. DeskStacks introduces intelligent floating stacks, sleek glanceable capsules, an integrated Reminders & Calendar studio, a quick Markdown scratchpad, and 1-click desktop organization—all wrapped in native Liquid Glass aesthetics.

🌟 KEY FEATURES

• FLOATING DESKTOP STACKS & SLEEK CAPSULES
- Organize any folder, iCloud directory, or external volume into floating glass stacks.
- Collapse full stacks into compact, glanceable capsules displaying live item counts and badges.
- 6-Anchor Snapping: Dock capsules along the screen edges (Top Left, Top Right, Bottom Left, Bottom Right, Center, or custom coordinates).
- Quick Reveal (Option + Space / F7): Instantly bring all active stacks to the front of your screen.

• 1-CLICK DESKTOP SWEEP
- Instantly clear desktop clutter with Command + Shift + W.
- Intelligently organizes loose screenshots, PDFs, downloads, and stray files into structured archive directories.
- Optional toggle to hide native macOS desktop icons for an ultra-clean workspace.

• REMINDERS & CALENDAR STUDIO
- Native two-way synchronization with Apple Reminders and Apple Calendar.
- Natural Language Schedule Parsing: Simply type or speak "Meet Alex tomorrow at 3pm" and DeskStacks schedules it instantly.
- World Time & International Scheduler: Track colleagues across global time zones directly from your desktop.

• QUICK SCRATCHPAD & VOICE DICTATION
- Always-ready Markdown notepad floating on your desktop for rapid thoughts, code snippets, and to-do lists.
- 1-Click Apple Notes Export: Sync any scratchpad note directly to native Apple Notes.
- Smart Voice Intelligence (Option + V): Hands-free speech-to-text dictation powered by Apple's on-device speech recognition framework.

• SPOTLIGHT-FAST OMNISEARCH
- Lightning-fast fuzzy search window (Command + Shift + F or Option + F).
- Query files across all active stacks, scratchpad notes, reminders, and recent clipboard history without leaving your workflow.

• NATIVE APPLE MUSIC MINI-PLAYER
- Control Apple Music directly from a dedicated desktop stack.
- Displays live album artwork, track progress, playlist browsing, and playback controls.

• DUAL DISPLAY LAYER MODES
- Desktop Pinned Mode: Stacks sit directly above your desktop wallpaper behind other windows, creating a living interactive desktop layer.
- Floating HUD Mode: Stacks float above all application windows for rapid drag-and-drop file staging.

• LIQUID GLASS DESIGN & COLOR THEMES
- Native macOS translucent materials (.ultraThinMaterial), smooth spring animations, and 5 customizable neon accent themes.

🔒 ZERO-KNOWLEDGE & 100% ON-DEVICE PRIVACY
• 100% Offline: DeskStacks requires zero internet connection to manage files, notes, or reminders.
• Zero Data Collection: No tracking, no telemetry, no analytics, no cookies.
• Native Apple Silicon Optimization: Extremely lightweight binary with minimal CPU and memory footprint.
• Apple App Sandbox compliant.

PRICING & FREE TRIAL
DeskStacks includes an unrestricted 14-day Free Trial across all features. Choose between flexible monthly ($1.60/mo), yearly ($19.99/yr), or permanent Lifetime Pass ($34.99).
```
*(Exact character count: 3,254 / 4000)*

---

### 3. Keywords (max 100 caractere)
```text
desktop,stacks,organizer,workspace,reminders,calendar,widget,scratchpad,notes,macos,sweep,dock
```
*(Exact character count: 95 / 100)*

---

### 4. URLs
* **Support URL**: `https://raresmihailcristea-cmyk.github.io/deskstacks/support.html`
* **Marketing URL**: `https://raresmihailcristea-cmyk.github.io/deskstacks/`

---

### 5. App Review Information — Notes (max 4000 caractere)
```text
Dear Apple App Review Team,

Thank you for reviewing DeskStacks for macOS.

OVERVIEW:
DeskStacks is a native macOS productivity and desktop workspace manager. It introduces floating Liquid Glass stacks for folders, an integrated Reminders & Calendar studio, a quick Markdown scratchpad, Apple Music playback controls, and a 1-click desktop sweep utility.

HOW TO TEST THE APPLICATION:
1. LAUNCH & FLOATING STACKS:
   - Upon launching, DeskStacks places a status item in the macOS menu bar and initializes default desktop stacks.
   - Use the menu bar icon (or press Command + N) to add a Folder stack, Reminders stack, or Scratchpad.
   - Click the capsule toggle button on any stack header to collapse it into a compact floating pill, or drag it to reposition.
   - Press Option + Space (or F7) to trigger "Quick Reveal", bringing all stacks to the foreground.

2. 1-CLICK DESKTOP SWEEP:
   - Place a test screenshot or file on your macOS desktop.
   - Select "1-Click Desktop Sweep" from the menu bar icon (or press Command + Shift + W).
   - Loose desktop files are cleanly sorted into organized archive folders.

3. REMINDERS & SCRATCHPAD:
   - Add a Reminders stack to inspect local task integration.
   - Add a Scratchpad stack to test quick Markdown note-taking and the "Export to Apple Notes" button.

4. STOREKIT 2 IN-APP PURCHASES & SUBSCRIPTIONS:
   - DeskStacks offers an unrestricted 14-day free trial on first launch.
   - To test the paywall, click the menu bar icon and select the license status item (or press Command + Option + P) to open the Paywall window.
   - You can test purchasing using an Apple Sandbox tester account:
     • Monthly Subscription: com.npds.app.sub.monthly ($1.60/month)
     • Yearly Subscription: com.npds.app.sub.yearly ($19.99/year with 14-day free trial)
     • Lifetime Pass (Non-Consumable): com.npds.app.lifetime ($34.99)
   - The "Restore Purchases" button validates previously purchased entitlements.

PERMISSIONS & SECURITY:
- DeskStacks operates within the Apple App Sandbox.
- Files and Folders, Reminders, and Calendar permissions are requested on-demand only when activating the corresponding widgets.
- Apple Events permission is requested solely to control Apple Music playback and export notes to Apple Notes.
- No user accounts or external server logins are required. All processing occurs locally on-device.

If you have any questions or require additional information, please contact us at support@deskstacks.app.

Sincerely,
Rareș-Mihail Cristea
Developer of DeskStacks
```
*(Exact character count: 2,492 / 4000)*

---

### 6. App Review Information — Attachment
* **File Types**: `.mp4`, `.png`, `.jpg`, `.pdf`
* **Suggested Attachment**: A short 30-45 second video recording demonstrating:
  1. Creating a folder stack and collapsing it into a capsule;
  2. Executing a 1-Click Desktop Sweep (Cmd + Shift + W);
  3. Opening the Paywall (Cmd + Option + P) showing the monthly, yearly, and lifetime options.

---

### 7. App Sandbox Information
* **Required Entitlement Keys**:
  * `com.apple.security.app-sandbox` = `<true/>`
* **Optional / Additional Entitlement Keys**:
  * `com.apple.security.files.user-selected.read-write` = `<true/>` *(Enables organizing user-selected files and folders)*
  * `com.apple.security.files.downloads.read-write` = `<true/>` *(Enables organizing Downloads folder)*
  * `com.apple.security.assets.movies.read-write` = `<true/>` *(Enables Movies stack)*
  * `com.apple.security.assets.music.read-write` = `<true/>` *(Enables Music library stack)*
  * `com.apple.security.assets.pictures.read-write` = `<true/>` *(Enables Pictures stack)*
  * `com.apple.security.files.bookmarks.app-scope` = `<true/>` *(Persists folder access bookmarks across app restarts)*
  * `com.apple.security.network.client` = `<true/>` *(Enables StoreKit 2 receipt refresh and licensing)*
  * `com.apple.security.device.audio-input` = `<true/>` *(Enables microphone for voice dictation in Scratchpad)*
  * `com.apple.security.personal-information.calendars` = `<true/>` *(Enables Reminders & Calendar studio)*
* **Temporary Exceptions (To Declare in the Dropdown)**:
  * Select: `com.apple.security.temporary-exception.apple-events`
  * Values / Targets: `com.apple.Music, com.apple.Notes`
  * Reviewer Justification:
    > *DeskStacks provides an interactive desktop widget allowing users to control playback of the native Apple Music application and preview quick notes without switching windows.*

---

## B. Secțiunea App Information

### 1. General & Localizable Information
* **App Name**: `DeskStacks`
* **App Subtitle (max 30 caractere)**:  
  `Desktop Stacks & Organizer` *(Exact 26 caractere)*
* **Bundle ID**: `com.npds.app`
* **SKU**: `DESKSTACKS_MAC`
* **Apple ID**: *(Generated by Apple upon registration in ASC)*
* **Category (Primary)**: `Utilities`
* **Category (Secondary)**: `Productivity`

---

### 2. Content Rights
* **Question**: *Does your app contain, show, or access third-party content?*
* **Selection**:  
  🔘 **No, it does not contain, show, or access third-party content**  
  *(DeskStacks organizes the user's local files and system items; it does not host, stream, or redistribute third-party copyrighted content).*

---

### 3. License Agreement (EULA)
* **Selection**:  
  🔘 **Apply Apple’s standard end user license agreement (EULA) to all countries or regions.**  
  *(URL: [https://www.apple.com/legal/internet-services/itunes/dev/stdeula/](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/))*

---

### 4. Age Ratings & Suitability
* **Declared Age Rating**: **4+** (All Ages / General Audience)
* **Age Suitability URL**: `https://raresmihailcristea-cmyk.github.io/deskstacks/compliance.html#age-suitability`
* **Operating Systems Earlier than Version 26**:  
  * Compatible from macOS 14.0 Sonoma and newer. No legacy OS version overrides needed.

---

### 5. App Encryption Documentation

#### a. App Purpose (max 300 caractere)
```text
DeskStacks is an on-device macOS desktop organizer featuring floating file stacks, reminders, and scratchpad tools. It uses standard Apple CryptoKit and HTTPS APIs strictly for on-device StoreKit 2 license verification.
```
*(Exact character count: 232 / 300)*

#### b. Select which encryption algorithms does your app implement:
* **Option to Select**:  
  🔘 **None of the algorithms mentioned above**  
  *(DeskStacks uses only Apple OS-provided CryptoKit, Keychain, and standard HTTPS, exempt under EAR Category 5, Part 2).*

#### c. Is your app going to be available for distribution in France?
* **Selection**: **Yes** *(By selecting "None of the algorithms mentioned above", the app is automatically cleared for distribution in France without requiring French ANSSI government approval documentation).*

#### d. Specify your use of encryption in Xcode (ITSAppUsesNonExemptEncryption)
* Declared in `Resources/Info.plist`:
  ```xml
  <key>ITSAppUsesNonExemptEncryption</key>
  <false/>
  ```

---

### 6. App Store Regulations & Permits (URL)
* **URL**: `https://raresmihailcristea-cmyk.github.io/deskstacks/compliance.html`  
  *(Fulfills European Union General Product Safety Regulation - GPSR (EU) 2023/988 compliance notices).*

---

### 7. App Store Server Notifications
* **Production Server URL**: `https://raresmihailcristea-cmyk.github.io/deskstacks/notifications/production`
* **Sandbox Server URL**: `https://raresmihailcristea-cmyk.github.io/deskstacks/notifications/sandbox`
* *Architecture Note*: DeskStacks uses native on-device StoreKit 2 verification (`StoreKitManager.swift`). External server webhook integration is optional.

---

### 8. App-Specific Shared Secret
* **Action in ASC**: Click **Manage** ➔ Click **Generate** ➔ Copy the generated 32-character hexadecimal key ➔ Click **Done**.

---

## C. App Privacy / Privacy Policy

### a. Privacy Policy URL
* **URL**: `https://raresmihailcristea-cmyk.github.io/deskstacks/privacy.html`

### b. User Privacy Choices URL
* **URL**: `https://raresmihailcristea-cmyk.github.io/deskstacks/privacy-choices.html`

### c. App Privacy Questionnaire (Nutrition Label)
* **Question**: *Do you or your third-party partners collect data from this app?*
* **Selection**: 🔘 **No, we do not collect data from this app**
* **Result**: Displays the official Apple privacy badge: **"Data Not Collected"**.

---

## D. App Accessibility Support

In the **App Accessibility** showcase panel in ASC, configure the supported features:
* ✅ **Dark Interface**: Handcrafted dark theme with native Liquid Glass and `.ultraThinMaterial`.
* ✅ **Sufficient Contrast**: Strict WCAG AA-compliant contrast ratios between text and background surfaces.
* ✅ **VoiceOver**: All interactive stack items, buttons, and capsules provide full `accessibilityLabel` and `accessibilityValue` traits.
* ✅ **Voice Control**: Full compatibility with macOS system Voice Control.
* ✅ **Reduced Motion**: Respects `NSWorkspace.accessibilityDisplayShouldReduceMotion` to minimize spring animations.
* ✅ **Larger Text**: Adapts dynamically to macOS system font size scaling.
* ❌ *Captions*: Not Applicable (No spoken video content).
* ❌ *Audio Descriptions*: Not Applicable (No video playback).
* ❌ *Differentiate Without Color Alone*: Relies on dual visual indicators (badges, icons, and text labels).

---

## E. Secțiunea Pricing and Availability

### 1. Price Schedule
* **Base App Price**: **Free ($0.00)**  
  *(Free download enabling the 14-day free trial, with in-app subscriptions and lifetime unlock).*

### 2. App Availability
* **Selection**: 🔘 **All Countries or Regions**  
  *(Available across all 175 App Store countries and territories).*

### 3. App Distribution Methods
* **Selection**:  
  🔘 **Public — Discoverable by anyone on the App Store (default)**  
* **Offer a reduced price on Apple School Manager**:  
  ☑️ **Checked** *(Offers educational institutions a 50% discount when purchasing 20+ licenses through Apple School Manager).*

---

## F. Secțiunea In-App Purchases

### Lifetime Pass Configuration
* **Type**: `Non-Consumable`
* **Reference Name (max 64 caractere)**:  
  `DeskStacks Lifetime Pass`
* **Product ID (max 100 caractere)**:  
  `com.npds.app.lifetime`
* **Price Tier**: **$34.99** (Tier 35)
* **Display Name**: `DeskStacks Lifetime Pass`
* **Description**:  
  `Unlock permanent lifetime access to unlimited stacks, scratchpad, reminders studio, desktop sweeps, and all future updates.`
* **Review Screenshot**: Screenshot of `DeskStacksPaywallView` showing the $34.99 one-time purchase card.

---

## G. Secțiunea Subscriptions

### a. Auto-Renewable Subscriptions

#### 1. Monthly Subscription
* **Reference Name**: `DeskStacks Monthly`
* **Product ID**: `com.npds.app.sub.monthly`
* **Price Tier**: **$1.60 / month** (Tier 2 equivalent)
* **Display Name**: `DeskStacks Monthly`
* **Description**: `Full access to all DeskStacks features, unlimited floating stacks, and desktop sweep.`

#### 2. Yearly Subscription (Recommended)
* **Reference Name**: `DeskStacks Yearly`
* **Product ID**: `com.npds.app.sub.yearly`
* **Price Tier**: **$19.99 / year** (Tier 20)
* **Introductory Offer / Free Trial**: **14 Days Free Trial**
* **Display Name**: `DeskStacks Yearly`
* **Description**: `Full access to all DeskStacks features with 14-day free trial and over 45% annual savings.`

---

### b. Subscription Groups
* **Create Group**: Click **Create Subscription Group**
* **Reference Name (max 64 caractere)**:  
  `DeskStacks Subscriptions`
* *Group Organization*:
  - Level 1: `DeskStacks Yearly` ($19.99/year)
  - Level 2: `DeskStacks Monthly` ($1.60/month)

---

### c. Billing Grace Period
* **1. Grace Period Duration**: **16 days** *(standard for monthly and annual subscriptions)*
* **2. Eligible Subscribers**: **All Renewals** *(Apply a grace period to both free-to-paid and paid-to-paid subscribers)*
* **3. Server Environments**: **Production and Sandbox Environment**

---

### d. Streamlined Purchasing
* **Selection**: **Turn On Streamlined Purchasing** *(Recommended default by Apple; allows users to initiate purchases directly from the App Store product page).*

---

### e. Non-Renewing Subscriptions
* **Status**: **None (N/A)** *(DeskStacks' single-payment option is configured as a Non-Consumable In-App Purchase).*

---

## H. Secțiunea Nominations (App Store Feature)

### Nomination Pitch & Details
* **Action**: Click **Create Nomination**
* **Type**: Feature / Update Nomination
* **Details to Enter**:
  * **Title**: `DeskStacks — The Intelligent Floating Workspace & Desktop Architecture for macOS`
  * **Target Event / Date**: Launch Date
  * **Why Apple Should Feature DeskStacks**:
    * **Reinventing the Mac Desktop**: Transforms disorganized desktop clutter into structured, floating Liquid Glass stacks and capsules anchored anywhere on screen.
    * **Deep Apple Ecosystem Integration**: Native two-way sync with Apple Reminders, Apple Calendar, Apple Notes, and Apple Music without third-party services.
    * **On-Device Natural Language & Voice**: Natural language date parser and speech-to-text dictation powered entirely by on-device Apple Silicon intelligence.
    * **Zero-Knowledge Privacy Standard**: Zero telemetry, zero external cloud servers, and strict App Sandbox compliance.
