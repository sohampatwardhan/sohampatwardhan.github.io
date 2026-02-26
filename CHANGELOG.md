# Changelog

All notable changes to this project will be documented in this file.

## [0.5.0] - 2026-02-25

### Added
- 16x16 and 32x32 favicon PNGs for browser tab icon
- favicon.ico in root for automatic browser detection
- New icon sizes cached in service worker

### Fixed
- Favicon now displays in browser tab (added proper small sizes)
- Changed asset paths from absolute to relative for local file:// compatibility

## [0.4.0] - 2026-02-25

### Added
- CLAUDE.md project conventions file
- Reddit social link (between GitHub and Email)
- SMS social link (sms: protocol)
- Hover tooltips on all social icons
- .gitignore for system files

## [0.3.0] - 2026-02-25

### Changed
- Background now features subtle midnight blue and purple radial gradients instead of pure black
- WebGL canvas uses transparent alpha, letting CSS gradients show through behind stars

## [0.2.0] - 2026-02-25

### Added
- Progressive Web App (PWA) support with manifest.json and service worker
- Offline caching (network-first strategy with cache fallback)
- Mobile-responsive layout with safe area insets for notched devices
- Reduced star count on mobile (1500 vs 3000) for better performance
- Apple touch icon and PWA meta tags

## [0.1.0] - 2026-02-25

### Added
- Interactive WebGL starfield with 3000 stars on black background
- Parallax effect — stars shift based on cursor position with depth layers
- Star twinkling with per-star phase and brightness variation
- Mouse proximity glow effect — nearby stars brighten and enlarge
- Shooting star trails appearing every few seconds
- "Welcome to my website / Coming soon" centered text with fade-in animation
- Top-left name display: "Soham Patwardhan"
- Top-right social links: LinkedIn, GitHub, Email, Phone, WhatsApp (SVG icons with hover effects)
- Bottom-center copyright notice
- Touch input support for mobile devices
