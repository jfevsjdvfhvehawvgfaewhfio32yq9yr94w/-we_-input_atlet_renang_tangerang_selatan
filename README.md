# -we_-input_atlet_renang_tangerang_selatan
<!DOCTYPE html>
<html>

<head>
  <title>INPUT DATA ATLET RENANG TANGERANG SELATAN</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    /*  */
    body {
      background-color: #0c0a0a;
    }
    #form-container {
      width: 500px;
      margin: 0 auto;
      background-color: #f1f1f7;
      border: 2px solid #da0808;
      border-radius: 10px;
      padding: 20px;
    }
    #form-container h2 {
      text-align: center;
      color: #1E90FF;
    }
    #form-container input[type="text"], #form-container input[type="date"], #form-container input[type="tel"] {
      width: 100%;
      padding: 10px;
      margin-bottom: 20px;
      border: 2px solid #f1d0d0;
      border-radius: 5px;
    }
    #form-container input[type="submit"] {
      background-color: #1E90FF;
      color: #FFFFFF;
      border: none;
      border-radius: 5px;
      padding: 10px;
      cursor: pointer;
    }
    #form-container input[type="submit"]:hover {
      background-color: #004B8D;
    }
    #footer {
      text-align: center;
      margin-top: 30px;
      font-size: 12px;
      color: #f7f1f1;
    }
  </style>
</head>

<body>
  <div id="form-container">
    <h2>INPUT DATA ATLET RENANG TANGERANG SELATAN</h2>
    <!-- akses link script app -->
    <form action="https://script.google.com/macros/s/AKfycbxdYQCbEBCZgyY9vhP1BfN6VQ0RaP53PekT0EKZ_9anpEDMCE3gVhAh3VMY4hbjbahkeA/exec" method="post">
    <!-- end akses  -->

        <label for="nama">Nama:</label>
      <input type="text" id="nama" name="nama" required>
      <label for="kategori">Kategori:</label>
      <input type="text" id="kategori" name="kategori" required>
      <label for="tgl_lahir">Tanggal Lahir:</label>
      <input type="date" id="tgl_lahir" name="tgl_lahir" required>
      <label for="jns_kelamin">Jenis kelamin:</label>
      <input type="text" id="jns_kelamin" name="jns_kelamin" required>
      <label for="event_history">Event history:</label>
      <input type="text" id="event_history" name="event_history" required>
      <input type="submit" value="Simpan Data">
    </form>
  </div>

  <div id="footer">
    All Tutorial for you, jagan lupa subcribe karna akan selalu ada update
  </div>

</body>
</html>

