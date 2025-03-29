<!DOCTYPE html>
<html>
<head>
    <!--author: Johan Pablo-->
    <title>Personalized Account</title>
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
        }
        .header {
            background-image: url('');
            height: 300px;
            display: flex;
            justify-content: center;
            align-items: center;
            position: relative;
        }
        .header h1 {
            color: white;
            font-size: 36px;
            text-align: center;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }
        .container {
            padding: 20px;
        }
        .image-grid {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
        }
        .image-item {
            width: 48%;
            margin-bottom: 20px;
        }
        .image-item img {
            width: 100%;
            height: 200px;
            border-radius: 8px;
        }
        .caption {
            text-align: center;
            margin-top: 8px;
            font-weight: 700;
        }
    </style>
</head>
<body>

    <div class="header">
        <h1>Personalized Account</h1>
    </div>
    
    <div class="container">

        <div class="image-grid">
            <div class="image-item">
                <img src="https://photos.google.com/share/AF1QipNUskMmIX_2YBMtysUMk3S783x4eXxqazbA6aWq3gPlKquANNeaevgbpAYEqq2c-Q?key=bjNJUjI3SGYwa1VTQjlDeHh6S2tXNVp5QTE1c05R">
                <div class="caption">Graduation Picture</div>
            </div>
            <div class="image-item">
                <img src="https://photos.google.com/share/AF1QipPsOTe3TCF8HDvsdhZoWAY7J63_WghjV9neVWqaDaUKlBkdaUIXCEXCmPw9lNfcxg?key=b3pLSVZoNzlLeVRBbUg5WnV1WmZmN1gyUFI1ZWhR" >
                <div class="caption">First University Meet</div>
            </div>
        </div>
        
        <div class="img" >
            <div class="image-item">
                <img src="https://photos.google.com/share/AF1QipPjSa5h64vc4nPcUOPqD4DVvvcAmxsu4PF7-73mbOyAJbr8YfZmYHXzNrdhZwi0FQ?key=SjNjX1ZtcDNRSkNERmZfYVBSWGJ5Z0dPNHNSYmRB" >
                <div class="caption">Love taking pictures of sky</div>
            </div>
            <div class="image-item">
                <img src="https://photos.google.com/share/AF1QipMLLQ-aiPxB7fSyL3d7SpoDY2_ix2a71_y_64VbENh7a8wwjzhQ1Qaei_EEJG1WHQ?key=cnBGUWhKNlB3cnJycVY4X0pKRlhfUlRfV0xMQWdR">
                <div class="caption">Dream House</div>
            </div>
        </div>

    </div>
    
</body>
</html>
