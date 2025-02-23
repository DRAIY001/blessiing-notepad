<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BLESSING MOMODU</title>
</head>
<body>
    <style>
        body {
            background-image:url('media/blessing background.jpg');
            background-size: cover;
            background-repeat: no-repeat;
            background-attachment: fixed;
        }
    </style>
    <canvas id="birthdayCake" width="400" height="400"></canvas>
    <script>
        const canvas = document.getElementById('birthdayCake');
        const ctx = canvas.getContext('2d');

        // Draw the cake base
        ctx.fillStyle = '#D2691E';
        ctx.beginPath();
        ctx.ellipse(200, 300, 100, 50, 0, 0, Math.PI * 2);
        ctx.fill();
        ctx.closePath();

        // Draw the cake top
        ctx.fillStyle = '#F4A460';
        ctx.beginPath();
        ctx.ellipse(200, 200, 100, 50, 0, 0, Math.PI * 2);
        ctx.fill();
        ctx.closePath();

        // Draw the cake side
        ctx.fillStyle = '#D2691E';
        ctx.beginPath();
        ctx.moveTo(100, 200);
        ctx.lineTo(100, 300);
        ctx.lineTo(300, 300);
        ctx.lineTo(300, 200);
        ctx.fill();
        ctx.closePath();

        // Draw the number 31
        ctx.fillStyle = '#FFFFFF';
        ctx.font = '50px Arial';
        ctx.fillText('31', 170, 220);

        // Draw the candle
        ctx.fillStyle = '#FF6347';
        ctx.fillRect(190, 120, 20, 80);

        // Draw the candle flame
        ctx.fillStyle = '#FFD700';
        ctx.beginPath();
        ctx.moveTo(200, 100);
        ctx.lineTo(210, 140);
        ctx.lineTo(190, 140);
        ctx.fill();
        ctx.closePath();
    </script>
    <img src="media/blessing profile.jpg" alt="Blessing Momodu" style="width:200px;height:auto;border-radius:50%;">
    <h2>Blessing Momodu. </h2><p><h3>Born on the 23rd of februrary 1994 .Blessing is a 
        mother of two and a darling wife, not only that but she is a sibling to 4.
    Blessing is the first born daughter and first child of Mr and Mrs Igwe , she is a friend,
    cousin and all but who ever she is, she is loved by her family and friends and someday very soon ,by the world
    </p><p>We wish you a blissful +1 and many more years to come from your family</p><p>
        WE LOVE YOU VERY MUCH AND WISH YOU A HAPPY BIRTHDAY FROM
    
    </p> </h3>
    <p><h3>IK</h3>
        <video width="320" height="240" controls>
            <source src="media/IK vid.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </p>

    <p><h3>RITA</h3>
    <video width="320" height="240" controls>
        <source src="media/rita.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
    </p>
    
            
        <p><h3>BOBO</h3>
            <video width="320" height="240" controls>
                <source src="media/bobo.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        </p>
        <p><h3>MUMMY</h3>
        <video width="320" height="240" controls>
            <source src="media/mummy.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
        </p>

        <p><h3>MARCUS AND MARCELLINA</h3>
            <video width="320" height="240" controls>
                <source src="media/voice.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        <video width="320" height="240" controls>
            <source src="media/video.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    <img src="media/mar mum1.jpg" alt="Marcus and Marcellina with Mum 1" style="width:200px;height:auto;border-radius:10px;">
    <img src="media/marc mum 1.jpg" alt="Marcus and Marcellina with Mum 2" style="width:200px;height:auto;border-radius:10px;">
    <img src="media/marc mum 2.jpg" alt="Marcus and Marcellina with Mum 3" style="width:200px;height:auto;border-radius:10px;">
        </p>
        <canvas id="blimpCanvas" width="800" height="400"></canvas>
        <script>
            const blimpCanvas = document.getElementById('blimpCanvas');
            const blimpCtx = blimpCanvas.getContext('2d');

            // Draw the blimp body
            blimpCtx.fillStyle = '#FF69B4';
            blimpCtx.beginPath();
            blimpCtx.ellipse(400, 200, 150, 70, 0, 0, Math.PI * 2);
            blimpCtx.fill();
            blimpCtx.closePath();

            // Draw the blimp tail
            blimpCtx.fillStyle = '#FF69B4';
            blimpCtx.beginPath();
            blimpCtx.moveTo(250, 200);
            blimpCtx.lineTo(200, 170);
            blimpCtx.lineTo(200, 230);
            blimpCtx.fill();
            blimpCtx.closePath();

            // Draw the banner
            blimpCtx.fillStyle = '#FFD700';
            blimpCtx.fillRect(450, 180, 300, 40);

            // Draw the banner text
            blimpCtx.fillStyle = '#000000';
            blimpCtx.font = '20px Arial';
            blimpCtx.fillText('Happy Birthday Blessing', 460, 205);

            // Draw the ropes
            blimpCtx.strokeStyle = '#000000';
            blimpCtx.beginPath();
            blimpCtx.moveTo(450, 180);
            blimpCtx.lineTo(400, 160);
            blimpCtx.moveTo(450, 220);
            blimpCtx.lineTo(400, 240);
            blimpCtx.stroke();
            blimpCtx.closePath();
        </script>
    

    </body>
</html>
