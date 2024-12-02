<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Precicom 3D Printing Services Catalogue</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #2c2c2c;
            color: #e0e0e0;
            line-height: 1.6;
        }
        @page {
            size: A4;
            margin: 20mm;
        }
        header {
            background: linear-gradient(135deg, #0066cc, #00b8d4);
            color: #fff;
            text-align: center;
            padding: 20px;
            border-bottom-left-radius: 20px;
            border-bottom-right-radius: 20px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
        }
        h1 {
            font-size: 36px;
            font-weight: bold;
            margin-bottom: 5px;
        }
        p {
            font-size: 14px;
        }
        section {
            padding: 20px;
        }
        .intro, .service, .vision {
            background: #333;
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
            border-radius: 10px;
        }
        .service img {
            width: 180px;
            height: 180px;
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
            font-size: 22px;
            font-weight: bold;
            color: #00b8d4;
        }
        .service-details p {
            font-size: 14px;
        }
        .pricing {
            font-weight: bold;
            color: #00e676;
            font-size: 16px;
        }
        .contact-info {
            text-align: center;
            background: linear-gradient(135deg, #0066cc, #00b8d4);
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
            background-color: #00b8d4;
        }
        .tech-quote {
            font-size: 16px;
            font-style: italic;
            color: #b0b0b0;
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

    <h1>Precicom 3D Printing Services Catalogue</h1>
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
            <h3>FDM Printing (Ender 3)</h3>
            <p><strong>FDM (Fused Deposition Modeling)</strong> is one of the most widely used 3D printing technologies. FDM printers work by melting and extruding thermoplastic filaments, which are deposited layer by layer to form a solid object. This method is suitable for creating prototypes, models, and even functional parts. It's a cost-effective option that provides great versatility in terms of material options, including PLA, ABS, and more.</p>
            <p><strong>Ideal for:</strong> Rapid prototyping, small to medium-sized parts, durable and functional prototypes.</p>
            <p class="pricing">Pricing: ₹15/cc (PLA), ₹25/cc (ABS)</p>
        </div>
        <img src="https://www.bhphotovideo.com/images/images750x750/creality_ender_3v2_ender_3_v2_fdm_3d_1705448.jpg" alt="FDM Printer">
    </div>

    <div class="service">
        <div class="service-details">
            <h3>SLA Printing</h3>
            <p><strong>SLA (Stereolithography)</strong> is a high-precision 3D printing technology that uses ultraviolet light to cure liquid resin into solid layers. SLA printing provides exceptional accuracy, fine detail, and smooth finishes, making it perfect for industries that demand high resolution. It's commonly used for jewelry, dental products, and intricate parts.</p>
            <p><strong>Ideal for:</strong> High-detail parts, intricate models, dental and jewelry applications, prototypes with smooth finishes.</p>
            <p class="pricing">Pricing: ₹50/cc</p>
        </div>
        <img src="https://images.squarespace-cdn.com/content/v1/5b6e3beb85ede1a17e4a6830/1566499392899-64UXSZUPIVSBBIDE6EYS/form-2-printer-three-quarters-hart1.jpg" alt="SLA Printer">
    </div>

    <div class="service">
        <div class="service-details">
            <h3>SLS Printing</h3>
            <p><strong>SLS (Selective Laser Sintering)</strong> uses a laser to sinter powdered material (such as nylon or metals) into a solid structure. The laser melts the powder particles to form a solid part. SLS is particularly ideal for creating complex, high-strength parts and is commonly used for industrial and functional applications, producing durable components for end-use or prototyping.</p>
            <p><strong>Ideal for:</strong> Complex geometries, durable end-use parts, industrial applications, functional prototypes.</p>
            <p class="pricing">Pricing: ₹65/cc</p>
        </div>
        <img src="https://3dprint.com/wp-content/uploads/2017/10/1463590945-HP-HPQ-Launches-Multi-Jet-Fusion-3D-Printers.jpg" alt="SLS Printer">
    </div>
</section>

<section class="vision">
    <h2>Our Vision on Quality</h2>
    <p>At Precicom 3D, quality is our cornerstone. Our vision is to push the boundaries of innovation and excellence by delivering 3D-printed components that meet the highest standards. We ensure precision, durability, and the finest finishes in every project we take on.</p>
    <p>We are committed to providing our clients with the best-in-class service and results. Our advanced 3D printing technologies, attention to detail, and fast turnaround times ensure that every component meets the exact requirements and exceeds expectations.</p>
    <p><strong>Why Quality Matters:</strong></p>
    <ul>
        <li><strong>Precision:</strong> We ensure the highest level of accuracy in every printed model, ensuring all specifications are met with great detail.</li>
        <li><strong>Durability:</strong> Whether you are prototyping or manufacturing functional parts, our prints are designed to last and perform in real-world conditions.</li>
        <li><strong>Consistency:</strong> With our state-of-the-art machines and quality materials, we guarantee consistent output for every project.</li>
        <li><strong>Customer Satisfaction:</strong> Your satisfaction is our priority. We work closely with you to meet your needs and deliver top-notch results every time.</li>
    </ul>
</section>

<section>
    <h2>Contact Us</h2>
    <p>Email: <a href="mailto:precicom3d@gmail.com">precicom3d@gmail.com</a></p>
    <p>Phone: +91 8190911366</p>
    <p>Location: <a href="https://www.google.com/maps?q=Chennai, India" target="_blank">Chennai, India</a></p>
</section>

<div class="contact-info">
    <a href="mailto:precicom3d@gmail.com">Get In Touch</a>
</div>

<p class="tech-quote">"The future is printed." - 3D Printing Innovation</p>

</body>
</html>
