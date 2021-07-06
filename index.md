<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Got Passion?</title>
        <script src="https://kit.fontawesome.com/2e15c7c035.js" crossorigin="anonymous"></script>
        <style>
            @import url('https://fonts.googleapis.com/css2?family=Raleway:ital,wght@1,200&display=swap');
            
            * {
                margin: 0;
                padding: 0;
                border: 0;
            }

            body {
                font-family: 'Raleway', sans-serif;
                background-color: #ccc;
                font-size: 19px;
                max-width: 800px; /* good size for email */
                margin: 0 auto;
                padding: 3%;
            }

            img {
                max-width: 100%;
            }

            header {
                width: 98%;
            }

            #logo {
                max-width: 120px;
                margin: 3% 0 3% 3%;
                float: left;
            }

            #wrapper {
                background-color: #f8f9fa;
            }

            #social {
                float: right;
                margin: 3% 2% 4% 3%;
                list-style-type: none;
            }

            #main-image {
                width: 100%;
                height: auto;
            }

            #social > li {
                display: inline;
            }           

            .fa-facebook-square {
                color: #4267b2;
            }

            .fa-instagram-square {
                color: #8a3ab9;
            }

            .fa-twitter-square {
                color: #00acee;
            }

            .fa-youtube-square {
                color: #c4302b;
            }

            h1, p {
                margin: 3%;
            }

            .btn {
                float: right;
                margin: 0 2% 4% 0;
                background-color: #7c514b;
                color: #f8f9fa;
                text-decoration: none;
                font-weight: 800;
                padding: 8px 12px;
                border-radius: 8px;
                letter-spacing: 1.5px;
            }

            hr {
                height: 1px;
                background-color: #7c514b;
                clear: both;
                width: 94%;
                margin: auto;
            }

            #contact {
                text-align: center;
                padding-bottom: 3%;
                line-height: 16px;
                font-size: 14px;
                color: #7c514b;
            }
        </style>
    </head>
    <body>
        <div id="wrapper">
            <header>
                <div id="logo">
                    <img src="https://gabeaustin.github.io/MDB-project/img/logo.png" alt="Company Logo">
                </div>
                <div>
                    <ul id="social">
                        <li>
                            <a href="#" target="_blank"><i class="fab fa-facebook-square fa-2x"></i></a>
                        </li>

                        <li>
                            <a href="#" target="_blank"><i class="fab fa-instagram-square fa-2x"></i></a>
                        </li>

                        <li>
                            <a href="#" target="_blank"><i class="fab fa-twitter-square fa-2x"></i></a>
                        </li>

                        <li>
                            <a href="#" target="_blank"><i class="fab fa-youtube-square fa-2x"></i></a>
                        </li>
                    </ul>
                </div>
            </header>
            <div id="banner">
                <img src="https://gabeaustin.github.io/MDB-project/img/passion_img.jpeg" alt="Passion Image" id="main-image">
            </div>
            <div class="one-col">
                <h1>Where Will Your Passion Lead You?</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum accusantium vero sed aliquid quae accusamus. Ab totam pariatur perferendis unde similique ipsam quae debitis repellendus, a tempore dolor aspernatur vel?</p>

                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Itaque perspiciatis accusantium aliquam nobis quisquam similique reprehenderit soluta, cupiditate earum provident a at nisi enim beatae nostrum asperiores culpa. Saepe quasi aspernatur animi eaque aut possimus, velit labore fugit voluptatum molestiae!</p>

                <a href="#" class="btn">Learn More</a>

                <hr />

                <footer>
                    <p id="contact">
                        Passion USA, LLC <br />
                        38 Broadway, Suite 11A <br />
                        New York, NY 10011 <br />
                        info@passioninc.com
                    </p>
                </footer>
            </div>
        </div>
    </body>
</html>