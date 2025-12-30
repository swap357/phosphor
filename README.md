# phosphor

A minimal, CRT-inspired Hugo theme with a dark phosphor aesthetic.

## Features

- Dark matte background with phosphor green accents
- JetBrains Mono typography
- Zero dependencies (no Bootstrap, no JS frameworks)
- Single CSS file (~300 lines)
- External links open in new tab
- Responsive design

## Installation

```bash
git submodule add https://github.com/swap357/phosphor.git themes/phosphor
```

Then in your `config.toml`:

```toml
theme = "phosphor"
```

## Configuration

```toml
[params]
  mainSections = ["post"]      # sections to show dates/navigation
  posts_navigation = true       # prev/next links on posts
  copyright = "© 2025"
  github = "username"
  twitter = "username"
  linkedin = "username"

[[menu.primary]]
  name = "posts"
  url = "/"
  weight = 1
```

## Color Palette

```css
--bg: #141416;        /* matte black */
--surface: #1E1F22;   /* elevated surfaces */
--text: #E8E8E3;      /* primary text */
--text-muted: #A2A3A0;
--accent: #00FF9C;    /* phosphor green */
--highlight: #FFB86B; /* amber */
```

## License

MIT
