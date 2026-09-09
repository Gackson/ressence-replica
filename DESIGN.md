# RESSENCE TYPE 1
The physical scene is a watch face viewed straight on in soft daylight, with a neutral white surrounding field. Official watch colours take precedence over generated palette seeds.

A single responsive circular dial on an achromatic background. No visible text outside the dial. SVG geometry follows the user's 424-unit reference. Engraved-style rounded vector numerals, coplanar satellites, hairline seams and subtle convex shading. Official logo PNG is clipped to its hand symbol and used as an alpha mask, preserving the original outline.

Only transform attributes change every frame. Local wall-clock time is sampled directly. Satellite centres orbit once per hour; their scales counter-rotate equally. Seconds and hours rotate relative to the upright scales. Weekday advances continuously through seven segments with Saturday and Sunday outlined. Reduced motion uses one-second updates.

Dark backgrounds use a soft charcoal (OKLCH 0.235 / 0.005 / 250), with enough luminance to keep the surrounding field from appearing flat black. Background defaults to the system appearance and offers a saved four-mode cycle: light, dark, dial harmony, system. Dial harmony uses separate quiet companion colours (red / pale warm grey, black / mist grey, white / cool grey, blue / deep blue-grey, rose gold / pale taupe-grey, multicolour / neutral grey), never copies the dial fill. Text and tool icons adapt to the background.

A bottom-left toolbar uses 18px icons in 44px touch targets. It fades in and out over 500ms with no displacement on pointer proximity or keyboard focus; touch devices keep it visible. Icons match the reset control’s 0.55 resting opacity and full opacity on hover, with no tooltip or background fill. It links to Gackson’s GitHub profile, opens a native homepage setup dialog with address copying, and cycles the background. Respect reduced motion and safe-area insets.
