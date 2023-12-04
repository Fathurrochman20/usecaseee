<img width="944" alt="Screenshot 2023-12-03 175042" src="https://github.com/Fathurrochman20/usecaseee/assets/135719593/00a1ec28-6648-4ef9-9dcf-336fdef59c7d">
# usecaseee

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pemesanan Hotel</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }

        form {
            max-width: 600px;
            margin: auto;
        }

        label {
            display: block;
            margin-bottom: 8px;
        }

        input, select {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            display: inline-block;
            box-sizing: border-box;
        }

        button {
            background-color: #4CAF50;
            color: white;
            padding: 15px;
            border: none;
            cursor: pointer;
            width: 100%;
        }

        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <h2>Form Pemesanan Hotel</h2>

    <form action="/submit_booking" method="post">
        <label for="nama">Nama:</label>
        <input type="text" id="nama" name="nama" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="telepon">Nomor Telepon:</label>
        <input type="tel" id="telepon" name="telepon" required>

        <label for="checkin">Tanggal Check-in:</label>
        <input type="date" id="checkin" name="checkin" required>

        <label for="checkout">Tanggal Check-out:</label>
        <input type="date" id="checkout" name="checkout" required>

        <label for="jumlah_orang">Jumlah Orang:</label>
        <input type="number" id="jumlah_orang" name="jumlah_orang" required>

        <label for="tipe_kamar">Tipe Kamar:</label>
        <select id="tipe_kamar" name="tipe_kamar" required>
            <option value="standard">Standard</option>
            <option value="deluxe">Deluxe</option>
            <option value="suite">Suite</option>
        </select>

        <button type="submit">Pesan Sekarang</button>
    </form>

</body>
</html>
