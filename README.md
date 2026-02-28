
Basic Details
Team Name: Visionaries
Team Members
Member 1: [Pournamy B P] - [College of engineering,chengannur]
Member 2: [Athira Warrier] - [College of engineering,chengannur]
Hosted Project Link
[mention your project hosted link here]

Project Description
[The women safety app is a mobile application to provide immediate help during emergency situations through a single SOS button.The app aims to enhance women's security and confidence by using real-time tracking and instant alert technology.]

The Problem statement
[Women often face unsafe situations while traveling, working late, or being alone, and may not have enough time to call for help manually. In emergency situations, quickly informing trusted contacts and sharing location becomes difficult. Therefore, there is a need for a fast, reliable, and easy-to-use mobile application that can send alerts and share live location instantly with a single action.]

The Solution
[The Women Safety App provides a one-tap SOS button that instantly activates multiple emergency features. When pressed, it automatically sends the user’s live location via SMS with a Google Maps link, makes an emergency call, and starts audio/video recording for evidence. This ensures quick communication, real-time tracking, and immediate support during dangerous situations.]

Technical Details
Technologies/Components Used
For Software:

Languages used: [ Dart]
Frameworks used: [ Flutter]
Libraries used: [ geolocator,permission_handler,url_launcher,flutter_sms,shared_preferences,audioplayers]
Tools used: [ flutter,dart,android studio,visual studio code,android emulator,git]
For Hardware:

Main components: [List main components]
Specifications: [Technical specifications]
Tools required: [List tools needed]
Features
List the key features of your project:

Feature 1: [SOS Emergency button-Sends immediate help notification to saved contacts.]
Feature 2: [Live location sharing-Sends google map links through sms.Helps family or police to track exact location.]
Feature 3: [Emergency call-Directly calls the saved emergency contacts.]
Feature 4: [ Audio/Video recording feature-Audio feature allows the application to automatically start recording surrounding sounds when the SOS button is pressed.Video feature enables the app to activate the mobile camera and start recording video when the SOS button is triggered.]
Implementation
For Software:
Installation
[ flutter doctor,flutter create women_safety_app,cd women_safety_app,flutter pub get]
Run
[flutter devices,flutter run,fluter clean,flutter pub get]
For Hardware:
Components Required
[List all components needed with specifications]

Circuit Setup
[Explain how to set up the circuit]

Project Documentation
For Software:
Screenshots (Add at least 3)
![Screenshot (3)](C:Gambar\Screenshots\Screenshot (3).png) Add caption explaining what this shows

![Screenshot (4)](C:Gambar\Screenshots\Screenshot (4).png) Add caption explaining what this shows

![Screenshot (5)](C:Gambar\Screenshots\Screenshot (5).png) Add caption explaining what this shows

Additional Documentation
For Web Projects with Backend:
API Documentation
Base URL: https://api.yourproject.com

Endpoints
GET /api/endpoint

Description: [What it does]
Parameters:
param1 (string): [Description]
param2 (integer): [Description]
Response:
{
  "status": "success",
  "data": {}
}
POST /api/endpoint

Description: [What it does]
Request Body:
{
  "field1": "value1",
  "field2": "value2"
}
Response:
{
  "status": "success",
  "message": "Operation completed"
}
[Add more endpoints as needed...]

For Mobile Apps:
App Flow Diagram
App Flow Explain the user flow through your application

Installation Guide
For Android (APK):

Download the APK from [Release Link]
Enable "Install from Unknown Sources" in your device settings:
Go to Settings > Security
Enable "Unknown Sources"
Open the downloaded APK file
Follow the installation prompts
Open the app and enjoy!
For iOS (IPA) - TestFlight:

Download TestFlight from the App Store
Open this TestFlight link: [Your TestFlight Link]
Click "Install" or "Accept"
Wait for the app to install
Open the app from your home screen
Building from Source:

# For Android
flutter build apk
# or
./gradlew assembleDebug

# For iOS
flutter build ios
# or
xcodebuild -workspace App.xcworkspace -scheme App -configuration Debug
For Hardware Projects:
Bill of Materials (BOM)
Component	Quantity	Specifications	Price	Link/Source
Arduino Uno	1	ATmega328P, 16MHz	₹450	[Link]
LED	5	Red, 5mm, 20mA	₹5 each	[Link]
Resistor	5	220Ω, 1/4W	₹1 each	[Link]
Breadboard	1	830 points	₹100	[Link]
Jumper Wires	20	Male-to-Male	₹50	[Link]
[Add more...]				
Total Estimated Cost: ₹[Amount]

Assembly Instructions
Step 1: Prepare Components

Gather all components listed in the BOM
Check component specifications
Prepare your workspace Step 1 Caption: All components laid out
Step 2: Build the Power Supply

Connect the power rails on the breadboard
Connect Arduino 5V to breadboard positive rail
Connect Arduino GND to breadboard negative rail Step 2 Caption: Power connections completed
Step 3: Add Components

Place LEDs on breadboard
Connect resistors in series with LEDs
Connect LED cathodes to GND
Connect LED anodes to Arduino digital pins (2-6) Step 3 Caption: LED circuit assembled
Step 4: [Continue for all steps...]

Final Assembly: Final Build Caption: Completed project ready for testing

For Scripts/CLI Tools:
Command Reference
Basic Usage:

python script.py [options] [arguments]
Available Commands:

command1 [args] - Description of what command1 does
command2 [args] - Description of what command2 does
command3 [args] - Description of what command3 does
Options:

-h, --help - Show help message and exit
-v, --verbose - Enable verbose output
-o, --output FILE - Specify output file path
-c, --config FILE - Specify configuration file
--version - Show version information
Examples:

# Example 1: Basic usage
python script.py input.txt

# Example 2: With verbose output
python script.py -v input.txt

# Example 3: Specify output file
python script.py -o output.txt input.txt

# Example 4: Using configuration
python script.py -c config.json --verbose input.txt
Demo Output
Example 1: Basic Processing

Input:

This is a sample input file
with multiple lines of text
for demonstration purposes
Command:

python script.py sample.txt
Output:

Processing: sample.txt
Lines processed: 3
Characters counted: 86
Status: Success
Output saved to: output.txt
Example 2: Advanced Usage

Input:

{
  "name": "test",
  "value": 123
}
Command:

python script.py -v --format json data.json
Output:

[VERBOSE] Loading configuration...
[VERBOSE] Parsing JSON input...
[VERBOSE] Processing data...
{
  "status": "success",
  "processed": true,
  "result": {
    "name": "test",
    "value": 123,
    "timestamp": "2024-02-07T10:30:00"
  }
}
[VERBOSE] Operation completed in 0.23s
Project Demo
Video
[Add your demo video link here - YouTube, Google Drive, etc.]

Explain what the video demonstrates - key features, user flow, technical highlights

Additional Demos
[C:\Users\athir\Downloads\WhatsApp Video 2026-02-28 at 10.32.10 AM.mp4]

AI Tools Used (Optional - For Transparency Bonus)
If you used AI tools during development, document them here for transparency:

Tool Used: [e.g., GitHub Copilot, v0.dev, Cursor, ChatGPT, Claude]

Purpose: [What you used it for]

Example: "Generated boilerplate React components"
Example: "Debugging assistance for async functions"
Example: "Code review and optimization suggestions"
Key Prompts Used:

"Create a REST API endpoint for user authentication"
"Debug this async function that's causing race conditions"
"Optimize this database query for better performance"
Percentage of AI-generated code: [Approximately X%]

Human Contributions:

Architecture design and planning
Custom business logic implementation
Integration and testing
UI/UX design decisions
Note: Proper documentation of AI usage demonstrates transparency and earns bonus points in evaluation!

Team Contributions
[Name 1]: [Specific contributions - e.g., Frontend development, API integration, etc.]
[Name 2]: [Specific contributions - e.g., Backend development, Database design, etc.]
[Name 3]: [Specific contributions - e.g., UI/UX design, Testing, Documentation, etc.]
License
This project is licensed under the [LICENSE_NAME] License - see the LICENSE file for details.

Common License Options:

MIT License (Permissive, widely used)
Apache 2.0 (Permissive with patent grant)
GPL v3 (Copyleft, requires derivative works to be open source)
Made with ❤️ at TinkerHub