<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Thank You, Teacher!</title>
  <style>
    /* Reset and Body Styling */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Georgia', serif;
      background: linear-gradient(to right, #fefcea, #f1da36);
      color: #333;
      padding: 20px;
      animation: fadeIn 1.5s ease;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    /* Container Styling */
    .container {
      max-width: 800px;
      margin: 40px auto;
      padding: 30px;
      background-color: #fff8dc;
      border-radius: 15px;
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
    }

    h1 {
      text-align: center;
      font-size: 2.8em;
      color: #d4af37;
      margin-bottom: 20px;
      animation: slideDown 1s ease;
    }

    @keyframes slideDown {
      from { transform: translateY(-30px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    .message, .charm {
      font-size: 1.2em;
      line-height: 1.8;
      margin: 25px 0;
      animation: fadeIn 2s ease;
    }

    .charm {
      background-color: #fff3b0;
      padding: 20px;
      border-left: 5px solid #f4b400;
      border-radius: 10px;
      font-style: italic;
    }

    .button-container {
      text-align: center;
      margin-top: 30px;
    }

    .button {
      padding: 15px 30px;
      background-color: #f4b400;
      color: white;
      font-size: 1.2em;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      transition: all 0.3s ease;
    }

    .button:hover {
      background-color: #c49000;
      transform: scale(1.05);
    }

    /* Audio Player Styling */
    .audio-container {
      text-align: center;
      margin-top: 30px;
    }

    audio {
      width: 100%;
      max-width: 300px;
      margin-top: 10px;
      outline: none;
    }

    /* Responsive Design */
    @media (max-width: 600px) {
      h1 {
        font-size: 2em;
      }

      .message, .charm {
        font-size: 1em;
      }

      .button {
        font-size: 1em;
        padding: 12px 24px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Dear Teacher, Thank You!</h1>

    <div class="message">
      <p>
        From chalkboard to heart, your lessons stay with us far beyond the classroom.
        You’ve been a guiding star, not just in academics, but in how to be better humans.
      </p>
      <p>
        This webpage is a simple token of ou
