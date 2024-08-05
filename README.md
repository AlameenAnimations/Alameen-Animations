abdulazeez-alameen-portfolio/
├── assets/
│   ├── images/
│   │   ├── hero-bg.jpg         (Place your hero background image here)
│   │   ├── profile-picture.jpg  (Place your profile picture here)
│   │   └── other-images.jpg     (Place any other images here)
│   ├── css/
│   │   └──  <style>
        body {
    font-family: 'Roboto', sans-serif;
    margin: 0;
    padding: 0;
    color: #333;
    line-height: 1.6;
    background: #e9f5f9;
}

header {
    background: #34495e;
    color: #fff;
    padding: 20px 0;
    text-align: center;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

header h1 {
    margin: 0;
    font-size: 3em;
    font-weight: 700;
}

header p {
    margin: 5px 0 0;
    font-size: 1.2em;
}

header nav {
    margin-top: 20px;
}

header nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
    gap: 20px;
}

header nav ul li {
    display: inline;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: 500;
    transition: color 0.3s;
}

header nav ul li a:hover {
    color: #1abc9c;
}

#hero {
    background: url('hero-bg.jpg') no-repeat center center/cover;
    color: #fff;
    text-align: center;
    padding: 150px 20px;
    background-attachment: fixed;
    position: relative;
}

#hero::after {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: rgba(0, 0, 0, 0.4);
}

.hero-content {
    position: relative;
    z-index: 2;
}

.hero-content h2 {
    font-size: 3.5em;
    margin-bottom: 20px;
    animation: fadeIn 2s ease-in-out;
}

.hero-content p {
    font-size: 1.4em;
    margin: 20px 0;
    max-width: 600px;
    margin: 0 auto;
    animation: fadeIn 2s ease-in-out 0.5s;
}

.btn-primary {
    background: #1abc9c;
    color: #fff;
    padding: 15px 30px;
    text-decoration: none;
    border-radius: 30px;
    font-weight: bold;
    transition: background 0.3s, transform 0.3s;
    display: inline-block;
    margin-top: 20px;
}

.btn-primary:hover {
    background: #16a085;
    transform: scale(1.05);
}

#blog {
    margin-bottom: 80px;
    padding: 40px;
    background: #fff;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
}

#blog h2 {
    font-size: 4em; /* Increased font size for a larger heading */
    margin-bottom: 40px;
    color: #001f3f; /* Navy blue color */
    font-weight: 700;
    text-align: center; /* Ensures the heading is centered */
}

.blog-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
}

.blog-item {
    flex: 1 1 calc(50% - 20px);
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    overflow: hidden;
    background: #fff;
    position: relative;
    margin-bottom: 20px;
    transition: transform 0.3s, box-shadow 0.3s;
    padding: 20px;
    text-align: center;
}

.blog-item img {
    width: 100%;
    height: auto;
    border-bottom: 1px solid #ddd;
    margin-bottom: 15px;
}

.blog-item .text {
    padding: 10px 0;
}

.blog-item h3 {
    font-size: 1.8em;
    margin: 0;
}

.blog-item p {
    font-size: 1.2em;
    margin: 10px 0 20px;
}

.blog-item:hover {
    transform: scale(1.05);
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
}

@media (max-width: 768px) {
    .blog-item {
        flex: 1 1 100%;
    }
}

.container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

section {
    margin-bottom: 80px;
    padding: 40px;
    background: #fff;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    position: relative;
    overflow: hidden;
}

#about {
            margin-bottom: 80px;
            padding: 60px 40px;
            background: #fff;
            border-radius: 15px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        #about h2 {
            font-size: 2.8em;
            font-weight: 700;
            margin-bottom: 20px;
            color: #2c3e50;
            position: relative;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        #about h2::after {
            content: '';
            position: absolute;
            left: 50%;
            transform: translateX(-50%);
            bottom: -15px;
            width: 120px;
            height: 4px;
            background: #1abc9c;
            border-radius: 2px;
        }

        #about p {
            font-size: 1.2em;
            font-weight: 500;
            margin: 20px 0;
            color: #7f8c8d;
            line-height: 1.8;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
        }

        #profile-picture {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            margin-bottom: 20px;
            background: #ddd; /* Placeholder background */
            display: block;
            margin-left: auto;
            margin-right: auto;
            object-fit: cover;
        }

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
}

#portfolio {
    margin-bottom: 80px;
    padding: 40px;
    background: #fff;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    position: relative;
    overflow: hidden;
    text-align: center;
}

#portfolio h2 {
    font-size: 3em; /* Adjusted for a larger size */
    margin-bottom: 40px;
    color: #333;
    font-weight: 700;
}

.portfolio-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 30px;
    justify-content: center;
}

.portfolio-item {
    flex: 1 1 calc(33.333% - 30px);
    border-radius: 20px;
    overflow: hidden;
    background: #fff;
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.15);
    transition: transform 0.3s, box-shadow 0.3s;
    position: relative;
    border: 1px solid #ddd;
    cursor: pointer;
}

.portfolio-item:hover {
    transform: scale(1.05);
    box-shadow: 0 20px 40px rgba(0, 0, 0, 0.2);
}

.portfolio-item .image-wrapper {
    position: relative;
    padding-bottom: 56.25%;
    height: 0;
    overflow: hidden;
    background: #000;
    border-radius: 20px 20px 0 0;
    transition: opacity 0.3s;
}

.portfolio-item .image-wrapper img {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.portfolio-item .text {
    padding: 20px;
    text-align: center;
    background: #f9f9f9;
}

.portfolio-item h3 {
    font-size: 1.8em;
    margin: 0 0 10px;
    color: #333;
    font-weight: 700;
}

.portfolio-item p {
    font-size: 1.1em;
    margin: 10px 0;
    color: #666;
}

.overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.7);
    color: #fff;
    opacity: 0;
    transition: opacity 0.3s;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 20px;
    box-sizing: border-box;
}

.portfolio-item:hover .overlay {
    opacity: 1;
}

.text {
    max-width: 90%;
}

.text h3 {
    margin: 0;
    font-size: 1.6em;
}

.text p {
    margin: 10px 0 0;
    font-size: 1.1em;
}

.btn-primary {
    background: #1abc9c;
    color: #fff;
    padding: 12px 25px;
    text-decoration: none;
    border-radius: 30px;
    font-weight: bold;
    transition: background 0.3s, transform 0.3s;
    display: inline-block;
}

.btn-primary:hover {
    background: #16a085;
    transform: scale(1.05);
}

#services {
    margin-bottom: 80px;
    padding: 60px 40px;
    background: linear-gradient(135deg, #f3f4f6, #e2e8f0);
    border-radius: 12px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    text-align: center;
}

#services h2 {
    font-size: 3em;
    margin-bottom: 50px;
    color: #2c3e50;
    font-weight: 800;
    text-align: center;
    text-transform: uppercase;
    letter-spacing: 1.5px;
}

.services-grid {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
    justify-content: center;
}

.service-item {
    flex: 1 1 calc(50% - 20px);
    background: #ffffff;
    padding: 30px;
    border-radius: 12px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s, box-shadow 0.3s;
    overflow: hidden;
    position: relative;
}

.service-item:hover {
    transform: translateY(-10px);
    box-shadow: 0 8px 24px rgba(0, 0, 0, 0.2);
}

.service-item h3 {
    margin-top: 0;
    margin-bottom: 20px;
    color: #1abc9c;
    font-size: 1.5em;
    font-weight: 700;
}

.service-item p {
    color: #666;
    font-size: 1em;
    line-height: 1.6;
}

.service-item::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: linear-gradient(45deg, rgba(0, 0, 0, 0.05), rgba(0, 0, 0, 0.1));
    opacity: 0;
    transition: opacity 0.3s;
    z-index: 0;
}

.service-item:hover::before {
    opacity: 1;
}

.service-item-content {
    position: relative;
    z-index: 1;
}

body {
    font-family: 'Roboto', sans-serif;
    margin: 0;
    padding: 0;
    background: #f5f5f5;
    color: #333;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
}

#contact {
    padding: 60px 40px;
    background: #fff;
    border-radius: 12px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    text-align: center;
    margin-bottom: 80px;
}

#contact h2 {
    font-size: 3.5em;  /* Increased font size */
    margin-bottom: 20px;
    color: #2c3e50;
    font-weight: 700;
    text-transform: uppercase;
    letter-spacing: 1.5px;
    position: relative;
    text-align: center;  /* Center the heading */
}

#contact h2::after {
    content: '';
    width: 100px;
    height: 4px;
    background: #1abc9c;
    display: block;
    margin: 20px auto 0;
    border-radius: 2px;
}

#contact p {
    font-size: 1.2em;
    color: #7f8c8d;
    line-height: 1.8;
    margin: 20px 0;
    max-width: 800px;
    margin-left: auto;
    margin-right: auto;
}

.contact-buttons {
    display: flex;
    flex-direction: column;
    gap: 15px;
    align-items: center;
    margin-top: 20px;
}

.btn-contact {
    background: #1abc9c;
    color: #fff;
    padding: 12px 25px;
    text-decoration: none;
    border-radius: 8px;
    font-weight: bold;
    transition: background 0.3s, transform 0.3s;
    display: block;
    width: 200px;
    text-align: center;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.btn-contact:hover {
    background: #16a085;
    transform: scale(1.05);
}

    .container {
        max-width: 1200px; /* Adjust according to the width of other sections */
        margin: 0 auto;
        padding: 0 20px;
    }

    #showreel {
        margin-bottom: 80px;
        padding: 60px 20px;
        background: linear-gradient(to right, #ff7e5f, #feb47b);
        border-radius: 12px;
        box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
        position: relative;
        overflow: hidden;
        text-align: center;
        color: #fff;
    }

    #showreel h2 {
        font-size: 3em;
        margin-bottom: 20px;
        color: #fff;
        position: relative;
    }

    #showreel .showreel-content {
        max-width: 900px;
        margin: 0 auto;
        animation: fadeIn 2s ease-in-out;
    }

    #showreel .video-wrapper {
        position: relative;
        padding-bottom: 56.25%;
        height: 0;
        overflow: hidden;
        max-width: 100%;
        background: #000;
        border-radius: 12px;
        box-shadow: 0 6px 12px rgba(0, 0, 0, 0.3);
        margin-bottom: 30px;
        transition: transform 0.3s;
    }

    #showreel .video-wrapper:hover {
        transform: scale(1.02);
    }

    #showreel .video-wrapper iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        border: 0;
        border-radius: 12px;
    }

    #showreel .showreel-description {
        font-size: 1.4em;
        color: #fff;
        margin-bottom: 30px;
        animation: fadeIn 2s ease-in-out 0.5s;
    }

    #showreel .btn-primary {
        background: #fff;
        color: #ff7e5f;
        padding: 15px 30px;
        text-decoration: none;
        border-radius: 30px;
        font-weight: bold;
        transition: background 0.3s, transform 0.3s;
        display: inline-block;
        margin-top: 20px;
    }

    #showreel .btn-primary:hover {
        background: #f8f8f8;
        transform: scale(1.05);
    }
.video-wrapper iframe {
    border: none; /* Removes the border */
}
    @keyframes fadeIn {
        from {
            opacity: 0;
            transform: translateY(20px);
        }
        to {
            opacity: 1;
            transform: translateY(0);
        }
    }

body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background: #f5f5f5;
    color: #333;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 40px 20px;
}

#testimonials {
    margin-bottom: 60px; /* Add margin bottom to separate from other sections */
}

#testimonials h2 {
    text-align: center;
    font-size: 3em;
    margin-bottom: 50px;
    color: #333;
    position: relative;
    font-weight: bold;
}

#testimonials h2::after {
    content: '';
    width: 100px;
    height: 4px;
    background: #28a745;
    display: block;
    margin: 20px auto 0;
    border-radius: 2px;
}

.testimonials-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 30px;
    justify-content: center;
}

.testimonial-item {
    flex: 1 1 calc(50% - 30px);
    background: #fff;
    padding: 30px;
    border-radius: 15px;
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
    text-align: center;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.testimonial-item:hover {
    transform: translateY(-10px);
    box-shadow: 0 12px 24px rgba(0, 0, 0, 0.2);
}

.testimonial-item img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 20px;
    border: 3px solid #28a745;
}

.testimonial-item p {
    font-style: italic;
    color: #555;
    margin: 20px 0;
    font-size: 1.1em;
    line-height: 1.6;
}

.testimonial-item h3 {
    margin-top: 10px;
    font-weight: bold;
    font-size: 1.4em;
}

.testimonial-item h4 {
    margin-top: 5px;
    color: #28a745;
    font-size: 1.1em;
}
.cta-section {
    background: radial-gradient(circle, #fbc2eb, #a6c0fe);
    color: #fff;
    padding: 120px 20px;
    text-align: center;
    position: relative;
    overflow: hidden;
    border-radius: 20px;
    box-shadow: 0 20px 40px rgba(0, 0, 0, 0.3);
    animation: fadeIn 2s ease-in-out;
}

.cta-section::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(255, 255, 255, 0.25);
    z-index: 1;
    border-radius: 20px;
    transform: rotate(-5deg);
}

.cta-content {
    position: relative;
    z-index: 2;
    padding: 40px;
    max-width: 900px;
    margin: auto;
    background: rgba(0, 0, 0, 0.5);
    border-radius: 20px;
    box-shadow: 0 15px 30px rgba(0, 0, 0, 0.4);
    animation: slideIn 1.5s ease-in-out;
}

.cta-content h1 {
    font-size: 4em;
    margin-bottom: 20px;
    line-height: 1.2;
    font-weight: 700;
    letter-spacing: -1px;
    color: #fffae6;
    text-shadow: 3px 3px 6px rgba(0, 0, 0, 0.3);
    animation: textPopUp 1.5s ease-in-out;
}

.cta-content p {
    font-size: 1.3em;
    margin-bottom: 30px;
    line-height: 1.8;
    color: #fffae6;
    text-shadow: 1px 1px 4px rgba(0, 0, 0, 0.3);
    animation: textPopUp 2s ease-in-out;
}

.cta-button {
    display: inline-block;
    padding: 15px 40px;
    font-size: 1.2em;
    color: #fff;
    background: linear-gradient(135deg, #ff7e5f, #ffb84d);
    text-decoration: none;
    border-radius: 50px;
    box-shadow: 0 12px 30px rgba(0, 0, 0, 0.3);
    transition: all 0.4s ease;
    border: 2px solid transparent;
    font-weight: 700;
    letter-spacing: 1px;
    position: relative;
    overflow: hidden;
    animation: buttonPopUp 1s ease-in-out;
}

.cta-button::before {
    content: '';
    position: absolute;
    top: 50%;
    left: 50%;
    width: 400%;
    height: 400%;
    background: rgba(255, 255, 255, 0.4);
    transition: all 0.4s ease;
    border-radius: 50%;
    z-index: 0;
    transform: translate(-50%, -50%) scale(0);
}

.cta-button:hover::before {
    transform: translate(-50%, -50%) scale(1);
}

.cta-button:hover {
    background: linear-gradient(135deg, #ffb84d, #ff7e5f);
    transform: translateY(-6px);
    border-color: #fff;
    box-shadow: 0 16px 35px rgba(0, 0, 0, 0.4);
    color: #fff;
    z-index: 1;
}
footer {
    background: #34495e;
    color: #fff;
    text-align: center;
    padding: 20px 0;
    font-size: 0.9em;
}

footer a {
    color: #1abc9c;
    text-decoration: none;
}

footer a:hover {
    text-decoration: underline;
}
.footer-content {
    text-align: center;
    padding: 20px;
}

.social-icons {
    margin: 10px 0;
}

.social-icon {
    color: #fff;
    font-size: 1.5em;
    margin: 0 10px;
    text-decoration: none;
    transition: color 0.3s;
}

.social-icon:hover {
    color: #1abc9c;
}
@keyframes fadeIn {
    from {
        opacity: 0;
        transform: translateY(20px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

@media (max-width: 768px) {
    .portfolio-item, .blog-item, .service-item, .testimonial-item {
        flex: 1 1 100%;
    }
}
    </style>
│   ├── fonts/
│   │   ├── Roboto-Regular.ttf
│   │   ├── Roboto-Medium.ttf
│   │   └── Roboto-Bold.ttf
│   └── js/
│       └── scripts.js
├── index.html
├── about.html
├── portfolio.html
├── services.html
├── blog.html
├── contact.html
└── README.md
