# Contributing

Contributions are welcome! Here's how to get started:

## Getting Started

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/my-feature`)
3. Commit your changes (`git commit -m 'feat: add my feature'`)
4. Push to the branch (`git push origin feature/my-feature`)
5. Open a Pull Request

## Development Setup

```bash
git clone https://github.com/rwiren/team-tactical-map.git
cd team-tactical-map
pip install ultralytics supervision opencv-python numpy matplotlib
```

## Ideas for Contributions

- **New sport templates** — basketball court, ice hockey rink, rugby pitch
- **Automated pitch detection** — replace manual 4-point selection with line detection
- **Ball tracking** — dedicated ball detector + trajectory visualization
- **Drone footage mode** — nadir view with simplified affine transform
- **Speed/distance stats** — per-player metrics from position data
- **Real-time streaming** — RTSP input with live radar output
- **Military/tactical overlay** — terrain map with team movement

## Code Style

- Python 3.9+
- Follow existing patterns in the codebase
- Add docstrings to new functions
- Test with the provided sample clip before submitting
