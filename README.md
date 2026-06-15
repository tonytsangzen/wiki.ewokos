# EwokOS Web

PPT-style introduction website for EwokOS - a lightweight microkernel operating system.

## Design

Built with taste-skill design principles:
- Dark tech theme with cyan accent
- PPT-style vertical slide navigation
- Keyboard navigation (arrow keys, space, home, end)
- Scroll-snap slide transitions
- Responsive layout

## Skills

This project uses [taste-skill](https://github.com/Leonxlnx/taste-skill) for frontend design guidance.
The skill has been installed via `npx skills add https://github.com/Leonxlnx/taste-skill`.

### Available Skills

All 13 taste-skill variants are installed in `.agents/skills/`:

| Skill | Description |
|-------|-------------|
| `design-taste-frontend` | Main anti-slop frontend skill |
| `design-taste-frontend-v1` | Original v1 version |
| `minimalist-ui` | Premium utilitarian minimalism |
| `industrial-brutalist-ui` | Hard mechanical language |
| `high-end-visual-design` | Polished, calm, expensive UI |
| `gpt-taste` | Aggressive anti-slop for GPT/Codex |
| `image-to-code` | Image-first design pipeline |
| `brandkit` | Brand asset generation |
| `full-output-enforcement` | Prevents truncated/placeholder code |
| `redesign-existing-projects` | Redesign protocol |
| `stitch-design-taste` | Multi-skill composition |
| `imagegen-frontend-web` | Web design reference images |
| `imagegen-frontend-mobile` | Mobile design reference images |

## Usage

Open `index.html` in a browser, or serve with any static file server:

```bash
cd web
python3 -m http.server 8080
```

Then visit http://localhost:8080
