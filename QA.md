# Verification — November 24, 2026

## Desktop layout

Checked in Chrome at 1440 × 1000 CSS pixels. Two-column hero and contact layout, horizontal navigation, service rows and visible concept notice. Document width equals viewport width, with no horizontal overflow.

## Mobile layout

Checked in Chrome at 390 × 844 and 320 × 740 CSS pixels. Hero, services and contact stack into a single column. Call button spans the content width. Both viewport checks report no horizontal overflow. Original vector illustration scales with the available width.

## Links

- Call for Service and service number: `tel:+15165420855`.
- Main phone: `tel:+15165420413`.
- Email: `mailto:memavlios@gmail.com`.
- Directions: HTTPS Google Maps directions endpoint, `api=1`, destination decodes to `314 East Meadow Ave, East Meadow, NY 11554`.
- All fragment links resolve to existing IDs. Contact and Back to top were clicked and their URL fragments verified.
- Telephone and email destinations were inspected without placing a real call or sending mail. Directions URL parameters were checked; no route was started.
- Local page responds with HTTP 200. No remote image or font dependencies.

## Publication

Netlify project created without Git linkage or uploading a deployment. Project requires team SSO for all deploys and has no published deploy ID. Source repository is public as requested. Build guard exits 1 with a publication-blocked message. Netlify build keys and types were checked against the official JSON schema. Robots metadata is noindex/nofollow/noarchive; this is indexing guidance, while local loopback binding provides the private preview.

## Content and accessibility

Supplied business address, numbers, email and two service categories only. No hours, prices, warranties, certifications or unsupported business claims. Visible unofficial concept label. Original SVG artwork has an accessible description; no stock or generated photos are used. Semantic headings, landmarks, skip link, visible keyboard focus and reduced-motion support are included.

## Graphics revision

Redrew the hero wheel with connected, symmetrical spokes, concentric rotor details and a red caliper. Replaced the brake and tire icons, phone icon and favicon. Verified all three SVG image assets load in Chrome at desktop and mobile widths; the service icons render at 58px on desktop and 48px on mobile. Removed README at the user's request.

## Social link

Added a Nextdoor link in the contact section. Verified on November 24, 2026 that https://nextdoor.com/pages/father-son-auto-care-east-meadow-ny/ matches the supplied business name, 314 East Meadow Ave address, (516) 542-0413 main phone and memavlios@gmail.com email. Facebook and Instagram were not added because matching profiles could not be verified. External link opens a new tab with noopener/noreferrer and an accessible new-tab notice.
