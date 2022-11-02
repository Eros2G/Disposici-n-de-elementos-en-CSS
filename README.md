<!DOCTYPE html>
<html lang="es">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Disposición de elementos en CSS</title>
        <link rel="stylesheet" href="CSS/Ejercicio-disposicion-multimedia.css">
    </head>
    <body>
        <div class="galeria">
            <img class="img" src="Img/EldenRing.jpg" alt="Elden Ring">
            <img class="img" src="Img/HorizonForbiddenWest.jpg" alt="Horizon Forbidden West">
            <img class="img" src="Img/GodOfWarRagnarok.jpeg" alt="God Of War Ragnarok">
            <img class="img" src="Img/APlagueTaleRequiem.jpeg" alt="A Plague Tale Requiem">
            <img class="img" src="Img/CardShark.jpg" alt="Card Shark">
            <img class="img" src="Img/TMNTShreddersRevenge.jpg" alt="TMNT Shredders Revenge">
        </div>
    </body>
</html>


CSS

.galeria {
    display: flex;
    flex-wrap: wrap;
    gap: 5px;
}

.img {
    width: 300px;
}
