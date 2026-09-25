# Alder & Vane — Design & Development Notes

## 1. Structure and Approach

I ordered the page around the questions a prospective client is likely to ask: what Alder & Vane does, how it approaches a project, whether it has relevant experience, and how to make contact. I prioritised the homeowner consultation as the primary journey, so that action appears in the header, hero and final contact section.

I gave the design partner programme a clearly differentiated dark section because architects, builders and designers generate most of Alder & Vane’s work. For a realistic 2–3 hour exercise, I intentionally left out a contact form, CMS, project detail pages, testimonials, carousels and elaborate animation.

## 2. Market and Audience

A technology integrator plans and coordinates lighting, shading, entertainment, networks and control so they work together and fit the architecture. The homeowner audience receives plain-language benefits, residential imagery and a direct consultation route. The professional audience needs coordination and reliability, so its section focuses on drawings, specification text, site coordination and one named contact.

## 3. UI and UX

I kept the serif and sans-serif pairing but created a more deliberate scale: the hero remains expressive while secondary headings and project titles are quieter. Body copy stays at a readable size and line length. Warm cream, charcoal, stone and restrained bronze reference desert materials without making bronze a large decorative device.

The page deliberately alternates text-led and image-led sections, followed by the dark professional section, a lighter editorial quote and the final conversion area. Spacing and section boundaries vary so the experience reads as one composition rather than repeated components. Anchor navigation keeps the journey predictable. Interaction is limited to the menu, a compact header on scroll, drawn link underlines, slight service-title movement and a very small image scale on hover. Reduced-motion preferences suppress those transitions.

## 4. Creative Design

I chose an editorial rather than equipment-led design because AV integration should support the architecture. The new SVG identity uses intersecting A and V strokes based on plan lines and joined planes; it stays monochrome, legible at small sizes and avoids familiar house or technology symbols.

I used asymmetry and varied image proportions to prevent the page feeling like a standard component template. The large landscape, offset portrait and medium landscape projects create editorial pacing. The Old Town image crosses the light-to-dark section boundary slightly, connecting Selected Work to the partner programme without adding a decorative shape. The typography hierarchy also varies by purpose rather than repeating one heading component. Fine rules and offset captions provide structure, while services read like an architectural specification rather than software cards.

## 5. Copy and Imagery

The copy remains concise and uses only supplied company facts, projects and quotations. I selected a limited number of supplied images instead of using the full asset pack, and intentionally avoided visible product or equipment catalogue imagery.

`modern-residence-exterior-web.jpg` was selected for the hero because its strong horizontal architecture and large glazing communicate a design-led residential context. `illuminated-pool-residence-web.jpg` supports the Camelback story through indoor-outdoor living and integrated evening light. `desert-mountain-estate-remodel-web.jpg` gives Desert Mountain a material-focused crop built around the carved entrance. `dark-members-club-bar-web.jpg` provides the layered hospitality lighting needed for Old Town. These images are used editorially and are not presented as documentary photographs of the fictional projects. Each crop was manually art-directed rather than relying on a shared centered position.

## 6. The Build

The build uses semantic HTML5 landmarks, one H1 and a logical H2/H3 hierarchy. CSS Grid and Flexbox handle the layout with two focused breakpoints. Short vanilla JavaScript enhances the mobile menu, header and copyright year; content and anchor links still work if JavaScript fails.

Keyboard focus states, a skip link, meaningful image alt text, contrast and reduced-motion handling support accessibility. On smaller screens the layout intentionally simplifies the desktop asymmetry into a clear reading order rather than merely shrinking it. The four displayed photographs now use 2400px presentation exports with intrinsic dimensions; below-the-fold images also use lazy loading and asynchronous decoding. WebP or AVIF variants would be the next production optimization if a deployment pipeline were available. If the site grows, these semantic sections can map directly to CMS blocks or templates.

## 7. SEO and AEO

The title and meta description identify AV integration, home automation and Scottsdale without keyword stuffing. Semantic headings and naturally written service-area content clarify the page subject. LocalBusiness JSON-LD contains only supplied details: name, description, founding year, phone, email, Scottsdale locality, Arizona region and service areas. No street address, hours, coordinates, ratings, pricing or licence number was invented.
