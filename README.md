<!DOCTYPE html>
<html>
<head>
    <title>Questionnaire</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #F9F9F9;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 600px;
            margin: 0 auto;
            background-color: #FFFFFF;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #FF6600; /* Couleur orange */
        }
        label {
            display: block;
            margin-top: 10px;
        }
        input[type="radio"] {
            margin-right: 5px;
        }
        input[type="submit"] {
            background-color: #FF6600;
            color: #FFFFFF;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Voulez-vous continuer à recevoir nos e-mails ?</h2>
        <form action="mailto:juliette.legrand@123fleurs.com" method="post" enctype="text/plain">
            <label for="oui"><input type="radio" id="oui" name="reponse" value="Oui"> Oui</label>
            <label for="non"><input type="radio" id="non" name="reponse" value="Non"> Non</label><br>
            <input type="submit" value="Envoyer">
        </form>
    </div>
</body>
</html>
