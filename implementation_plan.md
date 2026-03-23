# Logo Integration Implementation Plan

## Goal Description
Integrate the official "Inn The Hills" logo into the navbar, booking modals, and footer to enhance branding and professional aesthetic.

## Proposed Changes
- **Navbar**: Replace the text-based logo ("TBP & Inn The Hills") with the image logo (`gallery/THE BETTER PLACE REVAMPED/3985d3a7-6f99-4bca-ba2e-3a68ca98d843.jpg`). Set height to ~44px.
- **Booking Modals**: 
  - Ensure both the specific room modal and the general booking modal feature the logo at the top center.
  - Standardize logic: ~60px width, centered, proper padding.
- **Footer**: Add a subtle version of the logo (reduced opacity) near the copyright/branding area.
- **CSS**: Add centralized styles for `.logo-img` and modal logo containers to ensure responsiveness and premium alignment.

## Verification Plan
- Check navbar on desktop and mobile.
- Open both modals to verify logo placement.
- Check footer for logo integration.
- Verify that `object-fit: contain` is used to prevent distortion.
