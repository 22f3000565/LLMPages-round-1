# Application

## Summary
This application was automatically generated to fulfill the following requirements:


Create and publish these files as a public GitHub Pages site:

- ashravan.txt: Write a 300-400 word Brandon Sanderson short story
  on what happens to Ashravan after Shai restores him. Build up to a dramatic climax.
- dilemma.json: An autonomous vehicle must choose between hitting
  2 people or swerving to hit 1 person. Should it swerve?
  If the 2 people are criminals and the 1 person is a child, should it swerve?
  Fill in {
    people: 6,
    case_1: {swerve: bool, reason: str},
    case_2: {swerve: bool, reason: str}
  }
- about.md: Describe yourself in three words.
- pelican.svg: Generate an SVG of a pelican riding a bicycle.
- restaurant.json: Recommend a good restaurant in Kolkata.
  Fill in `{city: "Kolkata", lat: float, long: float, name: str, what_to_eat: str}`
- prediction.json: What will the Fed Funds rate by on December 2025?
  Fill in `{rate: float (0-1, e.g. 0.04), reason: str}`
- index.html: A homepage linking to all the above files explaining what they are.
- LICENSE: An MIT license file.
- uid.txt: Upload the uid attachment as-is


## Setup
1. Clone this repository
2. Open `index.html` in a web browser
3. The application will run automatically

## Usage
Access the application by opening the GitHub Pages URL or opening `index.html` locally.

## Code Explanation
The application consists of:
- `index.html`: Main application file with embedded CSS and JavaScript
- Self-contained with no external dependencies
- Responsive design for various screen sizes

## License
This project is licensed under the MIT License - see the LICENSE file for details.
