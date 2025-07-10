# ---
אפרת אדלר - צלמת
![family1](https://github.com/user-attachments/assets/c3b8c443-75c7-46d7-8019-514c4c1dac8e)
![family_7](https://github.com/user-attachments/assets/294925b8-7a33-44ba-9584-f44c9fcf53c6)
![family_6](https://github.com/user-attachments/assets/6265851d-a8e0-44a0-97fe-81ba340053f9)
![family_5](https://github.com/user-attachments/assets/313059c4-8340-4c99-b7d7-957e4bd0cb1c)
![family_4](https://github.com/user-attachments/assets/62263d54-6ffc-42f8-83a4-0b43891a8e41)
![family_3](https://github.com/user-attachments/assets/3b4bb5ec-93df-4e49-9a86-ac1112a5b95e)
![family_2](https://github.com/user-attachments/assets/6611570b-d836-412b-91<!DOCTYPE html>
<html lang="he" dir="rtl">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>אפרת אדלר - צילום טבעי ומקצועי</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" />
    <link rel="icon" type="image/x-icon" href="images/favicon.ico">
    <link
        href="https://fonts.googleapis.com/css2?family=Varela+Round:wght@400;700&family=Heebo:wght@300;400;500;600;700&family=Rubik:wght@300;400;500;600&display=swap"
        rel="stylesheet">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --primary-color: #F3C9C1;
            --secondary-color: #B7BACD;
            --accent-pink: #E8A8A8;
            --accent-purple: #6060a7;
            --dark-bg: #161917;
            --card-bg: #36323e;
            --text-light: #F0EDF5;
            --text-bright: #F8F8F8;
            --text-soft: #D8D5DC;
            --border-soft: rgba(243, 201, 193, 0.12);
            --transition-gentle: cubic-bezier(0.25, 0.46, 0.45, 0.94);
            --transition-spring: cubic-bezier(0.68, -0.55, 0.265, 1.55);
            --section-spacing: 7.2rem;
            --timeline-color: linear-gradient(45deg, var(--primary-color), var(--secondary-color));
        }

        html {
            scroll-behavior: smooth;
            font-size: 90%;
        }

        body {
            font-family: 'Heebo', 'Arial', sans-serif;
            background: linear-gradient(135deg, var(--dark-bg) 0%, #27252e 100%);
            color: var(--text-light);
            line-height: 1.7;
        }

        ::-webkit-scrollbar {
            width: 8px;
        }

        ::-webkit-scrollbar-track {
            background: var(--dark-bg);
        }

        ::-webkit-scrollbar-thumb {
            background: linear-gradient(180deg, var(--primary-color), var(--secondary-color));
            border-radius: 10px;
        }

        .navbar {
            position: fixed;
            top: 18px;
            width: 80%;
            margin-right: 10%;
            background: #4A4553;
            backdrop-filter: blur(0.0001px);
            z-index: 1000;
            padding: 1.1rem 0;
            border-radius: 50px;
            transition: all 0.4s var(--transition-gentle);
            box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
        }

        .nav-container {
            max-width: 3200px;
            margin: 0 auto;
            height: 45px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo-container {
            transform: scale(0.45);
            display: flex;
            margin-left: -15px;
        }

        .logo-image {
            color: white;
        }

        .logo-image:hover {
            transform: scale(1.1) rotate(-360deg);
            transition: all 1.5s var(--transition-spring);
        }

        .logo {
            font-size: 2rem;
            font-weight: 700;
            font-family: 'Varela Round', 'Arial Black', sans-serif;
            color: var(--text-bright);
            letter-spacing: 0.5px;
        }

        .nav-links {
            display: flex;
            gap: 3.2rem;
            list-style: none;
            justify-content: center;
            flex-wrap: wrap;
            margin-left: auto;
        }

        .nav-links a {
            color: var(--text-light);
            text-decoration: none;
            transition: all 0.4s var(--transition-gentle);
            font-weight: 550;
            position: relative;
            padding: 0.75rem 0;
            font-size: 1.35rem;
        }

        .nav-links a:hover {
            color: var(--primary-color);
            transform: translateY(-1px);
        }

        .nav-links a::after {
            content: '';
            position: absolute;
            bottom: 0;
            right: 0;
            width: 0;
            height: 2px;
            background: linear-gradient(90deg, var(--primary-color), var(--secondary-color));
            transition: width 0.4s var(--transition-gentle);
            border-radius: 2px;
        }

        .nav-links a:hover::after {
            width: 100%;
        }

        .gallery-dropdown {
            position: relative;
        }

        .dropdown-content {
            position: absolute;
            top: 120%;
            right: -35px;
            background: rgba(58, 55, 66, 0.98);
            backdrop-filter: blur(20px);
            border-radius: 15px;
            padding: 0.45rem;
            box-shadow: 0 15px 50px rgba(0, 0, 0, 0.3);
            border: 1px solid var(--border-soft);
            opacity: 0;
            visibility: hidden;
            transform: translateY(-10px);
            transition: all 0.4s var(--transition-gentle);
            min-width: 135px;
            z-index: 1001;
        }

        .gallery-dropdown:hover .dropdown-content {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        .dropdown-content a {
            display: block;
            padding: 0.8rem 0.9rem;
            border-radius: 8px;
            transition: all 0.3s var(--transition-gentle);
            font-size: 1rem;
        }

        .dropdown-content a:hover {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: var(--dark-bg);
            transform: translateX(5px);
        }

        .navbar-scrolled {
            background: #4A4553;
            padding: 1.1rem 0;
            box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
        }

        .page {
            display: none;
            opacity: 0;
            transition: opacity 0.6s var(--transition-gentle);
        }

        .page.active {
            display: block;
            opacity: 1;
        }

        .fade-in {
            animation: gentleFadeIn 1s var(--transition-gentle);
        }

        @keyframes gentleFadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }

            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .hero-slider {
            height: 100vh;
            width: 100%;
            position: relative;
            overflow: hidden;
            border-bottom: 2px solid var(--border-soft);
            background: radial-gradient(ellipse at center, rgba(243, 201, 193, 0.05) 0%, transparent 70%);
        }

        .slide {
            position: absolute;
            left: 0;
            width: 100%;
            height: 100%;
            opacity: 0;
            visibility: hidden;
            transition: all 1.5s var(--transition-gentle);
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .slide.active {
            opacity: 1;
            visibility: visible;
            transform: translateX(0) scale(1);
        }

        .slide-content {
            position: relative;
            width: 100%;
            height: 100%;
            display: flex;
            align-items: center;
            justify-content: center;
            z-index: 2;
            overflow: hidden;
            border-radius: 0px;
        }

        .slide-content img {
            width: 100%;
            height: 110%;
            object-fit: cover;
            object-position: top;
            transition: transform 7.5s ease-in-out;
        }

        .slide.active .slide-content img {
            transform: scale(1.2);
        }

        .gallery-nav-arrow {
            position: absolute;
            top: 50%;
            transform: translateY(-50%);
            background: rgba(243, 201, 193, 0.9);
            color: var(--dark-bg);
            border: none;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            font-size: 1.2rem;
            cursor: pointer;
            transition: all 0.3s var(--transition-gentle);
            z-index: 10;
            display: none;
        }

        .gallery-nav-arrow:hover {
            background: var(--primary-color);
            transform: translateY(-50%) scale(1.1);
        }

        .gallery-nav-arrow.left {
            left: 20px;
        }

        .gallery-nav-arrow.right {
            right: 20px;
        }

        .slider-nav {
            position: absolute;
            bottom: 2.7rem;
            left: 50%;
            transform: translateX(-50%);
            display: flex;
            gap: 1.35rem;
            z-index: 3;
            background: transparent;
            padding: 0.9rem 1.8rem;
            border-radius: 50px;
            backdrop-filter: blur(0.00001px);
        }

        .nav-dot {
            width: 12px;
            height: 12px;
            border-radius: 50%;
            background: rgba(248, 248, 248, 0.3);
            cursor: pointer;
            transition: all 0.4s var(--transition-gentle);
            border: 2px solid transparent;
            position: relative;
        }

        .nav-dot.active {
            background: var(--primary-color);
            transform: scale(1.3);
            border-color: transparent;
            box-shadow: 0 0 20px rgba(243, 201, 193, 0.4);
        }

        .nav-dot:hover:not(.active) {
            background: rgba(243, 201, 193, 0.6);
            transform: scale(1.1);
        }

        .about-section {
            padding: var(--section-spacing) 0;
            max-width: 1260px;
            margin: 0 auto;
            padding-left: 1.8rem;
            padding-right: 1.8rem;
            border-bottom: 1px solid var(--border-soft);
            position: relative;
            background: linear-gradient(135deg, rgba(243, 201, 193, 0.02) 0%, rgba(74, 69, 83, 0.02) 100%);
            border-radius: 27px 27px 0 0;
            margin-top: -27px;
            z-index: 10;
        }

        .about-section::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 1px;
            background: linear-gradient(90deg, transparent, var(--primary-color), transparent);
        }

        .rotating-welcome-container {
            position: absolute;
            left: 25%;
            top: 64%;
            transform: translate(-50%, -50%);
            width: 300px;
            height: 300px;
            z-index: 5;
            pointer-events: none;
        }

        .rotating-welcome {
            width: 100%;
            height: 100%;
            background-image: url('images/welcome.jpg');
            background-size: contain;
            background-repeat: no-repeat;
            background-position: center;
            transform-origin: center center;
            transition: transform 0.1s ease-out;
            transform: rotate(0deg);
        }

        .rotating-welcome img {
            width: 100%;
            height: 100%;
            object-fit: contain;
        }

        .parallax-gallery {
            padding: 3.5rem 0 130px 0;
            background: linear-gradient(135deg, rgba(58, 55, 66, 0.3), rgba(74, 69, 83, 0.2));
            border-radius: 10px;
            margin: 1.8rem 0;
            padding-bottom: 160px;
            overflow: hidden;
            position: relative;
        }

        .parallax-gallery::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: radial-gradient(ellipse at center, rgba(243, 201, 193, 0.03) 0%, transparent 70%);
            pointer-events: none;
        }

        .parallax-container {
            display: flex;
            padding: 0 1.8rem;
            overflow-x: auto;
            scroll-behavior: smooth;
            scrollbar-width: none;
            -ms-overflow-style: none;
        }

        .parallax-container::-webkit-scrollbar {
            display: none;
        }

        .parallax-item {
            min-width: 180px;
            height: 735px;
            overflow: hidden;
            cursor: pointer;
            transition: all 0.31s ease;
            position: relative;
            background: linear-gradient(135deg, var(--card-bg), rgba(74, 69, 83, 0.8));
            box-shadow: 0 15px 50px rgba(0, 0, 0, 0.2);
            border: 1px solid var(--border-soft);
            border-radius: 0px;
        }

        .parallax-item:hover {
            min-width: 750px;
            transform: translateY(-8px) scale(1.02);
            box-shadow: 0 20px 60px rgba(243, 201, 193, 0.3);
            border-color: rgba(243, 201, 193, 0.4);
        }

        .parallax-item:not(:hover) {
            min-width: 90px;
        }

        .parallax-item img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.1s var(--transition-gentle);
        }

        .parallax-item:hover img {
            transform: scale(1.13);
            transition: transform 0.2s ease;
        }

        .parallax-overlay {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            background: linear-gradient(transparent, rgba(0, 0, 0, 0.8));
            color: white;
            padding: 0.9rem;
            transform: translateY(100%);
            transition: all 0.25s var(--transition-gentle);
            backdrop-filter: blur(2px);
        }

        .parallax-item:hover .parallax-overlay {
            transform: translateY(0);
        }

        .category-title {
            font-size: 2.5rem;
            font-weight: 750;
            width: 110%;
            margin-bottom: 0.45rem;
            text-align: center;
            color: var(--text-bright);
        }

        .category-description {
            font-size: 1.65rem;
            opacity: 0.9;
        }

        .section {
            padding: var(--section-spacing) 0;
            max-width: 90%;
            margin: 0 auto;
            padding-left: 1.8rem;
            padding-right: 1.8rem;
            padding-top: 20px;
            margin-top: 20px;
            border-bottom: 1px solid var(--border-soft);
            position: relative;
        }

        .section1 {
            padding: var(--section-spacing) 0;
            max-width: 1260px;
            margin: 0 auto;
            padding-left: 1.8rem;
            padding-right: 1.8rem;
            padding-top: 20px;
            margin-top: 20px;
            border-bottom: 1px solid var(--border-soft);
            position: relative;
        }

        .section:last-child {
            border-bottom: none;
        }

        .section-title {
            text-align: center;
            font-size: 3.2rem;
            font-weight: 700;
            color: var(--text-bright);
            margin-bottom: 3.6rem;
            position: relative;
            letter-spacing: -0.02em;
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color), var(--primary-color));
            background-size: 200% 200%;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            animation: gradientShift 4s ease-in-out infinite;
            text-shadow: 0 0 30px rgba(243, 201, 193, 0.3);
        }

        @keyframes gradientShift {

            0%,
            100% {
                background-position: 0% 50%;
            }

            50% {
                background-position: 100% 50%;
            }
        }

        .section-title::after {
            content: '';
            position: absolute;
            bottom: -18px;
            left: 50%;
            transform: translateX(-50%);
            width: 80px;
            height: 3px;
            background: linear-gradient(90deg, var(--primary-color), var(--secondary-color));
            border-radius: 3px;
            box-shadow: 0 0 15px rgba(243, 201, 193, 0.5);
        }

        .section-title::before {
            content: '';
            position: absolute;
            top: -10px;
            left: 50%;
            transform: translateX(-50%);
            width: 40px;
            height: 2px;
            background: linear-gradient(90deg, transparent, var(--accent-pink), transparent);
            border-radius: 2px;
        }

        .about-text {
            padding-top: 1.8rem;
            font-size: 1.3rem;
            line-height: 1.8;
            color: var(--text-soft);
        }

        .about-text h3 {
            color: var(--primary-color);
            margin-bottom: 2.25rem;
            font-size: 2.2rem;
            font-weight: 600;
            line-height: 1.3;
            text-shadow: 0 0 20px rgba(243, 201, 193, 0.2);
        }

        .about-text p {
            margin-bottom: 1.8rem;
            color: var(--text-soft);
            opacity: 0;
            transform: translateY(20px);
            transition: all 0.6s ease;
        }

        .about-text p.visible {
            opacity: 1;
            transform: translateY(0);
        }

        .about-text p.fill-effect {
            background: linear-gradient(90deg, var(--primary-color) 0%, var(--text-soft) 0%);
            background-size: 0% 100%;
            background-repeat: no-repeat;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            animation: textFill 1.5s ease-in-out forwards;
        }

        @keyframes textFill {
            to {
                background-size: 100% 100%;
            }
        }

        .about-text strong {
            color: var(--primary-color);
            font-weight: 600;
            position: relative;
        }

        .card {
            background: linear-gradient(135deg, var(--card-bg), rgba(74, 69, 83, 0.8));
            border-radius: 22px;
            padding: 3.15rem;
            box-shadow: 0 15px 50px rgba(0, 0, 0, 0.2);
            transition: all 0.4s var(--transition-gentle);
            border: 1px solid var(--border-soft);
            position: relative;
            overflow: hidden;
        }

        .card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 1px;
            background: linear-gradient(90deg, transparent, var(--primary-color), transparent);
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 25px 70px rgba(0, 0, 0, 0.3);
            border-color: rgba(243, 201, 193, 0.3);
        }

        .gallery-categories {
            display: flex;
            justify-content: center;
            gap: 1.8rem;
            margin-bottom: 3.6rem;
            flex-wrap: wrap;
        }

        .category-btn {
            padding: 1.25rem 2.7rem;
            background: transparent;
            border: 2px solid var(--primary-color);
            color: var(--primary-color);
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.4s var(--transition-gentle);
            font-weight: 500;
            font-size: 1rem;
            position: relative;
            overflow: hidden;
            backdrop-filter: blur(10px);
        }

        .category-btn:hover,
        .category-btn.active {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: var(--dark-bg);
            transform: translateY(-3px);
            box-shadow: 0 12px 35px rgba(243, 201, 193, 0.4);
        }

        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1.5rem;
            width: 90vw;
            max-width: 1400px;
            margin: 0 auto;
            padding: 0 5vw;
        }

        @media (min-width: 1920px) {
            .gallery-grid {
                grid-template-columns: repeat(4, 1fr);
                gap: 2rem;
            }
        }

        @media (min-width: 1024px) and (max-width: 1919px) {
            .gallery-grid {
                grid-template-columns: repeat(3, 1fr);
                gap: 1.5rem;
            }
        }

        @media (max-width: 1023px) {
            .gallery-grid {
                grid-template-columns: repeat(2, 1fr);
                gap: 1rem;
            }
        }

        @media (max-width: 480px) {
            .gallery-grid {
                grid-template-columns: 1fr;
                gap: 0.5rem;
            }
        }

        .gallery-item {
            position: relative;
            overflow: hidden;
            border-radius: 8px;
            cursor: pointer;
            transition: all 0.4s var(--transition-gentle);
            background: var(--card-bg);
            aspect-ratio: 1/1;
        }

        .gallery-item.fade-out {
            opacity: 0;
            transform: translateY(20px) scale(0.95);
            transition: all 0.4s var(--transition-gentle);
        }

        .gallery-item.fade-in {
            animation: galleryFadeIn 0.6s var(--transition-gentle) forwards;
        }

        @keyframes galleryFadeIn {
            from {
                opacity: 0;
                transform: translateY(30px) scale(0.9);
            }

            to {
                opacity: 1;
                transform: translateY(0) scale(1);
            }
        }

        .album-row {
            display: flex;
        }

        .gallery-item:hover,
        .gallery-item-album:hover {
            transform: translateY(-5px) scale(1.02);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
        }

        .gallery-item img,
        .gallery-item-album img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            object-position: center;
            transition: transform 0.6s var(--transition-gentle);
        }

        .gallery-item:hover img,
        .gallery-item-album:hover img {
            transform: scale(1.05);
        }

        .gallery-overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(135deg, rgba(58, 55, 66, 0.9), rgba(74, 69, 83, 0.8));
            color: var(--text-bright);
            display: flex;
            align-items: center;
            justify-content: center;
            opacity: 0;
            transition: all 0.4s var(--transition-gentle);
            font-weight: 500;
            font-size: 1.1rem;
            backdrop-filter: blur(1px);
        }

        .gallery-item:hover .gallery-overlay,
        .gallery-item-album:hover .gallery-overlay {
            opacity: 1;
        }

        .gallery-item .zoom-icon,
        .gallery-item-album .zoom-icon {
            position: absolute;
            top: 10px;
            right: 10px;
            background: rgba(243, 201, 193, 0.9);
            color: var(--dark-bg);
            border: none;
            width: 35px;
            height: 35px;
            border-radius: 50%;
            font-size: 0.9rem;
            cursor: pointer;
            transition: all 0.3s var(--transition-gentle);
            z-index: 5;
            opacity: 0;
            transform: scale(0.8);
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .gallery-item:hover .zoom-icon,
        .gallery-item-album:hover .zoom-icon {
            opacity: 1;
            transform: scale(1);
        }

        .zoom-icon:hover {
            background: var(--primary-color);
            transform: scale(1.1);
        }

        .testimonials-grid {
            display: grid;
            grid-template-columns: repeat(3, minmax(288px, 1fr));
            column-gap: 4rem;
            max-width: 1000px;
            margin: auto;
            row-gap: 3rem;
            margin-bottom: 0.1px;
        }

        .testimonial-card {
            position: relative;
            height: 300px;
            width: 300px;
            gap: 5rem;
            perspective: 1000px;
        }

        .card-inner {
            position: relative;
            width: 100%;
            height: 100%;
            transition: transform 0.8s var(--transition-gentle);
            transform-style: preserve-3d;
        }

        .testimonial-card:hover .card-inner {
            transform: rotateY(180deg);
        }

        .testimonial-card .card-inner {
            animation-duration: 0.8s;
            animation-fill-mode: backwards;
            animation-timing-function: var(--transition-gentle);
        }

        .testimonial-card:not(:hover) .card-inner {
            animation-name: flipBack;
        }

        @keyframes flipBack {
            from {
                transform: rotateY(180deg);
            }

            to {
                transform: rotateY(360deg);
            }
        }

        .card-front,
        .card-front1,
        .card-front2 {
            position: absolute;
            width: 100%;
            height: 100%;
            backface-visibility: hidden;
            border-radius: 5%;
            overflow: hidden;
        }

        .card-front img {
            width: 100%;
            height: 100%;
            object-position: center;
            object-fit: cover;
            display: block;
        }

        .card-front1 img {
            width: 105%;
            height: 100%;
            object-position: 6px;
            object-fit: cover;
            display: block;
        }

        .card-front2 img {
            width: 100%;
            height: 100%;
            object-position: 80%;
            object-fit: cover;
            display: block;
        }

        .card-front {
            background: linear-gradient(135deg, var(--primary-color), var(--card-bg));
        }

        .card-back {
            position: absolute;
            width: 100%;
            height: 100%;
            backface-visibility: hidden;
            border-radius: 5%;
            overflow: hidden;
            background: linear-gradient(135deg, var(--card-bg), var(--dark-bg));
            color: var(--text-bright);
            padding: 3rem;
            display: flex;
            flex-direction: column;
            justify-content: center;
            text-align: center;
            transform: rotateY(180deg);
            border: 1px solid var(--border-soft);
        }

        .card-back blockquote {
            font-size: 0.78rem;
            font-style: italic;
            font-family: 'Rubik', 'Arial', sans-serif;
            font-weight: 300;
            margin-bottom: 2rem;
            color: var(--text-soft);
            line-height: 1.6;
        }

        .card-back cite {
            font-weight: 600;
            font-style: normal;
            color: var(--primary-color);
        }

        .gallery-view-more {
            text-align: center;
            margin-top: 3.6rem;
            padding-top: 2.7rem;
            border-top: 1px solid var(--border-soft);
        }

        .view-more-btn {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: var(--dark-bg);
            border: none;
            padding: 1.35rem 3.6rem;
            border-radius: 50px;
            font-size: 1.1rem;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.4s var(--transition-gentle);
            box-shadow: 0 8px 30px rgba(243, 201, 193, 0.2);
        }

        .view-more-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 12px 40px rgba(243, 201, 193, 0.3);
        }

        .contact-container {
            position: static;
            display: grid;
            grid-template-columns: 1.2fr 1fr;
            gap: 4.5rem;
            margin-top: 3.6rem;
            z-index: auto;
        }

        .contact-form {
            background: linear-gradient(135deg, #232224, rgba(74, 69, 83, 0.9));
            padding: 3.6rem;
            border-radius: 27px;
            box-shadow: 0 25px rgba(0, 0, 0, 0.2);
            border: 1px solid var(--border-soft);
        }

        .form-group {
            margin-bottom: 2.25rem;
        }

        .form-group label {
            display: block;
            margin-bottom: 0.9rem;
            font-weight: 500;
            color: var(--text-bright);
            font-size: 1rem;
        }

        .form-group input,
        .form-group textarea,
        .form-group select {
            width: 100%;
            padding: 1.35rem;
            border: 2px solid rgba(183, 186, 205, 0.2);
            border-radius: 13px;
            background: #2d2c30;
            color: var(--text-light);
            transition: all 0.3s var(--transition-gentle);
            font-size: 0.9rem;
            font-family: 'Heebo', 'Arial', sans-serif;
        }

        .form-group input:placeholder {
            color: #9a2121;
        }

        .form-group textarea {
            min-height: 126px;
            resize: vertical;
        }

        .form-group input:focus,
        .form-group textarea:focus,
        .form-group select:focus {
            outline: none;
            border-color: var(--primary-color);
            box-shadow: 0 0 0 4px rgba(243, 201, 193, 0.1);
        }

        .submit-btn {
            width: 100%;
            padding: 1.35rem;
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: var(--dark-bg);
            border: none;
            border-radius: 13px;
            font-size: 1.1rem;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.4s var(--transition-gentle);
            font-family: 'Heebo', 'Arial', sans-serif;
        }

        .submit-btn:hover:not(:disabled) {
            transform: translateY(-2px);
            box-shadow: 0 10px 30px rgba(243, 201, 193, 0.4);
        }

        .submit-btn:disabled {
            opacity: 0.7;
            cursor: not-allowed;
        }

        .contact-info {
            text-align: center;
        }

        .contact-card {
            background: linear-gradient(135deg, var(--dark-bg), rgba(74, 69, 83, 0.9));
            padding: 4.95rem;
            border-radius: 22px;
            margin-bottom: 2.25rem;
            margin-top: 30%;
            border: 1px solid var(--border-soft);
            box-shadow: 0 15px 40px rgba(0, 0, 0, 0.15);
        }

        .contact-card h3 {
            color: #E8A8A8;
            font-size: 2.5rem;
            margin-bottom: 1.35rem;
            font-family: 'Heebo', 'Arial', sans-serif;
        }

        .contact-card p {
            color: var(--text-soft);
            font-size: 1.25rem;
            margin-bottom: 1.1rem;
            line-height: 1.6;
        }

        .contact-card strong {
            color: var(--primary-color);
        }

        .contact-buttons {
            display: flex;
            gap: 1.8rem;
            justify-content: center;
            margin-top: 2.25rem;
        }

        .contact-btn {
            padding: 1.35rem 2.7rem;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.4s var(--transition-gentle);
            font-weight: 600;
            font-size: 1rem;
            font-family: 'Heebo', 'Arial', sans-serif;
        }

        .contact-btn-shortcut {
            padding: 1.35rem 2.7rem;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.4s var(--transition-gentle);
            background: linear-gradient(110deg, var(--primary-color), var(--accent-pink), #f39c9c);
            font-weight: 600;
            font-size: 1.5rem;
            font-family: 'Heebo', 'Arial', sans-serif;
        }

        .phone-btn {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: var(--dark-bg);
        }

        .email-btn {
            background: transparent;
            border: 2px solid var(--primary-color);
            color: var(--primary-color);
        }

        .contact-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(243, 201, 193, 0.3);
        }

        .contact-btn-shortcut:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(243, 201, 193, 0.3);
        }

        .success-message {
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: var(--dark-bg);
            padding: 2.7rem 3.6rem;
            border-radius: 18px;
            box-shadow: 0 25px 80px rgba(243, 201, 193, 0.4);
            z-index: 3000;
            text-align: center;
            opacity: 0;
            transform: translate(-50%, -50%) scale(0.9);
            transition: all 0.5s var(--transition-gentle);
            max-width: 405px;
            display: none;
            font-family: 'Heebo', 'Arial', sans-serif;
        }

        .success-message.show {
            opacity: 1;
            transform: translate(-50%, -50%) scale(1);
        }

        .success-message h3 {
            margin-bottom: 1.35rem;
            font-size: 1.35rem;
        }

        .success-message p {
            font-size: 1rem;
            line-height: 1.6;
        }

        .success-close {
            position: absolute;
            top: 0.9rem;
            right: 0.9rem;
            background: none;
            border: none;
            font-size: 1.35rem;
            cursor: pointer;
            color: var(--dark-bg);
            opacity: 0.7;
            transition: opacity 0.3s;
        }

        .success-close:hover {
            opacity: 1;
        }

        .success-overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(58, 55, 66, 0.8);
            z-index: 2999;
            opacity: 0;
            transition: opacity 0.5s var(--transition-gentle);
            backdrop-filter: blur(8px);
            display: none;
        }

        .success-overlay.show {
            opacity: 1;
        }

        .lightbox {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(58, 55, 66, 0.95);
            display: none;
            align-items: center;
            justify-content: center;
            z-index: 2000;
            backdrop-filter: blur(15px);
            opacity: 0;
            transition: all 0.5s var(--transition-gentle);
        }

        .lightbox.show {
            opacity: 1;
        }

        .lightbox img {
            max-width: 90%;
            max-height: 90%;
            object-fit: contain;
            border-radius: 13px;
            transform: scale(0.9);
            transition: transform 0.5s var(--transition-gentle);
            box-shadow: 0 25px 80px rgba(0, 0, 0, 0.5);
        }

        .lightbox.show img {
            transform: scale(1);
        }

        .lightbox-close {
            position: absolute;
            top: 36px;
            right: 36px;
            background: var(--primary-color);
            border: none;
            color: var(--dark-bg);
            font-size: 1.8rem;
            cursor: pointer;
            border-radius: 50%;
            width: 54px;
            height: 54px;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.3s var(--transition-gentle);
            box-shadow: 0 8px 25px rgba(243, 201, 193, 0.3);
        }

        .lightbox-close:hover {
            background: var(--text-bright);
            transform: scale(1.05) rotate(90deg);
            box-shadow: 0 12px 35px rgba(243, 201, 193, 0.5);
        }

        .footer {
            background: var(--card-bg);
            color: var(--text-soft);
            text-align: center;
            padding: 1.35rem 0;
            margin-top: 0;
            border-top: 1px solid var(--border-soft);
            font-family: 'Heebo', 'Arial', sans-serif;
        }

        .footer i.fa-solid.fa-square {
            opacity: 0;
        }

        .accent-text {
            font-family: 'Rubik', 'Arial', sans-serif;
            font-weight: 300;
            font-style: italic;
            color: var(--primary-color);
        }

        .quote-text {
            font-family: 'Rubik', 'Arial', sans-serif;
            font-weight: 300;
            font-style: italic;
        }

        .testimonial-intro {
            text-align: center;
            margin-bottom: 3.6rem;
            padding: 2.7rem;
            background: rgba(74, 69, 83, 0.2);
            border-radius: 18px;
            border: 1px solid var(--border-soft);
        }

        .loading-spinner {
            display: inline-block;
            width: 18px;
            height: 18px;
            border: 3px solid rgba(58, 55, 66, 0.3);
            border-radius: 50%;
            border-top-color: var(--dark-bg);
            animation: spin 1s ease-in-out infinite;
            margin-left: 0.45rem;
        }

        @keyframes spin {
            to {
                transform: rotate(360deg);
            }
        }

        .timeline-container {
            position: relative;
            max-width: 1000px;
            margin: 0 auto;
            padding: 2rem 0;
        }

        .timeline-line {
            position: absolute;
            left: 50%;
            top: 0;
            bottom: 0;
            width: 4px;
            background: var(--timeline-color);
            transform: translateX(-50%);
            border-radius: 2px;
            box-shadow: 0 0 20px rgba(243, 201, 193, 0.3);
        }

        .timeline-item {
            position: relative;
            margin-bottom: 4rem;
            opacity: 0;
            transform: translateX(50px);
            transition: all 0.6s ease;
        }

        .timeline-item.animate-left {
            transform: translateX(-50px);
        }

        .timeline-item.visible {
            opacity: 1;
            transform: translateX(0);
        }

        .timeline-item:nth-child(even) {
            text-align: left;
        }

        .timeline-item:nth-child(odd) {
            text-align: right;
        }

        .timeline-content {
            position: relative;
            background: linear-gradient(135deg, var(--card-bg), rgba(74, 69, 83, 0.8));
            padding: 2.5rem;
            border-radius: 20px;
            box-shadow: 0 15px 40px rgba(0, 0, 0, 0.15);
            border: 1px solid var(--border-soft);
            max-width: 45%;
            margin: 0 auto;
        }

        .timeline-content:hover {
            box-shadow: 6px 8px 35px rgba(243, 201, 193, 0.3);
        }

        .timeline-item:nth-child(even) .timeline-content {
            margin-left: 55%;
        }

        .timeline-item:nth-child(odd) .timeline-content {
            margin-right: 55%;
        }

        .timeline-number {
            position: absolute;
            left: 50%;
            top: 50%;
            transform: translate(-50%, -50%);
            width: 60px;
            height: 60px;
            background: var(--timeline-color);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--dark-bg);
            font-size: 1.5rem;
            font-weight: 700;
            font-family: 'Varela Round', 'Arial Black', sans-serif;
            box-shadow: 0 8px 25px rgba(243, 201, 193, 0.4);
            z-index: 2;
        }

        .process-title {
            color: var(--text-bright);
            margin-bottom: 1.2rem;
            font-family: 'Heebo', 'Arial', sans-serif;
            font-weight: 600;
            font-size: 1.3rem;
        }

        .process-description {
            color: var(--text-soft);
            font-family: 'Heebo', 'Arial', sans-serif;
            line-height: 1.7;
            font-size: 1rem;
        }

        .category-page {
            padding-top: 108px;
        }

        .category-hero {
            text-align: center;
            padding: 3.6rem 0 5.4rem;
            background: linear-gradient(135deg, rgba(243, 201, 193, 0.1), rgba(183, 186, 205, 0.05));
            border-radius: 27px;
            margin: 1.8rem;
        }

        .category-hero h1 {
            font-size: 3.15rem;
            margin-bottom: 0.9rem;
            color: var(--primary-color);
        }

        .category-hero p {
            font-size: 1.17rem;
            color: var(--text-soft);
            max-width: 540px;
            margin: 0 auto;
        }

        .about-content-new {
            max-width: 1200px;
            margin: 0 auto;
        }

        .about-hero-section {
            text-align: center;
            margin-bottom: 4rem;
            padding: 2rem 0;
        }

        .about-main-title {
            color: var(--primary-color);
            font-size: 2.5rem;
            font-weight: 600;
            line-height: 1.3;
            margin-bottom: 2rem;
            opacity: 1;
            transform: translateY(0);
            animation: fadeInUp 1s ease forwards;
        }

        .about-main-content {
            display: grid;
            grid-template-columns: 1fr 200px;
            gap: 4rem;
            align-items: start;
        }

        .about-text-new {
            padding-right: 2rem;
        }

        .specialty-item {
            margin-bottom: 1.8rem;
            opacity: 1;
            transform: translateX(0);
            animation: slideInRight 0.8s ease forwards;
        }

        .specialty-item:nth-child(2) {
            animation-delay: 0.2s;
        }

        .specialty-item:nth-child(3) {
            animation-delay: 0.4s;
        }

        .specialty-item:nth-child(4) {
            animation-delay: 0.6s;
        }

        .specialty-item:nth-child(5) {
            animation-delay: 0.8s;
        }

        .specialty-item:nth-child(6) {
            animation-delay: 1s;
        }

        .specialty-item:nth-child(7) {
            animation-delay: 1.2s;
        }

        .specialty-item h4 {
            color: var(--primary-color);
            font-size: 1.1rem;
            font-weight: 600;
            margin-bottom: 0.5rem;
            position: relative;
            padding-right: 1.5rem;
        }

        .specialty-item h4::before {
            content: "•";
            color: var(--secondary-color);
            font-size: 1.2rem;
            position: absolute;
            right: 0;
            top: 0;
        }

        .specialty-item p {
            color: var(--text-soft);
            font-size: 1rem;
            line-height: 1.6;
            margin-right: 1.5rem;
        }

        .about-quote {
            font-family: 'Rubik', 'Arial', sans-serif;
            font-style: italic;
            color: var(--primary-color);
            font-size: 1.1rem;
            text-align: center;
            margin-top: 2.5rem;
            width: fit-content;
            padding: 1.2rem;
            border-right: 3px solid var(--primary-color);
            background: rgba(243, 201, 193, 0.05);
            border-radius: 10px;
            opacity: 1;
            transform: translateY(0);
            animation: fadeInUp 1s ease 1.5s forwards;
        }

        @keyframes slideInRight {
            to {
                opacity: 1;
                transform: translateX(0);
            }
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }

            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .plan-btn {
            justify-content: center;
            padding: 1.35rem 2.7rem;
            border: none;
            position: absolute;
            bottom: 25px;
            left: 40%;
            right: 40%;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.4s var(--transition-gentle);
            font-weight: 600;
            font-size: 1.2rem;
            font-family: 'Heebo', 'Arial', sans-serif;
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: var(--dark-bg);
        }

        .plan-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(243, 201, 193, 0.3);
        }

        .album-btn {
            justify-content: center;
            padding: 1.35rem 2.7rem;
            border: none;
            position: absolute;
            bottom: 25px;
            left: 40%;
            right: 40%;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.4s var(--transition-gentle);
            font-weight: 650;
            font-size: 1.35rem;
            font-family: 'Heebo', 'Arial', sans-serif;
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: var(--dark-bg);
        }

        .album-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(243, 201, 193, 0.3);
        }

        .gallery-main-container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 2rem 1.5rem 2rem;
        }

        .gallery_grid_albums {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 2rem;
        }

        .gallery_item_album {
            aspect-ratio: 2.35 / 1;
            background: #322F3D;
            border-radius: 22px;
            overflow: hidden;
            box-shadow: 0 4px 32px 0 rgba(0, 0, 0, 0.13);
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .gallery_item_album img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            object-position: center;
            display: block;
        }

        .album .responsive-container-block {
            min-height: 75px;
            height: fit-content;
            width: 100%;
            padding: 10px;
            display: flex;
            flex-wrap: wrap;
            margin: 0 auto;
            justify-content: flex-start;
        }

        .album .responsive-container-block.bg {
            max-width: 1320px;
            margin: 0;
            justify-content: space-between;
        }

        .album .img {
            width: 100%;
            margin: 0 0 20px 0;
        }

        .album .responsive-container-block.img-cont {
            flex-direction: column;
            max-width: 33.3%;
            min-height: auto;
            margin: 0;
            height: 100%;
        }

        .album .img.img-big {
            height: 50%;
            margin: 0 0 16px 0;
        }

        .contact-container {
            position: static;
            display: grid;
            grid-template-columns: 1.2fr 1fr;
            gap: 4.5rem;
            margin-top: 3.6rem;
            z-index: auto;
        }

        .gallery-grid {
            display: block !important;
            column-count: 4;
            column-gap: 0.5rem !important;
            width: 90vw !important;
            max-width: 1400px !important;
            margin: 0 auto !important;
            padding: 0 !important;
            position: relative !important;
            left: 50% !important;
            transform: translateX(-50%) !important;
        }

        @media (min-width: 1920px) {
            .gallery-grid {
                grid-template-columns: repeat(4, 1fr) !important;
                gap: 1.5rem;
                width: 90vw !important;
                max-width: 90vw !important;
            }
        }

        @media (min-width: 1024px) and (max-width: 1919px) {
            .gallery-grid {
                grid-template-columns: repeat(3, 1fr) !important;
                gap: 1.2rem;
                width: 90vw !important;
                max-width: 90vw !important;
            }
        }

        @media (max-width: 1023px) {
            .gallery-grid {
                grid-template-columns: repeat(2, 1fr) !important;
                gap: 0.8rem;
                width: 90vw !important;
                max-width: 90vw !important;
            }
        }

        @media (max-width: 480px) {
            .gallery-grid {
                grid-template-columns: repeat(2, 1fr) !important;
                gap: 0.5rem;
                width: 90vw !important;
                max-width: 90vw !important;
            }
        }

        .gallery-item {
            position: relative;
            overflow: hidden;
            border-radius: 8px;
            cursor: pointer;
            transition: all 0.4s var(--transition-gentle);
            background: var(--card-bg);
            width: 100%;
            break-inside: avoid;
            margin-bottom: 0 !important;
            height: auto !important;
            aspect-ratio: unset !important;
        }

        .gallery-item img {
            width: 100%;
            height: auto !important;
            object-fit: cover;
            object-position: center;
            transition: transform 0.6s var(--transition-gentle);
            display: block;
            aspect-ratio: unset !important;
        }

        .gallery-item-album img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            object-position: center;
            transition: transform 0.6s var(--transition-gentle);
            display: block;
        }

        @media (max-width: 1600px) {
            html {
                font-size: 88%;
            }

            .nav-links {
                gap: 2.8rem;
            }

            .section {
                padding: 5.5rem 1.4rem;
            }

            .section-title {
                font-size: 2.5rem;
            }

            .parallax-item:hover {
                min-width: 550px;
            }

            .rotating-welcome-container {
                width: 280px;
                height: 280px;
            }
        }

        @media (max-width: 1400px) {
            html {
                font-size: 86%;
            }

            .parallax-item:hover {
                min-width: 480px;
            }

            .timeline-content {
                max-width: 48%;
            }

            .timeline-item:nth-child(even) .timeline-content {
                margin-left: 52%;
            }

            .timeline-item:nth-child(odd) .timeline-content {
                margin-right: 52%;
            }

            .rotating-welcome-container {
                width: 260px;
                height: 260px;
            }
        }

        @media (max-width: 1200px) {
            html {
                font-size: 84%;
            }

            .nav-links {
                gap: 2.3rem;
            }

            .section {
                padding: 5rem 1.35rem;
            }

            .section-title {
                font-size: 2.3rem;
            }

            .parallax-item:hover {
                min-width: 400px;
            }

            .timeline-line {
                left: 30px;
            }

            .timeline-content {
                max-width: calc(100% - 80px);
                margin-left: 80px !important;
                margin-right: 0 !important;
            }

            .timeline-item {
                text-align: left !important;
            }

            .timeline-number {
                left: 30px;
                transform: translateY(-50%);
            }

            .rotating-welcome-container {
                width: 220px;
                height: 220px;
                left: 75%;
            }
        }

        @media (max-width: 1100px) {
            .gallery_grid_albums {
                grid-template-columns: repeat(2, 1fr);
            }
        }

        @media (max-width: 768px) {
            html {
                font-size: 82%;
            }

            .navbar {
                padding: 1.1rem 0;
                width: 95%;
                margin-right: 2.5%;
            }

            .hero-slider {
                height: 80vh;
            }

            .section,
            .about-section {
                padding: 3.6rem 0.9rem;
            }

            .section-title {
                font-size: 2rem;
                margin-bottom: 2.7rem;
            }

            .about-content {
                grid-template-columns: 1fr;
                gap: 2.7rem;
                text-align: center;
            }

            .about-text {
                font-size: 1rem;
            }

            .gallery-categories {
                flex-direction: column;
                align-items: center;
                gap: 1.35rem;
            }

            .contact-container {
                grid-template-columns: 1fr;
                gap: 2.7rem;
            }

            .contact-buttons {
                flex-direction: column;
                gap: 1.35rem;
            }

            .contact-form,
            .contact-card {
                padding: 2.25rem;
            }

            .testimonials-grid {
                grid-template-columns: 1fr;
                gap: 1.8rem;
            }

            .parallax-item {
                min-width: 135px;
            }

            .parallax-item:hover {
                min-width: 270px;
            }

            .parallax-item:not(:hover) {
                min-width: 72px;
            }

            .nav-links {
                gap: 1.8rem;
            }

            .dropdown-content {
                right: -45px;
                min-width: 135px;
            }

            .rotating-welcome-container {
                width: 150px;
                height: 150px;
                left: 65%;
            }

            .about-main-content {
                grid-template-columns: 1fr;
                gap: 2rem;
                text-align: center;
            }

            .about-text-new {
                padding-right: 0;
            }

            .about-main-title {
                font-size: 2rem;
            }

            .about-intro-text {
                font-size: 1.1rem;
            }

            .specialty-item h4::before {
                display: none;
            }

            .specialty-item p {
                margin-right: 0;
            }

            .album .img {
                max-width: 32.5%;
                margin: 0;
            }

            .album .responsive-container-block.bg {
                flex-direction: column;
            }

            .album .responsive-container-block.img-cont {
                max-width: 100%;
                flex-direction: row;
                justify-content: space-between;
            }

            .album .img.img-big {
                max-width: 49%;
                margin: 0;
            }
        }

        @media (max-width: 700px) {
            .gallery-main-container {
                width: 97%;
            }

            .gallery_grid_albums {
                grid-template-columns: 1fr;
            }
        }

        @media (max-width: 480px) {
            html {
                font-size: 80%;
            }

            .section-title {
                font-size: 1.7rem;
            }

            .gallery-grid {
                grid-template-columns: 1fr;
            }

            .gallery-item {
                height: 270px;
            }

            .category-btn {
                padding: 0.9rem 1.8rem;
                font-size: 0.9rem;
            }

            .contact-form,
            .contact-card {
                padding: 1.8rem;
            }

            .nav-links {
                gap: 1.35rem;
                font-size: 0.9rem;
            }

            .logo {
                font-size: 1.35rem;
            }

            .parallax-item {
                min-width: 108px;
                height: 270px;
            }

            .parallax-item:hover {
                min-width: 225px;
            }

            .parallax-item:not(:hover) {
                min-width: 54px;
            }

            .category-hero h1 {
                font-size: 2.25rem;
            }

            .category-hero p {
                font-size: 1rem;
            }

            .rotating-welcome-container {
                width: 120px;
                height: 120px;
                left: 60%;
            }
        }

        @media (max-width: 500px) {
            .album .img {
                max-width: 94%;
                margin: 0 0 25px 0;
            }

            .album .responsive-container-block.img-cont {
                flex-direction: column;
                align-items: center;
                padding: 10px;
            }

            .album .img.img-big {
                max-width: 94%;
                margin: 0 0 25px 0;
            }

            .album .img.img-last {
                margin: 0 0 5px 0;
            }
        }

        button:focus,
        input:focus,
        textarea:focus,
        select:focus {
            outline: 3px solid var(--primary-color);
            outline-offset: 2px;
        }

        .gallery-item:focus,
        .gallery-item-album:focus,
        .parallax-item:focus {
            outline: 3px solid var(--primary-color);
            outline-offset: 3px;
        }

        .gallery-item-album {
            position: relative;
            overflow: hidden;
            border-radius: 8px;
            cursor: pointer;
            margin: 10px;
            transition: all 0.4s var(--transition-gentle);
            background: var(--card-bg);
            aspect-ratio: 2.35/1;
        }

        .batmitzvah-img {
            object-position: 38%;
        }

        .family-img {
            object-position: 57%;
        }

        .form-group input.invalid,
        .form-group textarea.invalid {
            border-color: #ff6b6b;
            box-shadow: 0 0 0 3px rgba(255, 107, 107, 0.1);
        }

        .form-group input.invalid:focus,
        .form-group textarea.invalid:focus {
            border-color: #ff6b6b;
            box-shadow: 0 0 0 4px rgba(255, 107, 107, 0.15);
        }

        /* Impressive Contact Form */
        .impressive-contact-section {
            background: transparent;
            margin: 4rem 0 0 0;
            padding: 4rem 2rem;
            border-top: 1px solid transparent;
            position: relative;
            overflow: hidden;
        }

        .impressive-contact-section::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: transparent;
            pointer-events: none;
        }

        .contact-content-wrapper {
            max-width: 1200px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: 1fr 1.2fr;
            gap: 4rem;
            align-items: start;
        }

        .contact-info-card {
            background: linear-gradient(135deg, rgba(74, 69, 83, 0.8), rgba(54, 50, 62, 0.9));
            border-radius: 24px;
            padding: 3rem;
            border: 1px solid var(--border-soft);
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            backdrop-filter: blur(20px);
            position: relative;
        }

        .contact-info-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 1px;
            background: linear-gradient(90deg, transparent, var(--primary-color), transparent);
        }

        .contact-info-card h3 {
            color: var(--primary-color);
            font-size: 2.2rem;
            margin-bottom: 0.8rem;
            font-weight: 700;
            text-align: center;
        }

        .contact-info-card .subtitle {
            color: var(--text-soft);
            text-align: center;
            margin-bottom: 2.5rem;
            font-size: 1.1rem;
            opacity: 0.9;
        }

        .contact-details {
            text-align: center;
            margin-bottom: 2.5rem;
        }

        .contact-details p {
            color: var(--text-soft);
            margin-bottom: 0.8rem;
            font-size: 1.1rem;
            line-height: 1.6;
        }

        .contact-details strong {
            color: var(--primary-color);
            font-weight: 600;
        }

        .contact-buttons-mini {
            display: flex;
            gap: 1rem;
            justify-content: center;
        }

        .contact-btn-mini {
            padding: 0.9rem 1.8rem;
            border: none;
            border-radius: 25px;
            cursor: pointer;
            transition: all 0.3s ease;
            font-weight: 600;
            font-size: 0.95rem;
            font-family: 'Heebo', 'Arial', sans-serif;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            gap: 0.5rem;
        }

        .phone-btn-mini {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: var(--dark-bg);
        }

        .email-btn-mini {
            background: transparent;
            border: 2px solid var(--primary-color);
            color: var(--primary-color);
        }

        .contact-btn-mini:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(243, 201, 193, 0.4);
        }

        .impressive-contact-form {
            background: linear-gradient(135deg, rgba(35, 34, 36, 0.95), rgba(74, 69, 83, 0.9));
            border-radius: 24px;
            padding: 3rem;
            border: 1px solid var(--border-soft);
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            backdrop-filter: blur(20px);
            position: relative;
        }

        .impressive-contact-form::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 1px;
            background: linear-gradient(90deg, transparent, var(--secondary-color), transparent);
        }

        .impressive-contact-form h3 {
            color: var(--text-bright);
            text-align: center;
            margin-bottom: 2rem;
            font-size: 1.6rem;
            font-weight: 600;
        }

        .impressive-form-row {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 1.2rem;
            margin-bottom: 1.2rem;
        }

        .impressive-form-group {
            margin-bottom: 1.2rem;
        }

        .impressive-form-group input,
        .impressive-form-group textarea,
        .impressive-form-group select {
            width: 100%;
            padding: 1rem;
            border: 2px solid rgba(183, 186, 205, 0.2);
            border-radius: 12px;
            background: rgba(45, 44, 48, 0.8);
            color: var(--text-light);
            font-size: 0.95rem;
            font-family: 'Heebo', 'Arial', sans-serif;
            transition: all 0.3s ease;
        }

        .impressive-form-group input:focus,
        .impressive-form-group textarea:focus,
        .impressive-form-group select:focus {
            outline: none;
            border-color: var(--primary-color);
            box-shadow: 0 0 0 4px rgba(243, 201, 193, 0.1);
            background: rgba(45, 44, 48, 0.95);
        }

        .impressive-form-group input::placeholder,
        .impressive-form-group textarea::placeholder {
            color: rgba(208, 213, 221, 0.6);
        }

        @media (max-width: 1024px) {
            .contact-content-wrapper {
                grid-template-columns: 1fr;
                gap: 2.5rem;
            }

            .impressive-form-row {
                grid-template-columns: 1fr;
                gap: 1rem;
            }

            .impressive-contact-section {
                padding: 3rem 1.5rem;
            }

            .contact-info-card,
            .impressive-contact-form {
                padding: 2.5rem;
            }
        }

        @media (max-width: 768px) {
            .contact-buttons-mini {
                flex-direction: column;
                gap: 0.8rem;
            }

            .impressive-contact-section {
                padding: 2.5rem 1rem;
            }

            .contact-info-card,
            .impressive-contact-form {
                padding: 2rem;
            }
        }
    </style>

    <meta name="NetsparkQuiltingResult" total-length="166230" removed="0"
        rules-found="w22544,w33626,w6340,w6341,w6361,w6362,w3473,w2676,w4838,w4839,w5260,w2598,w6589,w3056,w5513,w9033,w22645,w18843,w3115,w23078,w17813,w33129,w22038,w33718,w33224,w22884,w18428,w32964,w23122,w33719,w33502,w22558,w33633,w33634,w20342,w33114,w20789,w33223,w21160,w33641,w18084,w32902,w18958,w341,w33310,w20352,w32801,w20763,w18871,w22403,w23099,w33715,w10931,w10932,w33126,w18430,w17173,w33127,w33441,w23108,w21132,w12205,w12206,w6401,w6681,w4844,w9711,w9735" />
</head>

<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="nav-container">
            <div class="logo-container">
                <div class="logo-image"><img src="images/logo.jpg" alt="logo-image"></div>
            </div>
            <ul class="nav-links">
                <li><a href="#" onclick="showPage('home')">דף הבית</a></li>
                <li><a href="#" onclick="showPage('about')">אודות</a></li>
                <li class="gallery-dropdown">
                    <a href="#" onclick="showPage('gallery')">גלריה <i class=" fa-solid fa-chevron-down"></i></a>
                    <div class="dropdown-content">
                        <a href="#" onclick="showCategoryPage('newborn')">ניו בורן</a>
                        <a href="#" onclick="showCategoryPage('oneyear')">גיל שנה</a>
                        <a href="#" onclick="showCategoryPage('chalaka')">חלאקה</a>
                        <a href="#" onclick="showCategoryPage('batmitzvah')">בת מצווה</a>
                        <a href="#" onclick="showCategoryPage('family')">משפחות</a>
                    </div>
                </li>
                <li><a href="#" onclick="showPage('albums')">אלבומים</a></li>
                <li><a href="#" onclick="showPage('testimonials')">המלצות</a></li>
                <li><a href="#" onclick="showPage('contact')">צרו קשר</a></li>
            </ul>
        </div>
    </nav>

    <!-- Home Page -->
    <div id="home" class="page active">
        <!-- Hero Slider -->
        <section class="hero-slider">
            <div class="slide active">
                <div class="slide-content">
                    <img src="images/1year_23.jpg" alt="ניו בורן">
                </div>
            </div>
            <div class="slide">
                <div class="slide-content">
                    <img src="images/1year_8.jpg" alt="בת מצווה">
                </div>
            </div>
            <div class="slide">
                <div class="slide-content">
                    <img src="images/newborn11.jpg" alt="משפחה">
                </div>
            </div>
            <div class="slide">
                <div class="slide-content">
                    <img src="images/chalake_25.jpg" alt="גיל שנה">
                </div>
            </div>
            <div class="slide">
                <div class="slide-content">
                    <img src="images/chalake_1.jpg" alt="גיל שנה">
                </div>
            </div>
            <div class="slide">
                <div class="slide-content">
                    <img src="images/chalake_24.jpg" alt="חלאקה">
                </div>
            </div>

            <!-- Navigation Dots -->
            <div class="slider-nav">
                <span class="nav-dot active" onclick="currentSlide(1)" aria-label="Slide 1"></span>
                <span class="nav-dot" onclick="currentSlide(2)" aria-label="Slide 2"></span>
                <span class="nav-dot" onclick="currentSlide(3)" aria-label="Slide 3"></span>
                <span class="nav-dot" onclick="currentSlide(4)" aria-label="Slide 4"></span>
                <span class="nav-dot" onclick="currentSlide(5)" aria-label="Slide 5"></span>
                <span class="nav-dot" onclick="currentSlide(6)" aria-label="Slide 6"></span>
            </div>
        </section>

        <!-- About Preview -->
        <section class="about-section">
            <h2 class="section-title">קצת עליי</h2>
            <div class="about-content-new">
                <!-- כותרת מרכזית -->
                <div class="about-hero-section">
                    <!-- <h3 class="about-main-title">ברוכים הבאים לעולם הצילום שלי <i class="fa-solid fa-camera-retro"></i></h3> -->
                </div>

                <!-- תוכן עיקרי עם לוגו -->
                <div class="about-main-content">
                    <div class="about-text-new">
                        <h3 style="font-weight: 450;">היי, אני אפרת, צלמת מקצועית שמתמחה בצילום ילדים, משפחות.<br>
                            הצילום מבחינתי הוא הרבה יותר מתמונה – זו חוויה.<br>
                            אני כאן כדי לגרום לכם להרגיש בנוח, <br>ליצור אווירה נעימה, ולתפוס את הרגעים הכי יפים
                            ואמיתיים שלכם.<br>

                            עם גישה רגועה, חיבור טבעי לילדים והמון סבלנות,<br> אני דואגת שכל סשן - יהיה חוויה שכיף
                            לזכור.<br>

                            המטרה שלי היא שתהיו נינוחים, תיהנו מהתהליך,<br> ותקבלו תמונות שתשמחו לחזור אליהן שוב ושוב.
                        </h3>
                        <h3 style="color: transparent;">///</h3>
                        <h3 style="color: transparent;">///</h3>
                    </div>
                    <div class="rotating-welcome-container" id="rotatingWelcome">
                        <div class="rotating-welcome">
                            <img src="images/welcome.png" alt="welcome-rotating">
                        </div>
                    </div>
                    <button class="plan-btn" onclick="showPage('about')">לתהליך העבודה</button>
                </div>
            </div>
        </section>
        <!-- Jet Parallax Gallery -->
        <section class="parallax-gallery">
            <h2 class="section-title" style="margin-bottom: 5.4rem;">גלריה</h2>
            <div class="parallax-container">
                <div class="parallax-item" onclick="showCategoryPage('newborn')" tabindex="0">
                    <img src="images/newborn4.jpg" alt="צילומי ניו בורן">
                    <div class="parallax-overlay">
                        <div class="category-title">ניו בורן</div>
                    </div>
                </div>
                <div class="parallax-item" onclick="showCategoryPage('oneyear')" tabindex="0">
                    <img src="images/1year_23.jpg" alt="צילומי גיל שנה">
                    <div class="parallax-overlay">
                        <div class="category-title">גיל שנה</div>
                    </div>
                </div>
                <div class="parallax-item" onclick="showCategoryPage('chalaka')" tabindex="0">
                    <img src="images/chalake_3.jpg" alt="צילומי חלאקה">
                    <div class="parallax-overlay">
                        <div class="category-title">חלאקה</div>
                    </div>
                </div>
                <div class="parallax-item" onclick="showCategoryPage('batmitzvah')" tabindex="0">
                    <img src="images/batmitzva_3.jpg" class="batmitzvah-img" alt="צילומי בת מצווה">
                    <div class="parallax-overlay">
                        <div class="category-title">בת מצווה</div>
                    </div>
                </div>
                <div class="parallax-item" onclick="showCategoryPage('family')" tabindex="0">
                    <img src="images/family_7.jpg" class="family-img" alt="צילומי משפחות">
                    <div class="parallax-overlay">
                        <div class="category-title">משפחות</div>
                    </div>
                </div>
            </div>
            <button class="album-btn" onclick="showPage('albums')">
                טעימה מהאלבומים
            </button>
        </section>
        <h3 style="color: transparent;">.</h3>
        <!-- Testimonials -->
        <section class="section">
            <h2 class="section-title" style="margin-bottom: 65px;">המלצות</h2>
            <div class="testimonials-grid">
                <div class="testimonial-card">
                    <div class="card-inner">
                        <div class="card-front">
                            <div
                                style="width: 100%; height: 100%; background: linear-gradient(45deg, #F3C9C1, #423D4A);">
                                <img src="images/family_2.jpg" height="450" width="auto">
                            </div>
                        </div>
                        <div class="card-back">
                            <blockquote>"יצא אלבום משגע, מאוד מרוצה מהתמונות רמה גבוהה מאוד גם של הצילום וגם של העריכה!!
                                הילדים חזרו שמחים היה להם יום חוויתי, מבחינתם זה היה טיול כיף עד כדי שלא רצו לחזור
                                הביתה! שתפו פעולה מדהים.
                                המחיר בהחלט שווה וזול בשביל התמורה. הרגשתי שאכפת לך לרצות אותנו, היית קשובה וסבלנית.
                                ממליצה בחום לכל מי שמחפשת תמונות יפות!! וכבר אמרתי לבעלי שמחכה להזדמנות לקחת אותך שוב
                                לצילומים.. רק צריכה ארוע😉"</blockquote>
                            <cite>- אמא של שירה</cite>
                        </div>
                    </div>
                </div>
                <div class="testimonial-card">
                    <div class="card-inner">
                        <div class="card-front2">
                            <div
                                style="width: 100%; height: 100%; background: linear-gradient(135deg, #B7BACD, #312F36);">
                                <img src="images/chalake_22.jpg" height="450" with="auto">
                            </div>
                        </div>
                        <div class="card-back">
                            <blockquote>"הייתי מאוד מאוד מרוצה. עיבוד מדויק ומקצועי ביותר.
                                הילדים נהנו מאוד!! היחס והרוגע שלך מאוד הוסיפו.
                                מחיר מעולה. מקווה שיישאר כך.
                                שירות מעולה ,זריז ומדויק
                                ממליצה כבר לחברים ומשפחה!!"</blockquote>
                            <cite>- אמא של יהונתן המתוק</cite>
                        </div>
                    </div>
                </div>
                <div class="testimonial-card">
                    <div class="card-inner">
                        <div class="card-front1">
                            <div
                                style="width: 100%; height: 100%; background: linear-gradient(225deg, #F3C9C1, #B7BACD);">
                                <img src="images/chalake_2.jpg" height="450" with="auto">
                            </div>
                        </div>
                        <div class="card-back">
                            <blockquote>"מגיע לך תודה ענקית עשית לנו שמחת חג אמיתית....
                                זו היתה התוכנית המרכזית לכל האורחים
                                כולם שרקו מהתפעלות
                                ובכנות אני ממליצה בחום את פשוט אלופה זו החלאקה הרביעית שלנו ובאמת אין לך מתחרים
                                מצד העמידה בזמנים היחס ותשומת הלב
                                יצחק חזר שמח ומאושר ולא גמר לספר חוויות (כולל הסופגניה הנרות האביזרים המושקעים)
                                שלחת את התמונות ערוכות ומושלמות עם אלבום מעוצב ברמה הכי גבוהה שיש
                                ובזמן הקצר ביותר .....
                                התייחסת לכל בקשה ושינית שוב ושוב עד שנהיה הכי מרוצים...
                                ולסיום אין צלמת כמוך
                                תשריינו תאריכים אחרונים לפני עליית המחירים...."</blockquote>
                            <cite>- אמא של יצחק המתוק</cite>
                        </div>
                    </div>
                </div>
                <div class="testimonial-card">
                    <div class="card-inner">
                        <div class="card-front">
                            <div
                                style="width: 100%; height: 100%; background: linear-gradient(225deg, #F3C9C1, #B7BACD);">
                                <img src="images/family_6.jpg" height="450" with="auto">
                            </div>
                        </div>
                        <div class="card-back">
                            <blockquote>" אפרת את פשוט מדהימה צילמת את הבנות שלי ויצאו תמונות מהממות. הייתה אווירה ממש
                                נעימה, רגועה וכיפית, והכל הרגיש טבעי לגמרי. ממליצה עליה מכל הלב ❤️ "</blockquote>
                            <cite>- אמא לשלוש נסיכות -</cite>
                        </div>
                    </div>
                </div>
                <div class="testimonial-card">
                    <div class="card-inner">
                        <div class="card-front">
                            <div
                                style="width: 100%; height: 100%; background: linear-gradient(225deg, #F3C9C1, #B7BACD);">
                                <img src="images/1year_12.jpg" height="450" with="auto">
                            </div>
                        </div>
                        <div class="card-back">
                            <blockquote>"אני מאד מרוצה מהתמונות, הן באיכות, בזוויות, בהצלחה לתפוס את הרגע המדויק בו
                                הילדה עושה משהו/מחייכת וכדו'. היה נראה ששרית נהנתה מההתחלה. השירות שלך היה מעל ומעבר,
                                זמינות, גמישות ולא מתעקשת שאת רוצה משהו מסוים נותנת רעיונות ומקשיבה מאד מאד לדעת
                                הלקוחה!! זה חשוב מספר 1 בעייניי!!! ממליצה מאד לאנשים!!"</blockquote>
                            <cite>- אמא של שרית -</cite>
                        </div>
                    </div>
                </div>
                <div class="testimonial-card">
                    <div class="card-inner">
                        <div class="card-front">
                            <div
                                style="width: 100%; height: 100%; background: linear-gradient(225deg, #F3C9C1, #B7BACD);">
                                <img src="images/newborn6.jpg" height="450" with="auto">
                            </div>
                        </div>
                        <div class="card-back">
                            <blockquote>"היי אפרת אהובה,
                                רק רציתי לעצור לרגע ולהגיד תודה ענקית מכל הלב!

                                היינו מרוצים עד הגג – כל תמונה נראית כמו פוסטר, באמת שלא יכולנו לבקש יותר מזה.

                                הבייבי שלנו היה כל כך רגוע בידיים שלך – הרגשנו את החום, העדינות והסבלנות שלך בכל רגע.

                                השירות שלך היה פשוט מושלם – נעים, מרגיע, מקצועי ולא מכביד בשום שלב.

                                כבר אמרתי לכולם: אם מחפשים צלמת – ברור שלוקחים רק אותך! 💛
                                תודה רבה על הכל 🙏"</blockquote>
                            <cite>- אמא של ארי -</cite>
                        </div>
                    </div>
                </div>
            </div>
            <!-- Mini Contact Form -->
            <!-- Impressive Contact Section -->
            <section class="impressive-contact-section">
                <div class="contact-content-wrapper">
                    <div class="contact-info-card">
                        <h3>אפרת אדלר</h3>
                        <p class="subtitle">צלמת מקצועית לאירועים ומשפחות</p>

                        <div class="contact-details">
                            <p><strong>טלפון:</strong> 054-842-2817</p>
                            <p><strong>אימייל:</strong> e0548422817@gmail.com</p>
                            <p><strong>אזור השירות:</strong></p>
                            <p>לוד, מודיעין עילית, בית שמש והסביבה</p>
                        </div>

                        <div class="contact-buttons-mini">
                            <button class="contact-btn-mini phone-btn-mini" onclick="window.open('tel:054-842-2817')">
                                <i class="fa-solid fa-phone"></i>
                                התקשרו עכשיו
                            </button>
                            <button class="contact-btn-mini email-btn-mini"
                                onclick="window.open('mailto:e0548422817@gmail.com')">
                                <i class="fa-solid fa-envelope"></i>
                                שלחו אימייל
                            </button>
                        </div>
                    </div>

                    <div class="impressive-contact-form">
                        <h3>שלחו לי הודעה ואחזור אליכם בהקדם</h3>
                        <form id="impressiveContactForm" action="https://formspree.io/f/xjkrbzpr" method="POST">
                            <div class="impressive-form-row">
                                <div class="impressive-form-group">
                                <label for="fullName"></label>
                                    <input type="text" name="fullName" required placeholder="הכניסו את השם המלא *">
                                </div>
                                <div class="impressive-form-group">
                                    <label for="phone"></label>
                                    <input type="tel" name="phone" pattern="(05[0-9]{8}|0[0-9]{8})" required placeholder="מספר טלפון או פלאפון *">
                                </div>
                            </div>
                            <div class="impressive-form-group">
                                <label for="email"></label>
                                <input type="email" name="email" required placeholder="אימייל שלכם *">
                            </div>
                            <div class="impressive-form-group">
                                <label for="eventType"></label>
                                <select name="eventType">
                                    <option value="">בחרו סוג צילום</option>
                                    <option value="newborn">צילומי ניו בורן</option>
                                    <option value="oneyear">גיל שנה</option>
                                    <option value="chalaka">חלאקה</option>
                                    <option value="batmitzvah">בת מצווה</option>
                                    <option value="family">צילומי משפחה</option>
                                    <option value="other">אחר</option>
                                </select>
                            </div>
                            <div class="impressive-form-group">
                                <label for="message"></label>
                                <textarea name="message" rows="4" required
                                    placeholder="ספרו לי על האירוע המתוכנן, מה האווירה הרצויה ואיך אוכל לעזור לכם ליצור זכרונות מושלמים..."
                                    ></textarea>
                            </div>
                            <button type="submit" class="submit-btn">שלחו הודעה ואתחיל לתכנן עבורכם</button>
                        </form>
                    </div>
                </div>
            </section>
    </div>
    </section>

    <!-- About Page with Timeline -->
    <div id="about" class="page">
        <div style="margin-top: 115px;"></div>
        <section class="section">
            <h2 class="section-title">תהליך העבודה שלי</h2>
            <div class="timeline-container">
                <div class="timeline-line"></div>

                <div class="timeline-item" data-direction="right">
                    <div class="timeline-number"><i class="fas fa-phone"></i></div>
                    <div class="timeline-content">
                        <h3 class="process-title">ייעוץ ותכנון מוקדם</h3>
                        <p class="process-description">בשיחה קצרה נכיר, אבין מה אתם מחפשים ואעזור לכם לבחור את החבילה
                            והלוקיישן שהכי מתאימים לכם.</p>
                    </div>
                </div>

                <div class="timeline-item" data-direction="left">
                    <div class="timeline-number"><i class="fa-solid fa-magnifying-glass-location"
                            style="font-size: 26.5px;"></i></div>
                    <div class="timeline-content">
                        <h3 class="process-title">הכנות מקצועיות</h3>
                        <p class="process-description">אתם שולחים לי תמונות של הבגדים, ואני מתאימה לכם סטיילינג ולוקיישן
                            שיצרו יחד מראה הרמוני ומחמיא כמובן</p>
                    </div>
                </div>

                <div class="timeline-item" data-direction="right">
                    <div class="timeline-number"><i class="fas fa-camera" style="font-size: 24px;"></i></div>
                    <div class="timeline-content">
                        <h3 class="process-title">יום הצילום המושלם</h3>
                        <p class="process-description">ביום הצילומים אני שמה דגש על דיוק, סבלנות, ושפע של מקום לרגעים
                            הטבעיים שלכם. כי אצלי - יום צילום הוא כיף אמיתי!</p>
                    </div>
                </div>

                <div class="timeline-item" data-direction="left">
                    <div class="timeline-number"><i class="fa-solid fa-wand-magic-sparkles"></i></div>
                    <div class="timeline-content">
                        <h3 class="process-title">עריכה ועיבוד מקצועי</h3>
                        <p class="process-description">עד עשרה ימים לאחר הצילומים אשלח לכם גלריה מסודרת, מתוכה תבחרו את
                            התמונות האהובות עליכם לעיבוד מקצועי.</p>
                    </div>
                </div>

                <div class="timeline-item" data-direction="right">
                    <div class="timeline-number"><i class="fa-regular fa-images" style="font-size: 26.5px;"></i></div>
                    <div class="timeline-content">
                        <h3 class="process-title">מסירה וגלריה דיגיטלית</h3>
                        <p class="process-description">במידה ובחרתם חבילה עם אלבום - אני דואגת לערוך עבורכם אלבום
                            דיגיטלי מושלם וייחודי :)</p>
                    </div>
                </div>
            </div>
            <div style="display: flex; justify-content: center; margin-top: 70px;">
                <button class="contact-btn-shortcut" onclick="showPage('contact')">
                    בואו נתחיל לעבוד
                    <i class="fa-solid fa-location-dot fa-2xs"
                        style="color: transparent;"></i><i class="fa-solid fa-arrow-left"></i>
                </button>
            </div>
        </section>
    </div>

    <!-- Gallery Page with Navigation Arrows -->
    <div id="gallery" class="page">
        <div style="margin-top: 115px;"></div>
        <!-- Jet Parallax Gallery -->
        <section class="parallax-gallery">
            <h2 class="section-title">גלריית עבודות</h2>
            <div class="parallax-container">
                <div class="parallax-item" onclick="showCategoryPage('newborn')" tabindex="0">
                    <img src="images/newborn4.jpg" alt="צילומי ניו בורן">
                    <div class="parallax-overlay">
                        <div class="category-title">ניו בורן</div>
                    </div>
                </div>
                <div class="parallax-item" onclick="showCategoryPage('oneyear')" tabindex="0">
                    <img src="images/1year_23.jpg" alt="צילומי גיל שנה">
                    <div class="parallax-overlay">
                        <div class="category-title">גיל שנה</div>
                    </div>
                </div>
                <div class="parallax-item" onclick="showCategoryPage('chalaka')" tabindex="0">
                    <img src="images/chalake_3.jpg" alt="צילומי חלאקה">
                    <div class="parallax-overlay">
                        <div class="category-title">חלאקה</div>
                    </div>
                </div>
                <div class="parallax-item" onclick="showCategoryPage('batmitzvah')" tabindex="0">
                    <img src="images/newborn1.jpg" alt="צילומי בת מצווה">
                    <div class="parallax-overlay">
                        <div class="category-title">בת מצווה</div>
                    </div>
                </div>
                <div class="parallax-item" onclick="showCategoryPage('family')" tabindex="0">
                    <img src="images/family_6.jpg" alt="צילומי משפחות">
                    <div class="parallax-overlay">
                        <div class="category-title">משפחות</div>
                    </div>
                </div>
            </div>
            <div style="display: flex; justify-content: center; margin-top: 70px;">
                <button class="contact-btn-shortcut" onclick="showPage('contact')">
                    <i class="fa-solid fa-address-card"></i><i class="fa-solid fa-location-dot fa-2xs"
                        style="color: transparent;"></i>
                    צרו איתי קשר :)
                </button>
            </div>
        </section>
    </div>
    <!-- Category Pages -->
    <div id="newborn" class="page category-page">
        <div style="margin-top: 25px;"></div>
        <h2 class="section-title">צילומי ניו בורן</h2>
        <section class="section">
            <div class="gallery-grid">
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/newborn3.jpg" alt="ניו בורן - תינוק בסל">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/newborn4.jpg" alt="ניו בורן - תינוק בסל">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/newborn5.jpg" alt="ניו בורן - תינוק בסל">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/newborn6.jpg" alt="ניו בורן - תינוק בסל">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/newborn7.jpg" alt="ניו בורן - תינוק בסל">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/newborn8.jpg" alt="ניו בורן - תינוק בסל">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/newborn9.jpg" alt="ניו בורן - תינוק בסל">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/newborn10.jpg" alt="ניו בורן - תינוק בסל">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/newborn11.jpg" alt="ניו בורן - תינוק בסל">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/newborn12.jpg" alt="ניו בורן - תינוק בסל">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
            </div>
            <div style="display: flex; justify-content: center; margin-top: 70px;">
                <button class="contact-btn-shortcut" onclick="showPage('contact')">
                    <i class="fa-solid fa-address-card"></i><i class="fa-solid fa-location-dot fa-2xs"
                        style="color: transparent;"></i>
                    צרו איתי קשר :)
                </button>
            </div>
        </section>
    </div>
    <div id="oneyear" class="page category-page">
        <div style="margin-top: 25px;"></div>
        <h2 class="section-title">צילומי גיל שנה</h2>
        <section class="section">
            <div class="gallery-grid">
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/1year_23.jpg" alt="בן שנה - עוגת יום הולדת">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/1year_7.jpg" alt="בן שנה - עוגת יום הולדת">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/1year_14.jpg" alt="בן שנה - עוגת יום הולדת">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/1year_13.jpg" alt="בן שנה - עוגת יום הולדת">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/1year_22.jpg" alt="בן שנה - עוגת יום הולדת">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/1year_1.jpg" alt="בן שנה - משחק">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/1year_2.jpg" alt="בן שנה - חיוכים">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/1year_3.jpg" alt="בן שנה - חיוכים">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/1year_4.jpg" alt="בן שנה - חיוכים">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/1year_5.jpg" alt="בן שנה - חיוכים">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/1year_6.jpg" alt="בן שנה - חיוכים">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/1year_8.jpg" alt="בן שנה - חיוכים">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/1year_9.jpg" alt="בן שנה - חיוכים">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/1year_10.jpg" alt="בן שנה - חיוכים">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/1year_11.jpg" alt="בן שנה - חיוכים">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/1year_12.jpg" alt="בן שנה - חיוכים">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/1year_15.jpg" alt="בן שנה - חיוכים">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/1year_16.jpg" alt="בן שנה - חיוכים">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/1year_17.jpg" alt="בן שנה - חיוכים">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/1year_18.jpg" alt="בן שנה - חיוכים">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/1year_19.jpg" alt="בן שנה - חיוכים">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/1year_20.jpg" alt="בן שנה - חיוכים">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/1year_21.jpg" alt="בן שנה - חיוכים">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
            </div>
            <div style="display: flex; justify-content: center; margin-top: 70px;">
                <button class="contact-btn-shortcut" onclick="showPage('contact')">
                    <i class="fa-solid fa-address-card"></i><i class="fa-solid fa-location-dot fa-2xs"
                        style="color: transparent;"></i>
                    צרו איתי קשר :)
                </button>
            </div>
        </section>
    </div>

    <div id="chalaka" class="page category-page">
        <div style="margin-top: 25px;"></div>
        <h2 class="section-title">צילומי חלאקה</h2>
        <section class="section">
            <div class="gallery-grid">
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/chalake_1.jpg" alt="חלאקה - טקס הגזירה">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/chalake_5.jpg" alt="חלאקה - הילד החגיגי">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/chalake_25.jpg" alt="חלאקה - שמחת המשפחה">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/chalake_2.jpg" alt="חלאקה - שמחת המשפחה">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/chalake_3.jpg" alt="חלאקה - הילד החגיגי">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/chalake_4.jpg" alt="חלאקה - הילד החגיגי">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/chalake_11.jpg" alt="חלאקה - הילד החגיגי">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/chalake_12.jpg" alt="חלאקה - הילד החגיגי">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/chalake_6.jpg" alt="חלאקה - הילד החגיגי">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/chalake_7.jpg" alt="חלאקה - הילד החגיגי">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/chalake_8.jpg" alt="חלאקה - הילד החגיגי">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/chalake_9.jpg" alt="חלאקה - הילד החגיגי">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/chalake_10.jpg" alt="חלאקה - הילד החגיגי">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/chalake_23.jpg" alt="חלאקה - הילד החגיגי">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/chalake_13.jpg" alt="חלאקה - הילד החגיגי">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/chalake_14.jpg" alt="חלאקה - הילד החגיגי">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/chalake_15.jpg" alt="חלאקה - הילד החגיגי">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/chalake_16.jpg" alt="חלאקה - הילד החגיגי">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/chalake_17.jpg" alt="חלאקה - הילד החגיגי">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/chalake_18.jpg" alt="חלאקה - הילד החגיגי">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/chalake_19.jpg" alt="חלאקה - הילד החגיגי">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/chalake_20.jpg" alt="חלאקה - הילד החגיגי">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/chalake_21.jpg" alt="חלאקה - הילד החגיגי">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/chalake_22.jpg" alt="חלאקה - הילד החגיגי">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/chalake_24.jpg" alt="חלאקה - שמחת המשפחה">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
            </div>
            <div style="display: flex; justify-content: center; margin-top: 70px;">
                <button class="contact-btn-shortcut" onclick="showPage('contact')">
                    <i class="fa-solid fa-address-card"></i><i class="fa-solid fa-location-dot fa-2xs"
                        style="color: transparent;"></i>
                    צרו איתי קשר :)
                </button>
            </div>
        </section>
    </div>
    <div id="batmitzvah" class="page category-page">
        <div style="margin-top: 25px;"></div>
        <h2 class="section-title">צילומי בת מצווה</h2>
        <section class="section">
            <div class="gallery-grid">
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/batmitzva1.jpg" alt="בת מצווה - רגע הברכה">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/batmitzva_2.jpg" alt="בת מצווה - חגיגה">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/batmitzva_3.jpg" alt="בת מצווה - פורטרט">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/batmitzva_4.jpg" alt="בת מצווה - פורטרט">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/batmitzva_5.jpg" alt="בת מצווה - פורטרט">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/batmitzva_6.jpg" alt="בת מצווה - פורטרט">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/batmitzva_7.jpg" alt="בת מצווה - פורטרט">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/batmitzva_8.jpg" alt="בת מצווה - פורטרט">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/batmitzva_9.jpg" alt="בת מצווה - פורטרט">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/batmitzva_10.jpg" alt="בת מצווה - פורטרט">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/batmitzva_12.jpg" alt="בת מצווה - פורטרט">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/batmitzva_13.jpg" alt="בת מצווה - פורטרט">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/batmitzva_14.jpg" alt="בת מצווה - פורטרט">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/batmitzva_15.jpg" alt="בת מצווה - פורטרט">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
            </div>
            <div style="display: flex; justify-content: center; margin-top: 70px;">
                <button class="contact-btn-shortcut" onclick="showPage('contact')">
                    <i class="fa-solid fa-address-card"></i><i class="fa-solid fa-location-dot fa-2xs"
                        style="color: transparent;"></i>
                    צרו איתי קשר :)
                </button>
            </div>
        </section>
    </div>

    <div id="family" class="page category-page">
        <div style="margin-top: 25px;"></div>
        <h2 class="section-title">צילומי משפחות</h2>
        <section class="section">
            <div class="gallery-grid">
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/newborn1.jpg" alt="משפחה עם תינוקת">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/newborn2.jpg" alt="משפחה עם ילדים">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/family1.jpg" alt="משפחה בפארק">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/family_2.jpg" alt="משפחה על החוף">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/family_3.jpg" alt="משפחה בבית">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/family_4.jpg" alt="משפחה בבית">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/family_5.jpg" alt="משפחה בבית">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/family_6.jpg" alt="משפחה בבית">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
                <div class="gallery-item" onclick="openLightbox(this)" tabindex="0">
                    <img src="images/family_7.jpg" alt="משפחה בבית">
                    <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                        <i class="fa-solid fa-search-plus"></i>
                    </button>
                </div>
            </div>
            <div style="display: flex; justify-content: center; margin-top: 70px;">
                <button class="contact-btn-shortcut" onclick="showPage('contact')">
                    <i class="fa-solid fa-address-card"></i><i class="fa-solid fa-location-dot fa-2xs"
                        style="color: transparent;"></i>
                    צרו איתי קשר :)
                </button>
            </div>
        </section>
    </div>

    <!-- Albums Page -->
    <div id="albums" class="page">
        <div style="margin-top: 128px;"></div>
        <h2 class="section-title">אלבומים</h2>
        <div class="gallery-grid_albums">
            <div class="gallery-main-container">
                <div class="album-row">
                    <div class="gallery-item-album" onclick="openLightbox(this)" tabindex="0">
                        <img src="images/album_1.png" alt="משפחה בבית">
                        <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                            <i class="fa-solid fa-search-plus"></i>
                        </button>
                    </div>
                    <div class="gallery-item-album" onclick="openLightbox(this)" tabindex="0">
                        <img src="images/album_2.png" alt="משפחה בבית">
                        <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                            <i class="fa-solid fa-search-plus"></i>
                        </button>
                    </div>
                </div>
                <div class="album-row">
                    <div class="gallery-item-album" onclick="openLightbox(this)" tabindex="0">
                        <img src="images/album_3.png" alt="אלבום 3">
                        <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                            <i class="fa-solid fa-search-plus"></i>
                        </button>
                    </div>
                    <div class="gallery-item-album" onclick="openLightbox(this)" tabindex="0">
                        <img src="images/album_4.png" alt="אלבום 4">
                        <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                            <i class="fa-solid fa-search-plus"></i>
                        </button>
                    </div>
                </div>

                <div class="album-row">
                    <div class="gallery-item-album" onclick="openLightbox(this)" tabindex="0">
                        <img src="images/album_5.png" alt="אלבום 5">
                        <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                            <i class="fa-solid fa-search-plus"></i>
                        </button>
                    </div>
                    <div class="gallery-item-album" onclick="openLightbox(this)" tabindex="0">
                        <img src="images/album_6.png" alt="אלבום 6">
                        <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                            <i class="fa-solid fa-search-plus"></i>
                        </button>
                    </div>
                </div>

                <div class="album-row">
                    <div class="gallery-item-album" onclick="openLightbox(this)" tabindex="0">
                        <img src="images/album_7.png" alt="אלבום 7">
                        <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                            <i class="fa-solid fa-search-plus"></i>
                        </button>
                    </div>
                    <div class="gallery-item-album" onclick="openLightbox(this)" tabindex="0">
                        <img src="images/album_8.png" alt="אלבום 8">
                        <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                            <i class="fa-solid fa-search-plus"></i>
                        </button>
                    </div>
                </div>

                <div class="album-row">
                    <div class="gallery-item-album" onclick="openLightbox(this)" tabindex="0">
                        <img src="images/album_9.png" alt="אלבום 9">
                        <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                            <i class="fa-solid fa-search-plus"></i>
                        </button>
                    </div>
                    <div class="gallery-item-album" onclick="openLightbox(this)" tabindex="0">
                        <img src="images/album_10.png" alt="אלבום 10">
                        <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                            <i class="fa-solid fa-search-plus"></i>
                        </button>
                    </div>
                </div>

                <div class="album-row">
                    <div class="gallery-item-album" onclick="openLightbox(this)" tabindex="0">
                        <img src="images/album_11.png" alt="אלבום 11">
                        <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                            <i class="fa-solid fa-search-plus"></i>
                        </button>
                    </div>
                    <div class="gallery-item-album" onclick="openLightbox(this)" tabindex="0">
                        <img src="images/album_12.png" alt="אלבום 12">
                        <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                            <i class="fa-solid fa-search-plus"></i>
                        </button>
                    </div>
                </div>
                <div class="album-row">
                    <div class="gallery-item-album" onclick="openLightbox(this)" tabindex="0">
                        <img src="images/album_13.png" alt="אלבום 13">
                        <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                            <i class="fa-solid fa-search-plus"></i>
                        </button>
                    </div>
                    <div class="gallery-item-album" onclick="openLightbox(this)" tabindex="0">
                        <img src="images/album_14.png" alt="אלבום 14">
                        <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                            <i class="fa-solid fa-search-plus"></i>
                        </button>
                    </div>
                </div>
                <div class="album-row">
                    <div class="gallery-item-album" onclick="openLightbox(this)" tabindex="0">
                        <img src="images/album_15.png" alt="אלבום 15">
                        <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                            <i class="fa-solid fa-search-plus"></i>
                        </button>
                    </div>
                    <div class="gallery-item-album" onclick="openLightbox(this)" tabindex="0">
                        <img src="images/album_16.png" alt="אלבום 16">
                        <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)">
                            <i class="fa-solid fa-search-plus"></i>
                        </button>
                    </div>
                </div>
            </div>
        </div>
        <div style="display: flex; justify-content: center; margin: 40px 0 50px 0;">
                <button class="contact-btn-shortcut" onclick="showPage('contact')">
                    <i class="fa-solid fa-address-card"></i><i class="fa-solid fa-location-dot fa-2xs"
                        style="color: transparent;"></i>
                    צרו איתי קשר :)
                </button>
            </div>
    </div>
    <!-- Testimonials Page -->
    <div id="testimonials" class="page">
        <div style="margin-top: 115px;"></div>
        <section class="section">
            <h2 class="section-title">המלצות מלקוחות</h2>
            <div class="testimonials-grid">
                <div class="testimonial-card">
                    <div class="card-inner">
                        <div class="card-front">
                            <div
                                style="width: 100%; height: 100%; background: linear-gradient(45deg, #F3C9C1, #423D4A);">
                                <img src="images/family_2.jpg" height="450" width="auto">
                            </div>
                        </div>
                        <div class="card-back">
                            <blockquote>"יצא אלבום משגע, מאוד מרוצה מהתמונות רמה גבוהה מאוד גם של הצילום וגם של העריכה!!
                                הילדים חזרו שמחים היה להם יום חוויתי, מבחינתם זה היה טיול כיף עד כדי שלא רצו לחזור
                                הביתה! שתפו פעולה מדהים.
                                (פעמים שעברו הייתי צריכה להבטיח תשופרים למי שמשתף פעולה)
                                המחיר בהחלט שווה וזול בשביל התמורה. האלבום והקליפ שווים הרבה יותר ממה ששילמתי.
                                שירות מעולה. הרגשתי שאכפת לך לרצות אותנו, היית קשובה וסבלנית.
                                ממליצה בחום לכל מי שמחפשת תמונות יפות!! וכבר אמרתי לבעלי שמחכה להזדמנות לקחת אותך שוב
                                לצילומים.. רק צריכה ארוע😉"</blockquote>
                            <cite>- אמא של שירה</cite>
                        </div>
                    </div>
                </div>
                <div class="testimonial-card">
                    <div class="card-inner">
                        <div class="card-front2">
                            <div
                                style="width: 100%; height: 100%; background: linear-gradient(135deg, #B7BACD, #312F36);">
                                <img src="images/chalake_22.jpg" height="450" with="auto">
                            </div>
                        </div>
                        <div class="card-back">
                            <blockquote>"הייתי מאוד מאוד מרוצה. עיבוד מדויק ומקצועי ביותר.
                                הילדים נהנו מאוד!! היחס והרוגע שלך מאוד הוסיפו.
                                מחיר מעולה. מקווה שיישאר כך.
                                שירות מעולה ,זריז ומדויק
                                ממליצה כבר לחברים ומשפחה!!"</blockquote>
                            <cite>- אמא של יהונתן המתוק</cite>
                        </div>
                    </div>
                </div>
                <div class="testimonial-card">
                    <div class="card-inner">
                        <div class="card-front1">
                            <div
                                style="width: 100%; height: 100%; background: linear-gradient(225deg, #F3C9C1, #B7BACD);">
                                <img src="images/chalake_2.jpg" height="450" with="auto">
                            </div>
                        </div>
                        <div class="card-back">
                            <blockquote>"מגיע לך תודה ענקית עשית לנו שמחת חג אמיתית....
                                זו היתה התוכנית המרכזית לכל האורחים
                                כולם שרקו מהתפעלות
                                ובכנות אני ממליצה בחום את פשוט אלופה זו החלאקה הרביעית שלנו ובאמת אין לך מתחרים
                                מצד העמידה בזמנים היחס ותשומת הלב
                                יצחק חזר שמח ומאושר ולא גמר לספר חוויות (כולל הסופגניה הנרות האביזרים המושקעים)
                                שלחת את התמונות ערוכות ומושלמות עם אלבום מעוצב ברמה הכי גבוהה שיש
                                ובזמן הקצר ביותר .....
                                התייחסת לכל בקשה ושינית שוב ושוב עד שנהיה הכי מרוצים...
                                ולסיום אין צלמת כמוך
                                תשריינו תאריכים אחרונים לפני עליית המחירים...."</blockquote>
                            <cite>- אמא של יצחק -</cite>
                        </div>
                    </div>
                </div>
                <div class="testimonial-card">
                    <div class="card-inner">
                        <div class="card-front">
                            <div
                                style="width: 100%; height: 100%; background: linear-gradient(225deg, #F3C9C1, #B7BACD);">
                                <img src="images/family_6.jpg" height="450" with="auto">
                            </div>
                        </div>
                        <div class="card-back">
                            <blockquote>" אפרת את פשוט מדהימה צילמת את הבנות שלי ויצאו תמונות מהממות. הייתה אווירה ממש
                                נעימה, רגועה וכיפית, והכל הרגיש טבעי לגמרי. ממליצה עליה מכל הלב ❤️ "</blockquote>
                            <cite>- אמא לשלוש נסיכות -</cite>
                        </div>
                    </div>
                </div>
                <div class="testimonial-card">
                    <div class="card-inner">
                        <div class="card-front">
                            <div
                                style="width: 100%; height: 100%; background: linear-gradient(225deg, #F3C9C1, #B7BACD);">
                                <img src="images/1year_12.jpg" height="450" with="auto">
                            </div>
                        </div>
                        <div class="card-back">
                            <blockquote>"אני מאד מרוצה מהתמונות, הן באיכות, בזוויות, בהצלחה לתפוס את הרגע המדויק בו
                                הילדה עושה משהו/מחייכת וכדו'. היה נראה ששרית נהנתה מההתחלה. השירות שלך היה מעל ומעבר,
                                זמינות, גמישות ולא מתעקשת שאת רוצה משהו מסוים נותנת רעיונות ומקשיבה מאד מאד לדעת
                                הלקוחה!! זה חשוב מספר 1 בעייניי!!! ממליצה מאד לאנשים!!"</blockquote>
                            <cite>- אמא של שרית -</cite>
                        </div>
                    </div>
                </div>
                <div class="testimonial-card">
                    <div class="card-inner">
                        <div class="card-front">
                            <div
                                style="width: 100%; height: 100%; background: linear-gradient(225deg, #F3C9C1, #B7BACD);">
                                <img src="images/newborn6.jpg" height="450" with="auto">
                            </div>
                        </div>
                        <div class="card-back">
                            <blockquote>"היי אפרת אהובה,
                                רק רציתי לעצור לרגע ולהגיד תודה ענקית מכל הלב!

                                היינו מרוצים עד הגג – כל תמונה נראית כמו פוסטר, באמת שלא יכולנו לבקש יותר מזה.

                                הבייבי שלנו היה כל כך רגוע בידיים שלך – הרגשנו את החום, העדינות והסבלנות שלך בכל רגע.

                                השירות שלך היה פשוט מושלם – נעים, מרגיע, מקצועי ולא מכביד בשום שלב.

                                כבר אמרתי לכולם: אם מחפשים צלמת – ברור שלוקחים רק אותך! 💛
                                תודה רבה על הכל 🙏"</blockquote>
                            <cite>- אמא של ארי -</cite>
                        </div>
                    </div>
                </div>
            </div>
            <div style="display: flex; justify-content: center; margin-top: 70px;">
                <button class="contact-btn-shortcut" onclick="showPage('contact')">
                    <i class="fa-solid fa-address-card"></i><i class="fa-solid fa-location-dot fa-2xs"
                        style="color: transparent;"></i>
                    צרו איתי קשר :)
                </button>
            </div>
        </section>
    </div>

    <!-- Contact Page -->
    <div id="contact" class="page">
        <div style="margin-top: 115px;"></div>
        <section class="section1">
            <h2 class="section-title">צרו קשר</h2>
            <div style="margin-bottom: 3.6rem; text-align: center;">
            </div>
            <div class="contact-container">
                <div class="contact-form">
                    <h3
                        style="text-align: center; margin-bottom: 2.25rem; color: var(--text-bright); font-size: 1.35rem;">
                        שלחו לי הודעה ואחזור אליכם בהקדם</h3>
                    <form id="contactFormFull" action="https://formspree.io/f/xjkrbzpr" method="POST">
                        <div class="form-group">
                            <label for="fullNameFull">שם מלא *</label>
                            <input type="text" id="fullNameFull" name="fullName" required
                                placeholder="הכניסו את השם המלא">
                        </div>
                        <div class="form-group">
                            <label for="phoneFull">טלפון *</label>
                            <input type="tel" id="phoneFull" name="phone" pattern="(05[0-9]{8}|0[0-9]{9})" required
                                placeholder="מספר טלפון או פלאפון">
                        </div>
                        <div class="form-group">
                            <label for="emailFull">אימייל *</label>
                            <input type="email" id="emailFull" name="email" required placeholder="אימייל שלכם">
                        </div>
                        <div class="form-group">
                            <label for="eventTypeFull">סוג הפנייה</label>
                            <select id="eventTypeFull" name="eventType">
                                <option value="">בחרו סוג צילום</option>
                                <option value="newborn">צילומי ניו בורן</option>
                                <option value="oneyear">גיל שנה</option>
                                <option value="chalaka">חלאקה</option>
                                <option value="batmitzvah">בת מצווה</option>
                                <option value="family">צילומי משפחה</option>
                                <option value="other">אחר</option>
                            </select>
                        </div>
                        <div class="form-group">
                            <label for="messageFull">ספרו לי על האירוע שלכם *</label>
                            <textarea id="messageFull" name="message" rows="6" required
                                placeholder="ספרו לי על האירוע, התאריך המתוכנן, כמה אנשים, האווירה הרצויה ואיך אוכל לעזור לכם ליצור זכרונות מושלמים..."></textarea>
                        </div>
                        <button type="submit" class="submit-btn">שלחו הודעה ואתחיל לתכנן עבורכם</button>
                    </form>
                </div>
                <div class="contact-info">
                    <div class="contact-card">
                        <h3>אפרת אדלר</h3>
                        <p>-----------------------------------</p>
                        <p style="color: #F3C9C1; font-weight: 500; margin-bottom: 2.25rem; font-size: 1.1rem;">צלמת
                            מקצועית לאירועים ומשפחות</p>
                        <div style="text-align: right; line-height: 2;">
                            <p style="margin-bottom: 1.1rem;"><strong style="color: #F3C9C1;"> טלפון:</strong>
                                054-842-2817</p>
                            <p style="margin-bottom: 1.1rem;"><strong style="color: #F3C9C1;"> אימייל:</strong>
                                e0548422817@gmail.com</p>
                            <p style="margin-bottom: 1.1rem;"><strong style="color: #F3C9C1;"> אזור השירות:</strong></p>
                            <p style="margin-bottom: 2.25rem; padding-right: 0.9rem;">לוד, מודיעין עילית, בית שמש
                                והסביבה</p>
                        </div>
                    </div>

                    <div class="contact-buttons">
                        <button class="contact-btn phone-btn" onclick="window.open('tel:054-842-2817')">
                            <i class="fa-solid fa-phone"></i>
                            התקשרו עכשיו
                        </button>
                        <button class="contact-btn email-btn"
                            onclick="window.open('mailto:e0548422817@gmail.com?subject=פניה לצילום&body=שלום אפרת, אני מעוניין/ת לשמוע פרטים על...')">
                            <i class="fa-solid fa-envelope"></i>
                            שלחו אימייל
                        </button>
                    </div>
                </div>
            </div>
        </section>
    </div>

    <!-- Success Message Overlay -->
    <div id="successOverlay" class="success-overlay"></div>
    <div id="successMessage" class="success-message">
        <button class="success-close" onclick="hideSuccessMessage()">✕</button>
        <h3>תודה רבה! 🎉</h3>
        <p>ההודעה שלכם נשלחה בהצלחה.<br>אחזור אליכם בהקדם האפשרי!</p>
    </div>

    <!-- Enhanced Lightbox with Navigation -->
    <div id="lightbox" class="lightbox">
        <button class="lightbox-close" onclick="closeLightbox()" aria-label="Close lightbox">✕</button>
        <button class="gallery-nav-arrow left" id="lightboxPrevBtn" onclick="navigateLightbox(-1)"
            style="display: none;">
            <i class="fa-solid fa-chevron-left"></i>
        </button>
        <button class="gallery-nav-arrow right" id="lightboxNextBtn" onclick="navigateLightbox(1)"
            style="display: none;">
            <i class="fa-solid fa-chevron-right"></i>
        </button>
        <img id="lightbox-image" src="" alt="">
    </div>

    <!-- Footer -->
    <footer class="footer">
        <p>&copy; 2025 - כל הזכויות שמורות לאפרת אדלר<i class="fa-solid fa-square"></i>|<i
                class="fa-solid fa-square"></i>עיצוב ובניית אתרי תדמית<i class="fa-solid fa-square"></i>-<i
                class="fa-solid fa-square"></i>עמיאל מאזוז<i class="fa-solid fa-square"></i><i
                class="fa-solid fa-laptop-code"></i><i class="fa-solid fa-square"></i>|<i
                class="fa-solid fa-square"></i> 053-655-5534 <i class="fa-solid fa-square"></i><i
                class="fa-solid fa-phone"></i> <i class="fa-solid fa-square"></i> |<i class="fa-solid fa-square"></i>
            amielmazuz@gmail.com <i class="fa-solid fa-square"></i><i class="fa-solid fa-envelope"></i></p>
    </footer>
    <script>
        // Enhanced Slider functionality with smooth zoom effects
        let currentSlideIndex = 0;
        const slides = document.querySelectorAll('.slide');
        const totalSlides = slides.length;
        let slideInterval;
        let isTransitioning = false;

        function showSlide(index) {
            if (isTransitioning) return;
            isTransitioning = true;

            slides.forEach(slide => slide.classList.remove('active'));
            document.querySelectorAll('.nav-dot').forEach(dot => dot.classList.remove('active'));

            setTimeout(() => {
                slides[index].classList.add('active');
                document.querySelectorAll('.nav-dot')[index].classList.add('active');

                setTimeout(() => {
                    isTransitioning = false;
                }, 600);
            }, 100);
        }

        function nextSlide() {
            if (isTransitioning) return;
            currentSlideIndex = (currentSlideIndex + 1) % totalSlides;
            showSlide(currentSlideIndex);
        }

        function changeSlide(direction) {
            if (isTransitioning) return;
            currentSlideIndex = (currentSlideIndex + direction + totalSlides) % totalSlides;
            showSlide(currentSlideIndex);
            resetInterval();
        }

        function currentSlide(index) {
            if (isTransitioning) return;
            currentSlideIndex = index - 1;
            showSlide(currentSlideIndex);
            resetInterval();
        }

        function startSlideShow() {
            slideInterval = setInterval(nextSlide, 7000);
        }

        function resetInterval() {
            clearInterval(slideInterval);
            startSlideShow();
        }

        // Enhanced Gallery Navigation System
        let currentGalleryIndex = 0;
        let visibleGalleryItems = [];
        let currentCategory = 'all';

        function updateVisibleItems() {
            const activePage = document.querySelector('.page.active');
            const galleryItems = activePage.querySelectorAll('.gallery-item');

            visibleGalleryItems = Array.from(galleryItems);

            // Show/hide navigation arrows in lightbox
            const lightboxPrevBtn = document.getElementById('lightboxPrevBtn');
            const lightboxNextBtn = document.getElementById('lightboxNextBtn');

            if (visibleGalleryItems.length > 1) {
                if (lightboxPrevBtn) lightboxPrevBtn.style.display = 'block';
                if (lightboxNextBtn) lightboxNextBtn.style.display = 'block';
            } else {
                if (lightboxPrevBtn) lightboxPrevBtn.style.display = 'none';
                if (lightboxNextBtn) lightboxNextBtn.style.display = 'none';
            }
        }

        function navigateGallery(direction) {
            if (visibleGalleryItems.length <= 1) return;

            currentGalleryIndex = (currentGalleryIndex + direction + visibleGalleryItems.length) % visibleGalleryItems.length;
            const targetItem = visibleGalleryItems[currentGalleryIndex];

            // Scroll to the item and open lightbox
            targetItem.scrollIntoView({ behavior: 'smooth', block: 'center' });
            setTimeout(() => {
                openLightbox(targetItem);
            }, 300);
        }

        function navigateLightbox(direction) {
            if (visibleGalleryItems.length <= 1) return;

            currentGalleryIndex = (currentGalleryIndex + direction + visibleGalleryItems.length) % visibleGalleryItems.length;
            const targetItem = visibleGalleryItems[currentGalleryIndex];

            const lightboxImage = document.getElementById('lightbox-image');
            const img = targetItem.querySelector('img');

            if (img) {
                // Smooth transition effect
                lightboxImage.style.opacity = '0.5';
                setTimeout(() => {
                    lightboxImage.src = img.src;
                    lightboxImage.alt = img.alt;
                    lightboxImage.style.opacity = '1';
                }, 150);
            }
        }

        // Enhanced keyboard navigation with support for category galleries
        function handleKeyPress(e) {
            if (e.target.tagName === 'INPUT' || e.target.tagName === 'TEXTAREA' || e.target.tagName === 'SELECT') return;

            const lightbox = document.getElementById('lightbox');
            const isLightboxOpen = lightbox.classList.contains('show');

            // Check which page is active
            const activePage = document.querySelector('.page.active');
            const isHomePage = activePage && activePage.id === 'home';
            const isGalleryPage = activePage && activePage.id === 'gallery';
            const isCategoryPage = activePage && ['newborn', 'oneyear', 'chalaka', 'batmitzvah', 'family'].includes(activePage.id);

            switch (e.key) {
                case 'ArrowLeft':
                    e.preventDefault();
                    if (isLightboxOpen) {
                        navigateLightbox(1);
                    } else if (isGalleryPage || isCategoryPage) {
                        navigateCategoryGallery(1);
                    } else if (isHomePage) {
                        changeSlide(-1); // For RTL: left arrow = next slide
                    }
                    break;
                case 'ArrowRight':
                    e.preventDefault();
                    if (isLightboxOpen) {
                        navigateLightbox(-1);
                    } else if (isGalleryPage || isCategoryPage) {
                        navigateCategoryGallery(-1);
                    } else if (isHomePage) {
                        changeSlide(1); // For RTL: right arrow = previous slide
                    }
                    break;
                case 'Escape':
                    closeLightbox();
                    hideSuccessMessage();
                    break;
            }
        }

        // Navigation in category galleries
        function navigateCategoryGallery(direction) {
            const activePage = document.querySelector('.page.active');
            const galleryItems = activePage.querySelectorAll('.gallery-item');

            if (galleryItems.length <= 1) return;

            // Find current index
            let currentIndex = 0;
            const focusedItem = document.activeElement;
            if (focusedItem && focusedItem.classList.contains('gallery-item')) {
                currentIndex = Array.from(galleryItems).indexOf(focusedItem);
            }

            // Calculate new index
            const newIndex = (currentIndex + direction + galleryItems.length) % galleryItems.length;
            const targetItem = galleryItems[newIndex];

            // Scroll and open lightbox
            targetItem.scrollIntoView({ behavior: 'smooth', block: 'center' });
            setTimeout(() => {
                openLightbox(targetItem);
            }, 300);
        }

        // Page navigation
        function showPage(pageId) {
            document.querySelectorAll('.page').forEach(page => {
                page.classList.remove('active');
                page.style.display = 'none';
            });

            const targetPage = document.getElementById(pageId);
            targetPage.style.display = 'block';

            setTimeout(() => {
                targetPage.classList.add('active');
                targetPage.classList.add('fade-in');

                // Initialize timeline animations if it's the about page
                if (pageId === 'about') {
                    initTimelineAnimations();
                }

                // Update gallery navigation
                updateVisibleItems();
            }, 50);

            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        // Category page navigation
        function showCategoryPage(categoryId) {
            showPage(categoryId);
        }

        // Timeline Animation System
        function initTimelineAnimations() {
            const timelineItems = document.querySelectorAll('.timeline-item');

            // Reset all items
            timelineItems.forEach(item => {
                item.classList.remove('visible');
                const direction = item.dataset.direction;
                if (direction === 'left') {
                    item.classList.add('animate-left');
                }
            });

            // Set up intersection observer for timeline animations
            const timelineObserver = new IntersectionObserver((entries) => {
                entries.forEach((entry, index) => {
                    if (entry.isIntersecting) {
                        setTimeout(() => {
                            entry.target.classList.add('visible');
                        }, index * 200); // Stagger the animations
                    }
                });
            }, {
                threshold: 0.3,
                rootMargin: '0px 0px -100px 0px'
            });

            timelineItems.forEach(item => {
                timelineObserver.observe(item);
            });
        }

        // Enhanced Lightbox functionality
        function openLightbox(element) {
            try {
                if (!element) {
                    console.error('openLightbox: element is null or undefined');
                    return;
                }

                const lightbox = document.getElementById('lightbox');
                const lightboxImage = document.getElementById('lightbox-image');

                if (!lightbox || !lightboxImage) {
                    console.error('openLightbox: Required DOM elements not found');
                    return;
                }

                const img = element.querySelector('img');
                if (img && img.src) {
                    lightboxImage.src = img.src;
                    lightboxImage.alt = img.alt || '';

                    // Find current index in visible items
                    currentGalleryIndex = visibleGalleryItems.findIndex(item => item === element);
                    if (currentGalleryIndex === -1) currentGalleryIndex = 0;
                } else {
                    console.warn('openLightbox: No valid image found in element');
                    return;
                }

                lightbox.style.display = 'flex';
                document.body.style.overflow = 'hidden';

                setTimeout(() => {
                    lightbox.classList.add('show');
                    updateVisibleItems();
                }, 10);

            } catch (error) {
                console.error('openLightbox error:', error);
                // Ensure body overflow is reset even if there's an error
                document.body.style.overflow = 'auto';
            }
        }

        function closeLightbox() {
            const lightbox = document.getElementById('lightbox');
            lightbox.classList.remove('show');
            document.body.style.overflow = 'auto';

            setTimeout(() => {
                lightbox.style.display = 'none';
            }, 500);
        }

        // Success message functionality with auto-hide
        function showSuccessMessage() {
            const overlay = document.getElementById('successOverlay');
            const message = document.getElementById('successMessage');

            overlay.style.display = 'block';
            message.style.display = 'block';

            setTimeout(() => {
                overlay.classList.add('show');
                message.classList.add('show');
            }, 10);

            // Auto-hide after 5 seconds and redirect to home
            setTimeout(() => {
                hideSuccessMessage();
                showPage('home');
            }, 5000);
        }

        function hideSuccessMessage() {
            const overlay = document.getElementById('successOverlay');
            const message = document.getElementById('successMessage');

            overlay.classList.remove('show');
            message.classList.remove('show');

            setTimeout(() => {
                overlay.style.display = 'none';
                message.style.display = 'none';
            }, 500);
        }

        // Enhanced form handling - UNIFIED SINGLE FUNCTION
        function handleFormSubmit(event) {
            event.preventDefault();

            const form = event.target;
            const formData = new FormData(form);

            const submitBtn = form.querySelector('.submit-btn', '.impressive-submit-btn');
            const originalText = submitBtn.textContent;
            submitBtn.innerHTML = 'שולח... <span class="loading-spinner"></span>';
            submitBtn.disabled = true;

            // Add page source identifier
            const currentPage = document.querySelector('.page.active');
            const pageId = currentPage ? currentPage.id : 'unknown';
            formData.append('pageSource', pageId);

            fetch(form.action, {
                method: 'POST',
                body: formData,
                headers: {
                    'Accept': 'application/json'
                }
            })
                .then(response => {
                    if (response.ok) {
                        showSuccessMessage();
                        form.reset();
                        console.log(`הודעה נשלחה בהצלחה מעמוד: ${pageId}`);
                    } else {
                        response.json().then(data => {
                            if (data.errors) {
                                console.error('Form errors:', data.errors);
                            }
                            throw new Error('שגיאה בשליחת הטופס');
                        });
                    }
                })
                .catch(error => {
                    console.error('Error:', error);
                    alert('שגיאה בשליחת ההודעה. אנא נסו שוב או צרו קשר ישירות בטלפון: 054-842-2817');
                })
                .finally(() => {
                    submitBtn.textContent = originalText;
                    submitBtn.disabled = false;
                });
        }

        // Phone number validation
        function validatePhoneNumber(input) {
            const phonePattern = /(05[0-9]{8}|0[2-4,8-9][0-9]{7})/;
            const value = input.value.replace(/[-\s()]/g, '');

            if (value && !phonePattern.test(value)) {
                input.setCustomValidity('מספר הטלפון חייב להיות: 05X-XXXXXXX או 0X-XXXXXXXX');
                input.classList.add('invalid');
            } else {
                input.setCustomValidity('');
                input.classList.remove('invalid');
            }
        }

        // Enhanced navbar scroll effect
        function handleScroll() {
            const navbar = document.querySelector('.navbar');
            if (window.scrollY > 80) {
                navbar.classList.add('navbar-scrolled');
            } else {
                navbar.classList.remove('navbar-scrolled');
            }
        }

        // About section scroll-based text animations
        function initAboutTextAnimations() {
            const aboutText = document.querySelector('.about-text');
            if (!aboutText) return;

            const paragraphs = aboutText.querySelectorAll('p');

            const aboutObserver = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        const paragraphs = entry.target.querySelectorAll('p');
                        paragraphs.forEach((p, index) => {
                            setTimeout(() => {
                                p.classList.add('visible');
                                if (index === 0 || p.querySelector('strong')) {
                                    p.classList.add('fill-effect');
                                }
                            }, index * 300);
                        });
                    }
                });
            }, {
                threshold: 0.3
            });

            aboutObserver.observe(aboutText);
        }

        // Fixed parallax hover glitch
        function initParallaxGallery() {
            const parallaxItems = document.querySelectorAll('.parallax-item');
            let currentHovered = null;

            parallaxItems.forEach(item => {
                item.addEventListener('mouseenter', function () {
                    if (currentHovered && currentHovered !== this) {
                        // Reset previous item immediately
                        currentHovered.style.transform = '';
                        currentHovered.style.zIndex = '1';
                    }
                    currentHovered = this;
                    this.style.zIndex = '10';
                });

                item.addEventListener('mouseleave', function () {
                    this.style.zIndex = '1';
                    if (currentHovered === this) {
                        currentHovered = null;
                    }
                });

                // Keyboard navigation for parallax items
                item.addEventListener('keydown', function (e) {
                    if (e.key === 'Enter' || e.key === ' ') {
                        e.preventDefault();
                        this.click();
                    }
                });
            });
        }

        // Enhanced rotating welcome smiley with smooth scroll-based rotation
        function initRotatingWelcome() {
            const rotatingWelcome = document.querySelector('.rotating-welcome');
            if (!rotatingWelcome) return;

            let scrollPosition = 0;
            let rotation = 0;
            const rotationFactor = 0.5;

            function updateRotation() {
                const currentScrollPosition = window.scrollY || document.documentElement.scrollTop;
                const scrollDifference = currentScrollPosition - scrollPosition;

                rotation += scrollDifference * rotationFactor;
                rotatingWelcome.style.transform = `rotate(${rotation}deg)`;

                scrollPosition = currentScrollPosition;
            }

            let ticking = false;
            function requestTick() {
                if (!ticking) {
                    requestAnimationFrame(updateRotation);
                    ticking = true;
                    setTimeout(() => { ticking = false; }, 16);
                }
            }

            window.addEventListener('scroll', requestTick, { passive: true });
        }
        // Enhanced testimonials with continuous flip animation
        function initTestimonialCards() {
            const testimonialCards = document.querySelectorAll('.testimonial-card');

            testimonialCards.forEach(card => {
                const cardInner = card.querySelector('.card-inner');
                let isFlipped = false;

                card.addEventListener('mouseenter', () => {
                    if (!isFlipped) {
                        cardInner.style.transform = 'rotateY(180deg)';
                        isFlipped = true;
                    }
                });

                card.addEventListener('mouseleave', () => {
                    if (isFlipped) {
                        cardInner.style.transform = 'rotateY(360deg)';
                        setTimeout(() => {
                            cardInner.style.transform = 'rotateY(0deg)';
                            isFlipped = false;
                        }, 400);
                    }
                });
            });
        }

        // Add zoom icons to gallery items
        function addZoomIcons() {
            const galleryItems = document.querySelectorAll('.gallery-item');
            galleryItems.forEach(item => {
                if (!item.querySelector('.zoom-icon')) {
                    const zoomIcon = document.createElement('button');
                    zoomIcon.className = 'zoom-icon';
                    zoomIcon.innerHTML = '<i class="fa-solid fa-search-plus"></i>';
                    zoomIcon.setAttribute('aria-label', 'הגדל תמונה');
                    zoomIcon.addEventListener('click', (e) => {
                        e.stopPropagation();
                        openLightbox(item);
                    });
                    item.appendChild(zoomIcon);
                }
            });
        }

        // Pinterest-style Masonry Gallery with Natural Aspect Ratios
        function initMasonryGallery() {
            const galleries = document.querySelectorAll('.gallery-grid');

            galleries.forEach(gallery => {
                // Clear all existing styles
                gallery.style.cssText = '';

                // Create wrapper for centering
                let wrapper = gallery.parentElement.querySelector('.gallery-wrapper');
                if (!wrapper) {
                    wrapper = document.createElement('div');
                    wrapper.className = 'gallery-wrapper';
                    gallery.parentElement.insertBefore(wrapper, gallery);
                    wrapper.appendChild(gallery);
                }

                // Style the wrapper for centering
                wrapper.style.display = 'flex';
                wrapper.style.justifyContent = 'center';
                wrapper.style.width = '100%';
                wrapper.style.padding = '0';
                wrapper.style.margin = '0';

                // Style the gallery
                gallery.style.display = 'block';
                gallery.style.columnCount = '4';
                gallery.style.columnGap = '1rem';
                gallery.style.width = '90vw';
                gallery.style.maxWidth = '1400px';
                gallery.style.margin = '0';
                gallery.style.padding = '0';

                const updateColumns = () => {
                    const width = window.innerWidth;
                    if (width >= 1920) {
                        gallery.style.columnCount = '4';
                        gallery.style.width = '85vw';
                    } else if (width >= 1024) {
                        gallery.style.columnCount = '3';
                        gallery.style.width = '90vw';
                    } else if (width >= 768) {
                        gallery.style.columnCount = '2';
                        gallery.style.width = '95vw';
                    } else {
                        gallery.style.columnCount = '2';
                        gallery.style.width = '98vw';
                    }
                };

                updateColumns();
                window.addEventListener('resize', updateColumns);

                const items = gallery.querySelectorAll('.gallery-item');
                items.forEach(item => {
                    item.style.breakInside = 'avoid';
                    item.style.marginBottom = '1rem';
                    item.style.display = 'inline-block';
                    item.style.width = '100%';
                    item.style.borderRadius = '8px';
                    item.style.overflow = 'hidden';

                    const img = item.querySelector('img');
                    if (img) {
                        img.style.width = '100%';
                        img.style.height = 'auto';
                        img.style.display = 'block';
                    }
                });
            });
        }

        function optimizeForScreenSize(item, aspectRatio) {
            const screenWidth = window.innerWidth;

            if (screenWidth < 1024) {
                item.classList.remove('portrait', 'landscape');
                item.classList.add('square');
                return;
            }

            if (screenWidth > 1400) {
                if (aspectRatio < 0.6) {
                    item.style.gridRow = 'span 3';
                } else if (aspectRatio > 2) {
                    item.style.gridColumn = 'span 3';
                }
            }
        }

        function handleResize() {
            clearTimeout(window.resizeTimer);
            window.resizeTimer = setTimeout(() => {
                initMasonryGallery();
            }, 250);
        }

        // Initialize everything when DOM is loaded
        document.addEventListener('DOMContentLoaded', function () {
            // Start slideshow
            const firstSlide = document.querySelector('.slide.active');
            if (firstSlide) {
                const firstSlideImg = firstSlide.querySelector('img');
                if (firstSlideImg) {
                    firstSlideImg.style.transform = 'scale(1.1)';
                }
            }
            startSlideShow();

            // Initialize all components
            addZoomIcons();
            initParallaxGallery();
            initRotatingWelcome();
            initAboutTextAnimations();
            initTestimonialCards();
            initMasonryGallery();

            // Add keyboard navigation
            document.addEventListener('keydown', handleKeyPress);

            // Add scroll listener with throttling
            let scrollTimeout;
            window.addEventListener('scroll', function () {
                if (scrollTimeout) {
                    clearTimeout(scrollTimeout);
                }
                scrollTimeout = setTimeout(handleScroll, 8);
            }, { passive: true });

            // Form event listeners - ONLY 2 FORMS
            const forms = ['contactFormHome', 'contactFormFull', 'impressiveContactForm'];
            forms.forEach(formId => {
                const form = document.getElementById(formId);
                if (form) {
                    form.addEventListener('submit', handleFormSubmit);

                    const phoneInput = form.querySelector('input[type="tel"]');
                    if (phoneInput) {
                        phoneInput.addEventListener('input', function () {
                            validatePhoneNumber(this);
                        });
                    }

                    console.log(`טופס ${formId} אותחל בהצלחה`);
                } else {
                    console.log(`טופס ${formId} לא נמצא - זה תקין אם הוא לא קיים בעמוד הזה`);
                }
            });

            // Close lightbox when clicking outside image
            document.getElementById('lightbox').addEventListener('click', function (e) {
                if (e.target === this) {
                    closeLightbox();
                }
            });

            // Close success message when clicking overlay
            document.getElementById('successOverlay').addEventListener('click', function () {
                hideSuccessMessage();
            });

            // Gallery item keyboard navigation
            const galleryItems = document.querySelectorAll('.gallery-item');
            galleryItems.forEach(item => {
                item.addEventListener('keydown', function (e) {
                    if (e.key === 'Enter' || e.key === ' ') {
                        e.preventDefault();
                        openLightbox(this);
                    }
                });
            });

            // Enhanced intersection observer for animations
            const observerOptions = {
                threshold: 0.1,
                rootMargin: '0px 0px -50px 0px'
            };

            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.style.opacity = '1';
                        entry.target.style.transform = 'translateY(0)';
                    }
                });
            }, observerOptions);

            const animatedElements = document.querySelectorAll('.card, .gallery-item, .testimonial-card');
            animatedElements.forEach(el => {
                el.style.opacity = '0';
                el.style.transform = 'translateY(30px)';
                el.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
                observer.observe(el);
            });

            // Initialize gallery navigation
            updateVisibleItems();

            // Window resize handler
            window.addEventListener('resize', handleResize);
        });

        // Enhanced mobile support with touch handling
        let touchStartX = 0;
        let touchEndX = 0;
        let touchStartY = 0;
        let touchEndY = 0;

        function handleTouchStart(e) {
            touchStartX = e.changedTouches[0].screenX;
            touchStartY = e.changedTouches[0].screenY;
        }

        function handleTouchEnd(e) {
            touchEndX = e.changedTouches[0].screenX;
            touchEndY = e.changedTouches[0].screenY;
            handleSwipe();
        }

        function handleSwipe() {
            const swipeThreshold = 50;
            const diffX = touchStartX - touchEndX;
            const diffY = Math.abs(touchStartY - touchEndY);

            if (Math.abs(diffX) > swipeThreshold && diffY < swipeThreshold * 2) {
                const lightbox = document.getElementById('lightbox');
                const isLightboxOpen = lightbox.classList.contains('show');
                const activePage = document.querySelector('.page.active');
                const isHomePage = activePage && activePage.id === 'home';

                if (isLightboxOpen) {
                    if (diffX > 0) {
                        navigateLightbox(1);
                    } else {
                        navigateLightbox(-1);
                    }
                } else if (isHomePage) {
                    if (diffX > 0) {
                        changeSlide(1);
                    } else {
                        changeSlide(-1);
                    }
                }
            }
        }

        // Add touch events
        document.addEventListener('touchstart', handleTouchStart, { passive: true });
        document.addEventListener('touchend', handleTouchEnd, { passive: true });

        // Export functions for external use
        window.photographerWebsite = {
            showPage,
            showCategoryPage,
            openLightbox,
            closeLightbox,
            navigateGallery,
            navigateLightbox
        };

        window.galleryUtils = {
            initResponsiveGallery,
            optimizeForScreenSize
        };
    </script>
    <!-- CMS Integration System + Real Analytics -->
   <script>
        // ============================================
        // מערכת מעקב אנליטיקס אמיתית + אינטגרציה עם CMS
        // גרסה 2.1 - מוכן לפרודקשן עם נתונים אמיתיים בלבד
        // תואם ל-CMS v2.1 עם הגנות מתקדמות - FIXED
        // ============================================

        class RealWebsiteAnalytics {
            constructor() {
                this.sessionId = this.generateSessionId();
                this.visitorId = this.getOrCreateVisitorId();
                this.startTime = Date.now();
                this.lastActivity = Date.now();
                this.currentPage = window.location.pathname;
                this.scrollDepth = 0;
                this.interactions = 0;
                this.timeOnPage = 0;

                // נתונים שמורים
                this.data = this.loadStoredData();

                this.init();
            }

            generateSessionId() {
                return `session_${Date.now()}_${Math.random().toString(36).substr(2, 9)}`;
            }

            getOrCreateVisitorId() {
                let visitorId = localStorage.getItem('analytics_visitor_id');
                if (!visitorId) {
                    const fingerprint = [
                        navigator.userAgent,
                        screen.width,
                        screen.height,
                        navigator.language,
                        new Date().getTimezoneOffset()
                    ].join('|');
                    visitorId = `visitor_${btoa(fingerprint).substr(0, 16)}_${Date.now()}`;
                    localStorage.setItem('analytics_visitor_id', visitorId);
                }
                return visitorId;
            }

            // FIXED: Date handling with fallback
            getISOString() {
                try {
                    return new Date().toISOString();
                } catch (e) {
                    // Fallback for older browsers
                    const date = new Date();
                    return date.getFullYear() + '-' + 
                           String(date.getMonth() + 1).padStart(2, '0') + '-' + 
                           String(date.getDate()).padStart(2, '0') + 'T' + 
                           String(date.getHours()).padStart(2, '0') + ':' + 
                           String(date.getMinutes()).padStart(2, '0') + ':' + 
                           String(date.getSeconds()).padStart(2, '0') + '.000Z';
                }
            }

            loadStoredData() {
                try {
                    const stored = localStorage.getItem('website_analytics_data');
                    if (stored) {
                        const data = JSON.parse(stored);
                        // המר arrays חזרה ל-Sets
                        if (Array.isArray(data.uniqueVisitors)) {
                            data.uniqueVisitors = new Set(data.uniqueVisitors);
                        }
                        if (data.dailyStats) {
                            Object.keys(data.dailyStats).forEach(date => {
                                if (Array.isArray(data.dailyStats[date].visitors)) {
                                    data.dailyStats[date].visitors = new Set(data.dailyStats[date].visitors);
                                }
                            });
                        }
                        return data;
                    }
                } catch (e) {
                    console.log('Creating new analytics data structure');
                }

                // נתונים ראשוניים אמיתיים
                return {
                    totalPageViews: 0,
                    uniqueVisitors: new Set(),
                    totalSessions: 0,
                    activeSessions: 0,
                    todayPageViews: 0,
                    averageSessionDuration: 0,
                    bounceRate: 0,
                    lastVisit: null,
                    firstVisit: this.getISOString(),
                    dailyStats: {},
                    sessions: []
                };
            }

            init() {
                try {
                    this.recordPageView();
                    this.startSession();
                    this.setupEventListeners();
                    this.startHeartbeat();
                    console.log('📊 Real Analytics initialized:', this.getStats());
                } catch (e) {
                    console.error('Analytics initialization failed:', e);
                }
            }

            recordPageView() {
                try {
                    this.data.totalPageViews++;
                    this.data.uniqueVisitors.add(this.visitorId);
                    this.data.lastVisit = this.getISOString();

                    // סטטיסטיקות יומיות
                    const today = new Date().toDateString();
                    if (!this.data.dailyStats[today]) {
                        this.data.dailyStats[today] = { views: 0, visitors: new Set() };
                    }
                    this.data.dailyStats[today].views++;
                    this.data.dailyStats[today].visitors.add(this.visitorId);
                    this.data.todayPageViews = this.data.dailyStats[today].views;

                    this.saveData();
                    console.log(`📈 Page view recorded: ${this.data.totalPageViews} total, ${this.data.uniqueVisitors.size} unique visitors`);
                } catch (e) {
                    console.error('Page view recording failed:', e);
                }
            }

            startSession() {
                try {
                    const session = {
                        id: this.sessionId,
                        visitorId: this.visitorId,
                        startTime: this.startTime,
                        page: this.currentPage,
                        userAgent: navigator.userAgent,
                        referrer: document.referrer || 'direct',
                        screenResolution: `${screen.width}x${screen.height}`,
                        isActive: true
                    };

                    this.data.sessions.push(session);
                    this.data.totalSessions++;
                    this.updateActiveSessions();

                    // שמור רק 500 סשנים אחרונים
                    if (this.data.sessions.length > 500) {
                        this.data.sessions = this.data.sessions.slice(-500);
                    }

                    this.saveData();
                } catch (e) {
                    console.error('Session start failed:', e);
                }
            }

            setupEventListeners() {
                try {
                    // מעקב אחר אינטראקציות
                    ['click', 'scroll', 'keydown', 'mousemove', 'touchstart'].forEach(event => {
                        document.addEventListener(event, () => {
                            this.updateActivity();
                            if (event === 'click' || event === 'touchstart') {
                                this.interactions++;
                            }
                        }, { passive: true });
                    });

                    // מעקב עומק גלילה
                    window.addEventListener('scroll', this.trackScrollDepth.bind(this), { passive: true });

                    // סיום סשן
                    window.addEventListener('beforeunload', () => {
                        this.endSession();
                    });

                    // החזרה לעמוד
                    document.addEventListener('visibilitychange', () => {
                        if (!document.hidden) {
                            this.updateActivity();
                            this.recordPageView();
                        }
                    });
                } catch (e) {
                    console.error('Event listeners setup failed:', e);
                }
            }

            trackScrollDepth() {
                try {
                    const scrollTop = window.pageYOffset;
                    const docHeight = document.documentElement.scrollHeight - window.innerHeight;
                    const scrollPercent = docHeight > 0 ? Math.round((scrollTop / docHeight) * 100) : 0;

                    if (scrollPercent > this.scrollDepth) {
                        this.scrollDepth = scrollPercent;
                    }
                } catch (e) {
                    console.error('Scroll depth tracking failed:', e);
                }
            }

            updateActivity() {
                try {
                    this.lastActivity = Date.now();
                    this.timeOnPage = this.lastActivity - this.startTime;
                } catch (e) {
                    console.error('Activity update failed:', e);
                }
            }

            updateActiveSessions() {
                try {
                    const now = Date.now();
                    const sessionTimeout = 30 * 60 * 1000; // 30 דקות

                    // עדכן סשנים פעילים
                    this.data.activeSessions = this.data.sessions.filter(session => {
                        const sessionAge = now - session.startTime;
                        return sessionAge < sessionTimeout && session.isActive;
                    }).length;
                } catch (e) {
                    console.error('Active sessions update failed:', e);
                }
            }

            startHeartbeat() {
                try {
                    setInterval(() => {
                        this.updateActivity();
                        this.updateActiveSessions();
                        this.calculateMetrics();
                        this.saveData();
                        this.sendToCMS();
                    }, 30000); // כל 30 שניות
                } catch (e) {
                    console.error('Heartbeat failed:', e);
                }
            }

            calculateMetrics() {
                try {
                    // חישוב זמן ממוצע בסשן
                    const completedSessions = this.data.sessions.filter(s => s.endTime);
                    if (completedSessions.length > 0) {
                        const totalDuration = completedSessions.reduce((sum, s) => sum + (s.endTime - s.startTime), 0);
                        this.data.averageSessionDuration = Math.round(totalDuration / completedSessions.length / 1000);
                    }

                    // חישוב bounce rate
                    const shortSessions = completedSessions.filter(s => (s.endTime - s.startTime) < 30000).length;
                    this.data.bounceRate = completedSessions.length > 0
                        ? Math.round((shortSessions / completedSessions.length) * 100)
                        : 0;
                } catch (e) {
                    console.error('Metrics calculation failed:', e);
                }
            }

            endSession() {
                try {
                    const sessionIndex = this.data.sessions.findIndex(s => s.id === this.sessionId);
                    if (sessionIndex !== -1) {
                        this.data.sessions[sessionIndex].endTime = Date.now();
                        this.data.sessions[sessionIndex].duration = this.timeOnPage;
                        this.data.sessions[sessionIndex].scrollDepth = this.scrollDepth;
                        this.data.sessions[sessionIndex].interactions = this.interactions;
                        this.data.sessions[sessionIndex].isActive = false;
                    }
                    this.saveData();
                } catch (e) {
                    console.error('Session end failed:', e);
                }
            }

            saveData() {
                try {
                    // המרה של Set ל-Array לשמירה
                    const dataToSave = {
                        ...this.data,
                        uniqueVisitors: [...this.data.uniqueVisitors],
                        dailyStats: Object.fromEntries(
                            Object.entries(this.data.dailyStats).map(([date, stats]) => [
                                date,
                                { ...stats, visitors: [...stats.visitors] }
                            ])
                        )
                    };

                    localStorage.setItem('website_analytics_data', JSON.stringify(dataToSave));
                } catch (e) {
                    console.error('Failed to save analytics data:', e);
                }
            }

            sendToCMS() {
                // FIXED: Enhanced CMS communication with error handling
                try {
                    const cmsWindows = [];

                    // חפש חלונות CMS פתוחים
                    if (window.cmsWindow && !window.cmsWindow.closed) {
                        cmsWindows.push(window.cmsWindow);
                    }

                    // שלח הודעה לכל חלונות CMS - COMPATIBLE WITH FIXED CMS
                    cmsWindows.forEach(cmsWindow => {
                        try {
                            cmsWindow.postMessage({
                                type: 'analytics_update',
                                data: this.getStats()
                            }, '*');
                        } catch (e) {
                            console.error('Failed to send to CMS window:', e);
                        }
                    });

                } catch (e) {
                    // לא קריטי אם CMS לא פתוח
                    console.log('CMS communication not available');
                }
            }

            getStats() {
                try {
                    this.updateActiveSessions();
                    this.calculateMetrics();

                    return {
                        totalPageViews: this.data.totalPageViews,
                        uniqueVisitors: this.data.uniqueVisitors.size || this.data.uniqueVisitors.length,
                        totalSessions: this.data.totalSessions,
                        activeSessions: this.data.activeSessions,
                        todayPageViews: this.data.todayPageViews,
                        averageSessionDuration: this.data.averageSessionDuration,
                        bounceRate: this.data.bounceRate,
                        lastUpdate: this.getISOString(),
                        lastVisit: this.data.lastVisit,
                        currentSessionDuration: Math.round(this.timeOnPage / 1000 / 60),
                        scrollDepth: this.scrollDepth,
                        interactions: this.interactions
                    };
                } catch (e) {
                    console.error('Get stats failed:', e);
                    return {};
                }
            }

            reset() {
                try {
                    localStorage.removeItem('website_analytics_data');
                    localStorage.removeItem('analytics_visitor_id');
                    location.reload();
                } catch (e) {
                    console.error('Reset failed:', e);
                }
            }
        }
        // ============================================
        // מערכת אינטגרציה מלאה עם CMS v2.1 - FIXED
        // ============================================

        class CMSIntegration {
            constructor() {
                this.lastUpdate = Date.now();
                this.init();
            }

            init() {
                try {
                    this.loadAllCMSData();
                    this.setupMessageListeners();

                    // בדיקה תקופתית לעדכונים
                    setInterval(() => {
                        this.loadAllCMSData();
                    }, 10000); // כל 10 שניות

                    console.log('🔗 CMS Integration v2.1 initialized - FIXED');
                } catch (e) {
                    console.error('CMS Integration initialization failed:', e);
                }
            }

            loadAllCMSData() {
                try {
                    const gallery = this.getSecureData('website_gallery_data');
                    const content = this.getSecureData('website_content_data');
                    const testimonials = this.getSecureData('website_testimonials_data');

                    if (gallery && Object.keys(gallery).length > 0) {
                        this.updateGalleries(gallery);
                    }

                    if (content && Object.keys(content).length > 0) {
                        this.updateSiteContent(content);
                    }

                    if (testimonials && testimonials.length > 0) {
                        this.updateTestimonials(testimonials);
                    }

                } catch (e) {
                    console.log('Loading CMS data from localStorage...');
                    this.loadBasicCMSData();
                }
            }

            getSecureData(key) {
                try {
                    // FIXED: נסה תחילה מהאחסון המוצפן (CMS v2.1)
                    const encrypted = localStorage.getItem(key + '_secure');
                    if (encrypted) {
                        try {
                            // תואם למערכת ההצפנה החדשה של CMS
                            return JSON.parse(encrypted);
                        } catch (e) {
                            // אם נכשל, נסה כ-JSON רגיל
                            return JSON.parse(encrypted);
                        }
                    }

                    // אחרת מהאחסון הרגיל
                    const regular = localStorage.getItem(key);
                    if (regular) {
                        return JSON.parse(regular);
                    }
                } catch (e) {
                    console.log(`Could not load ${key}:`, e);
                }
                return null;
            }

            loadBasicCMSData() {
                try {
                    const gallery = JSON.parse(localStorage.getItem('website_gallery_data') || '{}');
                    const content = JSON.parse(localStorage.getItem('website_content_data') || '{}');
                    const testimonials = JSON.parse(localStorage.getItem('website_testimonials_data') || '[]');

                    if (Object.keys(gallery).length > 0) this.updateGalleries(gallery);
                    if (Object.keys(content).length > 0) this.updateSiteContent(content);
                    if (testimonials.length > 0) this.updateTestimonials(testimonials);
                } catch (e) {
                    console.log('No CMS data found, using defaults');
                }
            }

            updateGalleries(galleryData) {
                try {
                    const categoryMapping = {
                        'newborn': '.newborn-gallery .gallery-grid, #newborn .gallery-grid',
                        'oneyear': '.oneyear-gallery .gallery-grid, #oneyear .gallery-grid',
                        'chalaka': '.chalaka-gallery .gallery-grid, #chalaka .gallery-grid',
                        'batmitzvah': '.batmitzvah-gallery .gallery-grid, #batmitzvah .gallery-grid',
                        'family': '.family-gallery .gallery-grid, #family .gallery-grid',
                        'albums': '.albums-gallery .gallery-grid, #albums .gallery-grid, #albums .album-row'
                    };

                    Object.keys(galleryData).forEach(category => {
                        const selectors = categoryMapping[category];
                        if (!selectors) return;

                        const containers = document.querySelectorAll(selectors);
                        const images = galleryData[category];

                        if (!images || images.length === 0) return;

                        containers.forEach(container => {
                            if (!container) return;

                            // הסר תמונות CMS קיימות
                            const existingCMSImages = container.querySelectorAll('[data-cms-image="true"]');
                            existingCMSImages.forEach(img => img.remove());

                            // הוסף תמונות חדשות
                            images.forEach((image, index) => {
                                const galleryItem = this.createGalleryItem(image, category, index);
                                container.appendChild(galleryItem);
                            });
                        });
                    });

                    // רענן מערכת גלריה אם קיימת
                    setTimeout(() => {
                        if (typeof initMasonryGallery === 'function') {
                            initMasonryGallery();
                        }
                        if (typeof initLightbox === 'function') {
                            initLightbox();
                        }
                    }, 100);

                    console.log(`🖼️ Gallery updated: ${Object.keys(galleryData).length} categories`);
                } catch (e) {
                    console.error('Gallery update failed:', e);
                }
            }

            createGalleryItem(image, category, index) {
                try {
                    const item = document.createElement('div');
                    item.setAttribute('data-cms-image', 'true');
                    item.setAttribute('data-category', category);
                    item.setAttribute('data-index', index);

                    if (category === 'albums') {
                        item.className = 'album-item';
                        item.innerHTML = `
                            <div class="gallery-item-album" onclick="openLightbox(this)" tabindex="0" role="button" aria-label="צפה בתמונה">
                                <img src="${image.src}" alt="${image.alt || image.name}" loading="lazy" onerror="this.style.display='none'">
                                <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)" aria-label="זום">
                                    <i class="fa-solid fa-search-plus"></i>
                                </button>
                            </div>
                        `;
                    } else {
                        item.className = 'gallery-item';
                        item.innerHTML = `
                            <img src="${image.src}" alt="${image.alt || image.name}" loading="lazy" onerror="this.style.display='none'">
                            <button class="zoom-icon" onclick="event.stopPropagation(); openLightbox(this.parentElement)" aria-label="זום">
                                <i class="fa-solid fa-search-plus"></i>
                            </button>
                        `;
                    }

                    return item;
                } catch (e) {
                    console.error('Create gallery item failed:', e);
                    return document.createElement('div');
                }
            }

            updateSiteContent(contentData) {
                try {
                    // עדכון טקסט "קצת עליי"
                    if (contentData.about) {
                        const aboutSelectors = [
                            '#home .about-text-new',
                            '#home .about-text',
                            '.about-text h3',
                            '.about-content',
                            '[data-about-text]',
                            '.about-description'
                        ];

                        aboutSelectors.forEach(selector => {
                            const elements = document.querySelectorAll(selector);
                            elements.forEach(element => {
                                if (element) {
                                    element.innerHTML = contentData.about.replace(/\n/g, '<br>');
                                }
                            });
                        });
                    }

                    // עדכון תהליך העבודה - FIXED COMPATIBILITY
                    if (contentData.process) {
                        this.updateProcessSteps(contentData.process);
                    }

                    // עדכון פרטי קשר
                    if (contentData.contact) {
                        this.updateContactInfo(contentData.contact);
                    }

                    console.log('📝 Site content updated from CMS');
                } catch (e) {
                    console.error('Site content update failed:', e);
                }
            }

            // FIXED: Process steps update compatible with CMS v2.1
            updateProcessSteps(processData) {
                try {
                    const timelineItems = document.querySelectorAll('#about .timeline-item, .process-step, .timeline-step');

                    for (let i = 1; i <= 5; i++) {
                        const stepData = processData[`step${i}`];
                        const timelineItem = timelineItems[i - 1];

                        if (stepData && timelineItem) {
                            // עדכן כותרת - ENHANCED SELECTORS
                            const titleSelectors = [
                                '.process-title', 
                                '.step-title', 
                                '.timeline-title',
                                'h3', 
                                'h4',
                                '.step-number + h3',
                                '.step-content h3'
                            ];
                            
                            let titleElement = null;
                            for (const selector of titleSelectors) {
                                titleElement = timelineItem.querySelector(selector);
                                if (titleElement) break;
                            }
                            
                            if (titleElement && stepData.title) {
                                titleElement.textContent = stepData.title;
                            }

                            // עדכן תיאור - ENHANCED SELECTORS
                            const descSelectors = [
                                '.process-description', 
                                '.step-description', 
                                '.timeline-description',
                                'p',
                                '.step-content p',
                                '.description'
                            ];
                            
                            let descElement = null;
                            for (const selector of descSelectors) {
                                descElement = timelineItem.querySelector(selector);
                                if (descElement && !descElement.querySelector('h3, h4')) break;
                            }
                            
                            if (descElement && stepData.description) {
                                descElement.textContent = stepData.description;
                            }
                        }
                    }
                } catch (e) {
                    console.error('Process steps update failed:', e);
                }
            }

            updateContactInfo(contactData) {
                try {
                    // עדכון שם
                    if (contactData.name) {
                        const nameElements = document.querySelectorAll('.contact-name, .photographer-name, [data-contact-name]');
                        nameElements.forEach(el => {
                            if (el) el.textContent = contactData.name;
                        });
                    }

                    // עדכון תפקיד
                    if (contactData.title) {
                        const titleElements = document.querySelectorAll('.contact-title, .photographer-title, [data-contact-title]');
                        titleElements.forEach(el => {
                            if (el) el.textContent = contactData.title;
                        });
                    }

                    // עדכון טלפון
                    if (contactData.phone) {
                        const phoneElements = document.querySelectorAll('[data-phone], .phone-number');
                        phoneElements.forEach(el => {
                            if (el) el.textContent = contactData.phone;
                        });

                        // עדכון לינקי טלפון
                        const phoneLinks = document.querySelectorAll('a[href^="tel:"], .phone-btn');
                        phoneLinks.forEach(link => {
                            if (link.tagName === 'A') {
                                link.href = `tel:${contactData.phone.replace(/\D/g, '')}`;
                            } else {
                                link.onclick = () => window.open(`tel:${contactData.phone.replace(/\D/g, '')}`);
                            }
                        });
                    }

                    // עדכון אימייל
                    if (contactData.email) {
                        const emailElements = document.querySelectorAll('[data-email], .email-address');
                        emailElements.forEach(el => {
                            if (el) el.textContent = contactData.email;
                        });

                        // עדכון לינקי אימייל
                        const emailLinks = document.querySelectorAll('a[href^="mailto:"], .email-btn');
                        emailLinks.forEach(link => {
                            if (link.tagName === 'A') {
                                link.href = `mailto:${contactData.email}`;
                            } else {
                                link.onclick = () => window.open(`mailto:${contactData.email}`);
                            }
                        });
                    }

                    // עדכון כתובת/אזור שירות
                    if (contactData.address) {
                        const addressElements = document.querySelectorAll('[data-address], .service-area, .contact-address');
                        addressElements.forEach(el => {
                            if (el) el.textContent = contactData.address;
                        });
                    }
                } catch (e) {
                    console.error('Contact info update failed:', e);
                }
            }

            updateTestimonials(testimonialsData) {
                try {
                    const testimonialsContainers = document.querySelectorAll(
                        '#testimonials .testimonials-grid, #home .testimonials-grid, .testimonials-container'
                    );

                    testimonialsContainers.forEach(container => {
                        if (!container) return;

                        // הסר המלצות CMS קיימות
                        const existingCMSTestimonials = container.querySelectorAll('[data-cms-testimonial="true"]');
                        existingCMSTestimonials.forEach(testimonial => testimonial.remove());

                        // הוסף המלצות חדשות
                        testimonialsData.forEach((testimonial, index) => {
                            const testimonialCard = this.createTestimonialCard(testimonial, index);
                            container.appendChild(testimonialCard);
                        });
                    });

                    console.log(`⭐ Testimonials updated: ${testimonialsData.length} testimonials`);
                } catch (e) {
                    console.error('Testimonials update failed:', e);
                }
            }

            createTestimonialCard(testimonial, index) {
                try {
                    const card = document.createElement('div');
                    card.className = 'testimonial-card';
                    card.setAttribute('data-cms-testimonial', 'true');
                    card.setAttribute('data-index', index);

                    card.innerHTML = `
                        <div class="card-inner">
                            <div class="card-front">
                                <div style="width: 100%; height: 100%; background: linear-gradient(45deg, #F3C9C1, #423D4A);">
                                    <img src="${testimonial.image}" alt="תמונת המלצה" style="width: 100%; height: 100%; object-fit: cover;" loading="lazy" onerror="this.style.display='none'">
                                </div>
                            </div>
                            <div class="card-back">
                                <blockquote>"${testimonial.text}"</blockquote>
                                <cite>- ${testimonial.author}</cite>
                            </div>
                        </div>
                    `;

                    return card;
                } catch (e) {
                    console.error('Create testimonial card failed:', e);
                    return document.createElement('div');
                }
            }

            setupMessageListeners() {
                try {
                    window.addEventListener('message', (event) => {
                        if (!event.data || !event.data.type) return;

                        try {
                            switch (event.data.type) {
                                case 'cms_update':
                                    this.handleCMSUpdate(event);
                                    break;
                                case 'text_update':
                                    this.updateSiteContent(event.data);
                                    break;
                                case 'website_request':
                                    this.handleWebsiteRequest(event);
                                    break;
                            }
                        } catch (e) {
                            console.error('Message handling error:', e);
                        }
                    });
                } catch (e) {
                    console.error('Message listeners setup failed:', e);
                }
            }

            handleWebsiteRequest(event) {
                try {
                    const { action } = event.data;
                    let responseData = null;

                    switch (action) {
                        case 'get_analytics':
                            responseData = window.siteAnalytics ? window.siteAnalytics.getStats() : {};
                            break;
                        case 'ping':
                            responseData = { status: 'online', timestamp: Date.now() };
                            break;
                        default:
                            console.log('Unknown website request:', action);
                            return;
                    }

                    // שלח תגובה חזרה ל-CMS - COMPATIBLE WITH FIXED CMS
                    if (event.source && !event.source.closed) {
                        event.source.postMessage({
                            type: 'website_response',
                            action: action,
                            data: responseData
                        }, '*');
                    }
                } catch (e) {
                    console.error('Website request handling error:', e);
                }
            }

            handleCMSUpdate(event) {
                try {
                    const { action, data } = event.data;

                    switch (action) {
                        case 'full_sync':
                            if (data.gallery) this.updateGalleries(data.gallery);
                            if (data.content) this.updateSiteContent(data.content);
                            if (data.testimonials) this.updateTestimonials(data.testimonials);
                            break;
                        case 'gallery_update':
                            this.updateGalleries(data);
                            break;
                        case 'content_update':
                            this.updateSiteContent(data);
                            break;
                        case 'testimonials_update':
                            this.updateTestimonials(data);
                            break;
                    }

                    // שלח אישור חזרה ל-CMS - ENHANCED ERROR HANDLING
                    if (event.source && !event.source.closed) {
                        event.source.postMessage({
                            type: 'website_response',
                            status: 'success',
                            message: 'Content updated successfully',
                            timestamp: Date.now()
                        }, '*');
                    }

                    console.log(`✅ CMS update applied: ${action}`);
                } catch (e) {
                    console.error('CMS update error:', e);
                    
                    // שלח הודעת שגיאה חזרה ל-CMS
                    if (event.source && !event.source.closed) {
                        event.source.postMessage({
                            type: 'website_response',
                            status: 'error',
                            message: e.message,
                            timestamp: Date.now()
                        }, '*');
                    }
                }
            }
        }
        // ============================================
        // פונקציות עזר גלובליות משופרות - FIXED
        // ============================================

        // FIXED: פונקציה לפתיחת CMS עם זיהוי נתיב אוטומטי
        function openCMS() {
            try {
                // FIXED: נתיב נכון לפי מבנה התיקיות החדש
                const possiblePaths = [
                    './cms/admin.html',      // ברירת מחדל - נתיב נכון
                    './admin/admin.html',    // נתיב חלופי
                    '../cms/admin.html',     // אם בתת-תיקייה
                    './admin.html'           // אם באותה תיקייה
                ];

                let cmsUrl = possiblePaths[0]; // ברירת מחדל נכונה

                // נסה לזהות את הנתיב הנכון לפי מבנה התיקיות
                if (window.location.pathname.includes('/admin/')) {
                    cmsUrl = './admin.html';
                } else if (window.location.pathname === '/' || window.location.pathname.endsWith('index.html')) {
                    cmsUrl = './cms/admin.html'; // נתיב נכון
                }

                window.cmsWindow = window.open(cmsUrl, 'cms', 'width=1400,height=900,scrollbars=yes,resizable=yes,location=no,menubar=no,status=no,toolbar=no');

                if (window.cmsWindow) {
                    console.log('🚀 CMS opened at:', cmsUrl);
                    
                    // שלח ping ל-CMS כשהוא נטען - ENHANCED
                    setTimeout(() => {
                        if (window.cmsWindow && !window.cmsWindow.closed) {
                            window.cmsWindow.postMessage({
                                type: 'website_ping',
                                data: { 
                                    url: window.location.href,
                                    timestamp: Date.now(),
                                    analytics: window.siteAnalytics ? window.siteAnalytics.getStats() : {},
                                    version: '2.1_fixed'
                                }
                            }, '*');
                        }
                    }, 2000);
                } else {
                    alert('לא ניתן לפתוח את ה-CMS. אנא בדק חסימת פופאפים.');
                    console.warn('Failed to open CMS - popup blocked?');
                }
            } catch (e) {
                console.error('Open CMS failed:', e);
                alert('שגיאה בפתיחת ה-CMS');
            }
        }

        // פונקציות לגישה לנתוני אנליטיקס מקווים ובטוחים - ENHANCED
        function getPageViews() {
            try {
                return window.siteAnalytics ? window.siteAnalytics.getStats().totalPageViews : 0;
            } catch (e) {
                console.error('Get page views failed:', e);
                return 0;
            }
        }

        function getUniqueVisitors() {
            try {
                return window.siteAnalytics ? window.siteAnalytics.getStats().uniqueVisitors : 0;
            } catch (e) {
                console.error('Get unique visitors failed:', e);
                return 0;
            }
        }

        function getCurrentVisitors() {
            try {
                return window.siteAnalytics ? window.siteAnalytics.getStats().activeSessions : 0;
            } catch (e) {
                console.error('Get current visitors failed:', e);
                return 0;
            }
        }

        function getTodayViews() {
            try {
                return window.siteAnalytics ? window.siteAnalytics.getStats().todayPageViews : 0;
            } catch (e) {
                console.error('Get today views failed:', e);
                return 0;
            }
        }

        function getAnalyticsReport() {
            try {
                return window.siteAnalytics ? window.siteAnalytics.getStats() : {};
            } catch (e) {
                console.error('Get analytics report failed:', e);
                return {};
            }
        }

        function getDetailedAnalytics() {
            try {
                if (!window.siteAnalytics) return {};
                
                const stats = window.siteAnalytics.getStats();
                const rawData = window.siteAnalytics.data;
                
                return {
                    ...stats,
                    sessions: rawData.sessions || [],
                    dailyBreakdown: rawData.dailyStats || {},
                    averageScrollDepth: rawData.sessions.length > 0 ? 
                        Math.round(rawData.sessions.reduce((sum, s) => sum + (s.scrollDepth || 0), 0) / rawData.sessions.length) : 0,
                    averageInteractions: rawData.sessions.length > 0 ?
                        Math.round(rawData.sessions.reduce((sum, s) => sum + (s.interactions || 0), 0) / rawData.sessions.length) : 0,
                    topReferrers: this.getTopReferrers(rawData.sessions),
                    deviceStats: this.getDeviceStats(rawData.sessions)
                };
            } catch (e) {
                console.error('Get detailed analytics failed:', e);
                return {};
            }
        }

        function getTopReferrers(sessions) {
            try {
                const referrers = {};
                sessions.forEach(session => {
                    const ref = session.referrer || 'direct';
                    referrers[ref] = (referrers[ref] || 0) + 1;
                });
                
                return Object.entries(referrers)
                    .sort(([,a], [,b]) => b - a)
                    .slice(0, 10)
                    .map(([referrer, count]) => ({ referrer, count }));
            } catch (e) {
                console.error('Get top referrers failed:', e);
                return [];
            }
        }

        function getDeviceStats(sessions) {
            try {
                const devices = { mobile: 0, tablet: 0, desktop: 0 };
                sessions.forEach(session => {
                    const ua = session.userAgent || '';
                    if (/Mobile|Android|iPhone/i.test(ua)) {
                        devices.mobile++;
                    } else if (/Tablet|iPad/i.test(ua)) {
                        devices.tablet++;
                    } else {
                        devices.desktop++;
                    }
                });
                return devices;
            } catch (e) {
                console.error('Get device stats failed:', e);
                return { mobile: 0, tablet: 0, desktop: 0 };
            }
        }

        // ENHANCED: פונקציה לרענון נתוני CMS עם אישור
        function refreshCMSData() {
            try {
                if (window.cmsIntegration) {
                    window.cmsIntegration.loadAllCMSData();
                    console.log('🔄 CMS data refreshed manually');
                    
                    // הצג הודעה למשתמש
                    if (typeof showNotification === 'function') {
                        showNotification('נתוני CMS רוענו בהצלחה', 'success');
                    }
                } else {
                    console.warn('CMS Integration not available');
                }
            } catch (e) {
                console.error('Refresh CMS data failed:', e);
            }
        }

        // פונקציה בטוחה לאיפוס אנליטיקס (פיתוח בלבד) - ENHANCED
        function resetAnalytics() {
            try {
                if (window.location.hostname === 'localhost' || window.location.hostname === '127.0.0.1') {
                    if (window.siteAnalytics && confirm('האם אתה בטוח שברצונך לאפס את כל נתוני האנליטיקס? (פיתוח בלבד)')) {
                        window.siteAnalytics.reset();
                    }
                } else {
                    console.warn('Reset analytics is only available in development mode');
                }
            } catch (e) {
                console.error('Reset analytics failed:', e);
            }
        }

        // פונקציה לייצוא נתוני אנליטיקס - ENHANCED
        function exportAnalytics() {
            try {
                const analytics = getDetailedAnalytics();
                const dataStr = JSON.stringify(analytics, null, 2);
                const dataBlob = new Blob([dataStr], {type: 'application/json'});
                
                const url = URL.createObjectURL(dataBlob);
                const link = document.createElement('a');
                link.href = url;
                link.download = `analytics_export_${new Date().toISOString().split('T')[0]}.json`;
                link.click();
                
                URL.revokeObjectURL(url);
                console.log('📊 Analytics data exported successfully');
            } catch (e) {
                console.error('Failed to export analytics:', e);
            }
        }

        // FIXED: פונקציה לבדיקת חיבור CMS
        function checkCMSConnection() {
            try {
                if (window.cmsWindow && !window.cmsWindow.closed) {
                    window.cmsWindow.postMessage({
                        type: 'ping',
                        timestamp: Date.now()
                    }, '*');
                    console.log('🔍 Ping sent to CMS');
                    return true;
                } else {
                    console.log('❌ CMS is not connected');
                    return false;
                }
            } catch (e) {
                console.error('Check CMS connection failed:', e);
                return false;
            }
        }

        // פונקציה לשליחת נתונים ידני ל-CMS - ENHANCED
        function sendAnalyticsToCMS() {
            try {
                if (checkCMSConnection() && window.siteAnalytics) {
                    window.cmsWindow.postMessage({
                        type: 'analytics_update',
                        data: window.siteAnalytics.getStats()
                    }, '*');
                    console.log('📊 Analytics manually sent to CMS');
                }
            } catch (e) {
                console.error('Send analytics to CMS failed:', e);
            }
        }

        // ENHANCED: פונקציה לבדיקת תקינות נתונים
        function validateData() {
            try {
                const checks = {
                    analytics: !!window.siteAnalytics,
                    cmsIntegration: !!window.cmsIntegration,
                    localStorage: typeof Storage !== 'undefined',
                    analyticsData: !!localStorage.getItem('website_analytics_data'),
                    galleryData: !!localStorage.getItem('website_gallery_data'),
                    contentData: !!localStorage.getItem('website_content_data')
                };

                const failedChecks = Object.keys(checks).filter(key => !checks[key]);
                
                if (failedChecks.length === 0) {
                    console.log('✅ All data validation checks passed');
                } else {
                    console.warn('⚠️ Data validation warnings:', failedChecks);
                }

                return { checks, failedChecks, isHealthy: failedChecks.length === 0 };
            } catch (e) {
                console.error('Data validation failed:', e);
                return { checks: {}, failedChecks: ['validation_error'], isHealthy: false };
            }
        }

        // ============================================
        // אתחול המערכת המשופר - FIXED
        // ============================================

        // משתנים גלובליים
        let siteAnalytics;
        let cmsIntegration;
        let systemReady = false;

        // FIXED: פונקציה לאתחול מקיף
        function initializeSystem() {
            try {
                console.log('🚀 Initializing Website Analytics & CMS Integration v2.1 - FIXED...');

                // אתחול מערכת אנליטיקס
                siteAnalytics = new RealWebsiteAnalytics();
                window.siteAnalytics = siteAnalytics;
                console.log('📊 Analytics system ready');

                // אתחול אינטגרציה עם CMS
                cmsIntegration = new CMSIntegration();
                window.cmsIntegration = cmsIntegration;
                console.log('🔗 CMS integration ready');

                // טעינה ראשונית של נתוני CMS
                setTimeout(() => {
                    cmsIntegration.loadAllCMSData();
                    console.log('📦 Initial CMS data loaded');
                }, 1000);

                // בדיקת תקינות
                setTimeout(() => {
                    const validation = validateData();
                    if (validation.isHealthy) {
                        console.log('✅ System health check passed');
                    } else {
                        console.warn('⚠️ System health check warnings:', validation.failedChecks);
                    }
                }, 2000);

                systemReady = true;
                console.log('🌟 Website fully initialized with real analytics and CMS integration v2.1');
                console.log('📊 Current analytics:', siteAnalytics.getStats());

                // שלח אירוע מותאם אישית
                window.dispatchEvent(new CustomEvent('websiteSystemReady', {
                    detail: { 
                        analytics: siteAnalytics.getStats(),
                        timestamp: Date.now(),
                        version: '2.1_fixed'
                    }
                }));

            } catch (error) {
                console.error('❌ System initialization failed:', error);
                systemReady = false;
            }
        }

        // ============================================
        // חשיפת פונקציות למערכת הגלובלית - ENHANCED
        // ============================================

        // פונקציות בסיסיות
        window.openCMS = openCMS;
        window.getPageViews = getPageViews;
        window.getUniqueVisitors = getUniqueVisitors;
        window.getCurrentVisitors = getCurrentVisitors;
        window.getTodayViews = getTodayViews;
        window.getAnalyticsReport = getAnalyticsReport;
        window.refreshCMSData = refreshCMSData;

        // פונקציות מתקדמות
        window.getDetailedAnalytics = getDetailedAnalytics;
        window.exportAnalytics = exportAnalytics;
        window.checkCMSConnection = checkCMSConnection;
        window.sendAnalyticsToCMS = sendAnalyticsToCMS;
        window.validateData = validateData;

        // פונקציות פיתוח (רק במידה ומותר)
        if (window.location.hostname === 'localhost' || window.location.hostname === '127.0.0.1') {
            window.resetAnalytics = resetAnalytics;
            window.debugAnalytics = () => console.table(getDetailedAnalytics());
            console.log('🔧 Development functions enabled');
        }

        // ============================================
        // אתחול כאשר הדף נטען - ENHANCED
        // ============================================

        if (document.readyState === 'loading') {
            document.addEventListener('DOMContentLoaded', initializeSystem);
        } else {
            initializeSystem();
        }

        // שמירת נתונים לפני יציאה מהדף - ENHANCED
        window.addEventListener('beforeunload', function() {
            try {
                if (siteAnalytics) {
                    siteAnalytics.endSession();
                    console.log('💾 Session data saved before page unload');
                }
            } catch (e) {
                console.error('Before unload failed:', e);
            }
        });

        // ENHANCED: טיפול בשגיאות גלובליות
        window.addEventListener('error', function(event) {
            console.error('🚨 Global error caught:', event.error);
            // שלח לאנליטיקס אם מתאים
            try {
                if (siteAnalytics) {
                    siteAnalytics.interactions++; // ספירת שגיאות כאינטראקציות
                }
            } catch (e) {
                console.error('Error handling failed:', e);
            }
        });

        // ============================================
        // Export למודולים אם נדרש
        // ============================================

        if (typeof module !== 'undefined' && module.exports) {
            module.exports = {
                RealWebsiteAnalytics,
                CMSIntegration,
                getPageViews,
                getUniqueVisitors,
                getCurrentVisitors,
                getTodayViews,
                getAnalyticsReport,
                getDetailedAnalytics,
                validateData
            };
        }

        // ============================================
        // הודעה סופית למפתח - UPDATED
        // ============================================

        console.log(`
🎯 אפרת אדלר - Website Analytics & CMS Integration v2.1 - FIXED
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✅ Real-time Analytics System - FIXED
✅ CMS Integration with postMessage - ENHANCED  
✅ Secure data handling
✅ Auto-sync every 30 seconds  
✅ Hebrew RTL support
✅ Production-ready error handling - ENHANCED
✅ Performance optimized
✅ Privacy compliant
✅ Date.toISOString() compatibility - FIXED
✅ Process steps update - FIXED
✅ CMS path detection - FIXED

📱 Quick Commands:
• openCMS() - פתח פאנל ניהול (נתיב נכון)
• getAnalyticsReport() - דוח מלא
• refreshCMSData() - רענן תוכן
• validateData() - בדוק תקינות
• exportAnalytics() - ייצא נתונים

🔧 CRITICAL FIXES APPLIED:
• CMS path: ./cms/admin.html (נכון)
• Process selectors: תואם ל-CMS v2.1
• Analytics Date handling: fallback מוגדר
• Error handling: מקיף לכל פונקציה
• Communication: תואם ל-postMessage החדש

🚀 מוכן לפרודקשן עם CMS v2.1!
        `);

    </script>
</body>
</html>fb-1b820f8d96af)
![chalake_25](https://github.com/user-attachments/assets/483ec820-3f62-440f-981f-07fe17709370)
![chalake_24](https://github.com/user-attachments/assets/861ee117-0640-4812-a468-0335d4b76970)
![chalake_23](https://github.com/user-attachments/assets/f6a26142-61c1-4f01-b039-54041878a688)
![chalake_22](https://github.com/user-attachments/assets/35558a89-ac5d-4141-899f-11a16822fe06)
![chalake_21](https://github.com/user-attachments/assets/7eae66b2-7747-4e4d-ad86-34403b9b908f)
![chalake_20](https://github.com/user-attachments/assets/86ad27bd-2a24-4856-9f46-f98ea99d2fcc)
![chalake_19](https://github.com/user-attachments/assets/9d34516d-6ed5-435c-bb72-a3d55eb95cfa)
![chalake_18](https://github.com/user-attachments/assets/663b8bb2-5d84-43aa-8209-9c7d2c6230fa)
![chalake_17](https://github.com/user-attachments/assets/2ef60bf8-102a-4a53-b84f-00d8ffa048fb)
![chalake_16](https://github.com/user-attachments/assets/067d97ca-5d7c-44a9-a491-17e9ed1f68a0)
![chalake_15](https://github.com/user-attachments/assets/dd960b12-3411-4f0a-8f80-7c1b308d0ad6)
![chalake_14](https://github.com/user-attachments/assets/9d313c66-d003-4720-8939-9a1da40b6c45)
![chalake_13](https://github.com/user-attachments/assets/fc4c89b9-0c96-40ae-9b5e-22dd101bf195)
![chalake_12](https://github.com/user-attachments/assets/ca44f289-9b5b-4947-87da-67476f724592)
![chalake_11](https://github.com/user-attachments/assets/72c1475e-1c48-40df-a8ba-aa620a02b722)
![chalake_10](https://github.com/user-attachments/assets/fca98c92-b9a1-45cc-9f26-67d5ed78a1cd)
![chalake_9](https://github.com/user-attachments/assets/858142f0-1fe7-4841-ae64-545b52dc475a)
![chalake_8](https://github.com/user-attachments/assets/ea736286-519e-4c5e-8a9d-9fbd15d2a990)
![chalake_7](https://github.com/user-attachments/assets/fbb3a5a7-b368-407b-98b0-be17a77d71c4)
![chalake_6](https://github.com/user-attachments/assets/d7f225c9-6409-4fc6-b3ff-d0131c4def96)
![chalake_5](https://github.com/user-attachments/assets/c5e55032-e7fd-46d8-b039-daf3ac0c66d1)
![chalake_4](https://github.com/user-attachments/assets/63428670-e6db-4baa-ae34-6290c2ef0754)
![chalake_3](https://github.com/user-attachments/assets/62a024a5-7b32-475c-a8dd-cf077de01efa)
![chalake_2](https://github.com/user-attachments/assets/8af05255-ac85-4fff-87ad-6ff1a001e404)
![chalake_1](https://github.com/user-attachments/assets/7223fe69-5dbc-4f35-9297-13c9d9e0058c)
![batmitzva1](https://github.com/user-attachments/assets/caceb814-9fd2-4b87-a62a-d91cd11518a4)
![batmitzva_15](https://github.com/user-attachments/assets/d5b0cc6a-4b29-48af-9dcc-e5e4484ea3c4)
![batmitzva_14](https://github.com/user-attachments/assets/176c55fa-c889-4ec7-9d29-8c4e27e8449b)
![batmitzva_13](https://github.com/user-attachments/assets/b2824bd5-edc5-4b27-a588-5ac7670177c3)
![batmitzva_12](https://github.com/user-attachments/assets/efa2179b-34b1-4e7d-8ecf-68c20726826a)
![batmitzva_10](https://github.com/user-attachments/assets/ab0b6023-5b68-4b67-a727-e57ded579132)
![batmitzva_9](https://github.com/user-attachments/assets/c2f01f35-de84-46b0-b74d-b3633f122902)
![batmitzva_8](https://github.com/user-attachments/assets/85e24c30-5a47-40f5-b043-30758eaacf78)
![batmitzva_7](https://github.com/user-attachments/assets/be13a962-35bc-4b5b-89c6-9eb75040bb92)
![batmitzva_6](https://github.com/user-attachments/assets/ff8be1a1-ce19-4489-b8be-38e530abf5c4)
![batmitzva_5](https://github.com/user-attachments/assets/8ec7f892-deb6-4821-a3e0-f0c262f703cd)
![batmitzva_4](https://github.com/user-attachments/assets/42550791-9013-4f4e-9c0b-b04ba3a134d2)
![batmitzva_3](https://github.com/user-attachments/assets/c936e350-f24d-4c7d-ae81-3086461bda44)
![batmitzva_2](https://github.com/user-attachments/assets/d594eee2-13a1-4262-a9f0-f40f327754f8)
<img width="2079" height="759" alt="album_16" src="https://github.com/user-attachments/assets/d1f750e5-9a06-4af5-beaa-ecf4073361ff" />
<img width="2079" height="759" alt="album_15" src="https://github.com/user-attachments/assets/ba3961a6-7b98-4da8-862d-8045ca27ba4d" />
<img width="2079" height="759" alt="album_14" src="https://github.com/user-attachments/assets/058db3fa-8d0b-4b44-b0fa-e7da3b0caf72" />
<img width="2079" height="759" alt="album_13" src="https://github.com/user-attachments/assets/e4d50048-b0f3-40fa-97ae-6fa18c6707e5" />
<img width="2079" height="759" alt="album_12" src="https://github.com/user-attachments/assets/01e4a87f-402f-49f1-85a6-8063cb939bef" />
<img width="2079" height="759" alt="album_11" src="https://github.com/user-attachments/assets/8d37487d-96d5-498c-b1cc-70e2324bf8f2" />
<img width="2079" height="759" alt="album_10" src="https://github.com/user-attachments/assets/d526814c-ec41-4522-8896-4965e5091a49" />
<img width="2079" height="756" alt="album_9" src="https://github.com/user-attachments/assets/2f2a0e8c-54f8-4c96-8a67-b500d893760e" />
<img width="2079" height="756" alt="album_8" src="https://github.com/user-attachments/assets/3978d78b-8ac0-4779-ab34-392d41bc119c" />
<img width="2079" height="756" alt="album_7" src="https://github.com/user-attachments/assets/49076ac5-1d1e-4eb8-8b4a-aba887f5a037" />
<img width="2079" height="756" alt="album_6" src="https://github.com/user-attachments/assets/88c84bf8-44c4-4ae2-a210-81c90c275978" />
<img width="2079" height="756" alt="album_5" src="https://github.com/user-attachments/assets/1c7a697c-8414-473d-94be-5c3b7460c743" />
<img width="2079" height="756" alt="album_4" src="https://github.com/user-attachments/assets/c0f3415e-4624-4c62-afd0-9b754b8cd0c9" />
<img width="2079" height="756" alt="album_3" src="https://github.com/user-attachments/assets/2b79fdb4-cc6c-453c-9a57-7cbefe925cf7" />
<img width="2079" height="756" alt="album_2" src="https://github.com/user-attachments/assets/bb886a4e-e7cc-452f-9c09-cb8337ade254" />
<img width="2117" height="794" alt="album_1" src="https://github.com/user-attachments/assets/aeafcfde-7f16-48a6-beb1-faa74c4e17f6" />
![1year_23](https://github.com/user-attachments/assets/53bc369d-4d2a-43d7-b035-67e0c2f0e712)
![1year_22](https://github.com/user-attachments/assets/00373153-2f28-42df-80cf-f338a77ecf9f)
![1year_21](https://github.com/user-attachments/assets/fd87b84c-704a-4c04-853b-78be30ed4d6c)
![1year_20](https://github.com/user-attachments/assets/12c2d863-2bcb-438b-9828-fcda31ea76d1)
![1year_19](https://github.com/user-attachments/assets/dd0cc661-02f6-46ca-a919-a4b3d16583b1)
![1year_18](https://github.com/user-attachments/assets/8a46de33-a485-46ce-a2fe-499c86f52577)
![1year_17](https://github.com/user-attachments/assets/f009cc53-d380-41fb-a9e9-8e7f3a29029d)
![1year_16](https://github.com/user-attachments/assets/a7715c8b-f623-4644-823a-931333cd9f3a)
![1year_15](https://github.com/user-attachments/assets/c0648cea-07cd-4a7e-a448-ad64bfa6b784)
![1year_14](https://github.com/user-attachments/assets/a7ea12e8-9425-43a3-b086-7c3831db599e)
![1year_13](https://github.com/user-attachments/assets/25dc9b47-70c6-431d-8e37-4f0310426314)
![1year_12](https://github.com/user-attachments/assets/df2b49d4-8b64-4233-bcfa-8f9f84ddfba3)
![1year_11](https://github.com/user-attachments/assets/7f8441e0-f33c-43bc-92a5-e5ed3adf519a)
![1year_10](https://github.com/user-attachments/assets/578a64d0-9deb-4038-b258-1251bbcf9251)
![1year_9](https://github.com/user-attachments/assets/3ba4dfcd-6e04-460a-98f8-497571b722e4)
![1year_8](https://github.com/user-attachments/assets/b73e2a5c-756e-4295-96db-08c8debc3ccd)
![1year_7](https://github.com/user-attachments/assets/17c73065-ba94-4c2a-a716-c2fb75b79ae0)
![1year_6](https://github.com/user-attachments/assets/de599f07-b45e-4a84-b4d1-5c2299835dee)
![1year_5](https://github.com/user-attachments/assets/dc0afb03-2788-49f7-afbd-d72529293acf)
![1year_4](https://github.com/user-attachments/assets/d70282ae-8791-45d3-a1d5-68fd0e7bf3b7)
