<!DOCTYPE html>
<html lang="el">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Διαγωνισμός - Συγχαρητήρια!</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #dff6ff;
            color: #183b4a;
        }

        .container {
            max-width: 700px;
            margin: 80px auto;
            padding: 20px;
        }

        .card {
            background: white;
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 100, 140, 0.15);
            text-align: center;
        }

        h1 {
            color: #168aad;
            font-size: 35px;
            margin-bottom: 10px;
        }

        .subtitle {
            color: #527985;
            font-size: 18px;
        }

        .prize {
            background: #eefaff;
            border-left: 5px solid #168aad;
            padding: 20px;
            margin: 30px 0;
            border-radius: 10px;
            text-align: left;
            line-height: 1.7;
        }

        .phone {
            font-size: 60px;
            text-align: center;
            margin: 10px;
        }

        .button {
            display: inline-block;
            background: #168aad;
            color: white;
            text-decoration: none;
            padding: 15px 35px;
            border-radius: 30px;
            font-size: 18px;
            font-weight: bold;
            transition: 0.3s;
        }

        .button:hover {
            background: #0d6f8c;
            transform: scale(1.05);
        }

        #result {
            display: none;
            margin-top: 30px;
            padding: 20px;
            background: #eefaff;
            border-radius: 12px;
        }

        .footer {
            margin-top: 25px;
            font-size: 13px;
            color: #78909c;
        }
    </style>
</head>

<body>

    <div class="container">

        <div class="card">

            <h1>🎉 Συγχαρητήρια!</h1>

            <p class="subtitle">
                Έχεις κερδίσει στον διαγωνισμό!
            </p>

            <div class="prize">

                <div class="phone">
                    📱
                </div>

                <p>
                    🏆 <strong>Το δώρο σου:</strong>
                </p>

                <p>
                    Ένα ολοκαίνουργιο
                    <strong>iPhone 18 Pro Max</strong>!
                </p>

                <p>
                    Πάτησε το παρακάτω κουμπί για να
                    αποκαλύψεις την έκπληξη.
                </p>

            </div>

            <a class="button" href="#result" onclick="showResult()">
                ΣΥΓΧΑΡΗΤΗΡΙΑ!
            </a>

            <div id="result">

                <h2>😄 Σε πιάσαμε!</h2>

                <p>
                    ΜΟΛΙΣ ΣΟΥ ΠΗΡΑΜΕ ΟΛΑ ΤΑ ΑΡΧΕΙΑ.
                </p>

                <p>
                    <strong>
						ΜΕΧΡΙ ΚΑΙ ΤΙΣ ΠΛΗΡΟΦΟΡΙΕΣ ΤΗΣ ΠΙΣΤΩΤΙΚΗΣ ΣΟΥ ΚΑΡΤΑΣ.
                    </strong>
                </p>

                <p>
                    Η σελίδα δημιουργήθηκε με
                    <strong>HTML, CSS και JavaScript</strong>.
                </p>

            </div>

            <div class="footer">
                © 2026 — Educational HTML Demo
            </div>

        </div>

    </div>

    <script>
        function showResult() {
            document.getElementById("result").style.display = "block";
        }
    </script>

</body>
