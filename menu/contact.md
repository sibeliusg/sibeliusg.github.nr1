---
layout: page
title: Contact
---
<html>
    <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.2.1/css/bootstrap.min.css" integrity="sha384-GJzZqFGwb1QTTN6wy59ffF1BuGJpLSa9DkKMp0DgiMDm4iYMj70gZWKYbI706tWS" crossorigin="anonymous">
        <title>Contact</title>
        <style>
            h1 {
                text-align: center;
                margin: 20px;
            }
        </style>
    </head>

    <body>
        <div class="container">
            <form action="https://formsubmit.co/detlef.humps@yandex.com" method="POST">
                <div class="form-group">
                    <div class="form-row">
                        <div class="col">
                            <input type="text" name="name" class="form-control" placeholder="Full Name" required>
                        </div>
                        <div class="col">
                            <input type="email" name="email" class="form-control" placeholder="Email Address" required>
                        </div>
                    </div>
                </div>
                <div class="form-group">
                    <textarea placeholder="Your Message" class="form-control" name="message" rows="14" required></textarea>
                </div>
                <button type="submit" class="btn btn-lg btn-dark btn-block">Submit Form</button>
            </form>
        </div>
    </body>
</html>
