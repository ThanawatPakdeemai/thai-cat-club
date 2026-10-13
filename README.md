# THAI CAT CLUB

Responsive Thai cat character carousel built with React, TypeScript, Vite, Tailwind CSS and lucide-react.

## Run

- `npm ci`
- `npx vite --host 0.0.0.0`
- `npm run build` produces `dist/`

## Features

Five breeds, animated carousel with a 650 ms navigation lock, touch swipes and keyboard arrow navigation, breed details in native modal dialogs, and browser-local favorites. Reduced-motion preferences are respected. The visuals are generated 3D-style raster illustrations, not rotatable mesh models.

## Artwork

Assets are stored in `public/cats/{siamese,korat,suphalak,khao-manee,konja}.png` and copied into the deployment. Created with the built-in image-generation tool from the five supplied breed photographs. The common prompt requested an adorable full-body seated 3D collectible cat figurine with large glossy eyes, curled tail, soft studio lighting, transparent background, no text, props or accessories, and breed-specific fur and eye colors. Variants: Siamese cream fur with seal points and blue eyes; Korat silver gray and green eyes; Suphalak copper brown and amber eyes; Khao Manee white and blue/gold odd eyes; Konja black and yellow-green eyes.

Content follows the user's supplied breed descriptions. Favorite choices are stored only in the current browser. No backend or personal-data submission is required.

## Verification

TypeScript check and production Vite build. Browser automation was unavailable in the managed environment, so visual browser QA was not performed.
