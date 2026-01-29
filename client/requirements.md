## Packages
framer-motion | Complex animations for the cyberpunk UI feel
date-fns | Time formatting for logs and status
recharts | Charts for bot statistics
clsx | Class name utility
tailwind-merge | Class name merging

## Notes
Tailwind Config - extend fontFamily:
fontFamily: {
  cyber: ["'Orbitron'", "sans-serif"],
  tech: ["'Rajdhani'", "sans-serif"],
  mono: ["'Fira Code'", "monospace"],
}

Colors need to be defined in CSS variables for dynamic neon effects.
Authentication uses localStorage to store the token returned by /api/login.
