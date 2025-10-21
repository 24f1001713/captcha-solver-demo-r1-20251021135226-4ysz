# Captcha Solver Demo

```markdown
# Captcha Solver Demo

## Summary
The Captcha Solver Demo is a small web application that utilizes Optical Character Recognition (OCR) via [Tesseract.js](https://github.com/naptha/tesseract.js) to solve captchas. This project demonstrates the capabilities of OCR technology in recognizing text from images, specifically captcha forms commonly used in web applications.

## Setup
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/captcha-solver-demo.git
   cd captcha-solver-demo
   ```

2. **Install dependencies**:
   Ensure you have Node.js and npm installed. Then, in your project directory, run:
   ```bash
   npm install
   ```

3. **Start the server**:
   Run the following command to launch the web app:
   ```bash
   npm start
   ```
   The application will be accessible at `http://localhost:3000`.

## Usage
To use the captcha solver, navigate to the app in your web browser. You can input an image URL of the captcha you would like to solve. The app will process the image using Tesseract.js and display the recognized text.

## Test Instructions
You can test the captcha solver by visiting the following URL structure:
```
http://localhost:3000?url=<image>
```
Replace `<image>` with the actual URL of the captcha image you want to solve.

## Attachments Location
The project directory contains an `images` folder where example captchas are stored for testing purposes. You can also provide your own images through URL inputs.

## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for more details.
```
