@import url('https://fonts.googleapis.com/css?family=Big+Shoulders+Text:100,300,400,500,600,700,800,900&display=swap');

/* font-family: 'Big Shoulders Text', cursive; */

.nav-flex-row {
    display: flex;
    flex-direction: row;
    justify-content: center;
    position: absolute;
    z-index: 100;
    left: 0;
    width: 100%;
    padding: 0;
}

.nav-flex-row li {
    text-decoration: none;
    list-style-type: none;
    padding: 20px 15px;
}

.nav-flex-row li a {
    font-family: 'Big Shoulders Text', cursive;
    color: #ffff00;
    font-size: 1.5em;
    text-transform: uppercase;
    font-weight: 300;
}

.section-intro {
    height: 820px;
    background-image: url(IMG.jpg);
    background-size: cover;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.section-intro h1 {
    text-align: center;
    color: #ffff00;
    font-size: 4em;
    font-weight: 700;
}

.section-intro header {
    display: flex;
    flex: 4;
    flex-direction: row;
    justify-content: center;
    align-items: center;
}

.link-to-book-wrapper {
    flex: 1;
}

.about-section {
    display: flex;
    align-items: center;
    background-color: #f3f3f3c0;
    padding: 50px 30px;
}

.link-to-book {
    color: #ffff00;
    display: block;
    border: 2px solid #ffffff;
    padding: 5px 10px;
}

a.link-to-book:hover {
    background-color: #ffffff;
    color: #95999e;
    text-decoration: none;
}

.about-section p,
.about-section h3 {
    text-align: center;
    width: 60%;
    margin: auto;
    font-family: 'Big Shoulders Text', cursive;
    font-size: 1.8em;
    text-transform: uppercase;
}

.carousel-inner {
    height: 700px;
}

.row-flex {
    display: flex;
    flex-direction: row;
}

.flex-column-form {
    display: flex;
    flex-direction: column;
    flex: 1;
    margin: 30px 20px;
}

.btn.btn-primary {
    font-family: 'Big Shoulders Text', cursive;
    color: #ffffff;
    background-color: #95999e;
    text-transform: uppercase;
    font-size: 16px;
    padding: 5px 10px;
    letter-spacing: 2px;
    border: 0;
}

.btn.btn-primary:hover {
    background-color: #747474;
}
.opening-time,
.contact-adress {
    flex: 1;
    margin: 30px 20px;
    font-size: 1.2em;
}

.form-group p {
    font-size: 1.2em;
}

.opening-time p span,
.contact-adress p span {
    display: block;
}

@media (min-width:577px) and (max-width: 800px) {

    .section-intro {
        height: 500px;
    }

    .about-section p,
    .about-section h3 {
        font-size: 20px;
    }

    .carousel-inner {
        height: auto;
    }

    .row-flex {
        display: flex;
        flex-direction: column;
    }
}

@media screen and (max-width: 576px) {
    .section-intro {
        height: 300px;
    }

    .about-section {
        padding: 30px;
    }

    .section-intro h1 {
        font-size: 2em;
    }

    .about-section p,
    .about-section h3 {
        font-size: 15px;
    }

    .carousel-inner {
        height: auto;
    }

    .row-flex {
        display: flex;
        flex-direction: column;
    }

    .row-flex h3 {
        font-size: 25px;
        text-align: center;
    }

    .form-group p {
        font-size: 15px;
    }

    .opening-time p span,
    .contact-adress p span {
        font-size: 15px;
        text-align: center;
    }

}
