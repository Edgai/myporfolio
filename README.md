<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        #logo {
            display: flex;
            align-items: center;
        }
        #logo img {
            width: 150px;
            height: 150px;
            border-radius: 0%;
            margin-right: 40px;
        }
        #logo h4, #logo h3 {
            margin: 0;
        }
        section {
            padding: 20px;
            
        }
        h5 {
            padding: 0px;
            font-size: 1em;
            text-align: right;
        }
        .project {
            background-color: #fff;
            padding: 20px;
            margin-bottom: 20px;
        }
        h4 {
            font-size: 3.50em;
            margin-block-start: 0.83em;
            margin-block-end: 0.83em;
            margin-inline-start: 1px;
            margin-inline-end: 0px;
            font-weight: lighter;
        }
        .project p {
            margin-bottom: 10px;
        }
        h3 {
            font-size: 3.50em;
            margin-block-start: 0.83em;
            margin-block-end: 0.83em;
            margin-inline-start: 20px;
            margin-inline-end: 0px;
            font-weight: bold;
        }
        #print-btn {
            padding: 10px 20px;
            background-color: #333;
            color: #fff;
            border: none;
            cursor: pointer;
        }
        #print-btn:hover {
            background-color: #555;
        }
    </style>
</head>
<body>

<header>
    <section id="logo">
        <div>
            <img src="IMG_20220830_231529.png" alt="Your Name">
        </div>
        <div>
            <h4>EDGAR R.</h4>
            <h3>RAFALES</h3>
        </div>
    </section>
    <section id="personal-info">
            <h5>BRGY. MALOH, SIATON, NEGROS ORIENTAL <i class="fas fa-map-marker-alt"></i></h5>
            <h5>09558195301 <i class="fas fa-phone"></i></h5>
            <h5><a href="mailto:rafalesedgar@gmail.com">rafalesedgar@gmail.com <i class="fas fa-envelope"></i></a></h5>
    </section>
        
</header>

<section id="about">
    <h2>OBJECTIVE</h2>
    <p>Obtain a responsible employment opportunity that will allow me to make the most of my education and experience while significantly contributing to the company's success.</p>
</section>

<section id="projects">
    <h2><i class="fas fa-graduation-cap"></i>EDUCATION</h2>
    <div class="project">
        <h2><i class="fas fa-graduation-cap"></i>COLLEGE</h2>
        <p>Negros Oriental State University Main I</p>
        <p>2020-2024</p>
        <p>Bachelor of Science in Information Technology</p>
    </div>
    <div class="project">
        <h2><i class="fas fa-graduation-cap"></i>SENIOR HIGH SCHOOL</h2>
        <p>Maloh Provincial Community High School</p>
        <p>2019-2020</p>
        <p>STRAND/ TRACK: TVL(Computer Systems Servicing)</p>
    </div>
    <div class="project">
        <h2><i class="fas fa-graduation-cap"></i>JUNIOR HIGH SCHOOL</h2>
        <p>Maloh Provincial Community High School</p>
        <p>2015-2019</p>
        <p>TLE: Housekeeping</p>
    </div>
    <div class="project">
        <h2><i class="fas fa-graduation-cap"></i>ELEMENTARY (K-6)</h2>
        <p>Maloh Central School</p>
        <p>2008-2015</p>
    </div>
</section>


<section id="contact">
    <button id="print-btn">Print</button>
</section>

<script>
    document.getElementById("print-btn").addEventListener("click", function() {
        window.print();
    });
</script>

</body>
</html>
