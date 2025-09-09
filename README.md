<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Giedo Digital Marketing - شركة الدعاية والإعلان والتسويق الرقمي</title>
    <meta name="description" content="شركة Giedo Digital Marketing رائدة في مجال التسويق الرقمي والدعاية والإعلان والتجارة الإلكترونية">
    <meta name="keywords" content="تسويق رقمي, دعاية وإعلان, تجارة إلكترونية, تصميم مواقع, سوشيال ميديا">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Social Media Promotion Section */
        .social-promo {
            padding: 5rem 0;
            background: linear-gradient(135deg, #ff9a9e 0%, #fecfef 50%, #fecfef 100%);
            position: relative;
            overflow: hidden;
        }

        .social-promo::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1000 1000"><defs><pattern id="stars" width="100" height="100" patternUnits="userSpaceOnUse"><circle cx="25" cy="25" r="2" fill="rgba(255,255,255,0.3)"/><circle cx="75" cy="75" r="1.5" fill="rgba(255,255,255,0.2)"/><circle cx="50" cy="80" r="1" fill="rgba(255,255,255,0.4)"/></pattern></defs><rect width="100%" height="100%" fill="url(%23stars)"/></svg>');
            animation: sparkle 10s ease-in-out infinite;
        }

        @keyframes sparkle {
            0%, 100% { opacity: 1; transform: translateY(0); }
            50% { opacity: 0.7; transform: translateY(-10px); }
        }

        .promo-content {
            position: relative;
            z-index: 2;
        }

        .promo-header {
            text-align: center;
            margin-bottom: 4rem;
        }

        .promo-header h2 {
            font-size: 3rem;
            color: #fff;
            text-shadow: 3px 3px 6px rgba(0,0,0,0.3);
            margin-bottom: 1rem;
            animation: pulse 2s ease-in-out infinite;
        }

        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.02); }
        }

        .promo-subtitle {
            font-size: 1.5rem;
            color: rgba(255,255,255,0.9);
            text-shadow: 2px 2px 4px rgba(0,0,0,0.2);
        }

        .success-stories {
            margin: 4rem 0;
            text-align: center;
        }

        .success-stories h3 {
            font-size: 2.5rem;
            color: #fff;
            margin-bottom: 2rem;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .stories-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .story-card {
            background: rgba(255,255,255,0.15);
            backdrop-filter: blur(10px);
            padding: 2rem;
            border-radius: 20px;
            text-align: center;
            border: 1px solid rgba(255,255,255,0.2);
            transition: all 0.3s ease;
        }

        .story-card:hover {
            transform: translateY(-10px);
            background: rgba(255,255,255,0.25);
        }

        .story-icon {
            font-size: 3rem;
            margin-bottom: 1rem;
        }

        .story-card h4 {
            font-size: 1.3rem;
            color: #fff;
            margin-bottom: 1rem;
        }

        .story-card p {
            color: rgba(255,255,255,0.9);
        }

        .social-channels {
            margin: 4rem 0;
            text-align: center;
        }

        .social-channels h3 {
            font-size: 2.5rem;
            color: #fff;
            margin-bottom: 1rem;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .channels-subtitle {
            font-size: 1.2rem;
            color: rgba(255,255,255,0.9);
            margin-bottom: 3rem;
        }

        .channels-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .channel-card {
            display: flex;
            align-items: center;
            background: rgba(255,255,255,0.1);
            backdrop-filter: blur(10px);
            padding: 2rem;
            border-radius: 20px;
            text-decoration: none;
            color: #fff;
            border: 2px solid transparent;
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }

        .channel-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.2), transparent);
            transition: left 0.5s;
        }

        .channel-card:hover::before {
            left: 100%;
        }

        .channel-card:hover {
            transform: translateY(-5px);
            border-color: rgba(255,255,255,0.3);
            box-shadow: 0 15px 35px rgba(0,0,0,0.2);
        }

        .channel-card.facebook { border-left: 4px solid #1877f2; }
        .channel-card.instagram { border-left: 4px solid #e4405f; }
        .channel-card.youtube { border-left: 4px solid #ff0000; }
        .channel-card.tiktok { border-left: 4px solid #000000; }
        .channel-card.twitter { border-left: 4px solid #1da1f2; }
        .channel-card.linkedin { border-left: 4px solid #0077b5; }

        .channel-icon {
            font-size: 2.5rem;
            margin-left: 1.5rem;
            margin-right: 1rem;
        }

        .channel-info {
            flex: 1;
            text-align: right;
        }

        .channel-info h4 {
            font-size: 1.3rem;
            margin-bottom: 0.5rem;
        }

        .channel-info p {
            opacity: 0.9;
            margin-bottom: 0.5rem;
        }

        .follow-btn {
            background: rgba(255,255,255,0.2);
            padding: 0.3rem 1rem;
            border-radius: 15px;
            font-size: 0.9rem;
            font-weight: bold;
        }

        .channel-stats {
            font-size: 0.9rem;
            opacity: 0.8;
            font-weight: bold;
        }

        .viral-promise {
            background: rgba(255,255,255,0.1);
            backdrop-filter: blur(15px);
            border-radius: 30px;
            padding: 3rem;
            margin: 4rem 0;
            border: 2px solid rgba(255,255,255,0.2);
        }

        .promise-content h3 {
            text-align: center;
            font-size: 2.5rem;
            color: #fff;
            margin-bottom: 2rem;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .promise-features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin: 2rem 0;
        }

        .promise-item {
            display: flex;
            align-items: center;
            gap: 1rem;
            background: rgba(255,255,255,0.1);
            padding: 1.5rem;
            border-radius: 15px;
        }

        .promise-item i {
            font-size: 2rem;
            color: #ffd700;
        }

        .promise-item h4 {
            margin-bottom: 0.5rem;
            color: #fff;
        }

        .promise-item p {
            color: rgba(255,255,255,0.9);
        }

        .cta-section {
            text-align: center;
            margin-top: 3rem;
        }

        .cta-section h4 {
            font-size: 1.8rem;
            color: #fff;
            margin-bottom: 2rem;
        }

        .cta-buttons {
            display: flex;
            gap: 1rem;
            justify-content: center;
            flex-wrap: wrap;
        }

        .viral-btn {
            padding: 1.2rem 2.5rem;
            border: none;
            border-radius: 50px;
            font-size: 1.1rem;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s ease;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .viral-btn.primary {
            background: linear-gradient(45deg, #ff6b6b, #ee5a24);
            color: white;
            box-shadow: 0 10px 30px rgba(255, 107, 107, 0.4);
        }

        .viral-btn.primary:hover {
            transform: translateY(-3px);
            box-shadow: 0 15px 40px rgba(255, 107, 107, 0.6);
        }

        .viral-btn.secondary {
            background: rgba(255,255,255,0.2);
            color: white;
            border: 2px solid rgba(255,255,255,0.3);
        }

        .viral-btn.secondary:hover {
            background: rgba(255,255,255,0.3);
            transform: translateY(-3px);
        }

        .testimonials {
            margin: 4rem 0;
            text-align: center;
        }

        .testimonials h3 {
            font-size: 2.5rem;
            color: #fff;
            margin-bottom: 2rem;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .testimonials-slider {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
            gap: 2rem;
        }

        .testimonial {
            background: rgba(255,255,255,0.15);
            backdrop-filter: blur(10px);
            padding: 2rem;
            border-radius: 20px;
            border: 1px solid rgba(255,255,255,0.2);
        }

        .testimonial-content p {
            font-size: 1.1rem;
            color: rgba(255,255,255,0.95);
            font-style: italic;
            margin-bottom: 1.5rem;
            line-height: 1.6;
        }

        .testimonial-author strong {
            display: block;
            color: #fff;
            font-size: 1.1rem;
            margin-bottom: 0.5rem;
        }

        .testimonial-author span {
            color: rgba(255,255,255,0.8);
            font-size: 0.9rem;
        }

        /* Mobile Responsiveness */
        @media (max-width: 768px) {
            .promo-header h2 {
                font-size: 2rem;
            }
            
            .channels-grid {
                grid-template-columns: 1fr;
            }
            
            .channel-card {
                flex-direction: column;
                text-align: center;
            }
            
            .channel-icon {
                margin: 0 0 1rem 0;
            }
            
            .cta-buttons {
                flex-direction: column;
                align-items: center;
            }
            
            .viral-btn {
                width: 100%;
                max-width: 300px;
            }
            
            .testimonials-slider {
                grid-template-columns: 1fr;
            }
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Header & Navigation */
        header {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            position: fixed;
            top: 0;
            width: 100%;
            z-index: 1000;
            padding: 1rem 0;
            border-bottom: 1px solid rgba(255, 255, 255, 0.2);
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 2rem;
            font-weight: bold;
            color: white;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .nav-links {
            display: flex;
            list-style: none;
            gap: 2rem;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: all 0.3s ease;
            padding: 0.5rem 1rem;
            border-radius: 25px;
        }

        .nav-links a:hover {
            background: rgba(255, 255, 255, 0.2);
            transform: translateY(-2px);
        }

        .menu-toggle {
            display: none;
            background: none;
            border: none;
            color: white;
            font-size: 1.5rem;
            cursor: pointer;
        }

        /* Hero Section */
        .hero {
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1000 1000"><defs><pattern id="grid" width="50" height="50" patternUnits="userSpaceOnUse"><path d="M 50 0 L 0 0 0 50" fill="none" stroke="rgba(255,255,255,0.1)" stroke-width="1"/></pattern></defs><rect width="100%" height="100%" fill="url(%23grid)"/></svg>');
            animation: float 20s ease-in-out infinite;
        }

        .hero-content {
            position: relative;
            z-index: 2;
            color: white;
            max-width: 800px;
        }

        .hero h1 {
            font-size: 4rem;
            margin-bottom: 1rem;
            text-shadow: 3px 3px 6px rgba(0,0,0,0.3);
            animation: slideInUp 1s ease-out;
        }

        .hero p {
            font-size: 1.5rem;
            margin-bottom: 2rem;
            opacity: 0.9;
            animation: slideInUp 1s ease-out 0.2s both;
        }

        .cta-button {
            display: inline-block;
            background: linear-gradient(45deg, #ff6b6b, #ee5a24);
            color: white;
            padding: 1rem 2rem;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            font-size: 1.1rem;
            transition: all 0.3s ease;
            box-shadow: 0 10px 30px rgba(0,0,0,0.3);
            animation: slideInUp 1s ease-out 0.4s both;
        }

        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 15px 40px rgba(0,0,0,0.4);
        }

        /* Services Section */
        .services {
            padding: 5rem 0;
            background: white;
            position: relative;
        }

        .section-title {
            text-align: center;
            font-size: 3rem;
            margin-bottom: 3rem;
            color: #333;
            position: relative;
        }

        .section-title::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
            width: 100px;
            height: 4px;
            background: linear-gradient(45deg, #667eea, #764ba2);
            border-radius: 2px;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 4rem;
        }

        .service-card {
            background: white;
            padding: 2rem;
            border-radius: 20px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            text-align: center;
            transition: all 0.3s ease;
            border: 1px solid rgba(0,0,0,0.05);
        }

        .service-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 30px 60px rgba(0,0,0,0.15);
        }

        .service-icon {
            font-size: 3rem;
            margin-bottom: 1rem;
            background: linear-gradient(45deg, #667eea, #764ba2);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .service-card h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            color: #333;
        }

        /* Packages Section */
        .packages {
            padding: 5rem 0;
            background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
            color: white;
        }

        .packages .section-title {
            color: white;
        }

        .packages-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 2rem;
            margin: 3rem 0;
        }

        .package-card {
            background: white;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            transition: all 0.3s ease;
            position: relative;
            color: #333;
        }

        .package-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 30px 60px rgba(0,0,0,0.2);
        }

        .package-card.popular {
            transform: scale(1.05);
            border: 3px solid #ffd700;
        }

        .popular-badge {
            position: absolute;
            top: 0;
            right: 0;
            background: linear-gradient(45deg, #ffd700, #ffed4e);
            color: #333;
            padding: 0.5rem 2rem;
            font-weight: bold;
            font-size: 0.9rem;
            border-radius: 0 0 0 20px;
            z-index: 10;
        }

        .package-header {
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
            padding: 2rem;
            text-align: center;
        }

        .package-header h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
        }

        .price {
            display: flex;
            align-items: baseline;
            justify-content: center;
            gap: 0.5rem;
        }

        .currency {
            font-size: 1rem;
            opacity: 0.8;
        }

        .amount {
            font-size: 3rem;
            font-weight: bold;
        }

        .period {
            font-size: 1rem;
            opacity: 0.8;
        }

        .package-features {
            padding: 2rem;
        }

        .package-features ul {
            list-style: none;
            margin-bottom: 2rem;
        }

        .package-features li {
            display: flex;
            align-items: center;
            margin-bottom: 1rem;
            font-size: 1rem;
        }

        .package-features li i {
            color: #4CAF50;
            margin-left: 1rem;
            font-size: 1rem;
        }

        .package-btn {
            width: 100%;
            padding: 1rem 2rem;
            background: linear-gradient(45deg, #ff6b6b, #ee5a24);
            color: white;
            border: none;
            border-radius: 10px;
            font-size: 1.1rem;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .package-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
        }

        .social-platforms {
            margin: 4rem 0;
            text-align: center;
        }

        .social-platforms h3 {
            font-size: 2rem;
            margin-bottom: 2rem;
            color: white;
        }

        .platforms-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 1.5rem;
            max-width: 800px;
            margin: 0 auto;
        }

        .platform-item {
            background: rgba(255,255,255,0.1);
            backdrop-filter: blu
