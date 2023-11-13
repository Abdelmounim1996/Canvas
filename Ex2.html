<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    body {
        background-color: gray;
        height: 100vh;
        display: flex;
        flex-direction: column;
        justify-content: space-around;
        align-items: center;
        font-family: cursive;
        /* color: white; */
    }

    canvas {
        box-shadow: 0 0 20px white;
    }

    fieldset {
        border-radius: 5px;
        border: solid 2px;
        padding: 10px 15px 15px 15px;
        box-sizing: border-box;
        width: 400px;
    }

    input[type="url"],
    input[type="submit"] {
        padding: 10px;
        border-radius: 5px;
    }

    input[type="url"] {
        width: 70%;
        padding-left: 25px;
    }
</style>

<body>
    <form action="#" id="form">
        <fieldset>
            <legend>Image : </legend>
            <label for="#"></label>
            <input type="url" name="#" id="img">
            <input type="submit" value="submit">
        </fieldset>
    </form>
    <canvas id="canvas" width="400" height="400" style="border: solid;"></canvas>
    <script>
        let imgurl = document.getElementById("form").addEventListener("submit",
            function (event) {
                event.preventDefault();
                let img = new Image();
                let url = document.getElementById("img").value;
                img.src = url;
                img.onload = function () {
                    let canvas = document.getElementById("canvas");
                    console.log(canvas);
                    canvas.style.backgroundColor = "azure";
                    let ctx = canvas.getContext("2d");
                    canvas.height = img.height;
                    canvas.width = img.width;
                    if (document.body.clientHeight < img.height) {
                        canvas.height = document.body.clientHeight * 0.9;
                    }

                    if (document.body.clientWidth < img.width) {
                        canvas.width = document.body.width * 0.9;
                    }
                    let info = canvas.getBoundingClientRect();
                    document.addEventListener("mousemove", function (event) {
                        ctx.drawImage(img, 0, 0);
                        let x = event.clientX;
                        let y = event.clientY;
                        let xx = Math.round(event.clientX - info.left);
                        let yy = Math.round(event.clientY - info.top);
                        ctx.fillText("(X: " + xx + ", Y: " + yy + ")", 10, 20);
                        ctx.font = "16px cursive";
                        ctx.fillStyle = "white";
                        ctx.beginPath();
                        ctx.arc(xx, yy, 10, 0, 2 * Math.PI);
                        var z = 40;
                        ctx.moveTo(xx + z, yy);
                        ctx.lineTo(xx - z, yy);
                        ctx.moveTo(xx, z + yy);
                        ctx.lineTo(xx, yy - z);
                        ctx.fillStyle = "black";
                        ctx.strokeStyle = "black";
                        ctx.lineWidth = 5;
                        ctx.lineCap = "round";
                        ctx.stroke();
                        ctx.fill();
                    });
                }
            });

    </script>
</body>

</html>
