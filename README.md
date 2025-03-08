# Code-Scanner
Dragonball Fusion World Digital Card Code Scanner


Dragon Ball Scanner
Dragon Ball Scanner is a Windows tool that uses your webcam to extract digital codes from Dragon Ball Fusion cards. The tool leverages a custom OCRB model with Tesseract OCR to read codes from your cards. It also provides live image post-processing with adjustable sliders so you can fine-tune the image before scanning.

Features
Live Camera Feed: View your camera feed in real time.
Live Post-Processing: Adjust contrast, brightness, and sharpness with sliders to optimize the processed image.
Instant Scanning: Press the spacebar to scan the current frame and extract the 16-character code.
Code Management: Edit, delete, and undo changes in your list of scanned codes.
Additional Tools: View an example image to see ideal lighting, card positioning, and processed output.
Donation Option: A donate button is included to support further development.
Installation
Run the Installer:
Use the provided installer (DragonBallScanner_Installer.exe) to install the program on your Windows PC. The installer will copy the application executable, the required Tesseract portable files, the tessdata folder (with the OCRB model), and additional resources (README, requirements, and example image) to the installation directory.

Desktop Shortcut (Optional):
During installation, you can opt to create a desktop shortcut.

Launch the Application:
After installation, you can launch Dragon Ball Scanner either via the Start Menu or desktop shortcut.

Usage
Viewing the Example:
Open the example.png file (included in the installation) to see an ideal setup. This image shows the optimal lighting, card positioning, and how the processed image should look for the best OCR results.

Setting Up Your Camera:
Position your webcam so that it captures the code on your card as large and as clearly as possible. Good focus and lighting are essential.

Adjusting the Processed Image:
Use the provided sliders (Contrast, Brightness, and Sharpness) to adjust the processed (thresholded) image in real time.

Tip: Take a few scans while adjusting the sliders until the processed image is clear and the code is well-defined.
Scanning Codes:
Once the processed image looks good, press the spacebar to scan the code. The tool extracts the code in the format "XXXX XXXX XXXX XXXX" and adds it to the list.

Managing Scanned Codes:

Edit: Double-click any scanned code in the list to manually correct errors.
Delete: Use the "Delete Selected Code" button to remove any incorrect entries.
Clear All: Click the "Clear All Codes" button to start fresh.
Undo: If you delete codes accidentally, use the "Undo" button to restore them.
Copy to Clipboard: Use the "Copy to Clipboard" button to copy all scanned codes for later use.
Tips for Best Results
Camera Setup:
Ensure your camera is properly positioned and focused on the card's code. The code should occupy a large portion of the frame for better extraction accuracy.

Lighting:
Good, even lighting without glare will produce a clearer image for OCR.

Processed Image:
Use the sliders to optimize the contrast, brightness, and sharpness of the processed image until the code is distinctly visible.
Once you get the desired processed image, clear the scanned codes list and begin scanning.

Troubleshooting
OCR Accuracy:
If the OCR output is not accurate, try adjusting the sliders further. Experiment with different lighting conditions and camera positions.

Camera Issues:
If the camera feed does not display, ensure that your webcam is properly connected and that no other application is using it.

Installation:
If you encounter issues during installation, verify that all required files (Tesseract, tessdata, example.png, README.txt, etc.) are present in the installation package.

Feedback and Donations
If you enjoy using Dragon Ball Scanner and would like to support its development, please consider making a donation. Click the "Donate" button at the top of the app to contribute via PayPal.
"This took a while to get working properly. No donations are required but are very much appreciated."
