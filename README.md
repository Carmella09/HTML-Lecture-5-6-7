# HTML-Lecture-5-6-7

LECTURE #5


LECTURE #6


LECTURE #7

    <html lang="en">
    <head>
        <meta charset="UTF-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title></title>
        <link rel="stylesheet" href="style.css">
        <link .css>
    </head>
    <body>
        <ul>
            <li><a href="#">About us</a></li>
            <li><a href="#">Order</a></li>
            <li><a href="#">Contact</a></li>
            <li><a href="#">Services</a></li>
            <li class="dropdown">
                <a href="#">Designs </a>
                <div class="dropdown-content">
                    <a href="#">Modern </a>
                    <a href="#">Cultural</a>
                    <a href="#">Classic</a>
                    <a href="#">High Tech</a>
                </div>
            </li>
        </ul>
      <style>
          /*dropdown menu*/
          ul {
              list-style-type: none;
              margin: 0;
              padding: 0;
              overflow: hidden;
              background-color: #333;
              top: 0;
          }
          li {
              width: auto;
              float: right;
              top: 0;
          }
              li a, .dropbtn {
                  display: inline-block;
                  color: White;
                  text-align: center;
                  padding: 19px 23px;
                  text-decoration: none;
              }

                  li a:hover, .dropdown:hover .dropbtn {
                      background-color: #F023E6;
                  }

              li.dropdown {
                  display: inline-block;
              }
          .dropdown-content {
              display: none;
              position: absolute;
              background-color: #A5A5A5;
              min-width: 90px;
              box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
              z-index: 1000;
          }
              .dropdown-content a {
                  color: white;
                  padding: 14px 16px;
                  text-decoration: none;
                  display: block;
                  text-align: left;
              }

                  .dropdown-content a:hover {
                      background-color: #0E145E;
                  }

          .dropdown:hover .dropdown-content {
              display: block;
          }
      </style>
    </body>
    </html>

------------------------------------------------

<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title></title>
    <link rel="stylesheet" href="style.css">
    <link .css>
</head>
<body>
    <ul>
        <li><a href="#">About us</a></li>
        <li><a href="#">Order</a></li>
        <li><a href="#">Contact</a></li>
        <li><a href="#">Services</a></li>
        <li class="dropdown">
            <a href="#">Designs </a>
            <div class="dropdown-content">
                <a href="#">Modern </a>
                <a href="#">Cultural</a>
                <a href="#">Classic</a>
                <a href="#">High Tech</a>
            </div>
        <li style="float:left; margin:4px 0 0 0">
            <img src="C:\Users\Carmella Rei Van\Downloads\Wallpaper\wp7191319.png" alt=""
                 width="150" height="50" />
        </li>
       
    </ul>

   

    <style>
        /*dropdown menu*/
        ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            overflow: hidden;
            background-color: #333;
            top: 0;
        }

        li {
            width: auto;
            float: right;
            top: 0;
        }

            li a, .dropbtn {
                display: inline-block;
                color: White;
                text-align: center;
                padding: 19px 23px;
                text-decoration: none;
            }

                li a:hover, .dropdown:hover .dropbtn {
                    background-color: #F023E6;
                }

            li.dropdown {
                display: inline-block;
            }

        .dropdown-content {
            display: none;
            position: absolute;
            background-color: #A5A5A5;
            min-width: 90px;
            box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
            z-index: 1000;
        }

            .dropdown-content a {
                color: white;
                padding: 20px 20px;
                text-decoration: none;
                display: block;
                text-align: left;
            }

                .dropdown-content a:hover {
                    background-color: #0E145E;
                }

        .dropdown:hover .dropdown-content {
            display: block;
        }
    </style>
</body>
</html>

------------------------------------------------

















