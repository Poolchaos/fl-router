# FL-Router (Router Library for Flaapworks)

**Version:** 1.0.0

**Author:** [pjvanderberg](https://github.com/pjvanderberg)

## Overview

`fl-router` is a router library designed for Flaapworks, streamlining route configuration for navigating within a single-page app. Authored by [pjvanderberg](https://github.com/pjvanderberg), it provides an intuitive way to manage routes seamlessly.

## Features

- **Route Configuration:** Easily configure routes for navigation in a single-page app.
- **Integration with Flaapworks:** Designed to work seamlessly within the Flaapworks framework.
- **Version 1.0.0:** Initial release with essential features.

## Installation

To integrate `fl-router` into your Flaapworks project, follow these steps:

```bash
npm install fl-router
```

## Usage
```javascript
import { ViewLifecycle, Flaapworks } from 'flaapworks';

export class Home extends ViewLifecycle {
    Flaapworks.router.configure([
      { route: ['', 'home'], module: 'views/home/home', uri: 'Home' },
      { route: 'members', module: 'views/members/members', uri: 'Members' }
    ])
}
```

## Contributing

Contributions are welcome! If you have suggestions, found a bug, or want to contribute to `fl-router`, please feel free to open issues or submit pull requests on [GitHub](https://github.com/pjvanderberg/fl-router).

## License

This project is licensed under the [MIT License](LICENSE).

---

**Flaapworks - Where Innovation Meets Simplicity**
