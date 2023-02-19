<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Placement Cell - Ravenshaw University </title>
    <link rel="icon" type="image/x-icon" href="image/logo1.png">
    <link rel="stylesheet" href="style.css">
    <!-- Latest compiled and minified CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/css/bootstrap.min.css" rel="stylesheet">

    <!-- Latest compiled JavaScript -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/js/bootstrap.bundle.min.js"></script>

    <script src="https://kit.fontawesome.com/e12bc36359.js" crossorigin="anonymous"></script>
</head>


<style media="screen">
    .wrap {
        overflow: hidden;
        margin: 10px;
        max-width: 1500px;
        margin-left: auto;
        margin-right: auto;
    }

    .box {
        float: left;
        position: relative;
        width: 10%;
        padding: 5%;
    }

    .boxInner {
        position: absolute;
        left: 30px;
        right: 30px;
        top: 30px;
        bottom: 10px;
        overflow: hidden;
    }

    .boxInner img {
        width: 100%
    }


    @media only screen and (max-width:480px) {

        /* Smartphone view: 1 tile */
        .box {
            width: 100%;
            padding-bottom: 50%;
        }
    }

    @media only screen and (max-width:650px) and (min-width:481px) {

        /* Tablet view: 2 tiles */
        .box {
            width: 50%;
            padding-bottom: 50%;
        }
    }
    

    @media only screen and (max-width:1050px) and (min-width:651px) {

        /* Small desktop / ipad view: 3 tiles */
        .box {
            width: 33.3%;
            padding-bottom: 33.3%;
        }
    }
    .yr1{
        height: 42%; width: 0%; padding:5%;
    }

    @media only screen and (max-width:1290px) and (min-width:1051px) {

        /* Medium desktop: 4 tiles */
        .box {
            width: 25%;
            padding-bottom: 25%;
        }
    }
    .yr1{
        height: 100%; width: 95%; padding: 0%;
    }

    .card-registration .select-input.form-control[readonly]:not([disabled]) {
        font-size: 1rem;
        line-height: 2.15;
        padding-left: .75em;
        padding-right: .75em;
    }

    .card-registration .select-arrow {
        top: 13px;
    }

    .form-control-lg {
        min-height: calc(1.5em + 1rem + calc(var(--bs-border-width) * 2));
        padding: .5rem 1rem;
        font-size: 1.25rem;
        /* border-radius: .5rem; */
    }

    .btn:hover {
        color: #e9ecef;
        background-color: #333333;
        border-color: var(--bs-btn-hover-border-color);
    }

    .btn-group-lg>.btn,
    .btn-lg {
        --bs-btn-padding-y: 0.5rem;
        --bs-btn-padding-x: 1rem;
        --bs-btn-font-size: 1.25rem;
        --bs-btn-border-radius: 0px;
    }

    .btn-light {
        --bs-btn-color: #000;
        --bs-btn-bg: #707070;
        --bs-btn-border-color: #f8f9fa;
        --bs-btn-hover-color: #000;
        --bs-btn-hover-bg: #d3d4d5;
        --bs-btn-hover-border-color: #c6c7c8;
        --bs-btn-focus-shadow-rgb: 211, 212, 213;
        --bs-btn-active-color: #000;
        --bs-btn-active-bg: #c6c7c8;
        --bs-btn-active-border-color: #babbbc;
        --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
        --bs-btn-disabled-color: #000;
        --bs-btn-disabled-bg: #f8f9fa;
        --bs-btn-disabled-border-color: #f8f9fa;
    }

    .card1 {
        box-shadow: 0 2px 4px 0 rgba(0, 0, 0, 0.2);
        max-width: 200px;
        height: 300px;
        margin: auto;
        text-align: center;
        border-radius: 30px;
    }

    .title {
        color: rgb(139, 22, 22);
        font-size: 13px;
    }

    .title2 {
        color: rgb(0, 0, 0);
        font-size: 18px;
        margin: 9px;
    }

    .img1 {
        width: 100%;
        border-radius: 30px;
        block-size: 50%;
    }

    .container1 {
        position: relative;
        text-align: center;
        color: brown;
        font-size: 16px;
        align: justify;
        font-family: Baskerville Old Face;
    }

    /* Centered text */
    .centered {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        color: brown;
        font-size: 56px;
        align: justify;
        font-family: Baskerville Old Face;
    }
         .btn5 {
    padding: 1em 2.1em 1.1em;
    border-radius: 3px;
    margin: 8px 8px 8px 8px;
    color: #fbdedb;
    background-color: #fbdedb;
    display: inline-block;
    background: #e74c3c;
    -webkit-transition: 0.3s;
    -moz-transition: 0.3s;
    -o-transition: 0.3s;
    transition: 0.3s;
    font-family: sans-serif;
    font-weight: 800;
    font-size: .85em;
    text-transform: uppercase;
    text-align: center;
    text-decoration: none;
    -webkit-box-shadow: 0em -0.3rem 0em rgba(0, 0, 0, 0.1) inset;
    -moz-box-shadow: 0em -0.3rem 0em rgba(0, 0, 0, 0.1) inset;
    box-shadow: 0em -0.3rem 0em rgba(0, 0, 0, 0.1) inset;
    position: relative;
    width: 75%;height: 20%;
    
}
.btn5:hover, .btn:focus {
    opacity: 0.8;
}
.btn5:active {
    -webkit-transform: scale(0.80);
    -moz-transform: scale(0.80);
    -ms-transform: scale(0.80);
    -o-transform: scale(0.80);
    transform: scale(0.80);
}
.btn5.block {
    display: block !important;
}
.btn5.circular {
  border-radius: 50em !important;
}
.red {
    background-color: #d55050;
}
  
</style>


<body>
    <section style="background-color:rgb(145, 35, 35);padding: 3px;">
        <div class="container-fluid row">
            <div class="col-md-3"></div>
            <div class="col-md-3"></div>
            <div class="col-md-6">
                <a href="#"
                    style="text-decoration:none;color:white; padding:0 10px;border-right: 2px solid white;display: inline-block;"><i
                        class="fa-solid fa-house"></i> Skip
                    To Main Page</a>
                <a href="#"
                    style="text-decoration:none;color:white;padding:0 10px;border-right: 2px solid white;display: inline-block;"><i
                        class="fa-solid fa-tablet"></i> Screen
                    Reader Access</a>
                <a href="#"
                    style="text-decoration:none;color:white;padding:0 10px;border-right: 2px solid white;display: inline-block;"><i
                        class="fa-solid fa-folder"></i> Directory</a>
                <a href="#"
                    style="text-decoration:none;color:white;padding:0 10px;border-right: 2px solid white;display: inline-block;"><i
                        class="fa-solid fa-right-to-bracket"></i> Login</a>
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="16" fill="white" class="bi bi-search"
                    viewBox="0 0 16 16">
                    <path
                        d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z" />
                </svg>
            </div>
        </div>
    </section>

    <section>
        <div class="container">
            <div class="row">
                <div class="col" style="margin:10px">
                    <img src="Logo/Logo 2.png" alt="" height="80px" width="auto" style="margin-top: 15px;">
                </div>
                <div class="col">
                    <img src="Logo/The-temple-of-learning-1.png" alt="" height="70px" width="auto"
                        style="margin-top: 35px;">
                </div>

                <div class="col">
                    <img src="Logo/Higher-Education-Department-1.png" alt="" height="100px" width="auto"
                        style="margin:4px;" class="float-md-end mt-md-3">
                </div>
            </div>
        </div>
    </section>

    <!-- navbar -->
    <nav class="navbar navbar-expand-lg sticky-top" style="background-color: rgb(145, 35, 35);">
        <div class="container-fluid">
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#collapsibleNavbar"
                style="background-color: #ddd;">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="collapsibleNavbar" style="justify-content: center;">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link" href="#" style="color: white; font-weight:500 ; font-size:medium;">Home</a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link " href="#" role="button" data-bs-toggle="dropdown"
                            style="color: white; font-weight:500; font-size:medium;">About</a>
                        <ul class="dropdown-menu"
                            style="background-color: rgb(0, 0, 0);background-color: rgba(173, 148, 148, 0.3);">
                            <li><a class="dropdown-item" href="History.html"
                                    style="color: black; font-weight:500">History</a></li>
                            <li><a class="dropdown-item" href="mission&vision.html"
                                    style="color: black; font-weight:500">Vision &
                                    Mission</a></li>

                            <li><a class="dropdown-item" href="pdf/Ravenshaw-University-Act.pdf"
                                    style="color: black; font-weight:500">ACT</a></li>
                            <li><a class="dropdown-item" href="pdf/UNIVERSITY-STATUTE.pdf"
                                    style="color: black; font-weight:500">Statute</a></li>
                        </ul>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link " href="#" role="button" data-bs-toggle="dropdown"
                            style="color: white; font-weight:500; font-size:medium;">Team</a>
                        <ul class="dropdown-menu" style="   background-color: rgb(0, 0, 0);
                            background-color: rgba(173, 148, 148, 0.3);">
                            <li><a class="dropdown-item" href="Chancellor.html" style="color: black; font-weight:500">
                                    Chancellor</a></li>
                            <li><a class="dropdown-item" href="#" style="color: black; font-weight:500">Vice
                                    Chancellor</a></li>
                            <li><a class="dropdown-item" href="#" style="color: black; font-weight:500">Chairperson PG
                                    Council
                                </a></li>
                            <li><a class="dropdown-item" href="#" style="color: black; font-weight:500">Registrar</a>
                            </li>
                            <li><a class="dropdown-item" href="#" style="color: black; font-weight:500">Comptroller of
                                    Finance</a></li>
                            <li><a class="dropdown-item" href="#" style="color: black; font-weight:500">Controller of
                                    Examination</a></li>
                            <li><a class="dropdown-item" href="#" style="color: black; font-weight:500">Director,
                                    Students' Welfare</a></li>
                            <li><a class="dropdown-item" href="#" style="color: black; font-weight:500">Chief Warden</a>
                            </li>
                            <li><a class="dropdown-item" href="#" style="color: black; font-weight:500">Faculty</a></li>
                        </ul>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link " href="#" role="button" data-bs-toggle="dropdown"
                            style="color: white; font-weight:500; font-size:medium;">Academics</a>
                        <ul class="dropdown-menu"
                            style="background-color: rgb(0, 0, 0);background-color: rgba(173, 148, 148, 0.3);">
                            <li><a class="dropdown-item" href="#" style="color: black; font-weight:500">Departments</a>
                            </li>
                            <li><a class="dropdown-item" href="#" style="color: black; font-weight:500">Centers</a></li>
                            <li><a class="dropdown-item" href="#" style="color: black; font-weight:500">CIF</a></li>
                            <li><a class="dropdown-item" href="#" style="color: black; font-weight:500">Academic
                                    Calendar</a></li>
                        </ul>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link " href="#" role="button" data-bs-toggle="dropdown"
                            style="color: white; font-weight:500; font-size:medium;">Admission</a>
                        <ul class="dropdown-menu"
                            style="background-color: rgb(0, 0, 0);background-color: rgba(173, 148, 148, 0.3);">
                            <li><a class="dropdown-item" href="https://ruadmission.co.in/"
                                    style="color: black; font-weight:500">Admission in
                                    1year Certificate Course in Computational Humanities (2022-2023)</a></li>
                            <li><a class="dropdown-item" href="pdf/Notice-for-M.C.A.-Admission-2022-23.pdf"
                                    style="color: black; font-weight:500">Corrigendum for
                                    MCA Admission 2022</a></li>
                            <li><a class="dropdown-item" href="pdf/FINAL1.pdf" style="color: black; font-weight:500">PG
                                    Admission
                                    Prospectus 2022-23</a></li>
                            <li><a class="dropdown-item" href="https://ruadmission.co.in/"
                                    style="color: black; font-weight:500">UG Admission
                                    2022-23</a></li>
                            <li><a class="dropdown-item" href="pdf/UGAdmission-Prospectus-2022-Final"
                                    style="color: black; font-weight:500">UG Admission
                                    Prospectus 2022-23</a></li>
                            <li><a class="dropdown-item"
                                    href="https://ravenshawuniversity.ac.in/wp-content/uploads/2022/08/phd-brocture-final.pdf"
                                    style="color: black; font-weight:500">ph.D Admission
                                    Prospectus 2022-23</a>
                            </li>
                            <li><a class="dropdown-item" href="https://ruadmission.co.in/"
                                    style="color: black; font-weight:500">ph.D Admission
                                    2022-23</a>
                            </li>
                            <li><a class="dropdown-item" href="https://samsodisha.gov.in/"
                                    style="color: black; font-weight:500">SAMS</a>
                            </li>
                            <li><a class="dropdown-item" href="http://14.139.212.115:81/LoginPage.aspx"
                                    style="color: black; font-weight:500">Student
                                    Login</a>
                            </li>
                            <li><a class="dropdown-item"
                                    href="https://www.onlinesbi.com/sbicollect/icollecthome.htm?corpID=333825"
                                    style="color: black; font-weight:500">Online Payment
                                </a>
                            </li>
                            <li><a class="dropdown-item" href="pdf/UG-RESULT-2021.pdf"
                                    style="color: black; font-weight:500">Results</a>
                            </li>
                        </ul>
                    </li>

                    <li class="nav-item dropdown">
                        <a class="nav-link " href="#" role="button" data-bs-toggle="dropdown"
                            style="color: white; font-weight:500; font-size:medium;">Students</a>
                        <ul class="dropdown-menu"
                            style="background-color: rgb(0, 0, 0);background-color: rgba(173, 148, 148, 0.3);">
                            <li><a class="dropdown-item" href="#abstract-submission"
                                    style="color: black; font-weight:500">Star Performer</a></li>
                            <li><a class="dropdown-item" href="#Poster-Presentation"
                                    style="color: black; font-weight:500">Hostels</a></li>
                            <li><a class="dropdown-item" href="#abstract-submission"
                                    style="color: black; font-weight:500">Placement</a></li>
                            <li><a class="dropdown-item" href="#Poster-Presentation"
                                    style="color: black; font-weight:500">Anti Ragging</a></li>
                            <li><a class="dropdown-item" href="#abstract-submission"
                                    style="color: black; font-weight:500">GSCASH</a></li>
                            <li><a class="dropdown-item" href="#Poster-Presentation"
                                    style="color: black; font-weight:500">Equal Opportunity Cell</a></li>
                            <li><a class="dropdown-item" href="#Poster-Presentation"
                                    style="color: black; font-weight:500">Facilities</a></li>
                            <li><a class="dropdown-item" href="#Poster-Presentation"
                                    style="color: black; font-weight:500">Student Body</a></li>
                            <li><a class="dropdown-item" href="#Poster-Presentation"
                                    style="color: black; font-weight:500">Cultural Council</a></li>
                        </ul>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link " href="#" role="button" data-bs-toggle="dropdown"
                            style="color: white; font-weight:500; font-size:medium;">Research</a>
                        <ul class="dropdown-menu"
                            style="background-color: rgb(0, 0, 0);background-color: rgba(173, 148, 148, 0.3);">
                            <li><a class="dropdown-item" href="#" style="color: black; font-weight:500">Research
                                    Cell</a></li>
                            <li><a class="dropdown-item" href="#" style="color: black; font-weight:500">OHEPEE</a></li>
                            <li><a class="dropdown-item" href="#"
                                    style="color: black; font-weight:500">Collaborations</a>
                            </li>
                            <li><a class="dropdown-item" href="#" style="color: black; font-weight:500">MoUs</a></li>
                            <li><a class="dropdown-item" href="#" style="color: black; font-weight:500">Publication</a>
                            </li>
                            <li><a class="dropdown-item" href="#" style="color: black; font-weight:500">IPR</a></li>
                        </ul>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link " href="#" role="button" data-bs-toggle="dropdown"
                            style="color: white; font-weight:500; font-size:medium;">International Office</a>
                        <ul class="dropdown-menu"
                            style="background-color: rgb(0, 0, 0);background-color: rgba(173, 148, 148, 0.3);">
                            <li><a class="dropdown-item" href="#" style="color: black; font-weight:500">Overview</a>
                            </li>
                            <li><a class="dropdown-item" href="#" style="color: black; font-weight:500">Convention
                                    Center</a></li>
                            <li><a class="dropdown-item" href="#" style="color: black; font-weight:500">ICCR</a></li>
                        </ul>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link" href="#" role="button" data-bs-toggle="dropdown"
                            style="color: white; font-weight:500; font-size:medium;">Connect</a>
                        <ul class="dropdown-menu"
                            style="background-color: rgb(0, 0, 0);background-color: rgba(173, 148, 148, 0.3);">
                            <li><a class="dropdown-item" href="RTI-PIO.html"
                                    style="color: black; font-weight:500">RTI_PIO</a></li>
                            <li><a class="dropdown-item" href="PRoffice.html" style="color: black; font-weight:500">PR
                                    Office</a>
                            </li>
                            <li><a class="dropdown-item" href="SMC.html" style="color: black; font-weight:500">Social
                                    Media
                                    Champion</a></li>
                        </ul>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link " href="#" role="button" data-bs-toggle="dropdown"
                            style="color: white; font-weight:500; font-size:medium;">e-Office</a>
                        <ul class="dropdown-menu"
                            style="background-color: rgb(0, 0, 0);background-color: rgba(173, 148, 148, 0.3);">
                            <li><a class="dropdown-item" href="http://eduautonomous.eofficeodi.nic.in/"
                                    style="color: black; font-weight:500">Employees' Corner</a></li>
                        </ul>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link " href="#" role="button" data-bs-toggle="dropdown"
                            style="color: white; font-weight:500; font-size:medium;">Alumni</a>
                        <ul class="dropdown-menu"
                            style="background-color: rgb(0, 0, 0);background-color: rgba(173, 148, 148, 0.3);">
                            <li><a class="dropdown-item" href="RUDT.html" style="color: black; font-weight:500">RUDT</a>
                            </li>
                            <li><a class="dropdown-item" href="https://mocollegeodisha.in/"
                                    style="color: black; font-weight:500">Mo College</a>
                            </li>
                            <li><a class="dropdown-item" href="RAA.html" style="color: black; font-weight:500">RAA</a>
                            </li>

                        </ul>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="index.html"
                            style="color: white; font-weight:500; font-size:medium;">Recruitment</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="index.html"
                            style="color: white; font-weight:500; font-size:medium;">IQAC</a>
                    </li>

                    <li class="nav-item">
                        <a class="nav-link" href="index.html"
                            style="color: white; font-weight:500; font-size:medium;">Library</a>
                    </li>

                </ul>
            </div>
        </div>
    </nav>
    <!--Navbar End-->

    <div class="card text-bg-dark" style=" height: 10px; width: auto;">
        <img src="images/Almuni/bg1.png" class="card-img" style="height: 120px; width:100%; ">
        <div class="card-img-overlay">
            <center>
                <b>
                    <h1 class="card-title" style="margin: 3px;">Placement Overview</h1>
                </b>
            </center>
        </div>
    </div><br>
    <section style="margin-top: 20vh;">
        <div class="container1">
            <img src="link/handshake-close-up-executives.jpg"  alt="Snow" style="width:50%; height: 3%;">
            <!--<div class="centered">“Choose a job you love, and you will never have to work a day in your life."</div>-->
            
        </div>
    </section>
    <hr style="margin: 2%; opacity: 100%;">
   <section style="margin: 5%; ">
        <div class="container text-center">
            
            <div class="row">
                <div class="col-4" style="border: 1px solid black; border-radius: 50px; box-shadow: 2px 2px 2px 2px gray;">

                    <center >
                        <h6 style="padding-top: 2%;">Office</h6>
                        <hr style="opacity: 100%; height: 3px; width: 63px; background-color: #b02a37; margin-top: -2px;">
                    </center>
                    <div style="font-family: Montserrat, Sans-serif;">
                        <h5 style="font-size: 16px;"><strong>Biswaranjan Singh</strong></h5>
                        <div style="margin-top: -11px; color: brown; font-size: 13px;">
                            <p><strong> Placement Coordinator</strong></p>
                        </div>
                    </div>
                    <div style="font-family: Montserrat, Sans-serif;">
                    
                        <h5 style="font-size: 16px;"><strong>Srikant Bej</strong></h5>
                        <div style="margin-top: -11px; color: brown; font-size: 13px;">
                            <p><strong> Member</strong></p>
                        </div></div>
                        <div style="font-family: Montserrat, Sans-serif;">
                        
                            <h5 style="font-size: 16px;"><strong>Madhumita Harichandan</strong></h5>
                            <div style="margin-top: -11px; color: brown; font-size: 13px;">
                                <p><strong> Member</strong></p>
                            </div></div>
                            <div style="font-family: Montserrat, Sans-serif;">
                            
                                <h5 style="font-size: 16px;"><strong>Silpa Patra</strong></h5>
                                <div style="margin-top: -11px; color: brown; font-size: 13px;">
                                    <p><strong> Member</strong></p>
                                </div></div>
                    
                    
                    <div >
                        <p align="justify"><strong>9437670665, 7978800389</strong></p>
                    </div>
                    <div >
                        <p align="justify"><strong>placement[at]ravenshawuniversity [dot]ac[dot]in </strong></p></div>
                </div>
                <div class="col-8">
                    <p align="Justify" style=" margin-top: 1%; padding: 4px; font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif; font-size: 18px; background-color: azure; ">The University has a placement cell to take care of all types of placements of the University. The Placement Cell keeps
                    a liaison with the potential industries and companies, provides necessary guidance to the students and facilitates
                    arranging on-campus placements of students in various industries and companies. Arrangements are also made for students
                    to participate in off-campus drives organized at various institutions/industries.</p>
                </div>
                
            </div>
        </div>
   </section>
    
   <!--Placement report section-->
    <section style=" margin-top: 3%; background-color: azure;">
        <div class="container text-center">
            <div class="row">
                <div class="col">
                  
                <center>
                    <section>
                        <h1>Placement Report</h1>
                        <a href="#fakeLink" class="btn5 red">2015 - 2016</a><br>
                        <a href="#fakeLink" class="btn5 red">2016 - 2017</a><br>
                        <a href="#fakeLink" class="btn5 red">2017 - 2018</a><br>
                        <a href="#fakeLink" class="btn5 red">2018 - 2019</a><br>
                    </section>
                </center>
                </div>
                <div class="col">
                    <img class="yr1" src="link/Placement.png" alt="" style="margin: 3%;">
                </div>
            </div>
    </section>


<!--Gallery Section-->
<section style="background-color: beige; margin: 2%;">

    <center>
        <h1 style=" color:brown; ">Our Recruiters</h1>
    </center>
    <div class="wrap">
        <!-- Define all of the tiles: -->
        <div class="box">
            <div class="boxInner">
                <img src="link/1.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/2.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/3.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/4.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/5.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/6.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/7.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/8.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/9.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/10.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/11.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/12.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/13.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/14.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/15.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/16.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/17.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/18.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/19.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/20.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/21.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/22.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/23.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/24.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/25.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/26.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/27.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/28.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/29.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/30.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/31.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/32.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/33.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/34.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/35.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/36.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/37.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/38.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/39.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/40.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/41.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/42.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/43.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/44.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/45.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/46.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/47.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/48.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/49.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/50.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/51.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/52.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/53.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/54.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/55.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/56.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/57.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/58.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/59.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/60.jpg" height="100" />

            </div>
        </div>
        <div class="box">
            <div class="boxInner">
                <img src="link/61.jpg" height="100" />

            </div>
        </div>

    </div>
    </div>
</section>

<!--Paragraph-->
<section style="margin: 5%;">
    <h1 align="center" style="  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif; font-size: 30px;">Career
        Counselling Cell</h1>
    <p align="Justify"
        style=" margin-top: 1%; padding: 4px; font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif; font-size: 18px;">
        A “Career and Counselling Cell” has been established in Ravenshaw University with assistance from Higher
        Education
        Department, Government of Odisha. The focus of the cell is to facilitate and nurture the students for their
        personal
        development and career. The cell is regularly conducting career counselling and soft skill development sessions.
        The
        talk, training/ workshop etc. organized for the students facilitate them in preparing for their future
        challenges.
        <br><br>
        Motivating and guiding students for entrepreneurship is also a thrust area of the cell.
        <br><br>
        The cell has also started a lecture series namely ICAN (Inspiration, Career counselling And motivatioN), a brain
        child
        of Prof. Ishan Kumar Patro, the Hon’ble Vice Chancellor. The first two lectures of this series were held on
        14-11-2019.
        Two speakers Mr. Ramkumar Nair and Dr. Karthikeyan R spoke on “Entrepreneurship: The Road Less Travelled” and
        “Do What
        You Love: On Self Discovery and Career Planning” respectively. The third talk was delivered by Mr. Manas Roul”
        on
        “Reignite Your Hidden Power”. During these talks a number of faculty members as well as students were present.
    </p>
</section>

<section style="background-color: azure; ">
    <h1 align="center" style="  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif; font-size: 30px;">
        ICAN (Inspiration, Career counselling And motivatioN) Lecture Series</h1>
        <table class="table" style="margin-left: 5%; margin-right: 5%; margin-top: 1%;">
        
            <tbody>
                <tr>
                    <th scope="row"></th>
                    <td>14.11.2019</td>
                    <td>MR. RAMKUMAR NAIR</td>
                    <td>@Entrepreneurship : The Road Less Travelled</td>
                </tr>
                <tr>
                    <th scope="row"></th>
                    <td>14.11.2019</td>
                    <td>DR. KARTHIKEYAN R.</td>
                    <td>Do What You Love : On Self Discovery and Career Planning</td>
                </tr>
                <tr>
                    <th scope="row"></th>
                    <td>19.02.2020</td>
                    <td>MR. MANAS ROUL</td>
                    <td>Reignite Your Hidden Power</td>
                </tr>
            </tbody>
        </table>
</section>
    <!-- Footer -->
    <footer class="container-fluid pt-5" style=" margin-top: 10rem; height: auto;  background-color: rgb(48, 48, 48)">
        <center>
            <section>
                <div class="elementor-image" style="background-color: rgb(135,35,35); width: auto;">
                    <img width="350" height="84" src="images/Almuni/logo1.png" class="attachment-medium size-medium"
                        alt="" loading="lazy"
                        srcset="Project RU/Project RU/images/Almuni/logo1.png 300w, Project RU/Project RU/images/Almuni/logo1.png 197w, Project RU/Project RU/images/Almuni/logo1.png 717w"
                        sizes="(max-width: 300px) 100vw, 300px" />
                </div>
            </section>
            <section style="background-color: rgb(135,35,35);">
                <h5 style="color: aliceblue;">Registrar | Ravenshaw University | Cuttack-751003 | Odisha | India
                </h5>
                <h5 style="color: aliceblue;">Phone : +91-6712201690 | Email :
                    registrar@ravenshawuniversity.ac.in</h5>
                <hr class="elementor-divider-separator" style="width: 90%; color: coral; height: auto;">
                </hr>
            </section>

            <section>
                <div class="row">
                    <div class="col-lg-2 col-md-6 mb-4 mb-md-0">
                        <b>
                            <h5 class="text-uppercase" style="color: white;">Quick Links</h5>
                            <hr style="color: aliceblue; width: 55%;">
                        </b>

                        <ul class="list-unstyled mb-0">
                            <li>
                                <a href="#" class="text-white" style="text-decoration: none;">Annual Report</a>
                            </li>
                            <li>
                                <a href="#!" class="text-white" style="text-decoration: none;">Audit Report</a>
                            </li>
                            <li>
                                <a href="#!" class="text-white" style="text-decoration: none;">Ravenshaw
                                    Archive</a>
                            </li>
                            <li>
                                <a href="#!" class="text-white" style="text-decoration: none;">Academic
                                    Calendar</a>
                            </li>
                            <li>
                                <a href="#!" class="text-white" style="text-decoration: none;">Convocation</a>
                            </li>
                            <li>
                                <a href="#!" class="text-white" style="text-decoration: none;">Placement
                                    Cell</a>
                            </li>
                            <li>
                                <a href="#!" class="text-white" style="text-decoration: none;">ProQuest</a>
                            </li>
                            <li>
                                <a href="#!" class="text-white" style="text-decoration: none;">Sports
                                    Council</a>
                            </li>
                            <li>
                                <a href="#!" class="text-white" style="text-decoration: none;">Dispensary</a>
                            </li>
                            <li>
                                <a href="#!" class="text-white" style="text-decoration: none;">New Jobs</a>
                            </li>
                        </ul>
                    </div>
                    <div class="col-lg-2 col-md-6 mb-4 mb-md-0"><br><br>
                        <ul class="list-unstyled mb-0">
                            <li>
                                <a href="#!" class="text-white" style="text-decoration: none;">Give To
                                    Ravenshaw</a>
                            </li>
                            <li>
                                <a href="#!" class="text-white" style="text-decoration: none;">Places To
                                    Visit</a>
                            </li>
                            <li>
                                <a href="#!" class="text-white" style="text-decoration: none;">IQAC</a>
                            </li>
                            <li>
                                <a href="#!" class="text-white" style="text-decoration: none;">NAAC</a>
                            </li>
                            <li>
                                <a href="#!" class="text-white" style="text-decoration: none;">NIRF</a>
                            </li>
                            <li>
                                <a href="#!" class="text-white" style="text-decoration: none;">NAD</a>
                            </li>
                            <li>
                                <a href="#!" class="text-white" style="text-decoration: none;">IGNOU</a>
                            </li>
                            <li>
                                <a href="#!" class="text-white" style="text-decoration: none;">OSOU</a>
                            </li>
                            <li>
                                <a href="#!" class="text-white" style="text-decoration: none;">NDL</a>
                            </li>
                            <li>
                                <a href="#!" class="text-white" style="text-decoration: none;">RUTA</a>
                            </li>
                        </ul>
                    </div>
                    <div class="col-lg-2 col-md-6 mb-4 mb-md-0">
                        <h5 class="text-uppercase" style="color: #ffffff;">Important Links</h5>
                        <hr style="color: aliceblue; width: 80%;">
                        <ul class="list-unstyled mb-0">
                            <li>
                                <a href="http://www.dheodisha.gov.in/" class="text-white"
                                    style="text-decoration: none;">DHE, Govt. of
                                    Odisha</a>
                            </li>
                            <li>
                                <a href="https://mocollegeodisha.in/" class="text-white"
                                    style="text-decoration: none;">MoCollege
                                    Abhijan</a>
                            </li>
                            <li>
                                <a href="https://dst.gov.in/odisha" class="text-white"
                                    style="text-decoration: none;">DST,
                                    Govt. of
                                    Odisha</a>
                            </li>
                            <li>
                                <a href="https://www.education.gov.in/en" class="text-white"
                                    style="text-decoration: none;">MHRD, Govt. of
                                    India</a>
                            </li>
                            <li>
                                <a href="https://scholarship.odisha.gov.in/website/home" class="text-white"
                                    style="text-decoration: none;">State Scholarships Portal</a>
                            </li>
                            <a href="https://scholarships.gov.in/" class="text-white"
                                style="text-decoration: none;">National
                                Scholarship Portal</a>
                            </li>
                            </li>
                            <a href="https://egranthalaya.nic.in/" class="text-white" style="text-decoration: none;">NIC
                                e-Granthalaya</a>
                            </li>
                            <li>
                                <a href="http://dbtindia.gov.in/" class="text-white" style="text-decoration: none;">DBT
                                    ,</a>
                                <a href="https://www.csir.res.in/" class="text-white"
                                    style="text-decoration: none;">CSIR</a>
                            </li>
                            <li>
                                <a href="https://www.ugc.ac.in/" class="text-white" style="text-decoration: none;">UGC
                                    ,</a>
                                <a href="https://ravenshawuniversity.ac.in/?page_id=24076" class="text-white"
                                    style="text-decoration: none;">RUSA </a>
                            </li>
                            <li>
                            </li>
                            <li>
                            </li>
                            <li>
                                <a href="#!" class="text-white" style="text-decoration: none;">ICSSR ,</a>
                                <a href="https://brns.res.in/" class="text-white"
                                    style="text-decoration: none;">BRNS</a>
                            </li>
                            </li>
                        </ul>
                    </div>
                    <div class="col-lg-2 col-md-6 mb-4 mb-md-0">
                        <h5 class="text-uppercase" style="color: #ffffff;">Support</h5>
                        <hr style="color: aliceblue; width: 40%;">
                        <ul class="list-unstyled mb-0">
                            <li style="line-height:28px;">
                                <a href="https://ravenshawuniversity.ac.in/?page_id=24081" class="text-white"
                                    style="text-decoration: none;">Help Desk</a>
                            </li>
                            <li style="line-height:28px;">
                                <a href="https://ravenshawuniversity.ac.in/?page_id=24084" class="text-white"
                                    style="text-decoration: none;">Gender Equality</a>
                            </li>
                            <li style="line-height:28px;">
                                <a href="https://ravenshawuniversity.ac.in/?page_id=24086" class="text-white"
                                    style="text-decoration: none;">Equal Opportunity Cell</a>
                            </li>
                            <li style="line-height:28px;">
                                <a href="https://ravenshawuniversity.ac.in/?page_id=24088" class="text-white"
                                    style="text-decoration: none;">Anti-Ragging</a>
                            </li>
                            <li style="line-height:28px;">
                                <a href="https://ravenshawuniversity.ac.in/?page_id=24090" class="text-white"
                                    style="text-decoration: none;">GSCASH</a>
                            </li>
                            <li style="line-height:28px;">
                                <a href="https://ravenshawuniversity.ac.in/?page_id=20011&preview_id=20011"
                                    class="text-white" style="text-decoration: none;">Registrar Office</a>
                            </li>
                            <li style="line-height:28px;">
                                <a href="https://ravenshawuniversity.ac.in/?page_id=20017&preview_id=20017"
                                    class="text-white" style="text-decoration: none;">DSW Office</a>
                            </li>
                        </ul>
                    </div>
                    <div class="col-lg-4 col-md-6 mb-4 mb-md-0">
                        <h5 class="text-uppercase" style="color: #ffffff;">Location</h5>
                        <hr style="color: aliceblue; width: 20%;">
                        <ul class="list-unstyled mb-0">
                            <li>
                                <div id="map-container-google-1" class="z-depth-1-half map-container">
                                    <iframe
                                        src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d59808.6751429339!2d85.895867!3d20.46346!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xe48e3475c7591d81!2sRavenshaw%20University%2C%20Cuttack!5e0!3m2!1sen!2sus!4v1672054668437!5m2!1sen!2sus"
                                        width="350" height="200"
                                        style="border:0; border-radius: 10px; box-shadow: 6px 6px 10px 2px black;"
                                        allowfullscreen="" loading="lazy"
                                        referrerpolicy="no-referrer-when-downgrade"></iframe>
                                </div>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="row">
                    <div class="col-lg-6 col-md-6 mb-4 mb-md-0">

                    </div>
                    <div class="col-lg-6 col-md-6 mb-4 mb-md-0">

                    </div>
                </div>
            </section>
        </center>
    </footer>
</body>

</html>
