<!DOCTYPE html>
<html>
<head>
    <style>
        /* Video Background Styles */
        .background-video {
            position: relative;
            width: 100%;
            height: 100vh;
            overflow: hidden;
        }

        .background-video video {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .centered-container {
            position: relative;
            z-index: 1;
            text-align: center;
            padding: 20px;
            color: white;
            height: 100%;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }

        /* Stats Section Styles */
        .main-section {
            padding: 50px 0;
        }

        .main-container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        .header-wrap-left {
            text-align: center;
        }

        .purple-span {
            color: #6b46c1;
        }

        .spacer-50px {
            height: 50px;
        }

        ._1-3-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 30px;
        }

        .content-wrap-stats {
            text-align: center;
            padding: 20px;
        }

        .info-image {
            max-width: 100px;
            margin-bottom: 15px;
        }

        .counter-1, .counter-2, .counter-3, 
        .counter-4, .counter-5, .counter-6 {
            font-size: 2em;
            font-weight: bold;
            color: #6b46c1;
        }

        .h3 {
            margin-top: 10px;
            font-size: 1.2em;
        }

        /* Registration Form Styles */
        .registration-section {
            background-color: #b9ff78;
            padding: 50px 0;
        }

        .form-container {
            display: flex;
            max-width: 800px;
            margin: 0 auto;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            overflow: hidden;
        }

        .left-section {
            flex: 1;
            background: url('https://www.services.bis.gov.in/php/BIS_2.0/BISBlog/wp-content/uploads/2023/02/Natural-farming-.jpg') no-repeat center;
            background-size: cover;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 24px;
            font-weight: bold;
            text-align: center;
            padding: 20px;
            min-height: 500px;
        }

        .right-section {
            flex: 1;
            padding: 40px;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }

        .right-section input,
        .right-section select {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .right-section button {
            width: 100%;
            padding: 12px;
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
            margin-top: 10px;
        }

        .right-section button:hover {
            background-color: #0056b3;
        }

        @media (max-width: 768px) {
            ._1-3-grid {
                grid-template-columns: repeat(2, 1fr);
            }
            .form-container {
                flex-direction: column;
            }
            .left-section {
                min-height: 200px;
            }
        }

        @media (max-width: 480px) {
            ._1-3-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <!-- Video Section -->
    <div class="background-video">
        <video autoplay loop muted playsinline poster="https://cdn.prod.website-files.com/62551fa7bee8db16e944f95d/631e043726ebf9f7b2399002_final video-poster-00001.jpg">
            <source src="https://cdn.prod.website-files.com/62551fa7bee8db16e944f95d/631e043726ebf9f7b2399002_final video-transcode.mp4" type="video/mp4">
            <source src="https://cdn.prod.website-files.com/62551fa7bee8db16e944f95d/631e043726ebf9f7b2399002_final video-transcode.webm" type="video/webm">
        </video>
        <div class="centered-container">
            <h1 class="hero-heading">India's Largest<br>Integrated Fruits and Vegetables Value Chain</h1>
            <p class="hero-paragraph">A company of the farmers, by the farmers and for the farmers.</p>
            <div class="button-div">
                <a href="#About-us-Section" class="main-button">Explore</a>
            </div>
        </div>
    </div>

    <!-- Stats Section -->
    <div class="main-section">
        <div class="main-container">
            <div class="header-wrap-left">
                <h2 class="sub-hero-heading">Welcome to <span class="purple-span">EcoHarvest</span></h2>
            </div>
            <div class="spacer-50px"></div>
            <div class="_1-3-grid">
                <div class="content-wrap-stats">
                    <img src="https://cdn.prod.website-files.com/62551fa7bee8db16e944f95d/6321c9321900d229963842c0_18%2C000%2B%20Registered%20farmers.webp" loading="lazy" alt="" class="info-image">
                    <div class="counter-1">18,000+</div>
                    <div class="spacer-blank"></div>
                    <h3 class="h3">Registered farmers</h3>
                </div>
                <div class="content-wrap-stats">
                    <img src="https://cdn.prod.website-files.com/62551fa7bee8db16e944f95d/6321c93de6ae67a00c13f7c1_30%2C000%2BAcres%20of%20land.webp" loading="lazy" alt="" class="info-image">
                    <div class="counter-2">30,000+</div>
                    <div class="spacer-blank"></div>
                    <h3 class="h3">Acres of land</h3>
                </div>
                <div class="content-wrap-stats">
                    <img src="https://cdn.prod.website-files.com/62551fa7bee8db16e944f95d/6321c94fdbc6a7f8947876fe_252%2B%20Villages%20covered.webp" loading="lazy" alt="" class="info-image">
                    <div class="counter-3">252+</div>
                    <div class="spacer-blank"></div>
                    <h3 class="h3">Villages covered</h3>
                </div>
                <div class="content-wrap-stats">
                    <img src="https://cdn.prod.website-files.com/62551fa7bee8db16e944f95d/6321c9156a14a539808460e5_42%2BCountries%20served.webp" loading="lazy" alt="" class="info-image">
                    <div class="counter-4">42+</div>
                    <div class="spacer-blank"></div>
                    <h3 class="h3">Countries served</h3>
                </div>
                <div class="content-wrap-stats">
                    <img src="https://cdn.prod.website-files.com/62551fa7bee8db16e944f95d/62bc3cf06d06e555c4fb9205_Frame%2055.webp" loading="lazy" alt="" class="info-image">
                    <div class="counter-5">110+</div>
                    <div class="spacer-blank"></div>
                    <h3 class="h3">Customers worldwide</h3>
                </div>
                <div class="content-wrap-stats">
                    <img src="https://cdn.prod.website-files.com/62551fa7bee8db16e944f95d/6321c92717c076f99706284f_12%2B%20Years%20in%20the%20industry.webp" loading="lazy" alt="" class="info-image">
                    <div class="counter-6">12+</div>
                    <div class="spacer-blank"></div>
                    <h3 class="h3">Years in the industry</h3>
                </div>
            </div>
        </div>
    </div>

    <!-- Registration Form Section -->
    <div class="registration-section">
        <div class="form-container">
            <div class="left-section">
                <p>Join Our Farmer Community</p>
            </div>
            <div class="right-section">
                <h2>Farmer Registration</h2>
                <form action="#" method="POST">
                    <input type="text" name="name" placeholder="Full Name" required>
                    <input type="email" name="email" placeholder="Email Address" required>
                    <input type="tel" name="phone" placeholder="Phone Number" required>
                    <input type="text" name="address" placeholder="Farm Address" required>
                    <select name="farm_type" required>
                        <option value="" disabled selected>Select Farm Type</option>
                        <option value="Dairy">Dairy</option>
                        <option value="Poultry">Poultry</option>
                        <option value="Crop Farming">Crop Farming</option>
                        <option value="Other">Other</option>
                    </select>
                    <button type="submit">Register</button>
                </form>
            </div>
        </div>
    </div>
</body>
</html>
