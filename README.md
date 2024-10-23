# My AR project

This is a project of AR using AR.js y A-Frame.

pattern-LOGO-STB-ACADEMY-NEGRO-VERDE.png

## Description

This project shows how to use a custom marker instead of the default "hiro" marker.

## Instructions

1. Upload your image to AR.js Marker Training to generate a `.patt` file.
2. Upload the `.patt` file to your GitHub repository.
3. Use the URL of the `.patt` file in your CodePen project.
## Example Code

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>STB Academy</title>
    <script src="https://aframe.io/releases/1.0.4/aframe.min.js"></script>
    <script src="https://raw.githack.com/AR-js-org/AR.js/master/aframe/build/aframe-ar.js"></script>
</head>
<body>
    <a-scene embedded arjs>
        <a-marker type="pattern" url="https://tu-repositorio.github.io/ruta/a/tu/patron.patt">
            <a-entity position="0 0 0" scale="0.1 0.1 0.1">
                <a-sphere radius="5" color="blue"></a-sphere>
            </a-entity>
        </a-marker>
        <a-entity camera></a-entity>
    </a-scene>
</body>
</html>
