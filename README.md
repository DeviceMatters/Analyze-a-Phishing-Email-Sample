# Analyze-a-Phishing-Email-Sample
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  
</head>
<body>
  <h1>Phishing Email Analysis Report</h1>

  <div class="section">
    <h2>Subject</h2>
    <p><strong>Urgent: Your PayPal Account Has Been Limited</strong></p>
    <p class="flag">🚩 Uses urgency to scare the user into acting quickly.</p>
  </div>

  <div class="section">
    <h2>Sender</h2>
    <p><strong>support@paypalsecurity-alert.com</strong></p>
    <p class="flag">🚩 Spoofed address – not a genuine PayPal domain (should be something like @paypal.com).</p>
  </div>

  <div class="section">
    <h2>Greeting</h2>
    <p><strong>Dear Customer</strong></p>
    <p class="flag">🚩 Generic greeting – real companies usually use your full name.</p>
  </div>

  <div class="section">
    <h2>Link & Call to Action</h2>
    <p><strong>👉 Verify Now</strong></p>
    <p class="flag">🚩 Urges the user to click without showing the URL. Could lead to a fake login page.</p>
  </div>

  <div class="section">
    <h2>Threat Language</h2>
    <p><strong>Failure to do so within 24 hours will result in permanent suspension of your account.</strong></p>
    <p class="flag">🚩 Threatens consequences to pressure fast action.</p>
  </div>

  <div class="section">
    <h2>Other Phishing Indicators</h2>
    <ul>
      <li>🚩 Lack of personalization</li>
      <li>🚩 No account or case reference number</li>
      <li>🚩 No official contact links or help info</li>
    </ul>
  </div>

  </body>
</html>
