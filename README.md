
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Precicom 3D Printing Services Catalogue</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #ff5722, #2196f3, #4caf50);
            color: #f5f5f5;
            line-height: 1.6;
        }
        header {
            background: linear-gradient(135deg, #673ab7, #2196f3);
            color: #fff;
            text-align: center;
            padding: 30px;
            border-bottom-left-radius: 20px;
            border-bottom-right-radius: 20px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
        }
        h1 {
            font-family: 'Montserrat', sans-serif;
            font-size: 36px;
            font-weight: 700;
            margin-bottom: 5px;
        }
        p, h2, h3 {
            font-family: 'Poppins', sans-serif;
        }
        section {
            padding: 20px;
        }
        .intro, .service, .vision {
            background: rgba(0, 0, 0, 0.7);
            padding: 20px;
            border-radius: 15px;
            margin-bottom: 20px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }
        .service {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-top: 20px;
        }
        .service img {
            width: 200px;
            height: 200px;
            object-fit: cover;
            border-radius: 10px;
            transition: transform 0.3s ease;
        }
        .service img:hover {
            transform: scale(1.05);
        }
        .service-details {
            flex-grow: 1;
            margin-left: 20px;
        }
        .service-details h3 {
            font-family: 'Montserrat', sans-serif;
            font-size: 22px;
            font-weight: 700;
            color: #ff9800;
        }
        .pricing {
            font-weight: bold;
            color: #00e676;
            font-size: 16px;
        }
        .contact-info {
            text-align: center;
            background: linear-gradient(135deg, #00bcd4, #ff9800);
            color: #fff;
            padding: 10px;
            margin-top: 20px;
            border-radius: 15px;
        }
        .contact-info a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
            font-size: 14px;
            border: 2px solid #fff;
            padding: 5px 15px;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }
        .contact-info a:hover {
            background-color: #ff5722;
        }
        .tech-quote {
            font-family: 'Poppins', sans-serif;
            font-size: 16px;
            font-style: italic;
            color: #cfd8dc;
            margin-top: 30px;
            text-align: center;
        }
        @media (max-width: 768px) {
            .service {
                flex-direction: column;
                text-align: center;
            }
            .service img {
                width: 70%;
                margin-bottom: 20px;
            }
            .service-details {
                margin-left: 0;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Precicom 3D</h1>
    <p>Your Trusted 3D Printing Partner</p>
</header>

<section class="intro">
    <h2>About Us</h2>
    <p>Precicom 3D is a leading provider of 3D printing services based in Chennai, specializing in FDM, SLA, and SLS technologies. We offer high-quality, cost-effective solutions for prototypes, functional parts, and end-use components. Whether you need rapid prototyping or custom solutions, we are here to help bring your ideas to life.</p>
</section>

<section>
    <h2>Our Services</h2>
    <div class="service">
        <div class="service-details">
            <h3>FDM Printing</h3>
            <p>FDM (Fused Deposition Modeling) uses thermoplastic filaments deposited layer by layer to create objects. Suitable for rapid prototyping and functional parts.</p>
            <p class="pricing">Pricing: ₹15/cc (PLA), ₹25/cc (ABS)</p>
        </div>
        <img src="https://www.bhphotovideo.com/images/images750x750/creality_ender_3v2_ender_3_v2_fdm_3d_1705448.jpg" alt="FDM Printer">
    </div>

    <div class="service">
        <div class="service-details">
            <h3>SLA Printing</h3>
            <p>SLA (Stereolithography) provides high precision and smooth finishes, ideal for intricate models and prototypes with exceptional detail.</p>
            <p class="pricing">Pricing: ₹50/cc</p>
        </div>
        <img src="https://images.squarespace-cdn.com/content/v1/5b6e3beb85ede1a17e4a6830/1566499392899-64UXSZUPIVSBBIDE6EYS/form-2-printer-three-quarters-hart1.jpg" alt="SLA Printer">
    </div>

    <div class="service">
        <div class="service-details">
            <h3>SLS Printing</h3>
            <p>SLS (Selective Laser Sintering) produces durable, high-strength parts for industrial applications and complex geometries.</p>
            <p class="pricing">Pricing: ₹65/cc</p>
        </div>
        <img src="https://3dprint.com/wp-content/uploads/2017/10/1463590945-HP-HPQ-Launches-Multi-Jet-Fusion-3D-Printers.jpg" alt="SLS Printer">
    </div>
</section>

<section class="contact-info">
    <p>Contact us: <a href="mailto:precicom3d@gmail.com">precicom3d@gmail.com</a></p>
</section>

<section class="tech-quote">
    <p>"The best way to predict the future is to create it." – Abraham Lincoln</p>
</section>

</body>
</html>
