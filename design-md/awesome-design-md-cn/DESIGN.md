# Design System: awesome-design-md-cn

## 1. Visual Theme & Atmosphere

awesome-design-md-cn is a Chinese-first design archive for browsing DESIGN.md references over long sessions. It should feel like a well-edited reference room: tactile, calm, precise, and slightly archival. The current direction is an editorial archive rather than a generic SaaS dashboard.

The visual language combines a warm paper canvas, ink-black structure, brick-red indexing, and a restrained steel-blue support color. Thin rules, numbered labels, archive tags, and directory cards make a large collection feel navigable without turning every item into a marketing tile.

**Key characteristics**

- Warm paper canvas with a quiet paper grain and fine grid
- Ink-black headers, rules, and strong structural blocks
- Brick-red accent for index marks, active states, and links
- Small steel-blue details for focus and secondary emphasis
- Serif display typography paired with restrained sans-serif body copy
- Slightly asymmetric hero composition with an archive-side note
- Directory cards that read like catalog entries
- Chinese-first copy density for long browsing sessions

## 2. Color Palette & Roles

### Core

- **Paper** (#f3eee6): Global canvas and quiet reading surface
- **Paper Deep** (#e8dfd2): Recessed groups and secondary surfaces
- **Surface** (#fffdf9): Panels and cards
- **Ink** (#171614): Primary text, rules, and structural contrast
- **Ink Soft** (#2b2925): Secondary headings and control chrome

### Accents

- **Brick** (#bf4b34): Index marks, active states, and important links
- **Brick Dark** (#8f3224): Hover and emphasis states
- **Steel Blue** (#456b92): Focus rings and small supporting cues
- **Steel Blue Soft** (#dce7ef): Quiet selection and information fills

### Supporting

- **Muted** (#6f675e): Supporting copy and metadata
- **Line** (#d5cabc): Fine grid and panel borders
- **Line Strong** (#a99b8b): Section rules and primary dividers

## 3. Typography Rules

- **Display**: Iowan Old Style, Baskerville, Songti SC, STSong, serif
- **Body**: Avenir Next, PingFang SC, Noto Sans SC, Hiragino Sans GB, sans-serif
- **Labels**: SFMono-Regular, Cascadia Code, Roboto Mono, monospace

| Role | Size | Weight | Line Height | Notes |
|------|------|--------|-------------|-------|
| Hero title | 52–72px | 650 | 0.96–1.02 | Short, editorial, slightly asymmetric |
| Section title | 28–40px | 650 | 1.02–1.10 | Serif, compact |
| Card title | 18–22px | 700 | 1.10–1.20 | Strong catalog entry anchor |
| Body | 14–15px | 400 | 1.65 | Comfortable Chinese reading |
| Archive label | 10–12px | 600 | 1.00 | Monospace, uppercase or numbered |

Use type, spacing, and rules before adding more colors. Keep labels short and descriptions concrete.

## 4. Component Stylings

### Hero

Use a strong top rule, a concise headline, and a secondary archive note. Let the copy and index numbers create the asymmetry; do not fill the hero with controls.

### Navigation

Keep the topbar quiet and editorial. Use small arrow markers, a thin divider, and a serif brand lockup.

### Filter Rail

Treat filters as a reading index. Search comes first, followed by category and scenario chips. Keep the rail visually stable while the content column scrolls.

### Directory Cards

Cards should look like catalog entries: an index kicker, a title, a short summary, one metadata row, and two small actions. Keep radius restrained and use rules and surface contrast instead of floating shadows.

### Detail Pages

Use the same hero, rules, labels, and paper surfaces as the home page. Preview links, prompt blocks, and metadata should feel like pages in the same archive.

## 5. Layout Principles

- Main shell: wide editorial container with generous but controlled margins
- Browse area: stable filter rail plus a content column
- Library begins directly after the hero and filter controls
- Custom and reference cases remain separate collections
- Use fine grid lines and numbered labels to support scanning
- Prefer asymmetry in the hero and regular rhythm in dense lists

### Spacing scale

4 / 8 / 12 / 16 / 24 / 32 / 48 / 64

### Radius scale

4px cards and panels, 8px controls, 999px only for compact status pills

## 6. Depth & Elevation

- **Flat**: Paper canvas and plain reading areas
- **Card**: Surface with a fine border
- **Floating**: Subtle warm shadow reserved for hero notes and focused panels

Depth should come from paper, rules, and spacing. Avoid glossy gradients and inflated card shadows.

## 7. Do's and Don'ts

### Do

- Use warm paper, ink, and brick-red as the main visual grammar
- Make numbering and archive labels useful for orientation
- Keep Chinese copy edited and compact
- Use serif headlines for editorial character
- Let cards behave like index entries

### Don't

- Do not use purple gradients or default AI dashboard styling
- Do not stack large showcase cards before the library
- Do not over-round every surface
- Do not use accent colors without a structural reason
- Do not turn the archive into a generic marketing landing page

## 8. Responsive Behavior

- **Mobile**: Single column; the filter rail becomes a normal block
- **Tablet**: Reduce outer spacing and card columns
- **Desktop**: Keep the sidebar stable and let the catalog breathe

The hierarchy stays the same at every width: archive label, title, summary, filter index, then catalog entries.

## 9. Agent Prompt Guide

### Quick style summary

- Chinese editorial design archive
- Warm paper canvas
- Ink-black structure
- Brick-red index accent
- Serif headlines and restrained sans body
- Fine rules, numbers, archive labels, and directory cards
- Slightly asymmetric hero for a memorable first impression

### Example prompt

Design a Chinese design reference archive with a warm paper canvas, ink-black structure, and a restrained brick-red index accent. Use serif headlines, quiet sans-serif body copy, fine grid rules, archive labels, numbered sections, and directory cards. Keep the hero slightly asymmetric, the content dense but readable, and avoid purple gradients, excessive rounding, and generic AI dashboard patterns.

### Iteration guide

1. Establish paper, ink, and rule tokens first
2. Set the editorial type hierarchy
3. Add numbered labels and archive metadata
4. Build the catalog cards as index entries
5. Use brick red only where the archive needs direction
