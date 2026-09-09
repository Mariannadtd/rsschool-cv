# Marina

## Contacts

- GitHub: [Mariannadtd](https://github.com/Mariannadtd)
- Discord: mariannarom

## About Me

I am a front-end developer with experience in HTML, CSS, JavaScript,
and Vue.js. I am expanding my skills in React, Next.js, and TypeScript
by building personal projects.

I enjoy turning ideas into functional, user-friendly interfaces and
understanding how they work behind the scenes. My goal is to grow
as a developer, with a particular focus on Web3 and building
decentralized applications.

## Skills

- HTML, Pug
- CSS, Sass / SCSS, Bootstrap
- JavaScript
- TypeScript
- Web3 basics: MetaMask wallet integration
- Vue.js
- React, Next.js — learning through projects
- Git, GitHub
- VS Code

## Code Example

A reusable React button with TypeScript props from my Crypto Cards project.
The example below has simplified styling.

```tsx
import type { ComponentProps } from "react";

type ButtonProps = ComponentProps<"button">;

export default function Button({
  children,
  className = "",
  type = "button",
  ...props
}: ButtonProps) {
  return (
    <button type={type} className={className} {...props}>
      {children}
    </button>
  );
}
```

[Source code](https://github.com/Mariannadtd/crypto-cards/blob/main/app/components/UI/Button.tsx)

## Projects

### Crypto Cards

A web application for displaying cryptocurrency information.
The project includes utilities for formatting prices and percentage changes.

- Technologies: Next.js, React, TypeScript
- [Source code](https://github.com/Mariannadtd/crypto-cards)

### Door Renaissance

An online store project for doors, flooring, fittings, and ceilings.

- Technology: Vue.js
- [Source code](https://github.com/Mariannadtd/door-renaissance-frontend)

### Make Your Burger

An application for choosing ingredients and ordering a burger.

- Technology: Vue.js
- [Source code](https://github.com/Mariannadtd/Make-your-burger)

## Education

- RS School — currently studying.
- Self-study in front-end development through practical projects.

## English

B2 — Upper-Intermediate.
