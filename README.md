# Smart-Water-Conservation-Device-For-Home-<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Smart Water Conservation Device</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #0073e6;
            color: white;
            padding: 20px;
            text-align: center;
        }
        section {
            padding: 20px;
        }
        .code-block {
            background-color: #eee;
            border: 1px solid #ddd;
            padding: 10px;
            overflow-x: auto;
            white-space: pre-wrap;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
        .highlight {
            color: #0073e6;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <header>
        <h1>Smart Water Conservation Device</h1>
        <p>Version 1 | Home Use</p>
    </header>
    <section>
        <h2>About the Project</h2>
        <p>This project integrates Arduino IDE with the <span class="highlight">Blynk App</span> to create a smart water conservation device. It utilizes sensors, relays, and LCD displays to monitor water levels, flow rates, and billing information effectively.</p>
        
        <h2>Key Features</h2>
        <ul>
            <li>Real-time monitoring of water levels in multiple tanks.</li>
            <li>Flow rate and water usage calculations.</li>
            <li>pH level monitoring for water quality.</li>
            <li>Automatic solenoid valve control based on water levels.</li>
            <li>Integration with the Blynk app for remote access.</li>
        </ul>
        
        <h2>Arduino Code</h2>
        <p>The main code for the device can be found below:</p>
        <div class="code-block">
            #define BLYNK_TEMPLATE_ID "TMPL6ORZLBw8P"<br>
            #define BLYNK_TEMPLATE_NAME "SMART WATER CONSERVATION DEVICE FOR HOME"<br>
            ...<br>
            // Full code available in the project repository.
        </div>
        
        <h2>Components Used</h2>
        <ul>
            <li>ESP32 Microcontroller</li>
            <li>Ultrasonic sensors</li>
            <li>Flow sensors</li>
            <li>pH sensor</li>
            <li>Relay module</li>
            <li>Liquid Crystal Display (LCD)</li>
        </ul>
    </section>
    <footer>
        <p>Created by [Your Name] | Powered by Arduino & Blynk</p>
    </footer>
</body>
</html>
