# garvit
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hello Animation</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="animated-text">Hello</div>
    <style>body {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        margin: 0;
        background-color: #f0f0f0;
        font-family: Arial, sans-serif;
    }
    
    .animated-text {
        font-size: 3rem;
        color: #333;
        opacity: 0;
        animation: fadeInOut 3s infinite;
    }
    
    @keyframes fadeInOut {
        0% {
            opacity: 0;
        }
        50% {
            opacity: 1;
        }
        100% {
            opacity: 0;
        }
    }</style>
</body>
</html>
# garvit
