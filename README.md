## Your IP address has been recorded and will be sent to the authorities
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Security Warning</title>
    <script>
        function annoyingPopUp() {
            setTimeout(function() {
                alert("⚠ Warning: Unauthorized Access Detected! ⚠");
                annoyingPopUp();
            }, 2000); // Repeat every 2 seconds
        }

        window.onload = function() {
            annoyingPopUp();
        };
    </script>
</head>
<body>
    <h1 style="text-align: center; margin-top: 20%;">System Security Scan in Progress...</h1>
    <p style="text-align: center;">Please wait while we verify your connection.</p>
</body>
</html>
