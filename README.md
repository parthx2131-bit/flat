# MedPing — Minimalist NFC Elder Care Medication Tracking Widget

**MedPing** has been refined into a minimal, calm, and glanceable **iPhone frosted glass widget** that eliminates threatening alarms in favor of trusted clinical clarity.

---

## 🎨 Key Design Updates

1. **Gray for Missing / Pending Tablets (Zero Red)**:
   - Completely removed all red signals, red borders, red alert glows, and `✕` crosses.
   - Missing or pending tablets (such as Amlodipine 5mg) use **calm, neutral iOS gray** (`#636366`, `rgba(142, 142, 147, 0.12)` background, neutral clock outline).
   - Non-punitive and non-threatening: shows as `Pending` rather than an alarming failure.

2. **Preserved Forest Green for Taken Doses**:
   - Doses verified via NFC tap (Pantoprazole at 7:51 AM, Metformin at 8:22 AM) maintain the reassuring forest green (`#2E7D52`, `#EAF4EE`, `✓` checkmark).

3. **Streamlined, Minimal Information**:
   - Stripped away visual clutter, redundant headers, and oversized alert banners.
   - Clean top lockup: `Leela` · `2 of 4 taken`.
   - Four clean, prominent pillbox slots (Pantoprazole, Metformin, Amlodipine, Atorvastatin).
   - Minimal single-line footer: `Next: Atorvastatin at 9:00 PM` | `Details ›`.

4. **Basic iPhone Stock Wallpaper & Authentic Frosted Glass**:
   - Replaced previous custom mesh with Apple's iconic **iOS Stock Midnight Twilight Navy** gradient (`#0A1128` to `#111F3D` with deep celestial blues).
   - Presets included in controller: **iOS Stock Navy (Default)**, **iOS Astronomy**, **iOS Dark Titanium**, and **iOS Classic Cobalt**.
   - Beautiful frosted glass widget styling (`rgba(255, 255, 255, 0.75)` with `backdrop-filter: blur(28px)` and crisp border).

5. **Standard iPhone Screen (Borderless, No Notch)**:
   - Preserves standard iPhone screen dimensions (`390px x 844px`) with smooth rounded corners (`border-radius: 40px`).
   - Removed the outer phone border and hardware buttons for a clean, edge-to-edge screen appearance.
   - Removed the notch / Dynamic Island for an unobstructed, clean Apple status bar (`9:47`, cellular bars, Wi-Fi, battery pill).
   - Standard iPhone home indicator bar at the bottom.
   - Smooth mobile touch sliding with rubber-band elasticity.

6. **Calm First-Time User Experience (Zero Overwhelm & Less Clutter)**:
   - **Tip Included Inside Widget**: Reduced text to a crisp micro-tip: `💡 Tap any tablet to see history` directly embedded within the widget.
   - **Decluttered Layout**: Removed external wallpaper banners and redundant swipe text hints (`‹ Slide horizontally to switch screens ›` and external tip banner completely removed).
   - **Bottom-Left Emergency Contact Icon**: A dedicated, instant-access phone icon button in the bottom-left corner of the widget allows the caregiver or family member to immediately open emergency contacts (Dr. Ravi Shankar, Son Anand, Neighbor Meena, Lakshmi Caregiver) without needing to swipe to the last slide.
   - Friendly **Caregiver Live Sync Bar** with a single clear CTA: `Simulate NFC Tap (Mom takes pill)`.
   - Reassuring adherence progress track (`50% completed today`, animates to 75% on tap).

---

## 🌐 Live Server

- **URL**: [http://localhost:3000](http://localhost:3000)
- **Direct File**: [index.html](file:///c:/Users/Parth/Downloads/elder%20care%20widget/index.html)
