####Onligne Banking App
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .container {
            display: flex;
            justify-content: space-around;
        }

        .form-container {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 300px;
            text-align: center; /* Centrer le texte dans le formulaire */
        }

        form {
            display: flex;
            flex-direction: column;
        }

        h2 {
            color: #007BFF;
        }

        label {
            margin-bottom: 8px;
            color: #333; /* Couleur du texte du label */
        }

        input {
            margin-bottom: 16px;
            padding: 8px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        button {
            padding: 10px;
            background-color: #007BFF;
            color: #fff;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            transition: background-color 0.3s ease; /* Ajout d'une transition sur la couleur de fond */
        }

        button:hover {
            background-color: #0056b3;
        }
    </style>
    <title>Online Banking App</title>
</head>
<body>
    <div class="container">
        <div class="form-container">
            <form id="signin-form">
                <h2>Connexion</h2>
                <label for="username">Nom d'utilisateur :</label>
                <input type="text" id="username" required>
                <label for="password">Mot de passe :</label>
                <input type="password" id="password" required>
                <button type="submit">Se connecter</button>
            </form>
        </div>
        <div class="form-container">
            <form id="signup-form">
                <h2>Inscription</h2>
                <label for="new-username">Nouveau nom d'utilisateur :</label>
                <input type="text" id="new-username" required>
                <label for="new-password">Nouveau mot de passe :</label>
                <input type="password" id="new-password" required>
                <button type="submit">S'inscrire</button>
            </form>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>


