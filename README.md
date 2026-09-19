# MASA LinkShrink Suite

High-throughput URL shortening and link vanity transformation utility

## Technical Architecture

The application is architected with modular separation of concerns adhering to modern clean code standards:

- **Component Layering**: Isolated view layouts, state managers, and service controllers.
- **Defensive Engineering**: Robust input sanitization and exception management.
- **Modern Design Standards**: High-contrast dark-mode interface styled for optimal usability and visual polish.

## Preview

![Application Interface](screenshots/app_interface.png)

## Features

- Multi-provider shortening endpoint integration (TinyURL, is.gd, clck.ru).
- Automatic clipboard extraction and one-click shortened URL copying.
- Local history log tracking generated links with timestamps.
- Instant link validation and HTTP reachability checks.

## Prerequisites

- Python 3.10 or higher
- Required packages:

```bash
pip install customtkinter pillow requests
```

## Execution

Launch the application via Python:

```bash
python "Simple URL Shortener App in Python/index.py"
```

## Project Structure

```
.
├── Simple URL Shortener App in Python
├── screenshots/
│   └── app_interface.png
├── .gitignore
├── LICENSE             # MIT License
└── README.md           # Developer documentation
```

## License

This project is licensed under the terms of the MIT License. Refer to the `LICENSE` file for details.
