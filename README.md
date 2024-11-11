< html>

<head>
 
  <title>Hotel Management</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }
    header {
      background-color: #333;
      color: #fff;
      padding: 10px 0;
      text-align: center;
    }
    header h1 {
      margin: 0;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #444;
    }
    nav a {
      color: #fff;
      padding: 15px 20px;
      text-decoration: none;
    }
    nav a:hover {
      background-color: #666;
    }
    .container {
      padding: 20px;
    }
    .section {
      margin-bottom: 20px;
    }
    .section h2 {
      color: #333;
    }
    .room {
      display: flex;
      background-color: #fff;
      border: 1px solid #ddd;
      margin-bottom: 10px;
      padding: 10px;
      border-radius: 5px;
    }
    .room img {
      width: 150px;
      height: 100px;
      margin-right: 20px;
      border-radius: 5px;
    }
    .room-info {
      flex: 1;
    }
    footer {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 10px 0;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to Our Hotel</h1>
  </header>

  <nav>
    <a href="#rooms">Rooms</a>
    <a href="#amenities">Amenities</a>
    <a href="#contact">Contact Us</a>
  </nav>

  <div class="container">

    <section id="rooms" class="section">
      <h2>Our Rooms</h2>
      <div class="room">
        <img src="C:\Users\harsh tonde\Downloads\Room1.jpeg" alt="Deluxe Room">
        <div class="room-info">
          <h3>Deluxe Room</h3>
          <p>Enjoy a luxurious stay in our Deluxe Room with a beautiful view, king-sized bed, and modern amenities.</p>
        </div>
      </div>
      <div class="room">
        <img src="C:\Users\harsh tonde\Downloads\ROOM3.jpeg" alt="Suite">
        <div class="room-info">
          <h3>Suite</h3>
          <p>Our spacious suite offers a separate living area, king-sized bed, and a stunning city view.</p>
        </div>
      </div>
      <div class="room">
        <img src="C:\Users\harsh tonde\Downloads\Room2.jpeg"  alt="Single Room">
        <div class="room-info">
          <h3>Single Room</h3>
          <p>A cozy room perfect for solo travelers with all the essential amenities and a comfortable bed.</p>
        </div>
      </div>
    </section>

    <section id="amenities" class="section">
      <h2>Amenities</h2>
      <p>Our hotel offers a variety of amenities for a relaxing stay:</p>
      <ul>
        <li>Free Wi-Fi</li>
        <li>Swimming Pool</li>
        <li>Gym & Spa</li>
        <li>24-hour Room Service</li>
        <li>Complimentary Breakfast</li>
      </ul>
    </section>

    <section id="contact" class="section">
      <h2>Contact Us</h2>
      <p>If you have any questions or need further assistance, please reach out to us:</p>
      <p>Email: info@ourhotel.com</p>
      <p>Phone: +1 (555) 123-4567</p>
    </section>

  </div>

  <footer>
    <p>&copy; 2024 Our Hotel. All Rights Reserved.</p>
  </footer>

</body>
</html>
