# ar-aquarium

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

An augmented reality (AR) aquarium simulation application that displays animated fish in a web browser.

## Demo
https://code4fukui.github.io/ar-aquarium/

## Features
- Displays an aquarium with animated fish
- Fish data is loaded from a CSV or JSON file
- Supports customization of fish size, wave frequency, amplitude, and speed
- Allows controlling the initial count of fish and the refresh rate

## Data
The fish data is stored in a CSV or JSON file, with the following fields:

- `file`: filename of the image
- `size`: width of the fish
- `freq`: wave frequency
- `amp`: wave amplitude
- `speed`: speed of the fish
- `enabled`: 1 or 0 to enable or disable the fish

## Usage
To run the application, open the `index.html` file in a web browser. The application can be customized by passing parameters in the URL:

- `url`: URL of the fish data file (CSV or JSON), default is `./fishes.csv`
- `nfishes`: initial count of fish, default is 30
- `dtrefresh`: refresh time in seconds, default is 0 (no refresh mode)

## License
MIT License — see [LICENSE](LICENSE).