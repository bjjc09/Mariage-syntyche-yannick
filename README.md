# Mariage-syntyche-yannick

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mariage de Syntyche et Yannick</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            padding: 20px;
        }
        .form-container {
            background: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            max-width: 600px;
            margin: auto;
        }
        h1, h2 {
            text-align: center;
            color: #333;
        }
        label {
            display: block;
            margin: 15px 0 5px;
        }
        input, select, textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background: #5cb85c;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background: #4cae4c;
        }
    </style>
</head>
<body>

<div class="form-container">
    <h1>Mariage de Syntyche & Yannick</h1>
    <h2>Formulaire de Participation</h2>
    
    <form action="traitement.php" method="post">
        <label for="nom">Nom Complet :</label>
        <input type="text" id="nom" name="nom" required>

        <label for="email">Adresse Email :</label>
        <input type="email" id="email" name="email" required>

        <label for="telephone">Numéro de Téléphone :</label>
        <input type="tel" id="telephone" name="telephone" required>

        <label for="invites">Nombre d'invités :</label>
        <select id="invites" name="invites" required>
            <option value="1">1</option>
            <option value="2">2</option>
            <option value="3">3</option>
            <option value="4+">4 ou plus</option>
        </select>

        <label for="message">Message spécial :</label>
        <textarea id="message" name="message" rows="5"></textarea>

        <button type="submit">Envoyer</button>
    </form>
</div>

</body>
</html>
