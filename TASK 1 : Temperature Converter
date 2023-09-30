<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>Temperature Converter</title>
 <style>
 body {
 font-family: Arial, sans-serif;
 text-align: center;
 }
 .container {
 margin: 50px auto;
 max-width: 400px;
 padding: 20px;
 border: 1px solid #ccc;
 border-radius: 5px;
 box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
 }
 h1 {
 color: #333;
 }
 label {
 font-weight: bold;
 }
 input[type="number"] {
 width: 100%;
 padding: 10px;
 margin-bottom: 15px;
 }
 button {
 background-color: #007BFF;
 color: white;
 border: none;
 padding: 10px 20px;
 border-radius: 5px;
 cursor: pointer;
 }
 button:hover {
 background-color: #0056b3;
 }
 #result {
 font-weight: bold;
 margin-top: 10px;
 }
 </style>
</head>
<body>
 <div class="container">
 <h1>Temperature Converter</h1>
 <label for="celsius">Enter Temperature in Celsius:</label>
 <input type="number" id="celsius" placeholder="Enter temperature in Celsius">
 <br>
 <label for="fahrenheit">Result in Fahrenheit:</label>
 <p id="result"></p>
 <button onclick="convertTemperature()">Convert</button>
 </div>
 <script>
 function convertTemperature() {
 // Get the input value in Celsius
 const celsiusInput = document.getElementById("celsius").value;

 // Check if the input is a valid number
 if (isNaN(celsiusInput)) {
 alert("Please enter a valid number.");
 return;
 }
 // Convert Celsius to Fahrenheit
 const fahrenheit = (celsiusInput * 9/5) + 32;
 // Display the result
 document.getElementById("result").innerText = `${celsiusInput}°C is equal to
${fahrenheit.toFixed(2)}°F`;
 }
 </script>
</body>
</html>
