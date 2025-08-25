Text to PowerPoint Converter
Overview
Text to PowerPoint Converter is a web-based application that transforms plain text into professional PowerPoint presentations using AI-powered design. Users can input text, customize presentation settings, preview slides, and export them as PowerPoint files. The application supports multiple themes, layouts, and font sizes, with features like presentation mode and mobile-friendly navigation.
Features

Text Input: Paste or type text to generate slides automatically.
Customizable Settings:
Themes: Professional, Creative, Corporate, Modern
Layouts: Standard, Minimal, Detailed
Font Sizes: Small, Medium, Large
Slides per Topic: Auto, 1, 2, or 3 slides
Optional Intro and Conclusion Slides


Slide Preview: Real-time preview of generated slides with navigation.
Presentation Mode: Full-screen presentation view with keyboard and touch navigation.
Export: Download presentations as .pptx files using PptxGenJS.
Responsive Design: Optimized for desktop and mobile devices.
Animations: Smooth transitions and processing animations for a polished user experience.

Technologies Used

Frontend: HTML, CSS (Bootstrap 5.3), Font Awesome
JavaScript: PptxGenJS for PowerPoint generation
Libraries:
Bootstrap 5.3 for responsive UI components
Font Awesome 6.4 for icons
PptxGenJS 3.12.0 for PowerPoint export


Styling: Custom CSS with CSS variables, gradients, and animations

Installation

Clone the repository:git clone https://github.com/your-username/text-to-powerpoint-converter.git


Navigate to the project directory:cd text-to-powerpoint-converter


Open index.html in a web browser to run the application locally. No server setup is required as it uses CDN-hosted libraries.

Usage

Input Text: Paste your text into the provided textarea or click "Use Sample Text" for a demo.
Customize Settings: Select a theme, layout, font size, and other options in the settings panel.
Generate Slides: Click the "Generate Slides" button to create slides from the text.
Preview Slides: Navigate through generated slides using the "Prev" and "Next" buttons or swipe gestures on mobile.
Present: Enter full-screen presentation mode by clicking the "Present" button.
Export: Download the presentation as a .pptx file by clicking the "Export" button.

Sample Text
The application includes a sample text about "Artificial Intelligence in Modern Business" to demonstrate slide generation. The text is structured with headings, bullet points, numbered lists, and paragraphs, which the application parses into slides.
File Structure
text-to-powerpoint-converter/
├── index.html        # Main HTML file with UI and JavaScript logic
└── README.md         # Project documentation

Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a feature branch (git checkout -b feature-name).
Commit your changes (git commit -m "Add feature").
Push to the branch (git push origin feature-name).
Open a pull request.

Issues
If you encounter any bugs or have feature requests, please open an issue on the GitHub repository.
License
This project is licensed under the MIT License. See the LICENSE file for details.
Acknowledgments

Built with Bootstrap
Icons by Font Awesome
PowerPoint generation by PptxGenJS
